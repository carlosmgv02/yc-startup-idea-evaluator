---
source_id: video__xc2FTBGRSJo
title: What If We Stopped Using GPUs? | YC Paper Club
speaker: YC Paper Club panel (alternative compute)
year: 2026
url: https://www.youtube.com/watch?v=xc2FTBGRSJo
kind: video
---

## One-line thesis
Research-heavy session on alternative compute (zero-order optimisers, optical, neuromorphic, biological); the transferable lessons are to match use case to hardware physics, benchmark honestly, and be explicit that scalability is unproven.

## Evaluation heuristics
- **Choose the use case carefully**: A new compute substrate only wins on a use case and algorithm co-designed for it; check whether the pitch names the narrow task where the physics gives a tangible advantage. Quote: "for the first demonstrations of useful optical compute we have to carefully choose the use case and the algorithm that we would like to run on the optical machines"
- **Application-specific before general-purpose**: First products are ASIC-type, not CPU replacements. Quote: "the first approach to this type of hardware is not a general purpose computing hardware like CPUs but it's more AIC type uh application specific approaches"
- **Interface costs eat the advantage**: Conversions between digital and optical (ADC/DAC) dominate the energy budget; ask where the system boundary cost lands. Quote: "we pay this large price for converting digital information to analog and then optical domain"
- **Compare against the incumbent honestly**: The optical energy advantage came with an asterisk (weights assumed passive, training done in a digital twin). Check footnotes. Quote: "here there's an asterics we assumed our weights passive"
- **Billion-parameter test**: Next milestone is showing advantages survive at scale (billion parameters), not only on small datasets like MNIST. Quote: "so that we can really claim these energy advantages or latency advantages survive when the systems are scaled out"
- **Know the pivot signal**: Light Matter reportedly pivoted from multispectral compute to HBM interconnects after ADC/DAC resolution problems (speaker's account, not independently supported). Quote: "which was the reason why light matter eventually pivoted to you know interconnects for HBMs"
- **Broad-tent definitions hide maturity**: Assess startups by what is manufacturable now rather than the sci-fi label. Quote: "I have to use the really broad tent definition of neuromorphic in order to answer that"
- **Gestation period**: Research directions need patience and some luck. Quote: "super compelling um but you have to be patient and and you have to be a little bit lucky"
- **Beware cheating the benchmark**: A silicon decoder can do the work and make the novel substrate look intelligent; companies often get this wrong. Quote: "it's very easy to cheat performance out of these systems all you have to do is you know massively oversize your decoder"
- **Run ablations to show the novel part matters**: Undersized the decoder and ran ablations so the spikes carried information. Quote: "ran a bunch of ablations to make sure that the spikes themselves actually carried information to play the game"
- **Honest answer on scalability**: The CEO of a brain-cell computing company says serving billions is unsolved. Quote: "I don't know how scalable it is um but maybe a better kind of answer to that is um we're trying to find out"
- **Hardware first or model first depends on the insight**: Start from the physical property you can exploit or from the architecture, and pick the substrate accordingly. Quote: "it depends on are you starting with like an insight around the physical property of some system"
- **Efficiency target**: The human brain at about 20 watts is the benchmark that motivates the field; GFLOPS per joule has stalled over two years (speaker's claim). Quote: "the human brain draws like 20 watts"

## Questions a YC partner would ask (derived from this source)
- What exact workload gives your hardware an advantage, and what does the incumbent GPU do on it? — Founder claims general-purpose superiority.
- What does the system boundary cost (conversion, memory, calibration) do to the claimed advantage? — Counts only the core compute.
- Would the result survive at ten or a thousand times the size? — Evidence only on toy datasets.
- How do you know the novel component, not the surrounding silicon, produces the result? — No ablation.
- Do you have a path to serve this at scale to many customers? — "We don't know".

## Red flags / kill signals
- Energy or speed claims with an unstated assumption (passive weights, precomputed twin) — presented as headline.
- Oversized conventional decoder carrying the task — result is not from the novel substrate.
- Back-propagation done in a digital twin while claiming analog efficiency — the speaker admits it is "the biggest bottleneck currently".

## Green flags
- Open code and published ablations.
- Honest statement of unsolved limits (nonlinear activations, writing and reading optical memory).
- Narrow prototype with a concrete next scale milestone.

## Named examples
- SPSA (zero-order optimiser): speaker's PhD work, requires fewer perturbations when sharded across many small experts.
- Light Matter, D-Matrix: photonic compute and in-memory-like digital compute used as industry reference points; D-Matrix called makeable now.
- Cortical Labs / Parasma: brain cells on chips playing Pong and Doom.

## Tensions
- The host predicts "in 10 years we'll stop using Backdrop"; contrasts with the entire GPU/transformer ecosystem described in other sources.
- The neuromorphic speaker concludes that digital silicon "going native" is where real innovation happened, undermining the claim that copying the brain is the path.
- Mostly research content with little direct startup guidance; use only for deep-tech scepticism checks.
