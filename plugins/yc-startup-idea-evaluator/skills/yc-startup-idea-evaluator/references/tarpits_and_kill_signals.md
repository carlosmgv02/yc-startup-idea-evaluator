# Tarpits, startup-killing mistakes and pivot criteria

## How to use this file

- Use it when an idea pattern-matches a known failure, when you need to decide whether "it sounds bad" means tarpit or unpopular-but-good, and when the founder already has a product and asks whether to keep going, pivot or stop.
- Section 1 defines a tarpit. Section 2 is the catalogue. Section 3 is the test that separates a tarpit from an unpopular-but-good idea. Section 4 lists the recurrent mistakes that kill startups, each with a detection question. Section 5 gives pivot and kill criteria. Section 6 lists how named YC companies pivoted.
- Never call an idea a tarpit only because it resembles a catalogue entry. A tarpit verdict needs the history-and-change test in section 3; the list is not static. [S28]
- Evidence tags: **[doctrine]** YC partner or PG general rule; **[anecdote]** one company's story; **[data]** YC-internal statistic as stated; **[opinion]** a guest's view.
- Idea-quality rules (origin, problem, market, why now) are in `idea_sources_and_quality.md`; false PMF and validation evidence in `validation_and_pmf.md`; team red flags in `founders.md`; AI wrapper risk in `ai_era.md`.

---

## 1. What a tarpit is

- **Definition**: a "smallish set of ideas" that many founders apply with "over and over and over again", that YC often funded, and that keep failing. — Dalton Caldwell and Michael Seibel [S28] [doctrine]
- Friedman's version: a common idea that seems easy, where "there's actually a structural reason why it's very hard or impossible to solve which is why after all these years no one has solved it". — Jared Friedman [S34]
- **Not just a bad idea.** Most ideas are "neither good nor bad, they're just normal". A tarpit needs all of:

| Criterion | Check |
|---|---|
| Common | Other founders "come up with them all the time constantly" [S28] |
| Praised | Friends love it. Honest friends usually say an idea is not good; "tarpit ideas get like a lot of praise" [S28] |
| Seems easy | "It seems so easy... why does this already exist" is "not like the shape of things that we see" [S28] |
| Tried and failed | "It's been done a lot, a lot of people have failed" [S28] |
| Nothing changed | No new technology or condition that removes the structural block [S28, S34] |

- **Common is not tarpit**: "copilot for X" (real estate agents, lawyers, dentists) is common but not a tarpit, because not enough people have tried it exactly. [S28]
- **Not static**: "this is not a static list of ideas". New technology can untar a pit; YC funds AI-generated personalized podcasts that it "would not have funded... in the pre-LLM world". [S28]

### 1.1 Two flavors [S28]

1. **The world should work differently.** "Wow, the way X works is..." Coming from a good place, but "it's just hard to change human behavior." Example: coordinating friends to hang out; "nobody would say no" and nobody adopts.
2. **Arbitrage / get rich quick.** "I have some secret knowledge and I can get very rich very fast." Mercenary, tied to a moment. Example: investment advisory from a founder doing well on Wall Street Bets.

---

## 2. Catalogue

Each entry says why it fails and which type of warning it is. **Tarpit** = repeated failure per [S28, S34]. **Low hit-rate space** = historical YC data, time-bound. **Structural** = incumbent or economics usually win. None is an automatic kill; apply section 3.

| Idea pattern | Type | Why it fails | Source |
|---|---|---|---|
| Restaurant / food discovery ("can't decide where to eat") | Tarpit | Praised by friends; classic repeat failure | [S28, S34] |
| App to coordinate friends meeting up / event planning | Tarpit (flavor 1) | Needs everyone to change behavior at once | [S28, S34] |
| Investment advisory from a hot trading streak | Tarpit (flavor 2) | Arbitrage window, mercenary | [S28] |
| Social network or portal "for X" (pet owners) | Sitcom idea | "No one is going to visit 20 different communities regularly" | [S12] |
| Recipe sites, local events aggregators | Schlep-avoidant, low stakes | Chosen because easy, nobody pays | [S11] |
| Portal for the founder's hobby ("outdoor portal") | Founder-preference idea | Liking a domain does not create demand | [S15] |
| Social networks, consumer hardware, adtech | Low hit-rate space | Low billion-dollar rate in the decade of YC data cited; spaces flip | [S34] [data] |
| Boring adtech | Low hit-rate / motivation | "Never work... not inspirational and no one cares" | [S22] |
| General consumer assistant or search | Structural | "Probably the incumbents will win all of those" | [S23] |
| Hackathon or thin wrapper with a cool demo | Structural | "Cool demo but there weren't customers that were willing to pay" | [S33] |
| Software a model plus a weekend can replicate (Calendly-, DocuSign-type) | Structural | Pure software is "too easy to replicate now" | [S75] |
| Copy of a model that works in another country | Trap | "If blank works here it should work there" without local users | [S27, S47] |
| Marginal niche picked to avoid competition | Trap | "You can only avoid competition by avoiding good ideas" | [S13] |
| Derivative copy of an existing company | Trap | Starts from a company, not a problem | [S13] |
| Same plan as ten other teams starting now | Trap | "We are skeptical" | [S01] |
| Hot-topic idea from X or TechCrunch | Trap | Derivative and obvious | [S29, S33, S39] |
| Another vertical AI agent for insurance or banking with no unique insight | Crowded | Several funded startups already, no secret | [S29] |
| Consumer AI replacing a human at "95%" quality on a cost pitch | Weak consumer pitch | Not 100x better, not magical | [S21] |
| Hardware crowdfunding before shipping a version | Trap | Unknown build cost, price and timeline; backers hold you accountable | [S27] |
| Non-technical team, unlaunched tarpit idea | Lowest odds at YC interview selection | Statistic on interview odds, not on company success | [S24] [data] |

Detail on AI-wrapper and point-solution risk: `ai_era.md`. Detail on easy-to-copy software: `moats_and_durability.md`.

---

## 3. The test: tarpit or unpopular-but-good?

Run in order. Stop as soon as a step decides.

**Step 1. Has the founder done the history?**
- Ask: "Who has tried this before and why did they fail?"
- Good: They Googled it and talked to past attempters, and can name "the hard part of this idea... that has caused other people to not be able to solve it yet". — Jared Friedman [S34]
- Bad: Unaware, or "history starts when I was born". Founders "avoid research to not learn things they don't want to learn". [S28]
- "What I hate to see is a Founder that's not even acknowledging that like many people have tried and failed before." — Caldwell/Seibel [S28]

**Step 2. Is there a structural reason it fails?**
- Name it: coordinated behavior change, a two-sided cold start, an incumbent with lock-in [S12], a natural monopoly [S17], unit economics. If the founder cannot name one for a heavily tried idea, they do not understand the space.

**Step 3. What changed, and does the change hit that structural reason?**
- Good: The founder "can explain to me why the new technology might make something accomplishable that wasn't accomplishable before". [S28]
- Bad: No link "between the two, technology and why your problem can be solved today", for an idea tried many times. [S28]
- Dead bodies are not proof by themselves: check whether pre-AI failures were failures of the missing capability. — Light Cone hosts [S29]
- AI can make a previously unworkable business model work; do not dismiss on "there have been a bunch of different kayaks and none of them worked". [S21]

**Step 4. Who praises and who criticizes?**
- Praise from friends, especially when it comes easily, is a tarpit sign. [S28] Politeness is not traction. [S22]
- Criticism from non-users is noise; criticism from users of the existing product is signal. [S30]

**Step 5. Is there pull from real customers?**
- Customers "pulling it out of" the founder, even while peers say "you're working on a tarpit idea", is the strongest counter-signal. [S29]
- "If the market's begging for something and you don't even think it's good... that's a pretty good sign." — Dalton Caldwell [S22]
- Before asking anyone whether it is a tarpit: "you should talk to users and get a customer". [S28]

**Step 6. Does it require everyone to change behavior at once, or is it an arbitrage window?**
- Yes to either = flavor 1 or 2 tarpit unless step 3 or 5 is strongly positive. [S28]

**Verdict table**

| Steps 1-2 done | Step 3 change | Step 5 pull | Verdict |
|---|---|---|---|
| No | — | — | Unresearched; send the founder to do steps 1-2 before anything else |
| Yes | None | None | Tarpit: kill or reframe |
| Yes | Credible, linked | None yet | Open question: fastest test is to get one customer |
| Yes | Any | Strong | Treat as unpopular-but-good; keep testing |

For the general "sounds bad but is good" signals (toy dismissal, contrarian thesis, investor rejection), see `idea_sources_and_quality.md` section 7.

---

## 4. Recurrent mistakes that kill startups

Root cause: "there's just one mistake that kills startups: not making something users want." — Paul Graham [S13] The rest are ways to get there. "Most startups fail because they don't make something people want, and the reason most don't is that they don't try hard enough." [S13]

### 4.1 Idea and problem mistakes

| Mistake | Detection question | Source |
|---|---|---|
| Solving a problem no one has | "Who has this problem? Name them." | [S12, S13] |
| Made-up problem from a technology (SISP) | "Did you start from the technology?" | [S34, S26] |
| Problem picked to look good, not cared about | "Would you work on this for five years?" | [S25] |
| Helping users you do not care about | "Do you like the people who use your product?" (Justin.tv before Twitch) | [S25] |
| No specific user ("someone will want it") | "Can you talk specific ones into using it?" | [S13] |
| Problem where you know nobody who has it, including yourself | "Who are your first five users by name?" | [S25] |
| Validation from investors, press, friends, competitions instead of users | "What validation do you have not from those?" | [S27] |
| Seeking authority figures to approve the idea | "What do your own customer conversations say?" | [S27, S28] |
| Fit assumed from another market | "Has a local user said they want it?" | [S27] |

### 4.2 Product and launch mistakes

| Mistake | Detection question | Source |
|---|---|---|
| Launching too slowly | "What stops you launching this month?" Slow launch "killed a hundred times more startups than launching too fast" — PG | [S13, S25] |
| Boiling the ocean: many use cases, none nailed | "Which single use case have you nailed?" | [S27] |
| Building everything before a single user | "Have you got a single user yet?" | [S27, S19] |
| Falling in love with the MVP, not the problem | "What would make you throw v1 away?" | [S36] |
| No usage measurement | "What do you measure about usage?" | [S25] |
| Techno-weenies solving interesting technical problems instead of users' problems | "Is this a problem you care about or one users care about?" | [S15] |
| Wrong platform that looks responsible (Java applets) | "Why this platform?" | [S13] |
| Big launch, big partner or press as the growth plan | "What will the founders personally do to get users?" Altman: such deals "effectively never work" | [S06, S01] |

Exception: in heavily regulated markets (banking, lending) launching early is hard [S25]; where the cost of failure is high, longer pre-launch is acceptable with a steady stream of real-customer grounding [S61]. Selling to unforgiving buyers before the product is reliable can be fatal (Legora froze sales for six months) [S59] [anecdote]. Detail in `validation_and_pmf.md`.

### 4.3 Company-building and money mistakes

| Mistake | Detection question | Source |
|---|---|---|
| Playing house: office, hires, round, no product people want | "How is usage growing?" | [S05] |
| Sizzle over steak: press, hiring, conferences, investors (cargo cult) | "What did you do this week besides those?" | [S25] |
| Fundraising as scoreboard | "Why do you want investors to like you before users do?" | [S05, S14] |
| Hiring too fast ("by far the biggest killer of startups that raise money") | "Headcount vs proof of product appeal?" | [S04] |
| Premature scaling of bad unit economics for impressive numbers | "Unit economics today and why they improve?" | [S04, S01] |
| Raising too little to reach the next visible level; take 50-100% more | "What does this round get you to?" | [S13] |
| Raising too much, hard to change direction | "Could you still pivot with this team?" | [S13] |
| Underfunding an experiment so the result is ambiguous ("worth $50 million or zero, not $5 million") | "What does the experiment cost? Raise twice that." | [S58] [opinion] |
| Not knowing default alive or dead | "At current burn and growth, do you reach profitability?" | [S04] |
| Running out of money just before the product is good | "Runway to the point the product is good?" | [S15] |
| Interest income above customer revenue | Sign the money outpaced the product | [S59] [anecdote] |
| Bad growth excuses; real reason is usually the product | "Why not faster?" | [S01, S04] |
| Signups without retention | "Retention by cohort?" | [S01] |
| Hiring before the idea works, especially while pivoting | "Do you know the idea works?" | [S22, S13] |

### 4.4 Founder and team mistakes

(Full treatment in `founders.md`.)

- Single founder: "the founder couldn't talk any of his friends into starting the company with him". [S13] Statistics have shifted; see `founders.md` section 6.
- Cofounder chosen out of convenience or recently met; suppressed misgivings. [S13, S25, S01]
- Non-technical founders outsourcing the product: "business guys can't tell which are the good programmers". [S13]
- No founder willing to sell or find users: "you can't just hack". [S13, S06]
- Day job kept, half-hearted effort. [S13, S02]
- Slow-moving founder: "I have never, not once, seen a slow-moving founder be really successful." — Sam Altman [S01]
- Early-stage founder focused on personal brand or with a publicist: "they almost always fail". [S01]
- Delegating judgment or customer conversations. [S58, S75]
- Obstinacy or the opposite, switching ideas every week (section 5.3). [S13]

### 4.5 Hard-tech specific

- One giant first prototype that tests everything at once; plan simpler builds with "multiple shots on goal". — Blake Scholl [S40] [anecdote]
- Every iteration depends on outside suppliers; no plan to integrate. [S40]
- Deep-tech companies rarely fail because the technology does not work; they fail on organization once they have hundreds of people. — Max Hodak [S58] [opinion]
- Idea whose break-even input cost is far below what is achievable (space solar at $50 per kilo; 95% transmission loss). "Kill the idea your numbers kill." [S70] [anecdote]
- Plan that requires raising $100 million before a prototype. [S22]

---

## 5. Pivot and kill criteria

### 5.1 Pivoting is normal and should be light early

- A pivot is just changing your idea. If you are not rapidly changing ideas or assumptions early, "you are likely doing it wrong". — Dalton Caldwell [S22]
- "On average most people take too long to pivot." [S22]
- In the average YC startup, about "70% of the idea is new at the end of the first three months". — Paul Graham [S09] [estimate]
- Opportunity cost: working on something with evidence it is not working means not doing something else. [S22]
- Shots on goal: luck is easier with "half a dozen shots on goal than one"; each shot is a full iteration shipped to people. [S22, S79]

### 5.2 Good reasons to pivot [S22 unless noted]

- Months of full-time effort with no progress.
- The founders hate working on it.
- Not growing.
- "You are just not the right person for the idea."
- Out of ideas for the current one.
- The idea depends on an external factor outside the founder's control (VR adoption, crypto).
- Real evidence that the fundamental hypothesis was wrong. [S75]
- Users are excited about the new direction: "probably a good bet". [S13]
- Customers pull the pivot out of you (GoCardless). [S75]
- The numbers kill it (StarCloud pivoted within two months). [S70]
- Repeated customer questions point to a different product (Groww). [S47]
- "A lot of founders know secretly that their thing isn't working." [S22]

Caldwell's joke pseudo-formula, useful as a prompt: if (how well it works ÷ months of concerted full-time effort) < (excitement for something else + confidence you can find better), pivot. [S22]

### 5.3 Bad reasons to pivot

- **Dodging sales**: building, then pivoting "right when it gets to sales time", repeatedly. [S22]
- **Hot trend**: pivoting after a TechCrunch funding story. [S22]
- **Lost enthusiasm only**: pivot on evidence, "not sadness". [S75]
- **Grass is greener**: leaving a domain you know deeply for a shallow one; "the grass will not be greener". [S75, S33]
- **Thrash**: switching every week. Convergence test: "If in each new idea you're able to re-use most of what you built for the previous ones, then you're probably in a process that converges." — Paul Graham [S13]
- **Whiplash**: "it's more deadly to your company to get whiplash and get sad than to work on a bad idea." [S22]

### 5.4 Traps that delay pivots

- **Uncanny valley of PMF**: "a little bit of traction" can trap founders; a total immediate failure "is actually a huge advantage". [S22]
- **Politeness mistaken for traction**: "add a few more features and we'll look". [S22]
- **Blaming the world**: "I'm not wrong. The world is wrong." / "way ahead of its time". [S22]
- **Five years on one failing idea**. [S22]
- **Perseverance stories** are lottery anecdotes, not a strategy. [S22]

### 5.5 Iterate vs pivot

- Keep the user and the problem, change the solution (screwdriver test). Searching for new problems for the same tool is the wrong move. — Michael Seibel [S19]
- Love the problem, not the MVP. [S36]
- Ego check: stay "passionate about the instinct" and "dispassionate about this particular product variant". — Mark Pincus [S86] [opinion]

### 5.6 After choosing the new idea

- Score the candidate 1-10 on four criteria and average: how big, founder-market fit, ease of getting started, early market feedback. "Ease of getting started" is undersold. — Dalton Caldwell [S22]
- Look first where the founders are experts; founders are often "allergic" to their own expertise. [S33]
- Pick one and burn the other boats: stop the others, tell customers you pivoted. — John (YC partner) [S64]
- Prefer something you can build and validate fast (a prototype in a weekend or two weeks). [S22]
- Do not hire while pivoting. [S22]
- Set weekly learning goals, not revenue goals, e.g. "can we get one single user to use this thing in production". — James (PostHog) [S79] [anecdote]

### 5.7 When to stop entirely

The sources say little about shutting down; what they say:
- Determination without flexibility ("don't give up on your dreams") is a red flag. [S07]
- Do not start, or keep, a company you would not want to keep; it becomes a trap. — Blake Scholl [S40] [opinion]
- Persistence vs obstinacy is "a hard judgment call". — Sam Altman [S01]
- OpenCode's founder says the prudent path in his case would have been to shut down, and survived only by living with parents: "don't try this at home". [S48] [anecdote]

---

## 6. How YC companies pivoted

| Company | From | To | Lesson | Source |
|---|---|---|---|---|
| Slack | Game (Glitch), ~100 employees | Team chat | Pivots can happen late | [S22] |
| Brex | Cardboard VR sunglasses / VR headset | Credit card for startups | Strong team plus founder-market fit (prior fintech sale in Brazil) | [S75, S22, S34] |
| Retool | Venmo for the UK (losing money per transaction) | Internal tools builder, built in two weeks | Escape the traction trap | [S22] |
| Magic | Blood pressure coach | Weekend prototype, #1 on Hacker News | Ease of start | [S22] |
| Segment | Classroom feedback tool | Open-source analytics library the market begged for | Market pull | [S22] |
| Justin.tv | Online reality show | Twitch, live game streaming | Founder who loves the users (gamer) | [S36, S25] |
| GovDash | Four failed ideas | Government procurement; Series B | Identity change each pivot | [S64] |
| Groww | US-style robo-advisor | Transparent investing marketplace | Read repeated customer questions | [S47] |
| Fivetran | Data analysis tools | What companies actually wanted, twice in one space | Fertile idea space | [S34] |
| Gather Town | Prior idea | Pivot at pandemic start | Recent change | [S34] |
| Datacurve | Consumer app (Uncle GPT) | Data for LLMs via a Cohere internship | Expertise from an internship | [S33] |
| Giga ML | Edtech, then fine-tuning | Customer support, won in a crowded space | Technical delivery | [S33] |
| Juicebox | Freelancer marketplace, AI people search | Agent that contacts and schedules | Do the whole job | [S33, S72] |
| OpenSea | Earlier idea | Simple NFT buy/sell site | Simple thing ground out | [S27] |
| Coinbase | P2P transfers | Buy/sell bitcoin website | Simple promise | [S30] |
| Reddit | Accepted with no code | Forced to pivot immediately | Founders over idea | [S26] |
| GoCardless | Sports-team payments | Broad payment collection | Customer-pulled | [S75] |
| StarCloud | Space-based solar | Data centers in space | Break-even math | [S70] |
| Ollama | Kubernetes tooling, desktop security | Local LLMs in a two-week sprint | Bias to action | [S60] |
| PostHog | Many pivots | Product analytics, then AI "self-driving software" | Shots on goal | [S79] |
| Lyft | Zimride long-distance | Short rides with smartphones | Platform shift | [S29] |
| NVIDIA | Wrong algorithm, undeliverable Sega contract | Pivot via OpenGL textbooks | Cheap learning loop | [S56] [anecdote] |
| Hotmail | A tool to talk about a previous startup idea | Webmail | Side tool became the company | [S12] |
| Greplin | Several ideas | — | Record flexibility | [S07] |

---

## Where sources disagree

- **Is the tarpit list fixed?** Friedman frames tarpits as structurally hard ideas and lists low hit-rate spaces [S34]. Caldwell and Seibel say "this is not a static list" and new technology can reopen them [S28]. The Light Cone hosts go further: peers calling it a tarpit while customers pull is not a reason to stop [S29]. Rule: the label needs the section 3 test.
- **When to pivot.** Caldwell says most founders pivot too late and should pivot early and often [S22]. The YC panel says pivot only on real evidence, not lost enthusiasm [S75]. John says pick one idea and burn the boats [S64]. Caldwell himself warns that whiplash kills [S22]. PG's reuse test separates healthy pivoting from thrash [S13].
- **Launch fast.** PG [S13], Seibel [S25] and the YC panel [S75] say launching too slowly kills. Collison accepts a slow public launch where failure is costly if real-customer grounding is steady [S61]; Legora froze sales to fix reliability [S59]. Regulated markets are an explicit exception [S25].
- **Money.** PG says too little and too much money both kill [S13]. Hodak says some ideas need $50 million or zero [S58]. Graham 2026 says you can still start with little money and raise on milestones [S62]. Collison says capital now makes bigger first versions possible [S61].
- **Competition as a kill signal.** Altman is skeptical of ten teams with the same plan [S01]; PG says competitors rarely kill startups [S12]. See `idea_sources_and_quality.md` section 6.
- **Hard tech.** Caldwell scores a VR headset by a non-expert founder 1/10 on founder-market fit [S22]; Scholl says hardware barriers are lower than thought but his company nearly died repeatedly over 10+ years [S40]; Hodak would not recommend capital-intensive biotech if you have a choice [S58].
- **Perseverance.** Altman calls persistence vs obstinacy "a hard judgment call" [S01]; Caldwell dismisses perseverance success stories as lottery anecdotes [S22]; Pincus says being early can mean being wrong for almost a decade [S86].

## Sources used

S01, S02, S04, S05, S06, S07, S09, S11, S12, S13, S14, S15, S17, S19, S21, S22, S23, S24, S25, S26, S27, S28, S29, S30, S33, S34, S36, S40, S47, S48, S56, S58, S59, S60, S61, S62, S64, S70, S72, S75, S79, S86
