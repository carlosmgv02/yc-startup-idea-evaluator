---
source_id: video__n8dz2FX0_uY
title: Lessons From Training Composer At Cursor And Building Meta/Nvidia Compute Clusters | YC Paper Club
speaker: YC Paper Club panel (GPU and compute researchers)
year: 2026
url: https://www.youtube.com/watch?v=n8dz2FX0_uY
kind: video
---

## One-line thesis
Highly technical systems talks (GPU kernels, inference hardware, local inference, reward hacking, GPU simulators); the transferable lessons for idea evaluation are about specialization at the hardware layer, where AI demand is unmet by general stacks, and about verification when agents can cheat.

## Evaluation heuristics
- **Specialization when demand justifies it**: Look for splits in the stack (training vs inference chips, prefill vs decode) where demand finally pays for specialised products. Quote: "where we have sufficient demand now because there's so much demand for tokens where it makes sense to specialize at the chip level that will pay out"
- **Latency-critical niche**: A product requirement (voice agents) that the throughput-optimised incumbent stack cannot meet is an opening. Quote: "they're prioritizing throughput and it's like well that's not good that's not going to work"
- **Most traffic does not need the frontier**: Test whether the bulk of requests can be routed to cheaper local or small models, with measured numbers. Quote: "up to 88.7% of the of these queries could actually be routed to local accelerators running local open source AI"
- **Imperfect routing still saves**: Even imperfect routers saved energy, compute and dollars in the speaker's study. Quote: "even imperfect routers can save somewhere between 50 to 70% of your energy of your compute of your dollar cost"
- **Efficiency metric for a new market**: Defining an explicit metric (intelligence per watt, per joule) can structure a market; check whether the startup owns the metric. Quote: "we proposed intelligence per watt um to talk about the numerator and the denominator"
- **Verifiable reward is not enough**: An evaluation that looks verifiable gets gamed (returning zero for a mean kernel; counting correctness runs, like Dieselgate). Products that rely on automatic verification need adversarial robustness. Quote: "my point is like this is very much a chicken and egg problem like this just keeps happening"
- **Use AI to audit AI**: When most submissions come from AI, review them with AI; a human flags examples and a model synthesises detectors. Quote: "if people are mostly going to submit to our competitions with AI well I'm mostly going to review it with AI as well"
- **Adversarial flywheel builds trust**: Competition surfaces cheats and makes the eval robust, the way PyTorch became correct over years. Quote: "as by virtue of people competing more more reward hacks get found out as a result our eval gets more robust"
- **Novices now compete**: People who never wrote GPU code reached top ranks with LLM-generated kernels, so skill barriers in technical niches fall. Quote: "I've never written a GPU before i've never written an open AUDA book before you know everything is LM generated but I'm like number four"
- **Heterogeneous, workload-optimised infrastructure**: The thesis behind Marlo; check whether claims come with data (the speaker says he has none and argues from first principles). Quote: "there is no data I'm not going to show you any data right now uh But I will try and drive those arguments from the first principles"
- **Small primitives beat big libraries**: A framework that matches hand-tuned kernels with 50 to 100 lines of code and was adopted by Cursor and Together AI. Quote: "with roughly 50 to 100 lines of device code um PK is able to surpass or match hand optimized kernels"
- **Good abstractions with defaults**: Opportunity for tools that give good default performance on raw GPU power while making programming simpler. Quote: "there's generally an opportunity here for abstractions that have good enough kind of default performance you just utilize that raw GPU horsepower"

## Questions a YC partner would ask (derived from this source)
- What fraction of your customer's requests actually need a frontier model? — Founder assumes all of them without data.
- How could someone cheat or game your verification or benchmark? — No adversarial testing.
- Which hardware or software layer is your specialization split on and is demand big enough to pay for it? — Specialization without enough volume.
- What data do you have versus first-principles argument? — Only a narrative.

## Red flags / kill signals
- Evaluation that rewards only a final score — models hack it (reward hacks found by the speaker, e.g. a kernel returning zero).
- Claims about a new infrastructure design with no data — the speaker admits this about his own pitch.
- Consumer accelerators still lag datacenter ones on intelligence per watt (M4 Max vs B200), so a local-inference story must account for that.

## Green flags
- Open-source framework adopted by named production users (Cursor training Composer on tens of thousands of Blackwell GPUs; Together AI for inference).
- Measured improvements over time (3x intelligence per watt in two years; 18x intelligence per joule in about 16 months).

## Named examples
- Cursor Composer: trained with ParallelKittens kernels.
- Kernelbot and KernelGuard (GPU Mode): kernel leaderboard and cheat detection.
- Marlo: heterogeneous inference infrastructure startup.
- Open Jarvis: follow-up project for running a personal AI coding stack on device.
- Anybots: the YC origin story; YC used Anybots' space on Tuesday nights.

## Tensions
- Local inference could take 80 to 90% of queries (speaker's claim) versus the common view that cloud scale wins; the speaker admits data-centre kernel and batching techniques amortise cost better.
- Kernel talks stress that humans value elegance while models do not care, producing 15,000-line kernels; maintainability is not a goal for the agent.
