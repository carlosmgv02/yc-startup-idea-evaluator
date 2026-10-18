# Validation and product-market fit

## How to use this file

- Use it when the founder claims demand, traction or fit, or when you have to propose the fastest test to validate or kill the idea.
- Start with section 1 (evidence ladder) to grade every claim the founder makes. Downgrade anything that sits on the bottom rungs, whatever the founder calls it.
- Pick the stage first: idea stage (no product) uses sections 2-3; launched pre-PMF uses sections 4-7; anything older than ~8-9 months also gets section 8 (default alive).
- Section 9 says when a rule does not apply (regulated, hard tech, enterprise, consumer). Check it before you penalize a founder for not launching or not growing weekly.
- First customers, sales, cold email and pricing live in `gtm_and_pricing.md`. Pivot and kill criteria live in `tarpits_and_kill_signals.md`. Founder traits live in `founders.md`. AI-specific validation (agents, harnesses, model risk) lives in `ai_era.md`.
- Evidence levels used below: **Doctrine** = a YC partner or PG/Altman stating general advice. **Anecdote** = one founder's story. **Forecast** = a guest's prediction. **Data (as stated)** = numbers a speaker cites that the source does not verify.

---

## 1. Evidence ladder: what counts as validation

Grade each claim on this ladder. The founder's own label ("validated", "PMF", "huge interest") does not move a claim up a rung.

| Rung | Evidence | Weight | Source |
|---|---|---|---|
| 0 | Compliments, "great idea", friends' and family's enthusiasm | None. Discard. | [S31, S37] |
| 0 | Answers to hypotheticals ("would you use / pay for this?") | None. Users say yes to every feature. | [S31, S37] |
| 1 | Cumulative signups, waitlist size, app opens, logins | Vanity. Signups without retention is "the classic error". | [S01, S18, S32, S44] |
| 1 | Aggregate DAU/MAU up and to the right | Weak. Goes up with any growth, even if users dislike the product. | [S44] |
| 2 | Interviews about specific past incidents, cost, frequency, current workarounds | Real problem evidence; not demand evidence. | [S31, S37] |
| 2 | Users already paying for or hacking together a solution (incl. Excel) | Problem is valuable and burning. | [S31, S37] |
| 3 | Enterprise letter of intent before code | Accepted entry evidence for enterprise. | [S01] |
| 3 | Card entered / payment for a feature that does not exist yet | Cash behavior beats stated intent. | [S31] |
| 4 | Users return on their own (day 1/3/7/30), long streaks per user on a value event | Retention evidence. | [S18, S44] |
| 4 | 40%+ "very disappointed" if the product went away | PMF proxy (Superhuman survey). | [S31] |
| 5 | Unprompted word of mouth; organic growth with falling CAC | Love. | [S01, S47] |
| 5 | Paying customers who renew; B2B: 10+ paying customers | Durable demand. | [S01, S18] |
| 6 | Team overwhelmed by usage from happy, loyal, paying customers | The PMF bar. | [S16] |

Evaluator rules:
- **Never count rung 0-1 as validation.** If the founder's best evidence is rung 0-1, the idea is unvalidated regardless of volume.
- **Love beats like.** A few users who love it outrank many who like it: "It's much better to first make a product a small number of users love than a product that a large number of users like." — Sam Altman [S01]. Same principle: satisfy all needs of a subset rather than a subset of needs of everyone [S02].
- **Ask "with no asterisks".** "do you have one real user with no asterisks?" — Caldwell/Seibel [S32]. Churned users count as zero: three users who all churned means zero users [S32].
- **Friends and family are a biased sample.** They are the people who most want you to succeed and still do not come back [S18]; they may be less honest to avoid offending you [S37].
- **Problem evidence is not demand evidence.** Willingness to pay for a solution and the problem being valuable are separate checks [S37].

---

## 2. Talking to users (idea stage and forever after)

Doctrine from YC partners [S31, S37], supported by PG [S02, S06] and Rusenko [S18].

### 2.1 Who does it and how

- **Founders, not delegates.** "the best companies are the ones where the founders themselves maintain a direct connection to their users" — Eric Migicovsky [S31]. Red flag: research outsourced to a sales or product hire, or users hidden behind a no-reply address. Gustaf's test: search your email for "do not reply" [S37].
- **Only two jobs early:** build and talk to users [S31].
- **Start before building.** Great founders talk to future customers before there is a product [S37]. But do not wait for hundreds of interviews: alternate understanding and delivery in a tight loop [S64].
- **Video or in person over surveys.** "you can learn a lot more from a five minute video interview than 500 or 5 000 [survey] responses" — Gustaf Alströmer [S37]. Showing up in person works when email fails (firefighters company got dozens of 10-15 minute meetings by walking into fire stations) [S31].
- **How many.** Start with one or two people [S31]; Rusenko suggests 5-10 interviews plus 3-5 UX sessions plus metrics [S18]. See "Where sources disagree".
- **Do not pitch.** The goal is data, "it is not to sell them on using your product" [S31]. Do not introduce the idea until the end of the call, or at all [S37]. Listen; do not talk [S31, S37].

### 2.2 Question script

Use past-behavior questions only. Merged from Migicovsky's five [S31] and Gustaf's six [S37]:

1. Tell me how you do X today. [S37]
2. What is the hardest part about doing X? [S31, S37]
3. Tell me about the last time you hit this problem. [S31]
4. Why was it hard? (Answers become marketing: customers buy the why.) [S31]
5. How often does it happen? [S37]
6. Why is it important to you / your company? Who cares most? [S37]
7. What have you tried to solve it? What do you use today? [S31, S37]
8. What don't you love about what you tried? (Start of your feature set.) [S31]

Follow-ups: "what do you mean by that", "tell me more", "why is that important to you" [S37].

**Banned questions** [S31, S37]: "Would you use our product?", "Would you pay for feature X?", feature wishlists, "what would a better product look like?", yes/no questions, two questions at once.

### 2.3 Reading the answers

- **Burning-problem test:** if prospects are not already exploring solutions, the problem may not be burning enough [S31]. Ask whether people pay money for other solutions today [S37].
- **Frequency or pain:** the best problems are frequent, or painful enough to warrant solving [S31].
- **Users have good problems, bad solutions.** Translate requests into the problem behind them: Gmail users asking for inbox and message on one screen meant slow loading; Airbnb hosts asking for guests' phone numbers meant lack of trust in the platform [S37]. Groww built "the elephant", not the literal request: "you would not build what customer is directly asking but you read between the lines" — Lalit Keshre [S47] (anecdote). Listen to problems, not solutions [S18].
- **Watch behavior, not just words.** Changing behavior is the hard part [S37]. Users who never act on the pain (a client who ignores a consultant's PDF report) are a red flag [S37].
- **Spreadsheet incumbent:** Excel or Google Sheets competes with hundreds of startups; you need a dramatically better experience [S37].
- **Synthesize fast:** bucket the problems, pick the one that matters most, then start designing the MVP; do not over-intellectualize [S37].
- **Hidden need:** the strongest needs are not obvious; market research only describes existing markets, so a new market will not show up in it [S18]. (Idea-quality implications: `idea_sources_and_quality.md`.)
- **Hard number on cost:** "how much does this problem cost them today and I like to get a hard number" — Migicovsky [S31]. Use this for first-customer selection in `gtm_and_pricing.md` §2.

### 2.4 Prototype and UX tests

- Give the user a goal, not instructions; watch; ask them to think aloud [S37].
- "you are not allowed to touch the phone or keyboard" — David Rusenko [S18] (UX session discipline).
- Keep early users in a group chat (Slack/WhatsApp) and react fast to feedback [S37]. Groww put every signup in a personal WhatsApp group [S47] (anecdote).
- Put contact info, including phone number, high in the signup flow [S31]. Airbnb founders gave hosts their personal cell numbers [S37].

### 2.5 Evaluator checks for this section

| Check | Good | Bad |
|---|---|---|
| Who talked to users? | Founders, weekly or daily | A hire, or nobody |
| What was asked? | Past incidents, cost, frequency, workarounds | Hypotheticals, pitch, feature wishlist |
| What do users do today? | Paying for alternatives, hacking spreadsheets | Nothing; cannot describe current process |
| How was it recorded? | Notes from first 5-10 interviews, stack-ranked | Memory, "everyone loved it" |
| Have they watched usage? | Screen-share or in person | Reported behavior only |

---

## 3. MVP scope

### 3.1 Definition and purpose

- "This is the first thing you can give to the very first set of users you want to target in order to see if you can deliver any value at all to them." — Michael Seibel [S19].
- The goal is not how many people want it but whether it solves the problem for any group [S36]. The first version is mainly "a pretext for engaging users" [S02].
- Ship when it has "a quantum of utility" and watch what users do [S06]. Identify a core that is useful alone and expandable into the whole project, then ship it as soon as possible [S13].
- Rusenko's variant: a "minimum remarkable product", the least you can build to be remarkable; launch when it is better than what's out there [S18] (founder anecdote; see disagreements).

### 3.2 Scope rules (doctrine)

- **Weeks, not months.** "you should be able to build it fast in weeks, not months." [S19]. Most consumer and B2B MVPs can launch in under a month [S25]; days or weeks [S36].
- **Three-week spec, written down, then cut.** Only what can be built in three weeks goes on the spec; write it down or "your three-week plan turns into a three-month plan"; if nothing unimportant is left, cut important things [S19].
- **Landing page plus spreadsheet** is an acceptable start [S19].
- **Be the software.** Do by hand what you plan to automate; a manual solution beats "something automatic that doesn't yet solve anyone's problems" [S06]. Stripe signed merchants up manually behind "instant" accounts [S06].
- **Narrow:** a small initial user set and their highest-order problem; ignore the rest [S19].
- **Hold problem and customer tightly, solution loosely** [S19]. Screwdriver test: keep the mechanic and the problem, fix the tool; do not hunt for new problems for your tool [S19]. "Founders often hold too tightly onto solutions and too loosely onto problems." — Seibel [S16]. v1 is usually wrong [S16, S36].
- **Prototype before full build:** building a fully functional product to test a hypothesis is very expensive [S18].
- **Isolate one hypothesis (Proven, Better, New).** Mark Pincus (consumer, founder anecdote/framework): build on something proven, make it unanimously "better" (10 of 10 existing users agree), and expect the "new" part to fail; new drives trial, proven drives retention [S86]. Useful for consumer MVPs to keep the number of unknowns low. Groww's equivalent: reduce open risks to one question mark [S47] (anecdote).

### 3.3 Launch

- "launch is when you get any customers." — Seibel [S19]. Not a press event.
- Many founder journeys end before a single user touches the product [S19]. Launching too slowly "has probably killed a hundred times more startups than launching too fast" [S13]. Biggest post-batch regret at YC: not launching sooner [S75].
- Nobody remembers launch days of Google, Facebook, Twitter, Snapchat, Instagram, WhatsApp, Uber, Lyft [S19, S25]. A big launch or big partnership as the growth plan is suspect [S06, S01].
- You "haven't really started working on it till you've launched." [S02].

### 3.4 How to test, by type (Altman doctrine [S01])

| Type | Fastest credible test |
|---|---|
| Consumer | Launch and watch behavior; stated intent does not cut through clutter. |
| Enterprise | Letter of intent from a customer before writing code. |
| B2B (any) | 10 paying customers is the bar Altman asks about. |
| Regulated or hard tech | "Heavy MVP": start with a simple website explaining what you do; show what you can in days [S19]. |

### 3.5 MVP red flags

- No named first user; "a mysterious set of users" [S19]. Founder knows nobody who has the problem, including themselves [S25].
- Pitch-deck work instead of building [S19]; sizzle (press, hiring, conferences, investors) over steak [S25].
- Feedback dismissed because "it is not the full thing" [S19].
- Months of building, perfectionism ("often an excuse for procrastination") [S06].
- Outsourced build: one shot when you need 20-30 iterations [S18].

---

## 4. Pre-PMF goals and metrics

### 4.1 The goal is users who love it, not a graph

Doctrine from Caldwell and Seibel [S32]:
- With near-zero users, "graphs are a waste of time."
- Goal ladder: 1 real user, then 10, 50, 100 who love it; then graduate to graphs.
- "It's almost impossible in my experience to have something that a hundred people love that's like somehow not growing." If a founder claims love and no growth: "You're either lying about the love or you're not looking at the growing."
- Weekly growth (e.g. 7%) is "a result of doing a lot of things right", not the cause. Hard to sustain while churning users.
- Build for users, not investors; a seed raised on optimized graphs still carries a "2% chance" of ultimate success in their framing.
- Post-PMF analytics habits (big-company A/B testing on tiny samples) do not transfer [S32, S18].

PG and Altman agree on the unit: ten users who love it is a green flag [S02]; unprompted recommendations, fanatical users, users bummed if it disappeared [S01].

### 4.2 Pick an honest value metric

- **Be careful what you measure**; track one number daily [S02].
- **Value event, not vanity event.** Chart "listened to a song", "shared a photo", not "opened the app" or "signed in" [S44].
- **Active users over signups** [S18, S01]. Cumulative signups regardless of use is the canonical cheat [S32].
- **Goodhart check:** founders "choose metrics that cheat" [S32]. Ask whether the metric could be gamed.
- **Time-in-product consistency check** [S32]: "to get value in a week, how much time should a user spend?" vs how much they actually spend. Disqualifying: "we're not measuring", or actual use far below the claimed need (an hour a week against a claimed hour a day).
- **Quantify the benefit:** a dollar amount for the customer, not time in app [S32]. Examples given: Whatnot sellers earn a living, DoorDash a third of a restaurant's revenue, Twitch streamers quit their jobs [S32].
- **Small samples mislead.** Do not tell stories with metrics that lack statistical significance [S18].

### 4.3 Dot plots and returning usage

- **Dot plot:** one row per user, one column per day, a dot per value event. "until you have hundreds of users the dot plot could be your only dashboard" — Dave [S44]. Cheap to build (minutes with AI coding tools [S44]); no excuse not to have it.
- Read for: one-and-done rows (onboarding or value problem), long streaks (value), features that precede streaks (hypothesis for causal value), segments (sort rows by platform, geography, income) [S44].
- Cohort curves tell *whether* groups stick; dot plots tell *how* [S44].
- **Returning usage at day 1, 3, 7, 30** is Rusenko's core early signal [S18].
- **B2B seat activation:** seats bought vs seats ever activated. Example: $80,000/year contract, 10 seats bought, 3 activated, nobody used it more than 2 days a week, churned at renewal [S44]. Single-champion adoption is a single point of failure; churn is visible in usage before renewal [S44].

### 4.4 Iteration capacity

- Expect roughly ten times more iterations than you think; runway must cover 20-30 iterations, not 2-3 [S18] (founder heuristic).
- Optimize for learning: pick the biggest unknown and work on it [S18]. PostHog set weekly learning goals ("can we get one single user to use this thing in production"), not revenue goals [S79] (founder anecdote).
- Cheapness = more iterations; running out of money is the most common death [S02].

---

## 5. Growth rate benchmarks (launched companies)

Applies once there is a product with users or revenue. For pre-100-user companies, apply §4.1 first.

| Metric | Benchmark | Source / level |
|---|---|---|
| Weekly growth during YC | 5-7% good; 10% exceptional; 1% = not figured out | PG [S08], doctrine |
| 10% a week compounding | ~14,000 users after a year, ~2 million after 2 years | PG [S06], illustration |
| 1%/wk vs 5%/wk | 1.7x vs 12.6x a year | PG [S08] |
| Annual revenue growth to count on investor interest while unprofitable | over ~5x a year | PG [S04], doctrine |
| End-of-batch revenue (2026) | median ~$20,000 MRR vs ~$8K earlier; some 0 to seven figures in 3 months | YC hosts [S72], data as stated |
| NPS | above 50 is "doing pretty well" | Rusenko [S18], founder heuristic |
| PMF survey | 40%+ "very disappointed" | Migicovsky citing Superhuman [S31] |

Rules:
- **State growth as a ratio**, not an absolute count. "a hundred new customers a month" constant = decaying growth rate [S08].
- **What to measure:** revenue first; active users if not charging [S08]. Usage-only (no monetization) companies need a higher growth rate, because investors discount predicted revenue and these companies need huge numbers [S08, S04].
- **Honest growth only:** no buying users above lifetime value, no counting inactive users as active, no manufactured invites [S08].
- **Paid-only growth is discounted.** "if paid acquisition is the only way that you were able to grow your company then I'm gonna discount that channel of growth greatly" — Kevin Hale [S26]. Word of mouth is the favorite [S26].
- **Churn edge case:** fast spread with high churn stalls when potential users run out [S08].
- **Small absolute numbers are fine** if the rate is good; ask "how big could this company get if the founders did the right things?" [S06].
- **Hype-budget risk (2026):** hosts flag that some AI revenue may come from experimentation budgets ("AI hype") [S72]. Ask whether demand is durable beyond that.
- **Weekly measure does not fit everything:** "A startup building a new database will probably not do that." [S08].

---

## 6. Real PMF vs false PMF

### 6.1 Definitions in the sources

| Definition | Who | Level |
|---|---|---|
| Overwhelmed by usage, can barely change the product; "a frantic founding team" with ever more happy, loyal, ideally paying customers | Seibel [S16] | Doctrine |
| Customers buying as fast as you can make it (Andreessen, as quoted) | [S16] | Doctrine (quoted) |
| 40%+ "very disappointed" in the Superhuman survey; Migicovsky calls PG/Andreessen definitions vague and retroactive | [S31] | Doctrine |
| "you have it when growth is not your biggest problem. It's other stuff." | Dalton Caldwell [S22] | Doctrine |
| "the whole world is beating a path to your door"; press and users arrive unprompted | Rusenko [S18] | Founder anecdote |
| Organic growth: customers come without paid acquisition; CAC falls while engagement and retention rise | Keshre [S47] | Founder anecdote (consumer) |
| Gradual compounding, no single moment; a sale closing for a company the founders did not recognize | Landau [S80] | Founder anecdote (B2B/infra) |
| Enterprises chasing you to sign the security agreement so employees can keep using the product | Jay, OpenCode [S48] | Founder anecdote (devtools) |
| Strong emotional reactions from users | Steinberger [S63] | Founder anecdote (open source) |

Use Seibel's as the bar and the others as observable proxies. A founder need not hit every proxy, but must show at least one rung 4-6 signal from §1.

### 6.2 False PMF signals (downgrade)

- Headcount or a funding round cited as fit [S16]. Raising is not fit; seed odds still low [S32].
- Rising signups with low returning use [S18, S01].
- "Moderately appealing" product with decent early growth and an easy first round [S04].
- **Uncanny valley:** a little traction can trap founders longer than an immediate failure would [S22].
- Friends and family usage [S18].
- Revenue from AI experimentation budgets [S72].
- Interest income on the raise exceeding customer revenue: Legora had a month like that and treated it as a bad sign [S59] (anecdote).
- Enterprise contract where most seats never activate [S44].
- Launch met with indifference: "if it is don't care that is the problem" — Keshre [S47].
- Growth explained by excuses other than the product. "very often the real reason is that the product just isn't good enough." — Altman [S01]; slow growth is usually the product not being appealing enough [S04].

### 6.3 Signals that fit is real

- Users hack the product to do something unintended; double down there [S18].
- Unprompted word of mouth [S01]; organic growth [S47].
- Beating a modest target by a wide margin: Groww expected 100 customers in a month and got 600 [S47] (anecdote).
- Renewal rate high (share of eligible customers who renew) [S18].
- Customers repeatedly asking for the next reasonable feature (Stripe's just-in-time development: card charge, then dashboard, refund, payout) [S61] (anecdote).
- Customers who cannot be pushed to a higher price signal limited value: PostHog's first customer would not pay more [S79] (anecdote; use as a test, see `gtm_and_pricing.md`).

### 6.4 Before vs after fit

- Before fit: stay lean, keep burn low, "resemble a Navy SEAL team instead of an Army battalion" [S16]. Do not hire, raise burn or optimize the product before discovering what to build [S16].
- Rusenko: do not scale past ~20 people before PMF; after PMF never more than double headcount in a year [S18] (founder heuristic).
- After fit: optimize the core product, hire specialists, make strategic investments [S16].
- Monetization is usually easier than PMF [S18]. Unit economics may be bad early only with a good reason they work later [S01]. Scaling bad unit economics for impressive numbers is premature scaling [S04].

---

## 7. Retention and love/hate signals

- **Love-or-hate launches.** Each launch should provoke "love it" or "hate it"; indifference means nothing was created [S47] (consumer anecdote, offered as a rule).
- **Trigger gap.** Low retention is often a trigger problem: you are hoping users "will somehow just remember on their own that they have the problem" — Kevin Hale [S26]. Ask what brings the user back.
- **Trial vs retention.** The new feature gets the first try; the proven core is what users come back for [S86].
- **Daily-use products give faster signal** (Pebble as a daily-worn watch) [S31].
- **Founder as power user.** Keshre uses Groww 2+ hours a day [S47]; Pincus distrusts a consumer CEO who does not love their product [S86]. Founder as first user (Gmail, built for himself, one or two users added a week, under 100 users for months) [S32].
- **Renewals over churn rate** for subscription products [S18].
- **Customer lifecycle:** as users' needs change, the product must evolve or rivals take them [S47].
- **Champion risk (B2B):** when the champion leaves, a new person comes in and usage drops [S44].

---

## 8. Default alive or default dead (older than ~8-9 months)

Doctrine from PG [S04], with Altman and Seibel in support.

- **The test:** with expenses constant and revenue growth as over recent months, "do they make it to profitability on the money they have left?" [S04]. Trevor Blackwell's default alive calculator exists for this [S04].
- **Self-knowledge signal:** "Half the founders I talk to don't know whether they're default alive or default dead." [S04]. Not knowing is itself a red flag.
- **Fatal pinch:** "default dead + slow growth + not enough time to fix it." [S04].
- **Make the hope explicit:** "We're default dead, but we're counting on investors to save us." [S04]. Fundraising is plan A only; plan B and its trigger date must be written down [S04].
- **Hiring:** "Hiring too fast is by far the biggest killer of startups that raise money." [S04]. Staff is an effect of growth, not a cause. Airbnb waited 4 months after YC funding to hire its first employee [S04]. Spend and growth are weakly linked [S04].
- **Ramen profitable** changes the relationship with investors [S02].
- **Raise for the next visible step** with 50-100% buffer, because software and deals take longer [S13].
- **Paying distractions** (day jobs, consulting, profitable side projects) are the worst kind [S02].

Evaluator: for a company older than ~8-9 months, ask the default-alive question before anything about ambition. If dead, the conversation is rescue: product appeal, growth, cuts, plan B [S04].

---

## 9. Applicability: when these rules bend

| Situation | What changes | Source |
|---|---|---|
| Idea stage, no product | §§1-3 only. Ask for interviews, a named first user, a 3-week MVP plan. Growth benchmarks do not apply yet. | [S19, S31, S37] |
| Launched, <100 users | §4.1 governs; do not demand a weekly growth graph. Ask for users who love it and a dot plot. | [S32, S44] |
| Launched, with revenue | Apply §5 growth benchmarks; revenue is the metric. | [S08] |
| >8-9 months old | Add §8 default alive. | [S04] |
| Regulated (banking, lending, payments, legal) | Launch-fast is relaxed: heavy MVP, longer pre-launch acceptable if there is a stream of real feedback. Cost of failure (money, security, reliability) justifies preconditions. | [S19, S25, S61] |
| Hard tech, deep infrastructure (a new database) | Weekly growth metric may not fit; check progress milestones and grounding instead. | [S08, S19] |
| Risk-averse buyer where one failed demo is fatal | Pausing sales to fix reliability can be right (Legora, 6-month freeze). | [S59] (anecdote) |
| Consumer | Launch and watch; stated intent is worthless; growth bar is higher if not monetizing; love-or-hate reactions matter. | [S01, S08, S47] |
| Enterprise | LOI before code; seat activation and champion risk; renewal rate. | [S01, S44, S18] |
| Not venture-scale by design | Do not penalize a good small business; tell the founder which game they are in. | [S08] |

---

## 10. Evaluator question bank (ordered)

1. Who exactly has this problem, by name, and when did you last talk to one of them? [S19, S31]
2. What do they do today to solve it, and what does it cost them (hard number)? [S31, S37]
3. What did you learn that changed the idea? [S02]
4. What can you put in front of users in three weeks? Why not this month? [S19, S25]
5. How many real users with no asterisks, and how many love it? [S32]
6. What is your value event? Show me one row per user per day. [S44]
7. What share of users come back at day 1, 7, 30? What share would be very disappointed without you? [S18, S31]
8. Weekly growth as a percentage of revenue or active users? How much is paid or churn-masked? [S08, S26]
9. Are users recommending it without being asked? [S01]
10. Default alive or dead? What is plan B and its trigger date? [S04]

**Fastest validation proposals** to offer (pick the one matching the stage):
- No interviews yet: 5-10 past-behavior interviews this week with the §2.2 script, notes stack-ranked by cost, frequency, budget [S18, S31].
- Problem confirmed, no product: landing page plus manual service ("be the software") to 1-5 known users within 3 weeks [S06, S19].
- Enterprise: ask for an LOI or a paid pilot with the value equation as success metric (see `gtm_and_pricing.md` §6) [S01, S20].
- Feature uncertain: pay-first upgrade flow before building [S31].
- Launched: run the 40% survey and build a dot plot this week [S31, S44].

---

## Where sources disagree

1. **Weekly growth as the goal.** PG makes growth rate the compass and 5-7%/wk the YC benchmark; pick a target and hit it weekly [S08, S06]. Caldwell and Seibel say graphs are a waste before ~100 lovers and that 7% is a result, not a cause; they grant "the genius of that advice" mainly as a way to expose churn [S32]. Resolution for the evaluator: apply §4.1 below ~100 engaged users, §5 above.
2. **Launch fast vs launch late.** Launch in weeks, under a month [S19, S25, S13, S75]. Stripe took about two years to public launch; Collison says that is fine only with a steady stream of real production users ("grounding") and when cost of failure is high [S61, S32]. Legora froze sales for six months for reliability [S59]. Rusenko says launch when better than what is out there ("minimum remarkable product") [S18], against "launch something bad quickly" [S19].
3. **What PMF is.** Overwhelmed by usage [S16] vs 40% survey, which explicitly calls PG/Andreessen definitions vague [S31] vs NPS >50 [S18] vs "growth is not your biggest problem" [S22] vs gradual compounding with no moment [S80]. Not reconcilable into one number; use §6.1 as a set of proxies.
4. **How many interviews.** Start with one or two [S31]; 5-10 [S18]; one founder did 200 before building [S53]; do not wait for hundreds, loop with delivery [S64].
5. **Friends as first users.** Start with yourself and friends for warm access [S31]; friends may soften the truth [S37]; friends and family do not return, so their usage misleads [S18].
6. **Charging early.** Revenue is the best growth metric [S08] and "what's your revenue" is a core question [S27]; Altman asks for 10 paying B2B customers [S01]. Groww ran about four years with zero revenue, accepted because CAC was near zero and retention high [S47] (consumer anecdote, not doctrine).
7. **Metrics discipline.** Rusenko: anecdotal is okay, do not overthink, and he did not measure KPIs for 18 months (which he says made PMF slower) [S18]; Seibel: measuring usage is part of building [S25]; dot-plot doctrine: read every user every day [S44].
8. **Interviews vs asking users.** Talk to users is the default remedy, but Altman notes it "doesn't work in every case" (Ford's faster horses) [S01]; Gustaf resolves it by translating requests into problems [S37].

## Source IDs used

S01, S02, S04, S06, S08, S13, S16, S18, S19, S22, S25, S26, S27, S31, S32, S36, S37, S44, S47, S48, S53, S59, S61, S63, S64, S72, S75, S79, S80, S86
