---
source_id: video__qz4GQ0zUFRw
title: World Models, JEPA And The Path To Sample-Efficient RL
speaker: Ankit and Francois (YC Decoded)
year: 2026
url: https://www.youtube.com/watch?v=qz4GQ0zUFRw
kind: video
---

## One-line thesis
Sample efficiency (intelligence per sample) is the open problem; world models (predicting the next state given an action) cut real-world data needs and could unlock robotics and self-driving, but fidelity, real-time planning and sensing remain unsolved.

(Pure research/explainer talk; this ficha keeps only lessons transferable to evaluating startups, mainly in robotics and self-driving.)

## Evaluation heuristics
- **Intelligence per sample and per watt**: the two unsolved efficiency problems; products that need less data per skill have an edge. Quote: "intelligence per sample is basically if I have one additional sample in my data set how much more intelligent am I getting"
- **Action space and state space size gauge difficulty**: bigger action space means more data and slower planning. Quote: "so much bigger than self-driving car"
- **Search-heavy methods do not scale to large action spaces or changing rules**: Quote: "the cardality of the action space must be extremely small if it's big sad"
- **Real-time constraint**: Quote: "imagine we were driving a car and like you took like 60 seconds to like turn the steering wheel everyone's dead"
- **Model-based adds cost**: Quote: "it would take a lot more time to perform inference because I have to do this full test time planning"
- **Unlabeled video without actions is plentiful; action data is the moat**: Quote: "those videos but we what we don't have is the actions they take"
- **Proprietary fleet data as a moat**: Quote: "this is a huge competitive mode of like what do people do in that state"
- **Cross-embodiment gap**: policies trained on one body degrade on another. Quote: "the degradation you have across c across embodiment is very very very strong"
- **Teleop data is expensive and painful**: Quote: "getting tea ops data is extremely painful and expensive"
- **Synthetic rollouts from a world model**: Quote: "trains a policy on only the syn the the synthetic data the imaginated uh rollouts and it actually performs well in the environment"
- **Foundation video model plus small action-conditioning**: Quote: "do a small amount of action conditioning on them to get to this uh this world model"
- **Small robot-data budget claim**: Quote: "it only takes them about 500 hours of teleyop data which is basically exactly this right to get it to be pretty good"
- **Ecosystem breadth in YC robotics**: Quote: "we see a lot of companies at YC working at every step of this from the collecting egocentric data collecting uh the teleyop data training their own world models and action models"
- **Open problems = opportunity**: world-model fidelity (physics), test-time adaptation, speed, tactile sensing. Quote: "getting higher fidelity in the world model is extremely important"
- **Tactile sensing gap**: Quote: "if I numb your hands like you actually can't tie your shoes"
- **Scale-and-pay path to home robots**: Quote: "we're getting to good enough that we can pay up for data in compute to get to Rosie the robot"
- **Demos vs deployment**: Quote: "this is the first year where you see demos where you're like okay this actually like kind of is starting to look like it's going somewhere"

## Questions a YC partner would ask (derived from this source)
- How many real-world samples per new skill do you need, and what is your plan to cut it? — Red flag: tens of thousands of expensive teleop examples per task.
- Where does your action-labeled data come from? — Red flag: only passive video, no action data and no fleet.
- Does your policy transfer across robot bodies or vehicles? — Red flag: one embodiment, retrained for every unit.
- What is the latency budget and does planning fit it? — Red flag: planning that takes seconds in a real-time setting.
- What sensing does the task require (touch, friction)? — Red flag: a tactile task with only a camera.

## Red flags / kill signals
- Approaches that need exhaustive search in huge action spaces (AlphaGo-style scaling to the physical world).
- Dependence on teleop at scale without a path to cheaper data.
- Single-embodiment data treated as general.
- Real-time safety-critical systems with slow inference.

## Green flags
- Plenty of action-free video plus small action-conditioned sets.
- Companies at each layer of the stack (ego-centric data, teleop, world models, new embodiments).
- Proprietary data from deployed fleets (Tesla noted as the exception).

## Named examples
- World Models (Schmidhuber), Dreamer V1-V4 (Hafner; mined diamonds in Minecraft on imagined rollouts), DreamZero (Nvidia), Wayve GAIA ("raised $1.5 billion", per the speaker), GenCast (weather).
- AlphaGo (800 MCTS simulations per move, cited as roughly 24,000 model calls per step), Waymo, Tesla FSD.
- JEPA / LeWM: predicting in latent space; needs anti-collapse techniques.

## Tensions
- Claims such as "perfect world model" examples, brain-evolution arguments and neuroscience parallels are speculative and not startup evidence.
- Hosts conclude world models look closer than autoregressive LLMs to the brain, but admit open issues (PINNs, speed, test-time adaptation).
- Figures (e.g. 500 hours of teleop data, $1.5 billion) are quoted second hand and unverified.
