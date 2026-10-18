---
source_id: video__IfoPg2QefF8
title: Going In Deep On Data | YC Paper Club
speaker: YC Paper Club panel (data researchers)
year: 2026
url: https://www.youtube.com/watch?v=IfoPg2QefF8
kind: video
---

## One-line thesis
Data, not architecture, GPUs or watts, is the bottleneck for automating the economy; data and RL environments are products with lasting value, and the hard part is scaling expert judgment into them.

## Evaluation heuristics
- **Data as terminal value, not commodity**: the old VC view that data businesses are worth zero was wrong; check whether the data company's asset keeps needing refresh. Quote: "everyone said the terminal value of data businesses was zero dollars And since then I think it's like a hundred billion dollars in market cap creation"
- **Look at the data first**: when a model underperforms, the right move is error analysis, not architecture tweaks. Quote: "The correct answer is you look at the data You classifi look at all the false positives You look at all the false negatives You put them in purto buckets"
- **Production shifts the weight to data**: Quote: "in your nice little imageet train set everything is really nice The train distribution is beautiful"
- **Datasets and environments are crafted products, not zip files**: Quote: "a lot of people think that they're just zip files and it's just really not"
- **Data goes stale, so the moat is continuous**: Quote: "you can have all the data you still need more data"
- **Expert and preference data for the whole economy**: where answers are subjective (design, medical, legal), the data needs experts. Quote: "we need both expert data and expert RL environments"
- **Apps analogy for the number of data companies**: the count of viable data companies is like apps on a phone; vertical depth is hard for a foundation lab to replicate. Quote: "how many apps do you have in your phone that's probably the answer"
- **Scaling expertise is the real bottleneck**: Quote: "scaling expertise actually giving leverage to experts in the field doctors clinicians um journalists people who actually have the spec in their head for what good looks like is the real bottleneck"
- **Encode expert judgment as software**: gets scale, adaptability and auditability. Quote: "we want to encode expert supervision in software"
- **Benchmarks lag usage**: agents are used as senior engineers but evaluated as juniors; a gap in evaluation is a product opening. Quote: "We're still evaluating them as as junior engineers"
- **Verifier tradeoff**: unit tests are reliable and inflexible; LLM judges flexible and unreliable; a middle approach combines them. Quote: "high reliability and low flexibility These are pre-written verifiers and think of these as unit tests"
- **Public benchmarks get benchmaxed**: check performance on real production logs, not leaderboards. Quote: "if you run these same models on real world production logs uh you're going to get much lower scores"
- **Speed as a wedge in latency-bound workloads**: voice pipelines are bottlenecked by the LLM. Quote: "The overall latency of the system is highly bottlenecked by the LLM"
- **Real usage data feeds synthetic environments**: Quote: "synthesizes a wide range of realistic RL environments similar to Dowbench based on real data based on real user interactions"
- **Task difficulty calibration**: Quote: "if a model consistently solves this task it's not useful for learning"
- **Underserved long-tail markets measured by data volume**: Quote: "in Madlad 400 a popular common crawl based pre-training corpora there are 0.6% the number of tokens in Thai as compared to English"
- **Synergy is asymmetric and must be measured empirically**: Quote: "Telugu is really helpful for Swahili you can't assume the opposite you have to go measure it"

## Questions a YC partner would ask (derived from this source)
- What does it take to refresh your data when the target changes (e.g. a UI redesign)? — Red flag: the dataset is a one-time asset.
- Who are your experts, and how does their judgment scale without hand-grading everything? — Red flag: output scales linearly with expert hours.
- How does your eval correlate with production logs? — Red flag: only public-benchmark scores.
- Why can't a frontier lab build this vertical data/environment themselves? — Red flag: no answer beyond "we are first".
- What is the error taxonomy (Pareto buckets) of your current model failures? — Red flag: improvement plan is to try more architectures.

## Red flags / kill signals
- Treating data as a commodity without curation work: "it's just zip files".
- Evals saturated or benchmaxed; models score in the 90s on a benchmark and much lower on real logs.
- Static datasets for dynamic targets: the UI changes and the data is invalid.
- Manual labeling that scales with data points and cannot adapt to spec changes.

## Green flags
- Expert network plus software that amplifies expert judgment.
- Real production data in the loop to refine synthetic generation.
- Vertical depth (compliance, domain ontology) that a generalist lab will not do.
- Held-out test split on different businesses to limit overfitting.

## Named examples
- Focal Systems: in-stock/out-of-stock vision, errors from fog and people in the way.
- Snorkel: data programming, labeling functions, SeniorSWE-Bench, "tasteful pass" metric.
- Inception Labs: diffusion LLM (Mercury 2), 1,000 tokens per second; Tau Forge [sic, "Dowo Forge"/"tforge"] synthetic RL environments; $500,000 credits offered to YC companies.
- Scale AI: cited as the data business once doubted.
- MIT/Google multilingual scaling laws: low-resource language data mixing.

## Tensions
- Contradicts the consensus that architecture and compute are the key lever: says "It is not the architecture It is not GPUs It is not watts".
- The multilingual and diffusion talks are research and product pitches; transferable lessons are limited to the data-curation and eval points above.
