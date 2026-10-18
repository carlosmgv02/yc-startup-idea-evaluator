# Go-to-market and pricing

## How to use this file

- Use it when you assess how the founder will get the first users or customers, who sells, which channel, and what to charge.
- Evaluate the idea as a pair: what they build plus the unscalable thing they will do to get going (§1). An idea with no credible first-10 plan is incomplete, not just "early".
- Identify the segment first (consumer, SMB, enterprise, devtools) and use §8 to pick the right rules. Do not demand enterprise rigor (LOIs, champions, signing authority) from a consumer app, or viral loops from an enterprise sale.
- For pricing questions use §6-§7. Most pricing doctrine here is B2B; consumer pricing has thin sourcing, say so rather than invent.
- Validation evidence, interview scripts and PMF metrics live in `validation_and_pmf.md`. AI pricing models (outcomes vs seats) are covered in depth in `ai_era.md`; incumbent pricing as a moat in `moats_and_durability.md`. Pivoting to dodge sales is a kill signal in `tarpits_and_kill_signals.md`.
- Evidence levels: **Doctrine** = YC partner or PG/Altman general advice. **Compilation** = S53 is a partner summarizing founder answers on Bookface (anecdotal, survivor-biased). **Anecdote** = one founder's story. **Data (as stated)** = unverified figures from a speaker.

---

## 1. Core doctrine: founders make it take off

- "Actually startups take off because the founders make them take off." — Paul Graham [S06]. Reject "build it and they will come".
- **Idea as a vector:** evaluate "pairs of what you're going to build, plus the unscalable thing(s) you're going to do initially" [S06].
- **Effort test:** "Any strategy that omits the effort — whether it's expecting a big launch to get you users, or a big partner — is ipso facto suspect." [S06]. Altman: deals with other companies and big press launches "effectively never work" [S01].
- **Sales is the founder's job.** "You have to do sales yourself initially." [S06]. Tech startups need at least one founder who is, or can become, good at sales and talking to users [S01].
- **Go out and get users:** "You can't wait for users to come to you." [S06].
- **No way to recruit users manually** for these founders is a sign the idea is bad "at least for those founders" [S06]. Enterprise idea with no small set of reachable users and no connections: "should you even be working on such an idea?" [S06].
- **Distribution is now a hard part.** With software easier to build, distribution can be "one of the hard things" [S75]; "The hardest problem now is like getting eyeballs" — Peter Steinberger [S63] (open-source founder anecdote).

Red flags: plan relies on a big launch or a big-company partnership [S06, S01]; founders will not sell or talk to strangers ("shyness and laziness") [S06]; "marketing channel" answers with no names [S06]; founder with a publicist or personal-brand focus [S01].

---

## 2. Choosing the first segment and first customer

### 2.1 Segment

- **Contained fire:** find a subset where you can reach critical mass quickly [S06]. Facebook started as "a site for Harvard undergrads" [S08].
- **Quickest to sign up over highest payers:** those are probably the early adopters [S06].
- **Find the vein:** if you are not your own user, run a fairly untargeted launch, watch who is most enthusiastic, seek more like them [S06]. Pinterest found design enthusiasts and recruited at a design bloggers conference [S06].
- **Build for yourself:** then "you only have to find your peers" [S06].
- **Hand-picked, filtered first users** for whom the problem is really important and who will try a startup [S36].
- **Tiny elite beachhead:** a small, powerful first group can beat broad reach (search used only by the top 10,000 hackers) [S03].
- **Large share of a small market** is Altman's preferred answer on market [S01] (market sizing lives in `idea_sources_and_quality.md`).
- **Customers who grow with you:** Supabase's ICP was venture-backed companies likely to grow fast [S51] (anecdote).
- **Avoid too few customers:** a handful of big payers can turn you into a de facto consulting firm [S08].

### 2.2 Startups and engineers as first customers

- B2B: "the best early adopters are usually other startups" [S06].
- Counterpoint: software engineers are "one of like the worst customers to sell to"; they change tools on a whim [S69] (founder view). See disagreements.
- **Startups only if you know which game you play** (Taggar, Seibel, Flora [S91], doctrine). Valid games: Stripe (win at two people, keep to IPO), Gusto (startups as a bridge to similar SMBs), AWS (startup engineers carry it into enterprises, which still needs an enterprise sales team later) [S91].
- **The customer must have the problem at its current size.** "if you tried selling snowflake to a startup they you just waste your time" [S91]. Selling an HRIS to startups is a waste [S88].
- **Churn as they grow:** products that scale with headcount (HR, CRM) get replaced as customers grow; products that scale with revenue (payments) stay [S91]. The buyer can change too (founder or engineer replaced by a marketing or recruiting team) [S91].
- **Fear-of-sales check:** "a lot of times ... when startups want to sell just to other startups it's because they are afraid to do the sales" [S91]. Willing to talk is not willing to buy; startups are not lower maintenance [S91]. Self-serve is not a distribution strategy [S91].
- Check: "Which game are you playing? What happens to the account at 100 or 500 people?" Bad: no path from startup customers to the end market; the problem only exists at scale [S91].

### 2.3 Scoring a first customer (B2B)

Migicovsky's three numbers [S31], stack-ranked in a spreadsheet:

| Axis | Ask | Good |
|---|---|---|
| Cost of the problem | "how much does this problem cost them today" (hard number) | High, measured |
| Frequency | How often do they hit it? | Daily or weekly |
| Budget and authority | Can this contact pay and decide? | Yes, or the decision maker is in the room |

- Wrong first customer is a trap: it can constrain you "without actually getting paid" [S31]. Smoothie-blender example: McDonald's beats a fine-dining restaurant and a Google cafe on all three axes [S31].
- **Consult for one user:** find one user who needs it and can act on that need; fit them perfectly [S06]. Do not charge by the hour for it, or "they expect you to do everything" [S06].
- **Sell above the team being replaced.** If the product replaces a team, that team will sabotage a bottom-up sale; sell to a decision maker high enough, or to companies without that team yet [S23]. Rainforest QA pitched "you don't need a QA team at all" [S23].
- **Ease of selling varies:** plumbers and contractors are "notoriously difficult" compared with startups [S37].

---

## 3. First 10 customers playbook

Main source: a YC visiting partner compiling Bookface founder answers [S53] (compilation; anecdotal, survivor-biased), with PG [S06] and YC partners [S31, S37, S83].

### 3.1 Phase model [S53]

| Customers | Where they come from |
|---|---|
| 1-3 | Personal network. "customers 1 through three almost always come from your personal network" (no counter-examples found in the survey) |
| 4-10 | Manual, unscalable, in-person or in-community work |
| 10-50 | Start tools (Apollo, Clay, LinkedIn Premium, Happenstance) only after 10-20 quality customers |

Early buyers "are buying because they trust you as a founder not just because of the quality of the product" [S53]. If the first three are strangers, ask how.

### 3.2 Channel follows the buyer

- First question: "where does your target customer actually spend their time" [S53].
- **Buyer-day test:** if the founder cannot describe the buyer's day concretely, they have not spent enough time with customers [S53].
- **Wrong-channel false negative:** cold email to non-desk buyers (school administrators, property managers, truck dispatchers) fails; that does not prove outbound fails [S53].
- One founder "closed more in 3 days than he had in 3 months of sending cold emails" at a trade show [S53].

### 3.3 Tactics that worked (compilation and anecdotes)

- **Work the network first:** unmessaged second-degree connections before outreach tools [S53]. Shake the tree with friends, family, investors; conversion is much higher [S83].
- **Make warm intros easy:** say who, why they care, and give a forwardable blurb [S53].
- **Be in the room:** in person "works better than basically anything else" [S53]. Founders flew to one buyer four weeks in a row; one was kicked out after 8 minutes and still landed a top account [S53]. Pebble did guerrilla meetings at CES for $0 [S31]. Firefighters company walked into stations after cold email failed [S31].
- **Conference calendar:** before a small industry conference, email the attendee list and fill back-to-back 15-minute slots [S53].
- **Micro dinners:** 6-10 ICP people at $50-100 each convert better than big events [S53].
- **Find public complaints** on Reddit, Facebook groups, forums and DM individually; lurkers convert quietly. A healthcare founder answered 2-5 threads a day for months [S53].
- **Give before asking:** a vulnerability scan, walkthrough or compliance note; "20 minutes of work before asking for 30 minutes of someone's time" [S53].
- **Research at scale before product:** one founder talked to 200 salespeople before building; 50% accepted connection requests, 20% converted to calls; she had a pipeline when the product shipped [S53].
- **Pay for feedback in high-ACV markets:** lawyers paid $100-200/hour, ~30% accepted, CAC stayed reasonable [S53].
- **Non-sales framing** (advice, product review) only if genuine; do not disguise a sales call [S53].
- **Audience before launch:** Wufoo had a blog audience of ~100,000 developers before launch and embedded forms that spread the product [S26] (anecdote). PostHog got early traction from non-product work (audience and brand with engineers) [S79] (anecdote).

### 3.4 Do things that don't scale (PG doctrine [S06])

- **Collison installation:** "Right then, give me your laptop" instead of "we'll send you a link" [S06].
- **Delight:** an insanely great experience with a buggy product if you make up the difference with attentiveness. "I have never once seen a startup lured down a blind alley by trying too hard to make their initial users happy." [S06]. Wufoo's hand-written thank-you notes [S06].
- **Door to door:** Airbnb in New York helping hosts improve listings [S06]; Pinterest's Silbermann recruited strangers in coffee shops [S01].
- **Use the software for lukewarm users** (Viaweb built stores for merchants) [S06].
- **Hardware:** assemble it yourself first (Meraki, Pebble hand-assembled the first several hundred before $10 million on Kickstarter) [S06].
- **Unscalable service is a learning tool**, and incumbents' atrocious service is an opening [S02].
- **Founder availability as a weapon:** founder phone numbers and 24/7 support, which Salesforce and Oracle cannot match [S20].

Limit: unscalable work is capped by the need to make money eventually [S01].

---

## 4. Founder-led sales

- **Founders sell first; hire sales after you understand it.** Encord's first two sales teams failed, the third worked; the founder stayed "intensely involved in every single part" of early deals [S80] (anecdote).
- **For B2B and enterprise, sales is the miracle to believe in:** "success will be determined by how well you can do sales how well you can tell the story" — Kevin Hale [S26].
- **Enterprise entry evidence:** LOI before code; 10 paying customers for B2B [S01].
- **Do not depend on deals closing.** Treat pending deals as background processes; Viaweb had about 20 deals fall through [S02]. Count only signed revenue.
- **Time kills deals:** reply fast [S83].
- **Trust before scale with unforgiving buyers.** Lawyers give "one chance to get it right"; Legora froze sales for six months to fix reliability [S59] (anecdote). Rule: if one failed demo kills the account, push quality before pushing pipeline.
- **Do not oversell to customers who do not need it yet at scale** [S80] (anecdote).
- **Status quo now looks risky to enterprises,** so they buy from startups more readily [S61] (Collison's view); enterprises are "trained on" point solutions [S23]. Treat as context, not proof that a given enterprise will buy.
- **Dodging sales:** founders who pivot right when it is time to sell [S22]. Cross-ref `tarpits_and_kill_signals.md`.
- **Founders avoid outbound; schedule it.** "the number one difference between founders who actually succeed ... is actually following through on the activity that they commit to" [S83].
- **Founders can sell enterprise themselves:** "if you aren't able to sell your product yourself at first chances are you're not going to be able to hire somebody else to do it for you" — Pete Koomen [S88] (doctrine).

### 4.1 Enterprise funnel, founder-run (Koomen [S88], doctrine)

| Stage | What good looks like | Red flag |
|---|---|---|
| Hypothesis | Written: "customer X has problem Y and our product will help them solve it"; you can name whom to call | Too vague to name a buyer |
| Prospect | People taking calls match the buyer profile | Easy-to-reach non-buyers; "the illusion that you're making progress" |
| Qualify (first call) | Mostly questions: how bad, how quantified, why unsolved, budget, how they buy, who decides; disqualifying is success | Pitch with no questions |
| Demo | A story about her problem with one flow, personalized with their data | Feature tour |
| Price | Each quote is an experiment; quote high (Optimizely asked $10,000/month, accepted $2,000) | Free for feedback |
| Close | Buying process and signers mapped early; security questionnaires in parallel; simple paper (Common Paper) | "Done deal" with unknown procurement |
| Implement | Vendor owns it; plan before signing; funnel ends at habitual use | "The customer will integrate it"; six-figure deals with zero usage (Optimizely) |

- **Top-down vs bottom-up fit:** if adoption needs many teams (hospital: CIO, software team, doctors, ops), individual contributors cannot buy; go to the CFO or CIO [S88].

### 4.2 Pilots, design partners and contracts (Blomfield [S89], doctrine)

- **Most founders are too slow** through the stages (design partner, pilot, contract) [S89].
- **Unpaid design partnership smell:** 3-6 months, vague scope, unpaid, low engagement, a logo on the website; polite partners imagine one more feature instead of saying it sucks [S89]. A growing bespoke requirements list from a free customer makes you an unpaid dev shop [S89].
- **Narrow wedge, then 10 similar customers:** a wedge can ship "in as little as 48 hours"; sell it to 10 similar customers before building a broad platform [S89].
- **Paid pilot over free:** "Getting a financial commitment from the customer is going to make them take your pilot much, much more seriously" [S89]. Take less money if it fits the champion's own approval limit (e.g. a $10,000-$20,000 card) and skips procurement [S89].
- **Pilot design:** agreed success metric from the value equation; low-risk format (backtest on history, side-by-side with humans, 1% of volume, one geography); a live project, client data and a named person; check-ins every couple of days; 7-14 days if the product is ready; post-pilot meeting booked before start [S89].
- **Time to first value is the north star;** janky is fine (Excel, emailed data); no integration needing customer engineering [S89].
- **Opt-out contract:** a monthly or annual recurring contract with a 30-60 day money-back period converts by default: "one sales process that turns into a recurring revenue contract" [S89]. Caveat: do not count opt-out-period contracts as ARR without telling investors [S89].
- **Signed is not implemented:** one YC company had $4 million signed and under $2 million implemented [S89]. Early on you sell the founders, including a cell number [S89].
- **Map every gatekeeper:** economic buyer, technical approver, security, legal, daily users; start SOC 2 if enterprise-targeted [S89].

### 4.3 Forward deployed engineers (McGrew [S90], operator view, Palantir/OpenAI)

- **Default is don't:** "my first, second, and third pieces of advice ... is like don't don't do this at home" [S90]. Use FDE only if a standard product cannot scale in the market [S90].
- **When it fits:** heterogeneous segments inside large enterprises and no incumbent product to copy (AI agents), so discovery happens inside the customer [S90]. Needs a 3x-10x change for the customer and a problem in the CEO's top five [S90].
- **Product vs consulting test:**

| Signal | Product (good) | Consulting (bad) |
|---|---|---|
| Margins on the same account | Negative at first, positive after a year or more | Stay negative; headcount per customer flat |
| Second customer | Reuses what the first built; product leverage rises | Every deployment bespoke |
| What gets built | One level more general than the request | What the customer asks for; one customer's solution pasted into the product |
| Sponsor | Near the CEO, strategic problem | Far from the CEO, easy tasks |
| Contract | Outcome-based and growing | Small flat contracts with heavy custom work |

- KPI is contract size and outcome value, the opposite of the PMF playbook's cost-per-customer reduction [S90]. Examples: Castle and Happy Robot with outcome-ramp pricing (YC companies) [S90].
- **Who must say yes:** IT, on-prem and security gatekeepers are not aligned with the end user; you need top-down authority [S90].
- Applicability: large-enterprise, high-contract AI deployments only. Do not apply to SMB, consumer or self-serve ideas.


---

## 5. Cold outbound

Main source: OneSchema founder and former YC visiting partner [S83] (doctrine from a practitioner), with [S53] and [S54].

### 5.1 Rules

- **100 by hand before automating.** "do at least 100 outreaches by hand before you automate anything" [S83]. A thousand-email blast with zero replies teaches nothing, because any of targeting, prospects, message, subject or deliverability could be wrong.
- **Targeting beats copy.** "those wrong job titles were never going to buy no matter how good your email was" [S83].
- **Find the buyer from closed deals:** who pushed the deal, who signed, who paid [S83]. With no customers: who has most to gain (a CSO who could be fired for a breach; not an engineering manager who would rather not be monitored) [S83].
- **Verify company fit by hand:** list tools return false matches (IT consultancies for "tech companies") [S83].
- **Intent signals:** job postings, headcount growth (compensation planning at ~100-500 employees) [S83].
- **Message their pain, not your features.** Executives do not care that your database is built in Rust [S83].
- **Structure:** one-sentence explanation, credibility (named customers or relevant background), a specific ask ("Got 20 minutes to hop on a call this week?") [S83].
- **Length:** 5-8 sentences for email, 2-5 for LinkedIn [S83]; under 75 words, read-aloud test [S53].
- **Peer tone.** The good example: informal, referenced a prior employer's fix for the same problem, noticed something on the prospect's site, proposed an experiment [S83].
- **Subject lines:** odd ones can win ("broken agents" beat "better agents for every workflow") [S83].
- **Baseline:** 2-3 replies per 100 emails is a fine start for iterating [S83].
- **Follow up 2-4 times,** ending with a low-pressure breakup email (higher reply rates; a real no is data) [S83].
- **Steal the customer's words:** ask what got their attention and why they bought [S83].
- **Cold works when the product is clearly better:** no warm intro or US presence needed; an Indian student sold to US insurers by email [S54] (investor/founder view).

### 5.2 Debug order when replies are zero [S83]

1. Right person (title) → 2. Right companies → 3. Subject lines → 4. Messaging → 5. Materials (website, LinkedIn) → 6. Deliverability.
If all six check out and replies are still zero, suspect a product-market fit problem [S83]. Before that, check channel fit: a non-desk buyer is a channel problem, not a PMF problem [S53].

---

## 6. B2B pricing

Main source: Tom Blomfield, YC partner [S20] (doctrine). Others noted.

### 6.1 Method

1. **Value equation first.** Write down with the champion what the product will do for them in money: time saved (cost), cost reduced, or revenue increased [S20]. The champion must challenge it.
2. **Price at 25-50% of value.** "they keep roughly 2/3 you keep roughly a third" [S20]. Worked example: 100 agents at $100,000 fully loaded = $10M; 20% reduction = $2M saving; charge ~$700k [S20].
3. **Cost is a floor, never the method.** Cost-plus "always ends up with you underpricing" [S20]. Target 80-90% software margins [S20].
4. **Treat cloud and AI credits as cash cost.** Free credits end and margins break [S20].
5. **Check value share vs cost.** If your share of value is $150k and cost is $200k, "you're in a bad" business [S20]. Pricing at or below cost is a land-grab bet that costs fall; "very very dangerous" [S20].
6. **The value equation is the pilot's success metric** [S20].

Fallback when you cannot do the math: pick a number and raise it 50% with every new pitch [S20]. "over optimizing for pricing early is a big mistake" [S20].

### 6.2 Structure

- **Mirror how they already pay for software** [S20].
- **Keep it simple:** "over complicating pricing will kill a sales process" [S20].
- **Committed recurring (MRR/ARR) beats usage-based**; pure usage revenue falls off a cliff in a bad month and investors worry [S20]. Bridge: start on usage for a month or two, then offer a commitment based on observed usage [S20].
- **Signing authority:** ask how much the champion can approve without the CFO or legal; price the first deal to fit or plan for approvals [S20].
- **Enterprise tier:** gate SOC 2 reports, SSO, audit logs, compliance reports, data residency; can be priced up to ~10x [S20].
- **Enterprise prices are "contact sales"**: value differs per customer; publishing leaves money on the table [S20].
- **Pilots:** long free trials or pilots are counterproductive (customer not bought in). Prefer an annual contract from the start with a 30- or 60-day money-back guarantee [S20]. Short paid pilots and opt-out contracts: §4.2 [S89].

### 6.3 Price tests

| Signal | Meaning | Source |
|---|---|---|
| Every deal closes immediately | "almost certainly underpricing" | [S20] |
| >25% of deals lost on price alone | Probably in the right ballpark | [S20] |
| Customer will not pay more when you try to raise | Low perceived value; PostHog's early customer | [S79] (anecdote) |
| Buyer and boss cannot name the category | They cannot price a "new thing"; frame it as an existing category | [S78] (Datadog founder anecdote) |
| Price anchored to consumer SaaS ($19 or $49/month) with no value math | Guesswork | [S20] |

- **Willingness to pay for time sinks is higher than founders assume:** PG would pay $50/month for better email given the hours it takes [S03].
- **No price wars on commodities.** Head-to-head undercutting drives margin out (airlines: 2.7% net margin); differentiate by niche, integrations, industry [S20].

### 6.4 AI-era pricing notes (brief; details in `ai_era.md`)

- Flat seat pricing breaks when agent loops consume more tokens; Dust moved from seats to credits [S71] (founder anecdote).
- Startup pricing increasingly on work delivered or tasks completed; per-seat pricing is the incumbents' weak spot if agents reduce headcount [S35] (YC partners).
- Token cost acts like CAC: free tokens that deliver the "magic moment" replace ad spend; check cost per activated user [S48] (founder anecdote).
- Gusto warns that running an LLM every 30 minutes gets expensive; choose deterministic jobs where possible [S67] (anecdote).
- Blomfield's "treat credits as cash" and 80-90% margin target apply directly to AI products [S20].

---

## 7. Price must fit the channel

| Rule | Threshold | Source / level |
|---|---|---|
| Sales force needs price | at least ~$200-300 per month per customer | Rusenko [S18], founder heuristic |
| Dead zone | ~$75/month: too expensive for impulse, too cheap for a sales force | Rusenko [S18] |
| Direct sales affordable | net LTV above $500; below that, repay CAC within ~3 months without sales | Altman [S01], doctrine |
| Salesperson economics | ~5:1 new signed ARR to total salesperson compensation | Blomfield [S20], doctrine |
| Too-small deals for outbound | if a rep would need ~42 deals a month, it is not an AE motion | Blomfield [S20] |

Rusenko calls this "product market Channel model fit" [S18]. Evaluator: compute contract size times realistic close rate against the channel the founder names. A mid-price product with an outbound team, or a $5k ACV with field sales, is a structural flag.

Also: ad-supported plans that rely on buying users are a red flag [S01]; paid-only growth is discounted [S26].

---

## 8. GTM by segment

### 8.1 Consumer

- Test by launching and watching behavior; intent statements do not cut through [S01].
- Word of mouth is the target; paid acquisition is discounted [S26, S01].
- Distribution is the open problem: "there is no proven path for distribution right now in I would argue in consumer" — Mark Pincus [S86] (founder view). Ask for the viral hook.
- Growth bar is higher when not monetizing [S08].
- Obvious general consumer AI (assistants, search) tends to go to incumbents [S23]; consumer AI that replaces a human at "95%" quality with a cost-saving pitch is weak; aim for a premium experience made far better and available to everyone [S21]. (Idea-level detail in `idea_sources_and_quality.md`.)
- Organic, near-zero CAC plus high retention can justify deferring monetization (Groww, ~4 years) [S47] (anecdote; exception, not rule).
- Love-or-hate reaction to launches [S47]; CEO must love the product [S86].

### 8.2 SMB and non-desk buyers

- Hard to sell (plumbers, contractors) [S37]; channel must match where they are (trade shows, in person, communities) [S53].
- Recurring pain "on my calendar" sells with little effort; start from known recurring tasks, not a blank canvas [S67] (Gusto, incumbent with an existing base; anecdotal).
- Small businesses adopt AI readily because no job-loss resistance [S67] (anecdotal).

### 8.3 Enterprise and mid-market

- LOI before code [S01]; champion-owned value equation [S20]; signing authority [S20]; short pilot with metrics or annual with money-back [S20].
- Enterprise tier gates (SOC 2, SSO, audit logs, residency) [S20].
- Sell above the team the product replaces [S23].
- Watch seat activation and champion risk after the sale (see `validation_and_pmf.md` §4.3) [S44].
- Security and trust are adoption gates for agents and capture products [S43, S49] (anecdote/incumbent view).
- PMF tell: inbound security questionnaires from companies whose employees already use it [S48] (anecdote).
- Founder-led sales first, hire sales by trial [S80]. Full founder-run funnel in §4.1 [S88].
- Paid 7-14 day pilot with a booked post-pilot meeting, then an opt-out recurring contract; avoid long unpaid design partnerships [S89] (§4.2).
- FDE only when no standard product can scale; watch the product-vs-consulting signals [S90] (§4.3).
- Startups are the wrong first customers for enterprise-only problems [S88, S91] (§2.2).

### 8.4 Developer tools and open source

- **Position by familiar reference:** "open source Firebase alternative" took off where a technical tagline had not [S51] (anecdote).
- **Time to value as the core metric:** Supabase measured the incumbent (8.5 minutes to launch an RDS instance, connect, insert a row) and drove theirs under a minute, now ~5 seconds [S51] (data as stated).
- **Community where users live:** Reddit, Twitter, Hacker News [S51].
- **Counter-position against the incumbent's own offering** [S51].
- **Slow early revenue is normal:** first revenue after ~1.5 years; ~$1M ARR first revenue year, then $7.5M [S51] (data as stated).
- **Agents as users:** Supabase says 60% (likely ~90%) of its databases are launched by agents [S51] (speaker's figure). Ask whether agents pick the product, but do not bet on becoming the agent default by luck [S51].
- **Bottom-up entry:** free, no-permission tools enter enterprise from below [S60].
- Engineers churn on a whim [S69].

---

## 9. Positioning and distribution

- **Remarkable spreads:** "if something is remarkable that you're building people will remark upon it on the internet" — James, PostHog [S79]. In a busy market the problem is standing out, not creating demand [S79]. Treat go-to-market "like a product" [S79].
- **Name an existing category** so buyers know the budget line [S78].
- **Customers over competitors;** do not chase feature grids [S18]. Ignore competitors until they beat you with a shipped product [S01]. Worrying about competitors moves you away from customers [S47].
- **Win one job better than anyone** [S18]; brands come from an unacknowledged consumer insight (Virgin America) [S18].
- **Embeds and built-in spread** (Wufoo forms) [S26].
- **Competitor missteps can be growth events** (OpenCode after a rival restricted third-party use) [S48] (anecdote).
- **Timing vs founder type:** being too early kills founders whose strength is pushing a product to market; founders good at turning early tech into product tolerate it [S76] (founder view). Market-opening events (ChatGPT) can make buyers "open to the conversation" [S80].
- **Edge of tech vs GTM polish in AI:** one investor-founder says this wave rewards living at the technical edge more than a polished GTM [S54] (view, see disagreements).
- **Platform dependence:** a single provider changing terms can cut distribution (Steinberger says one provider cut access with 24 hours' notice) [S63] (anecdote). Cross-ref `moats_and_durability.md`.

---

## 10. Evaluator checklist

| Question | Red flag answer | Source |
|---|---|---|
| Who were or will be your first 3 customers, by name? | Strangers via cold tools, or "the market" | [S53, S06] |
| What unscalable thing will you do in month one? | "Launch and see", a press launch, a partnership | [S06, S01] |
| Where does your buyer spend the day? | Email and LinkedIn because it is easy | [S53] |
| Who sells, and how many hours a week? | A sales hire; CEO delegates | [S06, S80] |
| How many outreaches by hand? Reply rate? Which debug step is ruled out? | Zero or a blast; no numbers | [S83] |
| What is the customer's quantified value, and your share of it? | No math; consumer-SaaS price guess | [S20] |
| Cost to serve one customer, without credits? Gross margin? | Near cost; margin well under 80% | [S20] |
| Does contract size fund the channel? | Mid-price with outbound; tiny ACV with AEs | [S18, S20, S01] |
| What happens when a competitor charges half? | Undercut | [S20] |
| How many deals lost on price? | None (underpricing) or most | [S20] |
| (Enterprise) LOI? Signing authority? Who gets replaced? | No LOI; pilot above authority; selling to the replaced team | [S01, S20, S23] |
| (Enterprise) Of your last 10 prospects, how many had problem, budget and authority? | Counting calls taken | [S88] |
| (Enterprise) Is any pilot paid? What happens by default after it? | Free, open-ended, another negotiation after | [S89] |
| (Enterprise) Who owns implementation? Signed vs implemented? | "The customer"; signed far above implemented | [S88, S89] |
| (FDE) What did customer two reuse? Margin trend per account? | Nothing; flat negative | [S90] |
| (Selling to startups) Which game: Stripe, Gusto or AWS? | Chosen because startups answer email | [S91] |
| (Consumer) What is the viral or word-of-mouth hook? | Paid ads only | [S86, S26] |

**Fastest GTM tests to propose:**
- Message every second-degree connection who fits the ICP this week; aim for 1-3 customers from the network [S53].
- 100 hand-written outreaches to one verified title, iterate after each 20 [S83].
- One in-person channel matched to the buyer (trade show, dinner, site visits) [S53].
- Quote a price from the value equation; raise 50% each pitch until >25% of deals balk on price [S20].
- Enterprise: ask for an LOI or an annual contract with 30-60-day money-back [S01, S20].

---

## Where sources disagree

1. **Warm network vs cold outreach.** First 1-3 customers almost always come from the network; tools only after 10-20 customers [S53]. Cold works if the product is clearly better, no warm intro needed [S54]. OneSchema founder uses both in sequence: warm first, then 100 hand-written cold [S83].
2. **Startups as first customers.** PG: other startups are the best early adopters [S06]; Supabase targeted fast-growing VC-backed startups [S51]. The S69 speaker (Bryant Cho, 40-year-old solo founder talk): engineers are among the worst customers, switching on a whim [S69]. Taggar, Seibel and Flora: startups are right only for Stripe, Gusto or AWS-style games, and a trap for enterprise-only or headcount-scaling products [S91]; Koomen agrees for big-company problems [S88].
3. **Usage-based vs committed vs outcome pricing.** Blomfield prefers committed recurring revenue and warns against pure usage [S20]. Dust moves to credit-based pricing because flat seats break under agent loads [S71]. YC partners describe startups pricing on tasks completed [S35]. Not reconciled; ask which fits the buyer's habits ("mirror how they pay") and margin stability.
4. **Charge early vs defer revenue.** Blomfield: annual contracts from the start [S20]; "what's your revenue" is a core question [S27]. PG: do not charge for consulting-style over-attentiveness to early users [S06]. Groww: ~4 years without revenue accepted on near-zero CAC [S47] (anecdote).
5. **Ship vs sell.** "Always be selling" vs Legora freezing sales for six months to fix reliability [S59] and Encord declining to oversell to early teams [S80].
6. **GTM rigor in the AI wave.** Most doctrine stresses channel, price and founder-led sales [S20, S53, S83]. One speaker says this wave is "more about are you living at the edge of the technology" than GTM or business model [S54].
7. **Ambitious vs narrow positioning.** PG and Altman favor a narrow subset and a large share of a small market [S06, S01, S02]. PostHog's CEO argues ambitious positioning is easier to sell, hire for and fund [S79]; Collison says lean niches are more crowded in the AI era [S61]. (Idea-level treatment in `idea_sources_and_quality.md`.)
8. **Email length.** Under 75 words [S53] vs 5-8 sentences [S83]. Minor; both mean short.
9. **Price thresholds for a sales force.** $200-300/month [S18], net LTV >$500 [S01], 5:1 ARR to comp [S20] are different measures, not contradictions; use the one the founder's data supports.
10. **Pilots: none vs short paid.** Blomfield's pricing talk calls long free pilots counterproductive and prefers an annual contract with money-back from the start [S20]; his sales talk endorses short paid pilots (7-14 days) that roll into an opt-out contract [S89]. Koomen discourages free-for-feedback deals [S88]. All agree on paid; they differ on whether a pilot stage exists. Blomfield also says "not all design partnerships are a waste of time, just most of them" [S89].
11. **FDE vs product discipline.** "Do things that don't scale" [S06] and the PMF playbook cut work per customer [S90]; FDE raises contract size and keeps customization, "doing things that don't scale at scale" [S90]. PG warns a handful of big payers can make you a consulting firm [S08]; McGrew accepts services if margins improve with time [S90]. Narrow wedge [S89] vs earning access to larger problems at the same customer [S90] are sequential, not opposed.

## Source IDs used

S01, S02, S03, S06, S08, S18, S20, S21, S22, S23, S26, S27, S31, S35, S36, S37, S43, S44, S47, S48, S49, S51, S53, S54, S59, S60, S61, S63, S67, S69, S71, S75, S76, S78, S79, S80, S83, S86, S88, S89, S90, S91
