---
source_id: video__CxXgV54KzpQ
title: Jeff Dean: The 1% Rule for Building in AI
speaker: Jeff Dean
year: 2026
url: https://www.youtube.com/watch?v=CxXgV54KzpQ
kind: video
---

## One-line thesis
Pick a problem you are excited about where today's general models succeed about 0 to 1% of the time (not around 20%), because the near-working ones will be absorbed by model progress; value then sits in private data, niche models, specs and taste.

## Evaluation heuristics
- **The 1% rule (model-capability probe)**: test frontier models on the task; total failure is a good sign, partial success is a warning. Quote: "look for something where the model succeeds 0% or 1% of the time not not 20%"
- **Partial success is a bad sign**: Quote: "if they're kind of able to do some of it but not very well that's maybe not a great sign because that's a probably a a sign that the capability is starting to be present in those models"
- **Selection criterion number one is excitement**: Quote: "the most important thing is to pick something you're super excited about and want to build and you think would be useful in the world"
- **Durability horizon**: ask whether frontier models will cover it in 6-12 months or 2-3 years. Quote: "is that going to be a durable thing or do you think the models uh at the forefront are going to get better at that in the next six months or 12 months"
- **Where startups beat general models: neglected domains**: Quote: "we don't have a lot of attention on particular domains where perhaps a really well-designed surface that and maybe a model and set of skills"
- **Private data visibility**: Quote: "your product has visibility into important data"
- **Niche specialized models**: Quote: "you can actually do that in a very affordable way you maybe it doesn't take that much compute to train a a niche model for this particular problem"
- **Context engineering is open to everyone**: Quote: "for context engineering everyone here could do you have you just need the API to something like Gemini"
- **Skills encode the human method**: Quote: "it really just is us giving the approach we would use as people to the model in a form that it could use"
- **Clear specs matter more with agents**: Quote: "the importance of specifying what what it is you want has actually gone up"
- **Taste as the scarce skill**: Quote: "it's really having incredibly good taste in what you ask your agents to work on right"
- **Problem choice beats execution**: Quote: "if you pick the problem well and you succeed in in in solving it that's way better than if you you know uh delightfully execute a research investigation into a rather boring problem"
- **Build taste by scoring your predictions**: Quote: "write down a bunch of things you think might be important in the next 12 months"
- **Napkin math for an order-of-magnitude gap**: Quote: "get you you know an order of magnitude or two orders of magnitude better uh performance or capability"
- **Measurable objective plus fast evaluator**: Quote: "anything where you can have a measurable objective uh I I think you can uh actually make a lot of progress these days"
- **Faster validators change the loop**: Quote: "300,000 times faster wow and nearly as accurate as running the full scale simulator"
- **Long-running agents**: Quote: "you can get them to run for days or weeks and do really really complicated tasks"
- **Impact test**: Quote: "will the world be a lot better in some way or will the world go eh that's kind of cool but whatever"
- **Team**: Quote: "you want people who are low ego that are team players"

## Questions a YC partner would ask (derived from this source)
- What fraction of your core task do frontier models solve today, tested by you? — Red flag: they solve a large partial share (the source's own "not 20%" warning) and improving.
- Will your advantage survive a model release in 6-12 months? — Red flag: advantage is a prompt or wrapper.
- What data or surface do you have that a general model cannot see? — Red flag: only public information.
- Is there a fast, measurable evaluator for your problem? — Red flag: no objective metric.
- How did you choose this problem, and would a great outcome really matter? — Red flag: "meh, that's kind of cool".

## Red flags / kill signals
- Models already do part of the task: capability "starting to be present"; more data and scale will improve it.
- Founder indifferent to the problem ("I don't really want to do this").
- Relying on general capabilities that the labs are broadening: "the general models are definitely getting better at a broader and broader range of things".

## Green flags
- Model fails at the task outright (about 0 to 1%).
- Proprietary or personal data the model cannot access.
- Specific domain where an accurate niche model is cheap to train (AlphaFold-style: protein structure, materials, chip design).
- Task with a clear spec, tests or verifier (e.g. language-to-language translation).

## Named examples
- TPU: napkin math on speech recognition at three minutes per user per day, which would double the fleet.
- MapReduce: abstraction from squinting at hand-parallelized crawl/index code.
- Distillation paper (2014): rejected at NeurIPS with "unlikely to have significant impact", now widely used.
- AlphaFold, AlphaEvolve, quantum-chemistry neural simulator (300,000x faster).
- Google "performance hints" 30-page document.

## Tensions
- The headline rule is "0% or 1% of the time"; he does NOT say 20-50% is a "danger zone" nor use the word "opportunity" for 0-1%. He says 20% is "maybe not a great sign".
- He first says pick what excites you, then warns that generalists are improving: excitement is not enough, durability must be checked.
- General models covering niche domains less well is a Google-insider view and expressly time-limited.
