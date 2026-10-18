---
source_id: video__rY0wnfFHYbs
title: Open Models Change The Economics of AI
speaker: Jeffrey Morgan (Ollama)
year: 2026
url: https://www.youtube.com/watch?v=rY0wnfFHYbs
kind: video
---

## One-line thesis
Open-weight models are moving into enterprise mainly on cost, driven by coding agents and always-on assistants; the opportunity is in the layers around the model (curation, harnesses, security, orchestration), not in the model itself.

## Evaluation heuristics
- **Cost first, control second**: enterprise adoption of open models starts with cost, then customization. Quote: "cost is by far the largest pain point that open models can jump in and solve"
- **Business vision is control**: Quote: "every business has a vision of getting better control over AI and customizing it for their business and that's really their north star"
- **Adoption data point (enterprise)**: Quote: "they've already shifted 40% of their token consumption to open models"
- **Token share is a prediction, spend share is smaller**: Quote: "the super majority of tokens and this is our take it will be open models within a business call it 80 90%"
- **Spend vs tokens**: Quote: "maybe you'll only pay 10 to 20% uh of of the cost towards open models but your token most of your tokens will be going through the open models"
- **Demand driven by agents, not chat**: per-developer token use jumped. Quote: "we saw 150x since the start of the year"
- **Capability unlocks adoption in steps**: Quote: "finally we had open models that could power coding agents"
- **Scarcity moves above the tokens**: Quote: "the new scarcity the problems now are what's above the tokens"
- **Curation as the open-model opportunity**: Quote: "curation and taking a fragmented universe of models and inference technology and cloud services and harnesses and like making that actually just work is a really valuable problem"
- **Stateful pieces stay outside the model**: Quote: "if it's a stateful problem like there's storage involved that's something that you know in the end can't go into the model"
- **Safety/security tooling as blocker and opening**: Quote: "the blocker to adopting open models is largely around security and safety"
- **Model origin vs where it runs**: Quote: "they don't really care where the model's from they care about where it's run"
- **Hybrid routing**: frontier model for hard tasks, open or local for line-item work. Quote: "a lot of the kind of line item work can happen through open models"
- **Local-first economics**: Quote: "you can run them effectively for free on the hardware you're buying for your business anyways"
- **Cheap per-task models unlock volume**: Quote: "it's also low cost per task which is a really important metric"
- **Platform dependency is less fatal in AI**: Quote: "going up the stack can sometimes be even better because you're closer to the customer"
- **Founder diagnosis**: two years lost "overthinking the customer the product"; shipped in two weeks. Quote: "we just had a bias to action"
- **No-permission adoption path**: Quote: "you could just get started you didn't need permission"
- **Lock-in vs coding agents**: Quote: "there's no lock in anymore"
- **Know your customers, not a blob**: Quote: "you consider your user base and customer base like your customer just a blob on the internet which is a really risky way to think about customers"

## Questions a YC partner would ask (derived from this source)
- What share of your customer's tokens versus spend could shift to open models, and who captures the savings? — Red flag: business depends on token reselling margins that open models compress.
- Which layer around the model do you own (memory, security, routing, curation) and can a coding agent replicate it in a weekend? — Red flag: thin harness with no state or distribution.
- What do you do when a new model drops weekly (cadence of open releases)? — Red flag: product tied to one model or a custom fine-tune that the next release obsoletes.
- Who is your actual customer behind the usage graph? — Red flag: treating open-source users as an anonymous blob; no monetization plan.

## Red flags / kill signals
- Custom fine-tunes that get "stomped by the next model release" (the source notes the cycle may be returning as tooling improves).
- Security and safety gaps in open-model stacks: unaddressed, they block enterprise adoption.
- Open-source traction without talking to customers.
- Lock-in as the moat: with agents, memory and harnesses can be synced across providers.

## Green flags
- Usage spikes when a capability threshold is crossed (coding agents, then OpenClaw/Hermes-style agents).
- Free/no-permission entry that enters enterprise bottom-up.
- Wedge in the glue: day-zero model launch playbook, inference engine, harness, hardware.

## Named examples
- Ollama: 9 million developers, 178,000 GitHub stars, used by 85% of the Fortune 500 (as stated in the intro).
- AT&T: 40% of token consumption moved to open models.
- OpenClaw, Hermes agent, Kimi, GLM, MiniMax, DeepSeek Flash, Open Router, OpenCode: open-model ecosystem players.
- Ollama's pivot path: Kubernetes dev tooling, then desktop security, then local LLMs in a two-week sprint, launched July 2023.
- Heroku/Docker: platform-as-a-service analogy for "layer on top".

## Tensions
- The 80-90% figure is the guest's own forecast of tokens "within a business", not an observed enterprise-wide statistic; he explicitly says spend share would be about 10-20%.
- Claims about local models matching frontier models (garbled in captions: "Quinn 3.8 38B is now as good as Opus 4.6 for coding") are unverified; do not rely on them.
- He is a vendor (Ollama) with an interest in open-model adoption; "cloud coding tokens are predominantly Chinese models" is Ollama-platform data, not the whole market.
- Says tooling returns interest in fine-tuning while the release cadence makes custom training harder.
