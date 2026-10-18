---
source_id: video__Jv5B5CEaPJI
title: Robot-Use Agents: Why General-Purpose Models May Win in Robotics
speaker: YC Decoded (on Phillip Isola's robot-use agents essay)
year: 2026
url: https://www.youtube.com/watch?v=Jv5B5CEaPJI
kind: video
---

## One-line thesis
General-purpose LLM coding agents wrapped in a harness may beat robot-specific models, because the bitter lesson favours the modality with the most useful data; the startup opportunities are the harness (consolidating context into fast skills) and evals.

## Evaluation heuristics
- **Bitter lesson test**: Check whether the company depends on a specialised model that a general model with more autonomy will absorb. Quote: "if you give the um agents or you give the AI model more autonomy and you if you unshackle it a bit more and give it more resources it can actually do a lot of the things that we fine-tune it to do"
- **Data modality over architecture**: The lesson is what data is most useful, not the architecture; transfer from a data-rich modality unlocks out-of-distribution domains. Quote: "perhaps the bitter lesson here isn't necessarily what architecture you build necessarily but it's what data is most useful"
- **Build the foundation, not the specialist**: Why build a robot-only model dependent on scarce robot data? Quote: "why not just build a really good foundational LLM and then use that to control robots rather than training like a model that's specifically for robotics"
- **Latency decides economics**: A model in the loop at every step is too slow to be economically useful; the harness should consolidate first passes into compiled skills. Quote: "if you just have Astra being in the loop thinking at every step this is really slow it's not going to be economically like useful"
- **Skills as consolidated memory**: Packaging learned behaviour into programs is a form of consolidating context for future agents. Quote: "writing out these skills and writing out these memories is a form of consolidating it's it's like a form of dissolation from past experience for your future agents to use"
- **Deterministic graph with points of variation**: Repetitive steps become code, flexible response (failure checks, detection) stays with a model in the loop. Quote: "while the coding graph is sort of deterministic there's points of variation that allow it to generalize"
- **In-context learning has ceilings**: ICL is cheap and fast but non-monotonic, saturates after about 20 to 40 examples, and degrades beyond the trained context length; with abundant data weights win. Quote: "it caps out very quickly and so after like 20 30 maybe 40 examples it is basically saturated"
- **Low-data regime is ICL territory**: In low-data settings in-context learning does surprisingly well; with Tesla-scale data you would not do that. Quote: "it's amazing how good in the in low data regimes uh you can do with ICL"
- **Trend extrapolation**: Latency of frontier LLMs reportedly improving about 2x per month, so real-time control may arrive soon; build for where it will be. Quote: "for fable class LLMs their latency is improving by around 2x per month"
- **Unrecognised adjacent data helps**: Computer-use data (dragging cursors in Blender or CAD) teaches spatial reasoning useful for robots. Quote: "this data helps so much for making these LLM so much better at robot use"
- **Design the harness to look like a known tool**: Tools that interface with the robot, made to look like computer-use tools, improved results. Quote: "if you design a right harness where you make the tools that interface with the robot look like computer use tools"
- **Evals as a company**: Measuring any robot, any model, any embodiment as a service. Quote: "we measure everything any robot any model uh including LLMs and also classical approaches"
- **General robots timeline claim**: Consensus within frontier labs and robotics foundation companies is general-purpose robots within two years; define it as what a competent teenager could do. Quote: "we will have general purpose robots within the next two years or even earlier"

## Questions a YC partner would ask (derived from this source)
- If a general frontier model with tools can already do this one-shot, what is your specialised model adding? — Nothing beyond fine-tuning that the next model absorbs.
- How do you move from "model in the loop" to fast compiled skills for repeated tasks? — No plan; every action calls the big model.
- Where does your system keep deterministic code and where does it call a model? — Cannot say.
- How much data do you need before in-context learning stops working for you? — Unaware of saturation.
- What would real-time control by end of the year do to your product? — Business depends on latency staying bad.

## Red flags / kill signals
- A robotics-specific foundation model that depends mainly on scarce robot data — the speakers argue general models with pre-training on other modalities already beat it.
- Reliance on ever-longer context for learning — ICL saturates and degrades beyond the trained context.
- Latency as the moat — speakers say latency is improving fast.

## Green flags
- Viral demos that LLMs can unscrew caps, coordinate robots and uncap pens (cited as the source of the "robot-use agents" essay).
- Harness that turns first-pass LLM reasoning into reusable skills and faster policies.
- A neutral evals layer that measures all models and embodiments.

## Named examples
- Philip Isola (MIT): essay proposing "robot-use agents".
- RT-2: pre-trained language model controlling robots by outputting end-effector poses.
- Voyager: Minecraft agent that created tools on the fly.
- Code as policies (Google DeepMind): LLM writes code over a function library, one-shot.
- DreamCoder: library of skills refactored during a sleep phase, used as an analogy.

## Tensions
- Against the "robotics needs robot data" view in the Chelsea Finn talk (nb__04), where robot-specific experience is called irreplaceable; here the claim is that general models with a harness win.
- Speakers admit they do not know how far in-context learning can go ("anyone's guess") and that the line between weight space and symbolic space is blurry.
