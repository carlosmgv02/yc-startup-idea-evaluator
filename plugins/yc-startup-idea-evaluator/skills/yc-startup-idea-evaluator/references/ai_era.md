# AI-era criteria: what changes for ideas built on models and agents

## How to use this file

- Run the applicability gate (section 0) first. If the idea is not AI-dependent, skip this file except section 13 (lean and small-team effects apply to everyone).
- For AI ideas, run in order: task selection (1), vertical agent shape (2), model-steamroller test (3), harness vs model (4), pricing shape (5), AI-specific assets (6), model supply risk (7). Add section 10 for robotics or physical AI and section 11 whenever the agent acts without a human check.
- Evidence labels used below: **[YC doctrine]** = YC partners stating general advice; **[operator]** = a founder or exec describing their own company (anecdote, n=1); **[forecast]** = a prediction, often by someone selling into that market; **[vendor]** = claim made by a company about its own product or market.
- Moat frameworks (the 7 powers, schlep and regulatory moats, incumbents) live in `moats_and_durability.md`. Pricing mechanics beyond the AI-specific points live in `gtm_and_pricing.md`. Founder evaluation lives in `founders.md`. Tarpits live in `tarpits_and_kill_signals.md`.
- Never apply a rule here to an idea where section 0 says it does not fit. Several of these rules are explicitly time-limited by their own speakers.

---

## 0. Applicability gate

Apply AI-era criteria only if at least one is true:
- The core value is delivered by a model or agent (generation, judgment, automation of a task humans do today).
- The pitch is "replace or augment labor with AI".
- The product sells to AI builders (data, evals, infra, harness, compute, safety tooling).
- The product is physical AI or robotics.

Do NOT apply them when:
- AI is incidental (a summary button on a marketplace, a CRM with a chat box). Evaluate with the classic files; only check section 3 for "could a coding agent clone this in a weekend" [S75].
- The idea is consumer and the AI is the pitch rather than the product. Use section 12 plus the consumer rules in `idea_sources_and_quality.md`.
- The idea started from the technology ("AI is cool, what can I apply it to?"). That is a solution in search of a problem, a classic mistake, not an AI-era question [S34].
- The rule is a vertical-B2B rule (labor budget, sell above the replaced team) and the idea is horizontal, consumer or developer tooling.

What does NOT change in the AI era, per YC doctrine: success is mostly the founder, shipping speed predicts success, and you still need a concrete problem [S62, S61, S75]. "Almost everything is exactly the same" (PG, as summarized in [S62]). Treat AI criteria as additional filters, never as replacements for user evidence.

---

## 1. Which tasks to target

### 1.1 The model-capability probe (Jeff Dean's actual rule)
- Rule: test frontier models on the core task. Near-total failure is a good sign; partial success is a warning, because the capability is "starting to be present" and will improve with data and scale [S55].
- Quote: "look for something where the model succeeds 0% or 1% of the time not not 20%" — Jeff Dean [S55]
- What he did NOT say: there is no "20-50% danger zone" and he does not call 0-1% an "opportunity zone". He says 20% is "maybe not a great sign" [S55]. Do not invent bands.
- Evidence level: senior Google researcher's heuristic, framed from a Google-insider view and expressly time-limited [S55].
- Check: "What fraction of the core task do today's frontier models solve, tested by you?" Bad: a large and improving partial share, or the founder never tested. Good: founder has run the task on frontier models, can show where they fail, and has a reason the gap is not closing in 6-12 months (private data, niche model, verifier) [S55].
- Durability horizon: ask whether frontier models will cover the task in 6-12 months or 2-3 years [S55].
- Excitement is criterion number one for Dean, but he adds that excitement does not exempt the idea from the durability check [S55].

### 1.2 Competing framings of "where on the capability curve"
Three sources frame the target differently. Present all three; they do not average out (see "Where sources disagree").
- **Model fails today (0-1%)**: durable because general models will not absorb it soon [S55].
- **Edge of models**: the idea "sits at the edge of what models can do today" and clearly improves with each model [S64]; "work on the things that are barely good enough for the models to do" [S54]. Build for models 6-12 months ahead [S54].
- **Product overhang**: today's model already can do things no product lets it express; the wedge is removing scaffolding to unlock them. Claude Code's origin: competitors did autocomplete, the winner gave the model write access and a terminal [S41, vendor describing its own product].
- How to reconcile operationally: ask which of the three the founder is betting on and whether their moat matches it. 0-1% bets need private data or a niche model [S55]. Edge-of-model bets need the product to get better, not obsolete, as models improve [S64, S45]. Overhang bets need speed, because the overhang is visible to everyone once shown [S41, S35].

### 1.3 Where AI ideas come from [YC doctrine]
- Boring, repetitive admin work with large headcount. Quote: "if you can find a boring repetitive admin task um there is likely going to be a billion dollar AI agent startup" — Light Cone partners [S23]
- Signals of a live opportunity: work outsourced to low-wage countries (Lilac Labs, drive-thru orders); products that need consultants to work (Automat vs UiPath) [S33].
- Founder access to the work: shadowing (founder's mother is a dentist), undercover jobs (medical biller), job-board mining for "remote clerk/analyst" roles [S23, S33].
- "Lazy hackathon idea" is the default bad AI idea; most good ideas are "at least somewhat hard to actually ship the first version of" [S33].
- AI makes small niches big: the product replaces a $60-80k human, not a CRM seat [S33].
- "Glue the model to the use case": models are good enough; giving them tools is a place to look [S79, operator].
- Hidden in plain sight: crowds chase only recently-possible ideas; old, solvable, unbuilt things are also open [S40, operator].
- Pre-AI dead bodies are not proof: check whether earlier failures were failures of a capability that now exists [S29]. Tarpits can be "untarred" by LLMs if the founder can say what changed [S28] (details in `tarpits_and_kill_signals.md`).
- Re-test ideas killed by cost: formal verification was "too hard" and is now tractable with AI token spend [S38].
- Backlog test: does making the task cheaper unlock a large backlog (patients, lawsuits)? [S56, vendor CEO; his "no job loss" claim is advocacy].
- "Let the tokens rip": explore the version where inference cost is ignored (10,000 unit tests, $5 per email reply); unmet needs surface [S54]. Pair with section 5 margins.

### 1.4 Red flags at task selection
- Idea chosen because it is hot on X or TechCrunch; "another vertical AI agent for insurance or banking" with no unique insight [S29, S33].
- Founders building for professionals they have never been and have no access to [S33].
- Idea easy to build in a weekend [S33, S66: "you better just go do three months of work in three months"].
- Answer to "why now" is just "AI" with no specific cost or capability shift [S66].

---

## 2. Vertical AI agents vs SaaS

### 2.1 The thesis [YC doctrine plus forecast]
- Vertical agents combine "the software plus the people in one product" and attack payroll spend, not software spend [S23].
- Forecast: "it's very possible the vertical equivalence will be 10 times as large as the SAS company that they are disrupting" — Light Cone partners [S23]. Label as forecast by analogy with SaaS (300+ SaaS unicorns, over 40% of VC dollars in 20 years) [S23].
- Wallet share example: Avoca (HVAC) takes 4-10% of customer spend for support vs about 1% for software [S35].
- 2026 YC data: companies doing full end-to-end work grew from 10% to over 25% of accepted companies; an agent that does the whole job is "more valuable than some like system of record that tracks the job" [S72; YC-selected cohort, not market-wide].

### 2.2 Checks for a vertical agent
| Check | Good | Bad |
|---|---|---|
| What budget? | A team's payroll cost, sized in salaries replaced [S23, S35] | Sized on software budget only [S23] |
| Replace or assist? | "You don't need a QA team at all"; can sell to companies that do not have the team yet [S23] | "Makes your people faster" [S23] |
| Who signs? | Decision maker above the team being replaced [S23] | Bottom-up sale to the team that gets automated: "they're going to sabotage it" [S23] |
| Depth | Can replace a 100-rep support team doing complex work; customer-specific evals (10,000 test cases for one customer) [S23] | Zero-shot prompting: "just kind of makes for like a nice demo" [S23] |
| Does the whole job? | End-to-end workflow (insurance broker, clinical intake, medical billing, recruiting to interviews) [S72] | Point solution that needs a human to operate it [S72] |
| Where does work happen? | Product is where work happens (harness) | System of record exposing only an MCP: "you lose your moat around the data" [S72] |
| Starting point for non-technical users | Recurring painful tasks the customer already has; uses data the vendor holds [S67] | Blank canvas agent that leaves users unsure what to do [S67] |

- Crowded category can be empty at the high end: about 100 AI support entrants, almost all shallow; less than 1% penetration by those attempting real replacement [S23]. Giga ML won Zepto/DoorDash in crowded support on delivery quality [S33, S54].
- Small businesses as AI buyers have no job-loss resistance [S67, operator at an incumbent; anecdotal].

### 2.3 The counter-thesis: vertical scaffolding value shrinks
- Dust's founder (horizontal, model-agnostic platform) argues vertical AI's go-to-market value came from scaffolding weak models, and "that second value just disappears as the models are getting better"; verticals then need network effects [S71, operator with a stake in horizontal].
- Labs entering verticals is real: Anthropic going after Legora's market (law) [S71].
- Rippling is "the case against vertical": horizontal bundling where each new product hits millions in ARR on day one [S23].
- Legora (legal) picked "a space more than a problem" and won anyway, 1 to 100M ARR in about 18 months [S59, operator; survivorship].
- Use: for a vertical agent, ask "what is left if a lab ships a general agent for this vertical next year?" Acceptable answers: customer-specific evals and workflows, licenses or regulatory permission, owned outcome, network effect, trust record (section 6 and `moats_and_durability.md`). Not acceptable: prompts and workflow glue [S71, S41].

---

## 3. Wrapper risk and the model-steamroller test

### 3.1 The risk
- "That first wave of llm apps mostly did get crushed by the next wave of GPT" — Light Cone partners [S23]. Example: Speedy Brand (blog-writing wrapper) [S23].
- The real risk is capability absorption, not labs entering: "agent capabilities will obviate a bunch of specific verticals or tasks" [S61, Collison, paraphrase of garbled caption].
- Harness and prompts have a short shelf life: "something that you did for one model maybe three months ago it just might not translate at all to the next model" [S41]. Even evals last only "one two three model generations" [S41].
- Custom fine-tunes get "stomped by the next model release" [S60]; Legora deliberately did not fine-tune in 2022-23 and bet on model improvement [S59].
- Robotics: the bitter-lesson argument says specialised robot models may be absorbed by general models with more autonomy and a harness [S65; speakers' hypothesis, contested by S42].
- Single-model optimization: "the fact that I optimized too much on their model" [S63, operator].

### 3.2 But "wrapper" is not a verdict
- "Some of the biggest companies today are AI rapper 100% before then they were SQL rappers or S3 rappers" — YC partner panel [S75]
- Owning a model is "just one of the possible moats"; context engineering getting "80 or 90% of the way there, that's plenty" early [S35].
- A better model can make a context-based product worth more: "a smarter reader extracts more from the same books" [S45, Garry Tan; keynote, his own open-source tools].

### 3.3 The next-model test (run on every AI idea)
Ask: "If the next frontier release doubles quality on your task, does your product get better or disappear?" [S45, S41]
- Gets better: value sits in owned context, private data, evals tied to customer outcomes, integrations, trust/licensing, distribution, or an outcome the company is accountable for [S45, S55, S23, S64].
- Disappears: value sits in prompts, orchestration that patches model weaknesses, rigid step-by-step flows ("hobbling"), or a fine-tune [S41, S60].
- Also ask: "What did you try six months ago that failed, and have you retried it on the newest model?" Stale priors about model limits are a red flag [S41].
- And: "Can a customer get the same outcome by pasting your idea into a coding agent?" Bad: yes, in an afternoon [S69]. Calendly or DocuSign-type products are named as bad starts today [S75].

---

## 4. Harness vs model


- "The model plus the harness gets you the output" [S72].
- Same model, very different results: on ARC-AGI a frontier model reached 30% while harness-based systems reached 95-100%; one comparison showed an 18% gap between two harnesses [S82] (research talk). "it's just a wrapper" is not a dismissal on its own.
- Rigid steps age out: early harnesses imposed fixed plan-act-critique loops that newer models now do natively; the parts that last are tools, memory, sub-agents and feedback [S82]. Build the harness "a bit better than what the current models are able to do" [S82]. Check: "Which parts of your scaffolding would a better model make unnecessary?" Bad: the value sits in fixed step-by-step flows [S82]. Durable products in the agent era are opinionated, always-on harnesses for an outcome: harness plus skills plus code plus an opinionated database [S69, operator].
- Beat DIY coding agents on integrations and domain knowledge: "claude code doesn't know how to connect to any of those things out of the box" [S69].
- Scarcity moves above the tokens: curation of a fragmented model and harness landscape, stateful pieces (storage, memory), security and orchestration [S60, vendor].
- Do not hobble the model: simplest harness that lets it act; re-add instructions only after repeated failure; give goal, guardrails and exit criteria [S41].
- Split latent vs deterministic: taste and judgment to the model; arithmetic, SQL, schedules and money movements to code. "Confusing them causes every agent failure I've ever seen" [S45]. Payroll needs scheduled deterministic jobs, not an LLM heartbeat [S67]. Robotics harnesses compile repeated steps into code and keep the model for variation points [S65].
- Verification is the key capability: a task the agent can verify itself can run for days (existing test suite, pixel comparison, spec) [S41, S63]. "Give it a way to verify the output of its work" [S41].
- Verifiers get gamed: reward hacks (a kernel returning zero) show automatic verification needs adversarial robustness [S57]; public benchmarks get "benchmaxed", so check real production logs [S46].
- Latency matters economically: a model in the loop at every step is too slow; compile first passes into skills [S65]. Voice pipelines are bottlenecked by the LLM [S46, S57].
- Leverage: best users fan out to thousands of agents; a product assuming one agent in a chat window may be underbuilt [S41, vendor].
- Controllability, not 100% accuracy, is the unsolved agent need [S56].

Check: "Which parts are deterministic code and which are model judgment?" Bad: "everything is prompts" [S45]. "How does your agent verify its own work?" Bad: a human checks every step [S41].

---

## 5. Owning outcomes vs selling seats

- Per-seat pricing is the incumbent's Achilles heel: if agents work, customers need fewer seats, so incumbents cannot follow without cannibalizing [S35]. (Counter-positioning detail in `moats_and_durability.md`.)
- AI startups price on "work delivered or tasks completed" [S35]. Finn charges about $1 per resolved ticket [S59].
- Flat seat pricing breaks when agent loops consume more tokens; move to credit or usage pricing [S71, operator]. Agents can be 450% more consumptive than humans on the same task [S49, vendor claim on network bandwidth].
- Sell the outcome, not software: "customer trust licenses regulatory permission and outcome ownership" become the valuable assets [S64]. Caveat: this assumes capital and regulatory capacity many early founders lack [S64 tensions].
- Value-based anchor: price about a third of value created; worked example 100 agents at $100k each, 20% saving = $2M, price about $700k [S20]. S20 prefers committed recurring revenue over pure usage (see disagreements).
- Margins: treating cloud or AI credits as free breaks margins when they run out; red flag if margin is well under 80-90% [S20]. Ask: "What is gross margin after token cost and how does it move with usage?" [S71].
- Token cost as CAC: free tokens to the aha moment, cheap plan, a fraction become high-spend per-token users whose pass-through becomes margin via volume discounts [S48, operator]. Subsidised flat plans: labs can subsidise, a startup mostly cannot [S48].
- Intelligence vs cost depends on the vertical: in law, token spend is tiny relative to human expertise, so buyers want maximum intelligence; in support, cost per ticket dominates [S59].

---

## 6. AI-specific durable assets (short list; frameworks in `moats_and_durability.md`)

| Asset | Test | Source |
|---|---|---|
| Owned, compounding context | "What context do you hold that no model has, and does it compound daily?" Retrieval alone is not the product: "retrieval is easy being worth retrieving from is the product" | [S45] |
| Private data visibility | Product sees data a general model cannot | [S55, S48 per-user cross-model usage] |
| Niche model | Cheap to train a specialised model for a narrow domain (AlphaFold-style) | [S55] |
| Customer-specific evals | Detailed eval set per customer; evals let you route between models by cost | [S23, S59]; shelf life 1-3 model generations [S41] |
| Proprietary data plus fine-tuning on open weights | "when you have proprietary data and you can train ... the open weight models are really nearly frontier" | [S72] |
| Data that must stay fresh | Data and RL environments are crafted products, and "you still need more data"; YC funded more than a dozen companies each over $10M/yr selling data or RL environments to labs | [S46, S72]; customer-concentration risk on labs [S72] |
| Curated corpus | 3,500 design prompts as inspiration source | [S69, operator] |
| Memory as consumer switching cost | "memory is already becoming a bit of a switching cost for me" | [S35] |
| Trust record | Evidence-grade operating record that cannot be leaked like a model | [S74] |
| Memory hygiene | A memory product without provenance and pruning compounds errors: "a brain nobody curates is a garbage dump with great search" | [S45] |

Fake AI moats: prompts and scaffolding [S41]; lock-in by data migration (LLMs can morph schemas; "there's no lock in anymore") [S35, S60]; latency staying bad [S65]; dependence on today's hardware or API prices [S74].

---

## 7. Open vs closed models and model-supply risk

### 7.1 Data points, with their evidence level
- **Observed (reported)**: AT&T shifted 40% of its token consumption to open models. Source: the Ollama guest citing a press article (The Information) [S60]. Use as a single enterprise datapoint, not a market statistic.
- **Forecast by a vendor CEO**: Jeffrey Morgan (co-founder and CEO of Ollama) predicts that within a business "call it 80 90%" of tokens will go through open models. This is tokens, not spend: he says spend share to open models may be only 10-20% [S60]. Never quote "80-90% of AI spend" or "80-90% of the market".
- Vendor data: per-developer token use up 150x since start of year; "cloud coding tokens are predominantly Chinese models" is Ollama-platform data only [S60].
- Research claim: up to 88.7% of queries in the speaker's study could be routed to local accelerators; imperfect routers saved 50-70% of cost [S57; one study, speaker also concedes data-centre batching amortises cost better].
- Price gap estimate: same-latency open-weight models about 9x cheaper, implying 70-80% lab margins (speaker's estimate) [S71].
- Cost trend claims: "a 10x cost reduction per year roughly speaking for the same intelligence" [S75]; "very safe to assume cost of compute per level of intelligence is going to go down a lot" [S54].
- Counter-signal: A100 GPU-hour price is appreciating; compute is scarce [S72]. Securing compute is hard even with money [S76].

### 7.2 What it means for evaluation
- Enterprise adoption of open models starts with cost, then control and customization; security and safety are the blockers [S60].
- Customers "don't really care where the model's from they care about where it's run" [S60].
- Hybrid routing: frontier model for hard tasks, open or local for line-item work [S60, S57].
- A business built on reselling token margin is exposed to open-model price compression [S60 question set].
- Model-agnostic neutrality is something labs cannot offer; the best model rotates over time [S71]. "Bet the field, not a winner" [S48].
- When one or two closed players dominate, the rest of the market coalesces around an open alternative; taking that slot early is hard to displace [S48, operator].
- Dependency risk: "Your dependencies business model is your business model" [S63]. Anthropic disabled a subscription with about 24 hours' notice (Steinberger's account) and checked system prompts for a competitor's name (OpenCode's account) [S63, S48].
- Do not anchor the business case on today's hardware or API prices [S74]. Design for the cost curve: imagine the product when it is free [S86].
- "No GPU before PMF" for product-layer companies; Dust raised $5M seed while training companies raised $100-200M [S71]. Raising training-scale money without use for it leads to the "coffin corner" [S71].

Checks: "What breaks if one model lab changes terms or pricing?" Bad: single-supplier dependence [S48, S63]. "Which layer around the model do you own, and could a coding agent replicate it in a weekend?" [S60].

---

## 8. Agents as customers and agent-facing products
- "If the agents choose you that's actually big and you're going to win huge" [S69, operator]. Make software agents want to use [S72].
- Supabase measures 60% of databases launched by an agent, likely closer to 90% [S51, operator figure].
- Ask: "Would an agent pick your product, and can it sign up on its own?" Bad: human-only onboarding [S69, S72].
- Agent-readable surface (distilled markdown) and prompt-injection notes on agent-facing pages [S85].
- Datadog builds product usable by agents and embeds intelligence because sending everything through a general coding agent is "like sending a postcard by buying a business class ticket" [S78, paraphrase].
- Agent-generated volume floods any human-review step with free submissions; each such system is a gap or a threat [S38].

---

## 9. Context and capture as a product
- Agents need context; a product that captures proprietary context (meetings, decisions) gains value as agent adoption rises [S43, operator].
- Trust and permissioning gate capture-everything products [S43].
- Skill-file test: a process is automatable if "a smart intern could follow it" [S45].

---

## 10. Physical AI and robotics realities

Apply this section to robotics, autonomy, drones, physical automation and any AI acting in the physical world.

### 10.1 Demo vs product
- "A working demo is 1% at best of the work" — Dmitri Dolgov, Waymo [S74]
- Count your nines before your demo views: each extra nine takes about 10x more effort; demos need one nine, copilots a few, public-facing autonomous agents a whole stack [S74].
- Reference timeline: Waymo's demo took about 18 months with a dozen engineers; the product took about 15 years [S74, operator].
- Later nines need different methods (redundancy, tiered fallbacks), not more of the same [S74]. Do not pick the technology with the steepest early ramp; it can plateau below required performance [S74].
- Build eval and metrics before the product; "if you can't quantitatively define what good enough means you're not really building a product" [S74].
- Robotics in 2026 is "definitely the year of the demos" [S81].

### 10.2 Reliability and autonomy
- Ask who decides: if a human reviews the AI output, errors are tolerable; if the system acts, it needs far fewer mistakes before it is useful [S42].
- If a human must babysit, value collapses [S42].
- Evidence: measured success rate and throughput over multi-hour runs in a real customer workflow (13 hours straight), not curated videos [S42].
- Path to 99%+ is a self-improving loop, not a person hand-tuning data; algorithms needing millions of attempts cost "700 robot days" [S42].

### 10.3 Startup shape that works now [research talks, transferable lessons]
- Robotics application companies that own a full business problem end to end, called "the new SaaS" [S81].
- Start with a single paying customer problem, teleoperation first and off-the-shelf hardware; do not start with foundation models [S81].
- Keep a replica of the customer environment; do the eval manually first; collect data with a training loop, not all up front [S81].
- Evaluation encodes business value that generic model companies will not encode [S81].
- Start from a generalist model and fine-tune; a single pre-trained model matched or beat fine-tuned specialists [S42]. Robotics startups fine-tune Physical Intelligence models; none use them out of the box [S72].
- Data diversity beats volume [S42]; action-labeled data is the moat, passive video is plentiful [S84]; fleet data is a competitive moat [S84]; teleop data goes stale as actuators wear (embodiment drift) [S81].
- Customers that are 100% supply constrained are a strong demand signal [S81].
- Distribution is slower than software: hardware must be physically present [S42].
- Hardware iteration cost is the variable to attack: make hardware development look like software [S40, operator]. Material proof objects between rounds (LOIs, a built motor, pre-orders) [S73, operator].
- First robot market: large enough, standardized, valuable [S56].

### 10.4 Forecasts to label as forecasts
- "General purpose robots within the next two years or even earlier" (claimed consensus among labs) [S65, forecast].
- Frontier LLM latency improving about 2x per month [S65, speakers' claim].
- "80% of economic activity is manipulating or moving things in the real world" and more robots than people in 5-10 years [S80, data-vendor CEO's claim].
- Physical AI at NVIDIA about $10B, next $100B line [S56, vendor CEO].

Red flags: needs perfect autonomy to have a business; only lab demos; heavy custom hardware too early; one-time data collection assumed to last; robot-specific foundation model raised on scarce robot data [S81, S42, S65].

---

## 11. Safety and reliability as product requirements

Apply whenever the agent takes irreversible actions, moves money, touches health, law, safety or regulated data.

- Trusted delegation is the market gate: "the difference between market leadership and complete abject bankruptcy" [S49, Cisco exec]. Example failure: an agent refunding three times the amount paid [S49].
- Human gates on irreversible actions: agents draft, humans send [S43].
- Safety must be the foundation of models and training, not an add-on [S74]. "Move fast and ship safely" when dealing with atoms [S74].
- Cost of failure decides launch pace: where failure is expensive (security, money, reliability), take longer and build preconditions before self-serve [S61]. Legora froze sales for six months because "you only really get one chance" with lawyers [S59].
- State the assumptions of any guarantee; a proof holds only relative to assumptions [S38]. Claims of "completely safe" or "unhackable" are red flags [S38].
- Independent, checkable certificates beat self-attestation [S38].
- Layered defense: sell one layer and say which holes remain ("make sure that the holes don't line up") [S38].
- Defense is a broad market: when a capability makes attacks cheaper, every bank, hospital and government with legacy systems needs defense [S38]. Machine-scale attacks need machine-scale defenses [S49].
- Evals for regression: without them each improvement breaks another part (the speaker's "whack-a-mole") [S43].
- Trust surfaces include design: shipping the default look of a coding agent erodes trust, worst in health and payments [S52].
- Do not size a safety market from a headline or a survey; check the primary report [S38].
- Market forces (competitors' pressure) drive adoption of safety tooling more than mandates [S38].

---

## 12. Consumer AI (brief; consumer idea rules in `idea_sources_and_quality.md`)
- Good: take an ultra-premium experience rich people get and make it 100x better and available to everyone with AI; "AI allows is for infinite personalization" [S21].
- Bad: faceless chatbot or voice agent that is 95% as good as a human with a cost-saving pitch [S21].
- Obvious general consumer assistant and search categories go to incumbents: "zero startups won in those categories 100% of the value flow to incumbents" [S23, about prior platform shifts].
- Proven, Better, New: copy what is proven, make it better in a way 10 of 10 users agree with, add one new hypothesis expected to fail; an LLM grades "new" ideas poorly because they are out of distribution [S86, operator].
- Cost-curve design and free as the model: "anything that can be free will be free" [S86].
- Consumer distribution has "no proven path" right now [S86]. Attention is the scarce currency; "your name cannot" be forked [S63].

---

## 13. Lean startup, small teams and solo founders under AI

### 13.1 Is AI breaking lean? (Collison) [operator, Stripe CEO]
- Lean niche-finding from ads and landing pages is now "much more aggressively tilled"; "maybe you have to more aggressively decorrelate" [S61].
- Many recent winners are anti-lean (labs, Anduril); capital and AI make ambitious first versions possible [S61].
- But grounding still rules: the problem must be "viscerally felt by a person who would pay money"; a slow public launch is fine only with a steady stream of real users (Stripe had a production user about two months in) [S61].
- Fear of incumbents is overstated: organisations cannot prosecute 100 priorities [S61].
- Data claim: new businesses starting on Stripe up roughly 2x year over year, time to revenue falling (Stripe data, not shown) [S61].
- Contrast: YC partners still say the biggest founder regret is not launching soon enough [S75]; PG says almost everything is the same [S62].

### 13.2 What building cheaply changes
- Bottleneck moves from building to learning and judgment: "you're limited by the pace with which you can learn" [S54]; "you need to know what to build that's like the high order bit now" [S72]; judgment on what to build becomes the bottleneck [S49]; code review becomes the bottleneck [S43].
- Distribution becomes the hard part: "The hardest problem now is like getting eyeballs" [S63]; "software no longer is the hard thing" [S75].
- Feature cost comes after shipping: "a new feature is just a prompt away the real cost comes after" (9,500 config options) [S63]. Cheap building demands more discipline to say no [S67].
- Prototype-first beats PRDs at a 50% hit rate [S67, operator]; V0 of everything, about 50% of projects fail [S50].
- Products easily cloned with a model plus a weekend are not durable [S75].

### 13.3 Small teams and solo founders (founder evaluation itself in `founders.md`)
- YC solo founders rose from about 5% to 18-19% of accepted companies; co-founders increasingly added later [S72, YC data].
- But "statistically they do worse" — YC partner panel [S75]. Present both.
- Experience is now an edge: expertise is needed "to know what to do with this boundless intelligence" [S69]; managing agent fleets resembles managing people [S72].
- Revenue per person as health metric; examples 15 people at $15M annualized (Emergent), about 40 at $60M [S45, Tan's keynote].
- A 10-employee unicorn is "completely plausible" [S23, forecast].
- Speed is the early moat; Cursor ran one-day sprints [S35]. "Fun is velocity" [S63, operator].
- Claims like "400 to 1,000 clones of myself" and "95% AI-generated code bases in a quarter of W25" are promotional or self-reported [S69, S45].
- Batch benchmarks: median company reaching about $20k MRR vs $8k before; some go zero to seven figures in 3 months [S72]. YC-selected cohort; the hosts themselves ask whether it is AI hype budgets [S72]. Do not use as a general market benchmark.

---

## 14. When NOT to apply AI-era criteria (recap)
- Non-AI ideas: skip sections 1-11. Only ask "could a coding agent and a weekend clone this?" [S75].
- Consumer: do not apply labor-budget, sell-above-the-team or seat-cannibalization logic [S23, S35 are B2B].
- Developer tools: engineers "can change tools on a whim" and are hard customers [S69]; switching-cost reasoning is weaker.
- Pre-PMF product-layer startups: do not demand a model-training plan or GPU spend [S71].
- Idea stage: do not reject for lacking a visible AI moat; moats come after something worth defending [S35, S29].
- Hard tech and deep science: domain expertise matters more (quantum, fusion) than in legal-style verticals [S59]; apply section 10 and `moats_and_durability.md`, not wrapper logic.
- Low-error-tolerance domains: lean "launch and let users find edge cases" does not apply [S74, S61, S42].
- Time-limited rules: Dean's 0-1% probe and the "general models cover niches less well" view are explicitly dated [S55]; Ollama's token forecast and robotics timelines are forecasts.

---

## 15. Partner questions for AI ideas (pick the ones that fit)
1. What fraction of the core task do frontier models do today, tested by you, and what will they do in 12 months? [S55]
2. If the next model doubles quality, do you get better or disappear? [S45, S41]
3. Which team or budget line do you replace, and who signs? [S23]
4. What does your product do that a zero-shot prompt or a coding agent cannot? [S23, S69]
5. Which parts are deterministic code and which model judgment? How does the agent verify its work? [S45, S41]
6. Do you price per seat, per task or per outcome, and what is gross margin after tokens at 2x usage? [S35, S71, S20]
7. What context, data or evals do you own that compound with use? [S45, S23, S35]
8. What breaks if your model supplier changes price or terms? [S63, S48]
9. How many nines does the product need, and what is the plan beyond the first two? [S74]
10. Does a human check the output before it matters? If not, what is the measured failure rate? [S42, S49]

---

## Where sources disagree

1. **Where on the capability curve to build.** Dean: target tasks where models succeed 0-1%; partial success is a warning [S55]. S64 and S54: build at the edge, on things "barely good enough" for models, and expect improvement. Cherny: build for capabilities today's model already has but products hide (product overhang) [S41]. These are different bets with different moats; ask the founder which one they are making.
2. **Vertical vs horizontal.** Light Cone: vertical agents may be 10x SaaS and lean vertical from day one [S23]. Dust's founder: vertical scaffolding value disappears as models improve; verticals need network effects [S71]. Rippling cited as the case against vertical inside S23 itself.
3. **Fine-tune or not.** Legora bet against fine-tuning [S59]; Ollama says custom fine-tunes get stomped but tooling may revive them [S60]; S72 says proprietary data plus fine-tuning makes open weights "nearly frontier"; robotics teams all fine-tune [S72, S42].
4. **Better models: threat or tailwind.** Most sources treat model progress as the steamroller [S23, S41, S61]. Tan: better models raise the value of owned context [S45]. Wang: debating model progress is a waste; the bottleneck is diffusion into the economy [S39].
5. **Specialised vs general models in robotics.** Finn: "no substitute for the robot experience itself", though generalists beat per-task specialists [S42]. Robot-use agents founders: general LLMs with a harness may beat robot-specific models [S65].
6. **Lean under AI.** Collison: lean niches are crowded, decorrelate and start ambitious [S61]. YC panel: biggest regret is not launching sooner [S75]; PG: almost everything is the same [S62]. Collison himself keeps the grounding rule.
7. **Solo founders.** YC data: solo share up to 18-19% [S72]. YC panel: solo founders statistically do worse [S75].
8. **Usage vs committed pricing.** AI sources push task, credit or outcome pricing [S35, S71]. Blomfield prefers committed recurring revenue over usage-based [S20].
9. **Compute cost direction.** Cost per unit of intelligence falls about 10x/year [S75, S54]. GPU-hour prices are appreciating and compute is hard to secure [S72, S76].
10. **Incumbent copilots.** Legora feared Microsoft Copilot for lawyers and it "didn't work" [S59]; Light Cone says incumbents win obvious general categories [S23]; Gusto shows an incumbent with customer data building a strong agent [S67].
11. **Brand vs speed.** Steinberger: everything can be cloned "but your name cannot" [S63]. Light Cone: brand takes time and is not an early moat; speed is [S35].

## Sources used
S20, S21, S23, S28, S29, S33, S34, S35, S38, S39, S40, S41, S42, S43, S45, S46, S48, S49, S50, S51, S52, S54, S55, S56, S57, S59, S60, S61, S62, S63, S64, S65, S66, S67, S69, S71, S72, S73, S74, S75, S76, S78, S79, S80, S81, S82, S84, S85, S86
