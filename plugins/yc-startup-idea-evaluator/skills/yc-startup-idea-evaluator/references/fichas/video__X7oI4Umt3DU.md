---
source_id: video__X7oI4Umt3DU
title: AI Safety Fact vs. Fiction | YC Paper Club
speaker: YC Paper Club panel (AI safety researchers)
year: 2026
url: https://www.youtube.com/watch?v=X7oI4Umt3DU
kind: video
---

## One-line thesis
Separate measurable AI risks (cyber offense, open-weight misuse, unverified code) from unmeasurable doom narratives; the startup-relevant opportunity is verification, validation and defense tooling for AI-generated code and systems.

## Evaluation heuristics
- **Hysteria test**: if a market narrative rests on things nobody can measure, check the primary source before building on it. Quote: "hysteria is when people can't measure something but they can't stop talking about it"
- **Check the headline against the primary document**: headlines about AI incidents were wrong versus the technical report; do not size a market from a headline. Quote: "openai says its ai models acted on its own openai never said that not in one statement but this is what was the headline"
- **Weak survey signal**: surveys of experts on long-horizon questions are noise, so do not use them as demand evidence. Quote: "people come up with coherent stories and confident predictions even when they know little or nothing about it"
- **Defense as the catch-all market**: when a capability makes attacks cheaper, the durable business is defense for every institution with legacy systems. Quote: "if you are a bank you are a hospital you are a uh you know financial service you're a government you should be investing heavily heavily heavily into into uh"
- **Bottleneck shift (spec is the new hard part)**: when code and proofs become cheap, the scarce thing moves to specifying intent; look for the startup there. Quote: "the thing that's left that's hard is the specification"
- **Collapse of cost makes a dead idea viable**: re-test ideas rejected for cost. Formal verification was rejected as "too hard" and is now tractable with AI. Quote: "you need like i don't know $100,000 in tokens"
- **Concrete benchmark result**: the evidence offered was a task measured against human effort. Quote: "30,000line rust program which is a crypto library took uh five experts three months or three three experts five months to do we were able to do it in 11"
- **State the assumptions of any guarantee**: a safety or compliance promise holds only relative to assumptions; vendors that hide them disappoint. Quote: "a proof is always with respect to some assumptions right"
- **Know the limit of the method**: pitch what it cannot do. Quote: "i don't even know how to formally specify a cat and a dog so that's beyond what formal can do"
- **Independence as product**: buyers distrust self-certification; a checkable certificate is a differentiator. Quote: "our goal is actually to produce independently checkable certificates"
- **Market forces over mandates**: adoption of a safety/quality tool comes from competitors' pressure, not regulation. Quote: "every other ciso is going to be like oh we better do that too or else you know we won't have that same advantage"
- **Scale breaks human-review systems ("more is different")**: any process with a human in the loop and a free submission cost gets flooded when agents file requests; each is a startup gap or a threat. Quote: "these human review in the loop systems they get ddos really hard"
- **Simplest method first**: try linear regression or trees before neural nets; keep complexity only if the lift justifies it. Quote: "try out the simplest method and then try something maybe a little bit more complicated and see if the performance lift justifies that additional complexity"
- **Layered defense (Swiss cheese)**: no single control is enough; sell one layer and be explicit about which holes it covers. Quote: "what we want to do is make sure that the holes don't line up"
- **Idea given on stage**: a curated "app store of benchmarks" because finding the right version of a benchmark is hard. Quote: "a great idea for a startup is like a apple app store of benchmarks where there's curation"

## Questions a YC partner would ask (derived from this source)
- Which layer of the defense stack do you cover, and which holes remain open? — A claim of "completely safe" or "unhackable" without stated assumptions.
- What is the specification or ground truth your product checks against, and who writes it? — No answer, or "the model decides".
- What was the cost before and after AI for the job you replace? — No measured before/after.
- Who is the independent party that can check your output? — Only self-attestation.
- Does your product depend on a human-review step that agent volume will flood? — Not considered.

## Red flags / kill signals
- Market thesis built on a viral headline or a single survey number — the source shows both misrepresented the underlying reports.
- Guarantees without stated assumptions — "people will be disappointed".
- Reaching for a complex model where a simple method would do.
- Claiming total safety of a real-world system — "i would not believe that".

## Green flags
- A measurable failure definition plus a likelihood measure (the two needs of adaptive stress testing).
- Outcome compared against expert-months of work.
- Adoption incentive that is market-driven (competitors force it).
- Product that is a bounded, containable capability.

## Named examples
- Focal / Walmart inventory: a bad model rollout can order too many avocados and lose millions; why validation matters.
- Hugging Face breach / OpenAI incident: headline versus technical report mismatch.
- Antruth [sic]: startup aiming at a universal code reasoning engine; success "when all the world's code is verified".
- ACAS X: aircraft collision avoidance system validated to a 10^-9 failure target per flight hour.
- NTSB / ASRS: independent investigation plus non-punitive reporting as a model for AI.
- ICLR 60,000 submissions: example of volume overwhelming review systems.

## Tensions
- Opposes the common "ban or regulate open weights / register GPUs" proposals, which the host says "all kind of suck".
- Nuances "move fast": the speakers say careless speed leaves broken benchmarks; the host also argues for accelerating so defenders get stronger models first.
