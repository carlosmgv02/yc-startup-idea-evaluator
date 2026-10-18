# Moats and durability

## How to use this file

- First decide the stage. At idea stage and pre-PMF, moats are a secondary check: never kill or rank ideas by forecast moats (section 1). From traction onward, defensibility becomes a real question.
- Run the "hard bit" test (section 2) on every idea; it is the quickest durability screen now that software is cheap to write.
- Use the 7 powers table (section 3) only once something works or when the founder claims a moat; ask for the specific mechanism, not the label.
- Use section 5 when the founder fears (or ignores) an incumbent or big tech; section 6 when they talk about competitors.
- Evidence labels: **[YC doctrine]** = YC partners or PG stating general advice; **[operator]** = founder or exec describing their own company (n=1); **[forecast]** = prediction.
- AI-specific assets (owned context, evals, private data, model-supply risk, wrapper test) are in `ai_era.md`. Schlep blindness as an idea source is in `idea_sources_and_quality.md`; here schleps appear only as barriers to entry. Tarpits are in `tarpits_and_kill_signals.md`.

---

## 1. Timing: when moats matter

- Rule [YC doctrine]: do not reject an idea, or choose between ideas, by forecasting its long-term moat. "A moat is inherently a defensive thing and you have to have something to defend." — Light Cone partners [S35]
- Using the 7 powers as the only gate "would be the stupidest thing in the world" [S29]. Focus on problem severity: "you'll figure out the rest" [S29].
- Early on, "the only mote that startups have is really just speed" [S35]. Cursor ran one-day sprints; incumbents take weeks to years [S35]. "Your ability as a smaller company to be fast versus your incumbent competition is the superpower" [S59, operator]. PG: shipping speed is still the best predictor of success [S62].
- Start worrying about moats after rapid growth and a proven use case: "you find any sort of struck gold, then you keep digging" [S35].
- Long-run question still exists [YC doctrine]: "we're looking for businesses that get more powerful with scale and that are difficult to copy" [S01]. Hale's test: "as your company grows is it more difficult for you to be defeated by competitors" [S26].
- Operational rule for the evaluator:
  - Idea stage: ask only "what is the hard bit?" (section 2) and "why will this get stronger as it grows?" as a curiosity, not a gate.
  - Launched with pull: ask which of the 7 powers is starting to form and what evidence shows it.
  - Scaling: demand a mechanism that makes the company harder to beat each quarter.

Red flag: a founder who picks among ideas by 5-year moat forecasts, or abandons a real-pain idea because no moat is visible [S35].

---

## 2. The hard-bit test (durability screen for every idea)

- Rule [YC panel doctrine]: "your startup has to have a hard bit and 10 years ago writing a lot of software was in and of itself the hard bit that is not hard anymore" — YC partner panel [S75]
- "Pure software is just ... too easy to replicate now so just ask yourself where's the hard bit" [S75]. Cheaper to build means "much much less durable and defensible" if it is the same software as five years ago [S75].
- Investors now broadly believe software has no moat; capital has swung toward hard tech [S70, operator, "probably accurate" in his view].

### Kinds of hard bit
| Hard bit | Examples and tests | Sources |
|---|---|---|
| Regulatory barrier | Banking license; licenses and regulatory permission as assets; outdated laws written before a tech shift | [S75, S64, S29] |
| Brutal sales | "Brutally hard B2B sales into some industries" | [S75] |
| Atoms / hard tech | Nuclear reactors, spaceflight, aircraft; iteration cost is the variable | [S75, S70, S73, S40] |
| Schleps | Deals with banks, fraud, regulation; "A company is defined by the schleps it will undertake" | [S11, S12, S34] |
| Last-mile reliability | 80% solution at 20% effort vs the 99% version customers need | [S35, S74] |
| Network effect | Value grows as the network grows | [S75, S26, S71] |
| Distribution | "Software no longer is the hard thing ... distribution can be one of the hard things" | [S75, S63] |
| Deep technical wedge | "Having a deep technical wedge can be really important or distribution" | [S75] |
| Ambition | The ambitious version "protects you from competitors attracts the best talent and has a moat worth building" | [S64] |

- Schlep as barrier [YC doctrine]: "If you pick an ambitious idea, you'll have less competition, because everyone else will have been frightened off" [S11]. Stripe is the canonical case: thousands knew payments hurt, few took on banks, fraud and regulation [S11, S12, S34].
- Hard problems as moat: "something that was hard for us would be impossible for our competitors" [S15, PG 2004].
- Thin wrapper is not automatically fatal: "some of the biggest companies today are AI rapper 100% before then they were SQL rappers or S3 rappers" [S75]. The question is still "where is the hard bit", not "is it a wrapper".
- Easy-to-replicate startups sit in the build stage; harder problems live in operating what was built [S51, operator].

Checks:
- "What is the hard bit?" Bad: "the software" [S75].
- "Who would clone you in a month?" Bad: a Calendly- or DocuSign-type product [S75].
- "What is the most unpleasant part of this business and who does it?" Bad: nobody; plan assumes no schleps [S11].
- "Is your distribution plan more than 'build it'?" [S75].

Applicability: the hard-bit test is general. For pure consumer apps the hard bit is usually distribution or network effects, not regulation. For hard tech the hard bit is obvious; check instead whether the team can lower iteration cost and show material proof (section 4).

---

## 3. The 7 powers in the AI era (Helmer's framework via Light Cone [S35])

The source presents these as defensive and secondary to finding a painful problem [S35]. Ask for the mechanism and the evidence.

| Power | Definition / AI-era form | Good evidence | Watch out | Examples |
|---|---|---|---|---|
| Process power | Hard, mission-critical last mile: "the version you build in a hackathon isn't useful to anyone" | 99% accuracy on tens of thousands of real requests a day; edge-case-heavy verticals (KYC, loan origination) | Demo-grade product only | Case Text, Greenlight, Casca, Plaid integrations [S35] |
| Cornered resource | Real data and real workflows captured by sitting with customers (forward-deployed work); privileged access | Workflows and data from customers who would not normally get good software | Pure prompt wrapper with no owned data | Scale AI and Palantir (DoD access) [S35] |
| Switching costs | Custom agent logic built during long pilots; consumer memory | Long pilots converting to seven-figure contracts | LLMs and codegen lower data-migration switching costs, for you and against you | Happy Robot (DHL), Salient (banks) [S35]; codegen switching cost "closer to zero" [S29] |
| Counter-positioning | "Doing something that is difficult for the incumbent ... to copy because it would cannibalize their business" | Incumbent sells per seat; you sell work delivered | Incumbent can bolt AI onto seats without self-harm; founder-controlled incumbents may cannibalize themselves | Speak vs Duolingo; ChatGPT vs Google ads [S35]; Supabase vs RDS/Aurora [S51] |
| Brand | Trust and recognition | Only at scale | "It just takes time to acquire brand"; not an early-stage moat | ChatGPT vs Gemini [S35] |
| Network economies | AI version: usage feeds evals and data that improve the product | Usage visibly improves evals or models | No feedback loop | Cursor tab autocomplete [S35] |
| Scale economies | Rare at the app layer; mostly at the model layer | Fixed asset reused across customers | Claims of scale economies in an app company | Exa web crawl; Character AI serving cost cut 10x [S35] |

Additional notes from the same source:
- Second-mover advantage is real: "we have seen over and over again that like advantage to being the second mover" (Stripe, DoorDash; Legora vs Harvey on app layer over fine-tuning) [S35]. S54 adds: do it better unless the first mover has "incredible network effects which few things do" [S54].
- Wallet share: labor budget (4-10% of spend) instead of software budget (about 1%) [S35]. See `ai_era.md` section 2.
- Pain intensity matters more than the moat: "It's not like a oh, it'd be nice ... It's a oh, I am not going to get promoted this year" [S35].
- Owning a model "is just one of the possible moats" [S35].

---

## 4. Other durable assets named across sources

| Asset | Test | Source |
|---|---|---|
| Earned trust backed by evidence | Hundreds of millions of audited real-world miles cannot be leaked or replicated like models and algorithms | [S74, operator] |
| Neutral or open position | When one or two players dominate, the rest coalesce around an open alternative; take that slot early | [S48, operator] |
| Building on technology nobody owns | "No one owns Postgress ... all the hyperscalers have to have the best Postgress offering"; a stack of tools working together is hard for a hyperscaler to clone | [S51, operator] |
| Model neutrality | Labs cannot sell neutral access to rivals' models | [S71, operator] |
| Infrastructure that grows on its own | A database grows as the customer's business grows, without more selling | [S51] |
| Uniting two warring buyers | Dev and ops on one platform, riding a secular shift (cloud) | [S78, operator] |
| Full stack on different planning cycles | Layers that change at different speeds are hard to copy | [S49, incumbent exec] |
| First-mover operational data | Only company with data on high-power GPUs operating in space | [S70, operator] |
| Fast iteration loop | "If you can learn one thing every week and there's a competitor that's learning a thing every month they will never matter" | [S58, operator, deep tech] |
| Cost advantage vs incumbent quote | Primes quoted $75-100M; the startup did a mission including launch for $2M | [S70, operator] |
| Data that must be refreshed | Data and RL environments go stale; continuous supply is the moat | [S46, S81] |
| Owned context, evals, private data | See `ai_era.md` section 6 | [S45, S55, S23] |

### Fake or weak moats (flag when the founder relies on them)
- Patents: "A big company is not afraid to be sued; it's an everyday thing for them" [S15].
- Prompts, scaffolding, harness tweaks: rewritten each model generation [S41].
- Lock-in by data migration: LLMs can morph data from one schema to another; "there's no lock in anymore" [S35, S60].
- Brand at early stage [S35]. (Steinberger disagrees; see below.)
- Money: "money will not solve your problems and that's a good thing for startups" [S51]. Large raises create expectation costs [S76] and a "coffin corner" if not used [S71].
- Latency staying bad [S65]; today's hardware or API prices [S74].
- Paid acquisition advantage: competitors pile in and the advantage dwindles [S26].
- Commodity products: "all the margin gets driven out" [S20].
- Altman: tell a real network effect or moat from a fake one; no defensibility beyond the model is a fake moat [S66].

---

## 5. Incumbents and big-tech blind spots

### 5.1 Why incumbents often do not build it [mix of YC doctrine and operator accounts]
| Reason | Test question | Source |
|---|---|---|
| Risk to the core business ("pot of gold") | Would building this endanger their main revenue or brand? | [S23] |
| Legal and brand risk | What can you ship that their legal or brand teams would never allow? (An internal chatbot that might say something inappropriate "we cannot release") | [S76, operator] |
| Cannibalization of seat pricing | Does their pricing model punish them for making your product work? | [S35] |
| No patience for domain nuance | "There's no one to Google who really understands payroll" | [S23] |
| Cannot prosecute many priorities | "Very hard to ... aggressively prosecute 100 different priorities" | [S61, Collison] |
| Had the idea, did not ship | Google published transformers and "did nothing with it" | [S76, operator] |
| Lack of courage of convictions | Earlier search engines shied from results that make users leave faster | [S12] |
| Model made obsolete by change | "You have to wait for things to change so much that their model is obsolete" | [S62, PG] |
| Drifting from its core | Incumbent degrading or distracted makes switching "thinkable" | [S03] |
| Regulatory risk avoidance | Uber, Airbnb were not cloned due to regulatory risk | [S23] |
| Slow product cycles | Weeks to years vs one-day sprints | [S35] |

### 5.2 When incumbents do win
- Obvious general consumer categories in past platform shifts: "zero startups won in those categories 100% of the value flow to incumbents"; general assistants and search likely go to incumbents [S23].
- Big company with brand, capital and distribution can "take away your market overnight" if you lack hard-to-duplicate technology [S15].
- Incumbent with system-of-record data can build a strong agent on recurring customer tasks (Gusto) [S67, operator at incumbent]. But a system of record that only exposes an MCP loses its data moat; it must become the harness where work happens [S72].
- Labs entering verticals (Anthropic in legal) [S71]. Collison's correction: the real risk is model capabilities absorbing the task, not labs entering [S61].
- Dominant supplier turning competitor: SpaceX announced a similar plan mid-round and investors dropped out [S70].
- Feared incumbents can fail: Microsoft Copilot for lawyers "didn't work" and Legora kept building value [S59].
- Enterprises now buy from startups because "the risk of the status quo is actually extremely high" [S61]; fast startups prefer fast new vendors over sleepy incumbents [S72].
- Big tech cannot take risks: "one thing you have that they don't is the ability to ... take some risks" [S76].

### 5.3 How to attack an incumbent
- Do not attack head-on; target a slice whose de facto monopoly the incumbent loses [S03, S62]. Frontal attacks on giants raise expectations and create "an army of haters" [S03].
- Speed alone can pull users from a slow incumbent: "something no better than GMail, but fast" [S03].
- Find the segment the incumbent technology serves badly (jet engines on short regional routes) [S73, operator].
- Counter-position on business model: incumbent charging the wrong side (Couchsurfing/hosts) [S30]; free where the incumbent charges [S86]; per task where the incumbent charges per seat [S35].
- Old incumbent software ("looked like it had built in the '9s") signals room [S59].
- Users who hate the incumbent beat a lack of competitors [S30, S61 "nobody liked the existing ways"].
- Call the product an existing category so buyers and their bosses can price it [S78].
- Revenue is a lagging indicator; do not read incumbent revenue as product vitality [S03].

### 5.4 Incumbent checks for the evaluator
1. "Why would the biggest incumbent not build this?" Bad: no answer; or the space is a general assistant or search [S23].
2. "What does it cost them to copy you (cannibalization, legal, brand, distraction)?" [S35, S76, S61]
3. "What changed that makes their model obsolete?" Bad: plan is a head-on attack [S62].
4. "What happens if your main supplier or channel enters your market?" [S70, S63]
5. "If they do copy you, what do customers lose by switching back?" [S35]

---

## 6. Handling competition

### 6.1 Core doctrine [YC]
- Competitors rarely kill startups: "so rare that you can almost discount the possibility" [S12]. Exception: a competitor with lock-in that prevents users from choosing you [S12].
- "Do not worry about a competitor until they are beating you with a real, shipped product" [S01].
- Competition is usually a good sign; no competitors often means "no one wants the product" [S34].
- Crowded is fine with a thesis: "so long as you have a thesis about what everyone else in it is overlooking" [S12]. Against entrenched competitors you need a new insight (Dropbox integrated into the OS; 20 competitors most people did not use) [S34].
- Choosing a marginal niche to avoid competition is a mistake: "You can only avoid competition by avoiding good ideas" [S13].
- Worrying about competitors pulls you away from customers [S47, operator].

### 6.2 Signals that competition is a real problem
- Same startup as everyone else: "you get a lot of hype and you can raise a lot of money but ... those are much less frequently the big outcomes" [S66, Altman].
- Ten companies starting at once with the same plan that sounds like something existing [S01].
- Hot category tail: "number three through number 98 of all the people in that market, their startups are going to die" [S29].
- Commodity product in an extremely competitive industry: margin driven out; plan to undercut is a red flag [S20].
- Copying a model from another market and assuming fit [S27, S47].

### 6.3 Signals that a crowded space is still open
- Crowded category empty at the high end: about 100 shallow AI support entrants, under 1% penetration by those attempting real replacement [S23].
- "Very very few people can actually deliver to the level that customers want" (Giga ML won Zepto) [S33].
- DoorDash entered a crowded delivery space with a contrarian marketplace bet [S29].
- Existing competitors that users ignore or hate [S34, S30].
- Strong competitors can push you; many weaker ones pivot or run out of money [S80, operator].

### 6.4 Competition checks
1. "Who are your competitors and what do you see that they missed, in one sentence more precise than 'ours doesn't suck'?" [S12, S34]
2. "Did you Google the idea? Who tried before and why did they fail?" [S34]
3. "Is there a competitor with real lock-in?" [S12]
4. "How many funded startups are already in this vertical, and what is your secret?" [S29]
5. "What will you do when a competitor charges half?" Bad: undercut [S20].
Red flag answer to any: "we have no competitors" [S34].

---

## 7. Durability beyond moats (company-level)

Short list; detail lives in other files.
- Launch early and run the company as an empirical exercise; best founders face a new bottleneck every two weeks [S75]. (`validation_and_pmf.md`)
- Pivot only on real evidence, not lost enthusiasm; customer-pulled pivots are easier calls [S75]. (`tarpits_and_kill_signals.md`)
- YC funds people, "the biggest moat by a wide margin" in the panelist's view [S75]. (`founders.md`)
- Frugal culture from day one; hard to change later [S76]. Raise modestly at the product layer [S71].
- Dependency risk: "Your dependencies business model is your business model" [S63]; overreliance on one supplier's roadmap (Starship) [S70].
- Survival through "the desert": Encord spent a couple of years before the market came to it; PMF arrived gradually [S80, operator]. Timing can take almost a decade [S86].
- Fun after PMF prevents burnout and keeps velocity [S79, S63].
- Founder must be willing to run it for 10-30 years if it succeeds [S61].

---

## 8. Durability verdict guide (qualitative; the sources give no numeric thresholds)
- **Fragile**: no hard bit; cloneable with a coding agent in a weekend; value in prompts or price; competitors identical [S75, S41, S66].
- **Defensible-in-progress**: a named hard bit (regulation, schlep, last-mile reliability, brutal sales, atoms) the team is actively taking on, plus speed; moat mechanism plausible but unproven [S75, S35, S11].
- **Durable**: evidence of a power forming (switching costs from custom workflows, counter-positioning the incumbent cannot follow, network or data flywheel, trust record) and the company is getting harder to beat as it grows [S35, S74, S26].
At idea stage, "fragile but real pain and fast founders" is not a kill; say what hard bit they must find [S35, S29].

---

## Where sources disagree

1. **Do moats matter at the start?** Light Cone: never choose or drop ideas by moats; speed is the only early moat [S35, S29]. Altman's playbook asks "how will this company one day be a monopoly?" and seeks businesses hard to copy, while also saying ignore competitors 99% of the time [S01]. Hale asks whether the company gets stronger as it grows [S26].
2. **Brand.** Light Cone: brand takes time and is not an early moat [S35]. Steinberger: "Everything ... can be forked or cloned but your name cannot" [S63, operator, open-source project].
3. **Is software still defensible?** YC panel and StarCloud: pure software is too easy to replicate [S75, S70]. Same panel: biggest companies were wrappers [S75]. SaaS stocks recovered, so moats may hold for now [S72].
4. **Crowded markets.** PG and Friedman: competition is fine, even a good sign, with an insight [S12, S34]; Altman: ten copycats at once is a skeptical signal, same-as-everyone gives hype not outcomes [S01, S66]; Light Cone: numbers 3 to 98 die [S29]. Reconcile by asking for the specific insight, not by counting competitors.
5. **Fear of incumbents.** Collison: overstated [S61]; PG (2004): a big company can take your market overnight without hard tech [S15]; Light Cone: incumbents won obvious consumer categories [S23]; Legora: the feared Copilot failed [S59].
6. **Network effects.** Dust's founder: back to 2010 advice, verticals need network effects [S71]. S54: few things have incredible network effects, so second movers can win. Light Cone: AI network effects take the form of eval and data flywheels [S35].
7. **Switching costs.** AI creates them (custom agent logic, memory) and destroys them (codegen and LLM data migration) [S35, S29, S60].
8. **Open source as moat or risk.** Supabase: open source plus a multi-tool stack is hard for hyperscalers to clone [S51]; the same source cites Redis and Elasticsearch being hosted by hyperscalers as the risk. OpenCode: the open slot is hard to displace [S48].

## Sources used
S01, S03, S11, S12, S13, S15, S20, S23, S26, S27, S29, S30, S33, S34, S35, S40, S41, S45, S46, S47, S48, S49, S51, S54, S55, S58, S59, S60, S61, S62, S63, S64, S65, S66, S67, S70, S71, S72, S73, S74, S75, S76, S78, S79, S80, S81, S86
