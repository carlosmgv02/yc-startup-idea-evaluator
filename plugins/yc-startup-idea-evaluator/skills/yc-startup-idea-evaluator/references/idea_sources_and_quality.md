# Idea sources and idea quality

## How to use this file

- Use it in the interrogation phase to grade the idea itself: where it came from, how good the problem is, whether the market and timing hold, and whether "sounds bad" means unpopular-but-good or just bad.
- Work section by section. Each rule gives a check, what good looks like, what bad looks like, and the source.
- Grade origin first (section 1), then problem (2), insight (3), market (4), why now (5), competition (6), contrarian test (7), ambition (8). Consumer ideas also go through section 9.
- Founder quality outweighs idea quality in most YC doctrine; grade the team with `founders.md`. Tarpits, startup-killing mistakes and pivot criteria live in `tarpits_and_kill_signals.md`. Evidence of demand, interviews and PMF live in `validation_and_pmf.md`. Durability and moats live in `moats_and_durability.md`. AI-specific idea rules live in `ai_era.md`.
- Evidence levels are tagged: **[doctrine]** = YC partner or PG stating a general rule; **[anecdote]** = a single founder's story; **[forecast]** = a prediction; **[data]** = a YC-internal statistic as stated by the speaker.
- Most rules here assume a venture-scale startup. If the founder wants a good small business, say which game they are in instead of penalizing it (section 4.6).

---

## 1. Where the idea came from

### 1.1 Organic (noticed) vs made-up (brainstormed)

- **Check**: How did the founder arrive at this idea? Ask for the moment they noticed it.
- **Good**: The idea grew out of the founder's own life, work or project; they wished someone would build it; it started as a side project not meant to be a company. [doctrine] [S10, S12, S05]
- **Bad**: The founder sat down to "think of startup ideas", picked a market from a list, or decided from afar what some other group needs. PG: brainstormed ideas are "bad and plausible-sounding", which makes them expensive to disprove. [S05]
- "The verb you want to be using with respect to startup ideas is not 'think up' but 'notice.'" — Paul Graham [S12]
- Data point: of YC's top 100 companies, "at least 70 percent" had organic ideas. — Jared Friedman [S34] [data]
- Brainstormed ideas drift toward the same tarpits (see `tarpits_and_kill_signals.md`). [S34]
- Young founders produce both the worst made-up ideas and the best organic ones, because they use the newest tools. [S10]
- Organic ideas often do not look like startup ideas at first; fix what is broken even if it seems too small to found a company on. [S10, S05]
- Caveat: PG admits Viaweb was made-up and still worked: "no sharp line between the two types". Do not reject a made-up idea on origin alone; demand stronger demand evidence. [S10]

### 1.2 Live in the future, then build what is missing

- **Check**: Is the founder at the leading edge of some fast-changing field, so the idea feels obvious to them?
- **Good**: The founder uses the latest technology daily and describes the problem as obvious to them. [S12, S05]
- **Bad**: The idea is tied to no frontier and no expertise.
- "Live in the future, then build what's missing." — Paul Graham [S12]
- When searching, turn off the "could this be a big company?" filter early, and pay attention to what chafes. [S12]
- AI-era restatement: "live at the edge and notice what's missing"; ideas found by building, not on a whiteboard. [S33, S54] (detail in `ai_era.md`)
- A field clash helps: an outsider entering a domain does not take its status quo for granted. [S12]
- Research warning: the more a project counts as research, the less likely it is a startup. [S12]

### 1.3 Schlep blindness and unsexy ideas

- **Check**: What is the most unpleasant part of this business, and does the team intend to do it?
- **Good**: The idea needs deals with incumbents, regulation, fraud handling or manual operations that scare other founders off; the team names these schleps and accepts them. [S11]
- **Bad**: The plan is "write code, money rolls in", with no users, partners or messy integrations. "No, you can't start a startup by just writing code." — Paul Graham [S11]
- Known pain with no builder is a signal: thousands of hackers knew payments hurt and built recipe sites instead. Ask what schlep stopped them. [S11]
- Schlep ideas are "like undervalued stocks": less founder demand, less competition. [S11]
- The schlep filter is more likely to be an illusion than the unsexy filter; turning it off matters more. [S12]
- "Make something unsexy that people will pay you for." — Paul Graham [S12]
- Ideas that are "somewhat hard to actually ship the first version of" beat weekend builds; the subconscious pulls founders toward weekend projects. [S33]
- Founders grow with the problem; current team capacity is not the ceiling. [S11]

### 1.4 Generation recipes the sources endorse

Use these to test whether the idea came from a credible process, and to suggest where a founder without an idea should look.

| Recipe | What it looks like | Source |
|---|---|---|
| Own need | "What do you wish someone would make for you?" | [S10, S11] |
| Team expertise | Idea from the founders' own field; "automatic founder market fit" | [S34, S33] |
| Unusual vantage point | Problem seen from a job, internship or family access others lack | [S34, S33] |
| Recent change | New technology, regulation or problem creates an opening | [S34, S26] |
| Proxy elsewhere | A large company doing something similar in another geography or segment (DoorDash as proxy for Rappi) | [S34] |
| Systematic search in a fertile space | Talk to anyone in the industry (A to B at truck stops) | [S34] |
| Get out of the house | Shadow a friend with a boring job, take an undercover job, mine job boards for outsourced clerical roles | [S33] |
| Outsourced or consultant-dependent work | Labor sent offshore or products that need consultants to work are "a strong signal" | [S33] |
| Peers' complaints | "If all of your smart technical friends are complaining about the same thing maybe it's a real problem" — Caldwell/Seibel [S30] | [S30] |
| Problem book | Keep a running notebook of problems, not ideas | [S36] |
| Annoyance | "My source of inspiration is usually being annoyed" — Steinberger [S63] [anecdote] | [S63] |
| Future embarrassment | Imagine how we will seem backward to future generations | [S03] |
| Run the clock forward | "If the launch cost was 10 times lower... what would make sense", then compute the break-even input cost | [S70] [anecdote] |
| First principles gap | List the inputs a buyer needs; find the one with "no button to press" (Scale AI: compute, code, data) | [S39] [anecdote] |
| Premium experience democratized (consumer) | See section 9 | [S21] |

- Caution on "wish it existed": ask "is there a reason why this thing doesn't exist yet". — Jared Friedman [S34]
- An idea search can take about a year; that is "quite normal". [S33]
- Pick one idea and go deep; running several in parallel "tends to produce bad data". — John (YC partner) [S64]

### 1.5 Solution in search of a problem (SISP)

- **Check**: Did the founder start from a technology ("AI is cool, what can I apply it to?") or from a problem?
- **Good**: Problem first, technology chosen to solve it. [S26, S34]
- **Bad**: The founder shoehorns a problem into a solution; the problem they find is "superficially plausible", "made-up". [S34, S26]
- "You want to fall in love with a problem." — Jared Friedman [S34]
- Iterate vs pivot (screwdriver test): keep the user and problem, fix the solution; do not hunt new problems for the tool. [S19]
- "Founders often hold too tightly onto solutions and too loosely onto problems." — Michael Seibel [S16]

---

## 2. Problem quality

### 2.1 Hale's six problem properties [doctrine] [S26]

A good problem has at least one; several is better. "You don't have to have all of them."

| Property | Check | Bad sign |
|---|---|---|
| Popular | Many people have it | Small number of sufferers |
| Growing | Number of sufferers rising | Flat or shrinking |
| Urgent | Must be solved quickly | Can wait indefinitely |
| Expensive | Costly to solve today, so you can charge a lot | Cheap workarounds |
| Mandatory | Required (law, compliance) | Optional |
| Frequent | Hit over and over; daily or several times a day | Once a year |

- Frequency matters because it gives the user many chances to convert and come back. [S26]
- Retention gaps are often trigger gaps (BJ Fogg: motivation, ability, trigger at the same time). Ask what brings the user back. [S26]

### 2.2 Acuteness

- **Check**: What does the user do today without the product?
- **Good**: "If the alternative to your solution is literally nothing that's what a good problem looks like." — Jared Friedman [S34] (Brex: no bank would give startups a card.)
- **Bad**: Users are fine with existing solutions, or do nothing and do not mind. [S34]
- Seibel's version: whose hair is on fire, and would they use a half-baked v1? [S16]
- The pain must be "viscerally felt by a person who would pay money", not hallucinated. — Patrick Collison [S61]

### 2.3 Narrow and deep beats broad and shallow

- **Check**: Who wants this so badly they would use "a crappy version one made by a two-person startup they've never heard of"? — Paul Graham [S12]
- **Good**: A specific small group wants it a lot. "A need that's narrow but genuine is a better starting point than one that's broad but hypothetical." — Paul Graham [S09]
- **Bad**: Many people "could see using" it. Summed mild interest is zero users. [S12]
- Altman: a product a few users love beats one many users like. [S01]
- Sitcom-idea detector: a plausible idea friends answer with "maybe I could see using something like that" (social network for pet owners) is a danger sign. [S12]
- "If all you know about a startup idea is that it sounds plausible, you have to assume it's bad." — Paul Graham [S12]
- Depth needs a fast path out; see 4.1.

### 2.4 Specific and tractable

- Global-poverty-size problems are "too abstract to make good starting points". — Jared Friedman [S34]
- Complex ideas "are almost always a sign of muddled thinking or a made up problem". — Sam Altman [S01]
- The idea should excite at least some people the first time they hear it. [S01]
- Ask the founder for a plain one-sentence description. Can the evaluator reproduce the idea from it? If not, the idea is unclear (application reading rules in `founders.md`). [S17]

### 2.5 Founder as user

- Best case the founder is the target user; second best they understand that user extremely well. [S01]
- "Would you use this thing yourself, if you hadn't written it?" — Paul Graham [S12]
- Founders should become users of their own product, however unnatural it seems. [S10]
- Be skeptical of plans centered on what the founder likes doing (the outdoor-portal founder): liking a domain does not create demand. [S15]
- Founder neither wants it nor knows anyone who does: "you definitely got to worry that... maybe nobody wants this". — Jared Friedman [S34]

---

## 3. Insight and unfair advantage

### 3.1 The idea as a hypothesis [doctrine] [S26]

Hale: a startup idea has three parts: problem (initial conditions), solution (experiment), insight (explanation of why it will grow fast). Without the insight "I can't use my imagination". Locate the part that lacks evidence and tell the founder what to prove next.

- Hale's posture: the evaluator's job is "to figure out how it could possibly win", not only to list what is wrong. Use this as the second half of devil's advocacy. [S26]

### 3.2 Types of unfair advantage (at least one) [S26]

| Advantage | Good | Bad |
|---|---|---|
| Founder | "One in ten of all the people in the world who can solve this problem" | A common job title ("a lot of product managers at Google") |
| Market | Market growing fast (Hale likes ~20% a year) | Stagnating or shrinking; also "one of the weakest" as the only advantage |
| Product | 10x better, visibly ("so much better than everything else") | 2x or 3x |
| Acquisition | Free growth: audience, embeds, word of mouth | Paid acquisition only (discounted heavily) |
| Monopoly | Gets harder to beat as it grows (network effects) | No scale effect (detail in `moats_and_durability.md`) |

- "Well-designed and easy to use" is not an insight. — YC How to Apply [S17]
- Insight must be precise: "a thesis about what everyone else in it is overlooking", sharper than "ours doesn't suck". [S12]
- Best is when incumbents "didn't have the courage of their convictions". [S12]
- Insights can come after starting (Airbnb found payments when a founder forgot to bring money). [S30]
- A simple promise can be enough insight: Coinbase was a website to buy and sell bitcoin. [S30]

### 3.3 Miracle belief

- Separate the threshold belief (they can build it) from the miracle belief (what must be true for it to take off). Ask for evidence on the miracle, not on buildability. [S26]
- B2B and enterprise: the miracle is usually sales ability. [S26]

---

## 4. Market size and the path out

### 4.1 Beachhead plus fast path out

- **Check**: Who is the first narrow market, and where does it lead once won?
- **Good**: A small market with a fast path out (Facebook from Harvard). [S12] A beachhead of people "doing something lots more people will be doing in the future" is big enough no matter how small. [S12]
- **Bad**: A niche that cannot expand, or "everyone" as the first market. [S12, S03]
- Paths out are hard to see; "do not demand a proof of the big market" up front. [S12]
- Altman: "the best answer is going after a large part of a small market." [S01]
- A tiny elite beachhead is powerful (a search engine for the top 10,000 hackers). [S03]

### 4.2 Two kinds of good markets [S34]

- Big now, or small but rapidly growing (Coinbase 2012). — Jared Friedman [S34]
- Altman's questions: size today, growth rate, why big in ten years. [S01]

### 4.3 Scalability test [S08]

- For a company to grow big it must "(a) make something lots of people want, and (b) reach and serve all those people". Barbershops pass (a) and fail (b); "software to teach Tibetan to Hungarian speakers" fails (a). [S08]
- Too few customers who pay a lot can turn you into "a de facto consulting firm". [S08]
- Services, agencies and dev shops that need high-skill labor per customer get into trouble on scale. [S34]

### 4.4 Do not over-trust TAM math

- TAM is "merely an indicator"; neither founders nor investors should use it to cross an idea off. — Light Cone hosts [S29] Flock Safety's TAM was put at "$50 or $60 million a year" and it reached "$7.5 billion". [S29] [anecdote]
- "Be very careful about pretending that you know how big the market could be." — Caldwell/Seibel [S30] Airbnb, Coinbase and Stripe each turned out bigger than the founders knew. [S30]
- The investor-return lens still applies if they raise VC: explain why it could be huge. [S01]

### 4.5 Ambition-size probes

- VC-fundable rule of thumb: can you imagine hundreds of millions or billions in net revenue a year, reached in under 5 to 10 years, with technology the founders build and software-like margins (70-80% gross)? — Dalton Caldwell [S22]
- "Explain to me how your business is going to lead to 100 million of ARR", or "add a zero" to the success metric and work backward. — Photoroom founders [S50] [anecdote]
- Swan test: judge the chance of succeeding really big, not the chance of succeeding at all. [S14]

### 4.6 Good small business is not a failure

- "Most people should not try to start startups." A constrained business may be fine; the evaluator should say which game the founder is in, not penalize it. [S08]
- Taking VC money is "a one-way door" into growth every year; ask whether the founder wants that. [S50]

---

## 5. Why now

### 5.1 Recent change [doctrine]

- **Check**: What changed recently (technology, regulation, a new problem) that makes this possible or necessary? [S34]
- **Good**: A named change (Checkr with gig workforces; Gather Town at pandemic start; law change such as the Affordable Care Act). [S34, S26]
- **Bad**: Nothing changed and the idea is obvious, so it is likely taken. [S08]
- "Formerly bad ideas often become good without anyone noticing." — Paul Graham [S08]
- "There's nothing more valuable than an unmet need that is just becoming fixable." — Paul Graham [S10]
- Great startups "cluster when the ecosystem shifts and incumbents lose a lot of their advantage", when costs fall and cycles shorten. — Sam Altman [S66]
- Ride a wave bigger than yourself. [S12] Pick the exponential with "the steepest curve" that "will go the longest". — Alexandr Wang [S39]
- After a new platform appears, obvious ideas are picked over in about two years; then you must look deeper for a secret. — Light Cone hosts [S29]
- Cost collapse can revive dead ideas: re-test ideas once rejected for cost (formal verification). [S38]

### 5.2 Timing risk

- Right idea, wrong timing kills: Wang's first idea (AI agent for medical care) was right long term and too early. [S39] [anecdote]
- Being early is fatal if the founder's strength is pushing a product to market; tolerable if their strength is turning very early tech into product. [S76] [anecdote]
- Dependence on an external factor outside the founder's control (VR adoption, crypto) is a pivot reason. [S22]
- Being early may mean being "wrong for like almost a decade". — Mark Pincus [S86] [anecdote]

### 5.3 Counterpoint

- "The answer to why now can be because I started now." — Blake Scholl [S40] [anecdote] Many old, solvable problems sit unbuilt in plain sight while founders crowd recent ones. Do not kill an idea only because it could have been built earlier; check that it is truly unsolved. See "Where sources disagree".

---

## 6. Competition and crowded markets

(Durability against competitors is in `moats_and_durability.md`. This section is about what competition says about idea quality.)

- **Competition is usually good**: "A crowded market is actually a good sign", it shows demand and that no solution is good enough. — Paul Graham [S12] "Most good startup ideas have competition." — Jared Friedman [S34]
- **No competitors is a warning**: often "the reason that there are no competitors is because no one wants the product". [S34]
- **Competitors that nobody uses** are the best case: Dropbox faced about 20 competitors "most people didn't use", plus an integration insight. [S34]
- **Entrenched competition needs a new insight.** [S34] Unless a competitor has lock-in that stops users choosing you, do not discard the idea. [S12]
- **Startups are rarely killed by competitors**: "so rare that you can almost discount the possibility". — Paul Graham [S12] Altman: ignore a competitor until it beats you with a shipped product. [S01]
- **Users hate the incumbent**: if you and your friends use the incumbent and hate it, the incumbent's size does not matter. [S30]
- **Incumbent drifting or degrading** makes switching thinkable. [S03] Natural monopolies explain bad incumbent software; you need a plan to crack them. [S17]
- **Derivative crowd**: "If there are ten other companies starting at the same time with the same plan... we are skeptical." — Sam Altman [S01] "Number three through number 98... are going to die." — Light Cone hosts [S29] Same startup as everyone brings hype and money but rarely big outcomes. [S66]
- **Hot means derivative**: choosing an idea because it is hot leads to derivative, obvious ideas. [S29] Wang: you could not have started Scale from reading the press. [S39]
- **Second mover**: find something that works and do it better, unless it has strong network effects. — Punit [S54]
- **Small markets ignored with disdain** by big players are good entry points; replacements come "in from the side". [S12]
- **Obvious consumer ideas went to incumbents**: in categories like general assistants and search, "100% of the value flow to incumbents". — Light Cone hosts [S23]

---

## 7. Unpopular-but-good vs bad

### 7.1 The intersection [doctrine]

- The sweet spot is ideas that seem bad but are good (Thiel's Venn diagram). [S14] "The best ideas sound bad but are in fact good." — Sam Altman [S01]
- "Most good ideas seem bad initially. If they were obviously good, someone would already be doing them." — Paul Graham [S07]
- But: "the vast majority of ideas that seem bad are bad". Sounding bad is necessary, not sufficient. [S14]
- Facebook looked like "a site (1) for a niche market (2) with no money (3) to do something that didn't matter". [S14]

### 7.2 Test: is "sounds bad" a signal or a verdict?

Run these checks. Unpopular-but-good needs most of the left column.

| Check | Unpopular-but-good | Just bad |
|---|---|---|
| Who calls it bad? | Non-users with no experience of the pain [S30]; investors who never used the technology [S39] | Users of the existing product [S30] |
| Is there pull? | Customers pulling it out of the founder [S29]; market begging [S22] | Only praise from friends (a tarpit sign; see `tarpits_and_kill_signals.md`) [S28] |
| Thesis | Founder states a specific belief most people do not hold, from data or direct experience [S29, S66, S39] | No thesis beyond "people are wrong" |
| Toy dismissal | Know-it-alls call it a toy and users like it [S12, S10] | Nobody uses it |
| Obstacles | Founder lists obstacles and a toehold plan [S17] | Obstacles the evaluator sees but the founder never mentioned [S17] |
| Objection type | About imagination (people cannot picture the new cost world) [S70] | About physics or numbers that do not close [S70] |
| Revenue | Grows while investors still call it unsexy [S39] | None |

- "Obviously good" (people really want it) and "obviously ridiculous" (nobody takes it seriously) at once is the Stripe pattern. — Patrick Collison [S61] [anecdote]
- Investor rejection is not a kill signal by itself: Coinbase had "an impossible time raising money on demo day" [S30]; StarCloud was rejected by at least 100 VCs [S70]; Flock was told it was not VC fundable [S29]. Fundraising is "positively misleading" as a quality metric. [S14]
- Fear can be signal, not filter: "non-obvious feels dangerous and scary". [S29] The biggest ideas "seem to threaten your identity". [S03]
- "Nine out of 10 people might tell you you're stupid or crazy", and the one in ten may share your belief. [S29] If you cannot find anyone who shares the belief, pay attention to that. [S66]
- Gray-area legal ideas: value lies where the law predates a tech shift, not in breaking laws that apply. "Don't just run out and do illegal things." [S29]
- Seek ideas that would be popular but seem hard to make money from. [S09]

---

## 8. Ambitious vs small

### 8.1 Doctrine

- "The best ideas are just on the right side of impossible." — Paul Graham [S03]
- Start with a deceptively small thing that works and expand in a direction: "expand westward". Do not chase a precise blueprint. [S03]
- Do not announce the giant goal; "just say you're building todo-list software". [S03]
- Expected value can be high even if the chance of success is low. [S03, S14]
- Ambitious ideas face less competition because others are scared off. [S11]

### 8.2 The most ambitious version

- "The cost of pursuing a wildly ambitious startup idea and the cost of pursuing a modest one are roughly the same." — John (YC partner) [S64] The ambitious version also protects against competitors and attracts talent. [S64]
- Ambitious ideas are easier to hire for, market and fund (with strong investors), if the founder holds the vision and the next practical step together and ships constantly. — James (PostHog) [S79] [anecdote]
- Hard ambitious problems make it possible to hire people smarter than you. [S50]
- YC now funds serious ideas (intercontinental ballistic cargo, many approaches to curing cancer). — Paul Graham [S62]
- Ask: "What is the bigger version if it works 10x?" A small, inconsequential idea is a red flag. [S33]

### 8.3 Ambition with focus

- "Very ambitious in a very wide field" is not credible; go narrow on one problem with a big vision. — Alex [S76] [anecdote]
- Depth delivers ambition: Photoroom grew 10x each time it narrowed (photo, then e-commerce photo). [S50] [anecdote]
- Collison: lean niche-and-expand is now crowded; "more aggressively decorrelate" with ambitious starts, while staying grounded in concrete customer problems. [S61] [forecast/opinion]

### 8.4 Hard and boring beats easy and fun

- "Boring ideas like payroll software have a much higher hit rate than fun ideas like apps to find new restaurants." — Jared Friedman [S34]
- How fun an idea sounds has "little to no correlation" with how fun the company is at month 12. [S34]
- Idea spaces have different hit rates (fintech infrastructure and enterprise vertical SaaS were high in the decade of YC data he cites); spaces flip from hot to cold over time. [S34] [data, time-bound]
- A fertile space lets a team drift into a good idea (Fivetran pivoted twice within it). [S34]

---

## 9. Consumer-specific rules

Apply only to consumer products. Do not apply enterprise rules (LOIs, 10 paying customers) here, and do not apply these to B2B.

- **Testing**: consumer ideas are tested by launching and watching; stated intent does not cut through clutter. Enterprise ideas need a letter of intent before code. — Sam Altman [S01]
- **Love, not like**: unprompted word of mouth is the love signal. [S01] Indifference to a launch ("don't care") means nothing was created; you want love or hate. — Lalit Keshre (Groww) [S47] [anecdote]
- **Higher growth bar**: products not charging need a higher growth rate because they need huge user numbers. [S08]
- **Premium experience to the masses**: find what people "with infinite resources" get (fixer, private banker, personal chef, tutor) and deliver it to everyone with AI, "100x better", not 10% better. — Caldwell/Seibel [S21] Use the star-rating stretch: "what's the six-star... 11-star experience?" [S21]
- **Weak consumer AI pitches**: replacing a human with a "95% as good" chatbot on a cost-saving pitch; a 10% better Kayak; faceless automation. [S21]
- **Competition for attention** is brutal now (TikTok, X); be "way more compelling". Old winners competed with nothing. [S21]
- **Incumbents take obvious consumer categories** (general assistant, search). [S23]
- **Proven, Better, New**: copy what is proven, make it better in a way "10 out of 10 existing users" would agree, and add one new hypothesis you assume is wrong. New gets trial; proven gets retention. — Mark Pincus [S86] [anecdote, framework]
- **Distribution is the unknown**: "there is no proven path for distribution right now... in consumer". Look for a viral hook. [S86] [opinion]
- **Free beats paid** where the incumbent charges ("anything that can be free will be free"). [S86]
- **Design for the cost curve**: imagine the product when intelligence is nearly free. [S86] [forecast]
- **Trust container**: Tribe failed with the wrong trust container; Facebook succeeded through .edu. [S86] [anecdote]
- **Investors versus consumer**: investors may push a consumer team with excellent metrics toward enterprise because it is more fundable; that can be "180 degrees off". [S86] [opinion]
- **Hit rates**: social networks, consumer hardware and adtech had low hit rates in the YC data Friedman cites. [S34] [data, time-bound]
- **Consumer hardware**: crowdfund only after shipping a couple of versions; software is "a lot easier". [S27]

---

## 10. Simple products that became big

- "A product that doesn't work with lots of features is infinitely worse than a product with one feature that works." — Caldwell/Seibel [S27]
- Nail a single use case before serving more. [S27]
- "Googleitis": judging an idea against today's giants instead of what they looked like at the start. [S27]

| Company | Simple start | Source |
|---|---|---|
| Amazon | A site selling books | [S27] |
| Gusto (Zen Payroll) | Online payroll only | [S27] |
| OpenSea | 1-2 years grinding a basic NFT buy/sell site | [S27] |
| Coinbase | A website to buy and sell bitcoin | [S30] |
| Facebook | A site for Harvard undergrads | [S08, S14] |
| Microsoft | A Basic interpreter for the Altair | [S03, S10] |
| Stripe | Almost no features; founders integrated it for users | [S19] |
| Rippling | Offer-letter generator as the wedge | [S69] |
| Airbnb | Floor space at conventions | [S12] |

- Treat the founder's first version as a "useful lie" about what customers want; the more you build before user contact, the more the lie grows. [S27]
- Copy-from-abroad trap: "if blank works here it should work there" without local users. [S27] Groww abandoned a US-style robo-advisor in India. [S47]

---

## 11. Quick question bank (idea quality)

Ask the ones the conversation has not answered yet.

1. How did you notice this problem? (origin, 1.1)
2. Would you use it yourself if you hadn't built it? (2.5)
3. Who wants it so badly they would use a crappy v1, by name? (2.3)
4. What do they do today, and what happens if they do nothing? (2.2)
5. Which of popular, growing, urgent, expensive, mandatory, frequent applies? (2.1)
6. What is your insight, in one sentence sharper than "ours is better"? (3.2)
7. Where does the first niche lead once won? (4.1)
8. What changed recently that makes this possible now? (5.1)
9. Who are the competitors and why do users not love them? (6)
10. Who told you this is a bad idea, and do they have the problem? (7.2)
11. What is the most ambitious version, and what ships this week toward it? (8)
12. What is the unpleasant part of this business that you will do? (1.3)

---

## 12. What YC is asking for now (RFS, Fall 2026)

Snapshot of YC's Requests for Startups as published for Fall 2026 [S92]. It dates: re-check before relying on it, and never treat a match as evidence of demand. Use it only to note that an idea sits in a space partners say they want, and to borrow the partners' questions (cost curve, labor vs software spend, what remains if an incumbent adds an agent).

- The Primer (Miklas): AI tutor teaching young children to read, write and do arithmetic at consumer scale [S92].
- The Future of American Defense (Driscoll, US Secretary of the Army): low-cost interceptors and open-architecture components [S92].
- A Cloud for Small Software (Koomen): hosting for agent-built tools with one or a few users [S92].
- Multiplayer AI (Epstein): shared live agent sessions for teams [S92].
- Compute at Sea (Chaubard): offshore modular compute vessels [S92].
- AI-Powered Consumer Products for 1 Billion People (Schaad): consumer apps now that agents act like people [S92].
- AI for the Aging Population (Kolysh): voice, monitoring, robotics and caregiver software for seniors [S92].
- New Operating Systems for the Physical World (Warren): software managing agents, robots and humans in construction, maintenance and fleets [S92].
- The Best Time to Build in Crypto (Dalal): stablecoins, agentic commerce, tokenized assets, ramps [S92].
- Data for the Real World (Tindle, Hu): new ways to collect dense physical-world data [S92].
- Proving You're Human (Kolysh): verified-human trust layer against deepfake fraud [S92].
- AI-Native Compliance Infrastructure (Goel): consolidated financial compliance with AI as default (see `market_types.md` §3.4) [S92].
- Self-Maintaining APIs (Gaddipati): agents that apply API provider changes to customer codebases [S92].

---

## Where sources disagree

- **Why now.** Friedman [S34], Hale [S26] and PG [S08] treat a recent change as a key test. Scholl [S40] says "why now" is overrated and can be "because I started now". Resolution for the evaluator: ask why now; if there is no change, require a credible reason the problem is still unsolved rather than killing the idea.
- **Competition.** PG [S12] and Friedman [S34] say competition is a good sign and startups are rarely killed by competitors. Altman [S01], Light Cone [S29] and Altman 2026 [S66] warn that crowded, same-plan, hot ideas mostly die or produce hype without outcomes. Both hold: demand-proving competition is good; being one of many identical new entrants is bad.
- **Market size.** Altman prefers "a large part of a small market" [S01]; Friedman wants big now or small and fast-growing [S34]; Hale likes markets growing about 20% a year but calls market growth alone "one of the weakest" advantages [S26]; Caldwell gives a VC-fundable revenue bar [S22]; the Light Cone calls TAM "merely an indicator" [S29] and Caldwell/Seibel warn against pretending to know market size [S30]. Do not kill on TAM; do ask for a path out.
- **Passion vs boring.** Friedman says boring beats fun and passion follows success [S34]. Seibel says founders fail when they lose motivation for a problem they do not care about [S25]; Scholl says passion beats domain knowledge [S40]; Caldwell says find an idea you are excited about and that boring adtech never works [S22].
- **Brainstorming.** PG says do not think up ideas, notice them [S12, S05]. Friedman says organic ideas win but also gives recipes and systematic search [S34]; the Light Cone gives undercover-job and job-board methods [S33]. Treat recipes as ways to put yourself where you can notice, not as a substitute for real users.
- **Narrow start vs ambitious start.** PG [S03] and Caldwell/Seibel [S27] say start small and simple. Collison says lean niches are crowded and ambitious decorrelated starts may now win [S61]; John [S64] and PostHog's James [S79] push for the most ambitious version; Ploy "boils the ocean" with AI [S69]. Alex [S76] and Photoroom [S50] reconcile: narrow problem, big vision.
- **Existing competitor vs new.** Caldwell/Seibel say an existing bad incumbent is an opportunity [S30]; Altman prefers new over derivative and is skeptical of copycats [S01]. The difference is whether the incumbent is hated and whether you have a 10x gap.
- **Consumer investability.** Pincus says consumer is "arguably not investable right now" yet the opportunity is great [S86]; the Light Cone says obvious consumer AI categories go to incumbents [S23]. Both say pick non-obvious consumer ideas.
- **RFS breadth vs narrow wedge.** The Fall 2026 RFS asks for broad AI-native rethinking of whole systems [S92], while YC sales talks push a narrow wedge first [S89]. Read RFS themes as spaces, not as a licence to start broad.
- **Idea vs founder weight.** YC doctrine says founders matter more than the idea [S17, S09] (see `founders.md`), while Friedman shows idea spaces have very different hit rates [S34]. Grade both.

## Sources used

S01, S03, S05, S07, S08, S09, S10, S11, S12, S14, S15, S16, S17, S19, S21, S22, S23, S25, S26, S27, S29, S30, S33, S34, S36, S38, S39, S40, S47, S50, S54, S61, S62, S63, S64, S66, S69, S70, S76, S79, S86, S89, S92
