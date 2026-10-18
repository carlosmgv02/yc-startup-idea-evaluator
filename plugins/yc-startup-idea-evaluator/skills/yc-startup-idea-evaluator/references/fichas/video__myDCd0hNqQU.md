---
source_id: video__myDCd0hNqQU
title: Why Robotics Still Isn't Solved - But Could Be Soon | YC Paper Club
speaker: YC Paper Club panel (robotics)
year: 2026
url: https://www.youtube.com/watch?v=myDCd0hNqQU
kind: video
---

## One-line thesis
Robotics research is still blocked by data, sim-to-real, touch sensing and embodiment drift, but a startup path is already working: robotics application companies that own a business problem end to end, start with teleoperation and off-the-shelf hardware, and iterate on evaluation and data.

(Mostly research talks; this ficha keeps only transferable startup lessons.)

## Evaluation heuristics
- **Discount "next year robotics is solved"**: Quote: "it's definitely the year of the demos I know that for certain"
- **Data bottleneck**: Quote: "we need to scale that up like crazy Um then it's we're kind of doomed"
- **Embodiment drift staleness**: collected data goes stale when actuators wear. Quote: "the teleops data is almost um uh uh stale and you have to recollect it"
- **Robotics application company (the new SaaS)**: Quote: "this kind of category of company is going to be the new SAS right"
- **Own the full business problem**: Quote: "taking ownership of a full business problem sort of end to end"
- **Start with teleop and off-the-shelf hardware**: Quote: "start with a single customer problem that someone will pay you for solve it with tele operation first and just offtheshelf hardware just scrappy"
- **Do not start with foundation models**: Quote: "not feeling the need to to start out with foundation models and solve like very very general problems"
- **Physical world is brutal**: Quote: "the physical world is brutal right uh everything that you do is going to break"
- **Replica of customer environment**: Quote: "I haven't seen a single office that doesn't have a replica of customer environments"
- **Evaluation encodes business value**: Quote: "you can really encode things that the sort of generic model companies will not do Like you're going to encode what is important to this business"
- **Do the eval manually first**: Quote: "do it manually your first"
- **Data collection with a training loop**: Quote: "You don't want to be like collecting all your data up front and then train later like um huge mistake"
- **Moat beyond modeling**: Quote: "these other areas that are not just modeling is like a lot of the source of your moat"
- **Supply-constrained demand signal**: Quote: "they basically are 100% supply constrained They they have a very very easy time like filling their demand"
- **Physical data needs its own data layer**: Quote: "physical data so all the data that you know you're going to be working with in robotics is just very very different than web data"
- **Memory in policies**: Quote: "most policies like PIO5 Groot all of these policies actually don't have any memory"
- **Selective reasoning**: Quote: "selective reasoning is way more important than exhaustive reasoning"
- **Sim-to-real RL scales with compute**: Quote: "This allows us to scale data collection with compute rather than human effort"
- **Inference infra opportunity**: Quote: "it still takes two GB 200s to run the same model"
- **Why few applications yet**: Quote: "it's there's been this lack of the basics that you need to kind of do this fairly cheaply"

## Questions a YC partner would ask (derived from this source)
- Can you deliver the paying customer's outcome with teleoperation before autonomy? — Red flag: needs full autonomy to have a business.
- Do you have a replica of the customer's environment and a repeatable success metric? — Red flag: only lab demos.
- How fast does your hardware, data and policy degrade (drift), and what is the retraining cost? — Red flag: one-time data collection assumed to last.
- Why are you building a general foundation model rather than a vertical application? — Red flag: raising a huge seed to solve "very very general problems".
- What does the customer care about (speed to onboard new designs, edge sharpness) that you learned on site? — Red flag: requirements only from theory.

## Red flags / kill signals
- Depending on demos, not deployed work cells.
- Product requiring perfect autonomy or exhaustive tasks.
- Heavy custom hardware too early.
- Data pipeline built for web data rather than multimodal episodic physical data.
- Pose tracking (perception) failures: about 60% of failures in one lab's system (Tyler Lum's number, a research detail).

## Green flags
- Customers supply constrained: "a very very easy time like filling their demand".
- Small capital raise with growth ("raised reasonably little small amounts of capital").
- Categories named: data centers, construction, warehouses, small-scale manufacturing, food.

## Named examples
- Rerun: open-source SDK and data catalog for physical AI (CEO "Nico" talk).
- Physical Intelligence (Pi) models: fine-tuned rather than used out of the box.
- General Instinct: inference infra for world action models; claims distilling flow-matching steps from 50 to 1-2 and running at about 500 ms per 16-action chunk.
- Sim-to-real RL (SimToolReal, Play to Perfect), MEM [sic "MAM", multiscale embodied memory], RBS-encore [sic "R&B encore"].

## Tensions
- Contradicts the pure-research push toward general foundation models: Nico argues vertical application companies first.
- Host says four walls (physical modeling, representation, tactile sensing, embodiment drift) are unsolved while later speakers show progress.
- Many speakers are researchers and vendors with pitches (credits, infra); claims such as speedups are self-reported.
