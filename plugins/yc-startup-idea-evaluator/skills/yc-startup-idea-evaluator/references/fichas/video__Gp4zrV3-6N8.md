---
source_id: video__Gp4zrV3-6N8
title: Waymo Co-CEO Dmitri Dolgov: The Demo Is Only 1% Of The Work
speaker: Dmitri Dolgov
year: 2026
url: https://www.youtube.com/watch?v=Gp4zrV3-6N8
kind: video
---

## One-line thesis
In safety-critical physical AI the demo is 1% of the work; count the nines of reliability your product needs before choosing technology, build eval and simulation first, and treat earned trust backed by evidence as the business advantage.

## Evaluation heuristics
- **Demo is 1%**: A working demo is at best 1% of the work; the many nines that follow are the real work. Check how many nines the product actually needs. Quote: "a working demo is 1% at best of the work that you have to do the many nines of performance the many nines of reliability that follow"
- **Count your nines**: Each extra nine takes about 10x more effort; demos need one nine, copilots a few, a public-facing autonomous agent a whole stack. Quote: "count your nines before you count your demo views"
- **Demo vs product timeline**: Waymo hit its first goals in about 18 months with a dozen engineers; the product took about 15 years. Use as a reference for founders extrapolating from a demo. Quote: "the demo took 18 months the product took about 15 years"
- **Long tail is the problem**: At scale a one-in-a-million event is a daily reality. Quote: "when you drive millions of miles per week a rare event that might happen once in a million miles that just becomes your daily reality"
- **Different approach per nine**: Later nines need fundamentally different methods (redundant systems, tiered fallbacks), not the same engineering. Quote: "you don't get to say six nines of performance or reliability by doing the same thing that you did for you know to achieve the first two"
- **Hype cycles produce demos, not products**: Every technology wave makes demos 100x easier while the tail moves little. Quote: "every hype cycle produces a wave of absolutely spectacular demos and very few real products"
- **Do not pick the tech with the fastest early ramp**: The steep early curve can plateau before the performance the product needs. Quote: "the technology path that you picked actually flattens out way before the performance that is required by your product"
- **Be honest on purpose**: Know whether you are building for a demo, for learning or for a product. Quote: "be honest with yourself where you're building for the purpose of a demo for the purpose of learning or towards an actual product"
- **Do not anchor on today's hardware prices**: Hardware cost drops with each generation. Quote: "betting your company betting your approach on today's hardware prices is just betting your company on a number that has a fairly short shelf life"
- **Tiger team success scenario**: Before starting a new-tech effort, define the path if it succeeds; otherwise a difficult project ends in a dead end. Quote: "often times I've seen a failure mode where you know a project a very difficult technical project succeeds and then there's a dead end"
- **Simplification launch bar**: A new technology must give both performance and unification, not fragmentation. Quote: "set your launch bar to demand both breakthrough performance and at the same time radical simplification and unification"
- **Structure that channels scale wins**: Bet on a system maximally learned and minimally constrained, use structure only where it helps scaling and validation. Quote: "structure that fights scale will always lose and structure that channel scale always wins"
- **Eval before technology**: Build eval and metrics before the product; models are table stakes. Quote: "build your eval before you build your technology build your eval and your metrics before you build your product"
- **Define good enough quantitatively**: Without it you are iterating on a demo. Quote: "if you can't quantitatively define what good enough means you're not really building a product you're just iterating on your demo"
- **Simulator as AI model, plus critic**: Build agent, simulator and critic sharing a foundation; deployment data grounds the simulator. Quote: "you can't just build the agent you and one AI you need to build three"
- **Trust as moat**: Models can be leaked and algorithms replicated; hundreds of millions of audited miles are hard to replicate. Quote: "your models can be leaked algorithms can be replicated but hundreds of millions of miles of fully autonomous operations in the real world backed by evidence-grade evaluation"

## Questions a YC partner would ask (derived from this source)
- How many nines does your product need and what is the plan for each nine beyond the first two? — Founder has no number or thinks the demo level suffices.
- Which parts of your demo path will plateau before required performance? — Has not tested beyond easy cases.
- What is your eval and how did you build it before the product? — Eval built after the product, if at all.
- What proof do you publish, and what would an audit find? — Trust claimed by demos.
- Does your plan depend on today's hardware or API prices? — Yes, and no plan for falling prices.

## Red flags / kill signals
- Extrapolating from a first 90% demo to the sky being the limit — Waymo "felt like we're on top of the world" in 2010 and still needed 15 years.
- Safety as an add-on — it must be the foundation of models and training recipes.
- Tiger-team success that has no integration path.

## Green flags
- Hard numbers from deployed operations: trips per week (caption says "around 500", which conflicts with the later "half a million trips per week"; treat as [sic]), over 4 million fully autonomous miles per week in 15 cities, about 17 times fewer serious-injury crashes than human drivers over about 220 million miles (all speaker's figures).
- Published safety data and a safety and readiness framework.
- A flywheel of deployment data, simulator and critic guided by metrics.

## Named examples
- Waymo driver: sensor fusion (cameras, lidar, radar), sixth generation hardware, Waymo foundation model (multimodal world action language model).
- Richard Sutton's bitter lesson, used to justify the foundation model plus distillation.
- Go-playing robot toy example: an intermediate structured representation helps scaling.

## Tensions
- "Move fast and break things" fails when dealing with atoms: the source says "move fast and ship safely". This contradicts the software-first lean MVP default.
- The four gaps (cost of error, latency, data, validation) differ from digital AI, where shipping something good enough and letting users find edge cases works; here validation must be strong on day one.
- Lean on end-to-end learned models is qualified: vanilla end-to-end is "not enough" for superhuman safety-critical performance.
