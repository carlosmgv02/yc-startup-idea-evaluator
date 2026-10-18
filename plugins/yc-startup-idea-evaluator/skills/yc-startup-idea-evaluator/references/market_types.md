# Market types: marketplaces, network effects, regulated markets

## How to use this file

- Use it when the idea is a marketplace, claims a network effect, or lives in a regulated or compliance-driven market. First classify the idea (section 0); then apply only the sections that match. Most ideas match none, and then this file does not apply.
- Each section separates what the sources say from what they do not. Where the sources are silent (take rate, disintermediation, "the law forces demand"), say so to the founder instead of filling the gap with outside knowledge.
- Evidence levels: **Doctrine** = YC partner or YC Continuity general advice. **Anecdote** = one founder's story (survivor-biased). **Policy view** = a government official describing his own policy. **Snapshot** = the Fall 2026 Requests for Startups, which will date.
- Cross-references: network effects as a moat in `moats_and_durability.md`; selling into enterprises (champions, pilots, procurement, FDE) in `gtm_and_pricing.md` §4 and §8.3; regulated-market exceptions to "launch fast" in `validation_and_pmf.md` §9; outdated laws and gray areas as idea sources in `idea_sources_and_quality.md` and `tarpits_and_kill_signals.md`.

---

## 0. Classify the idea first

Ask the founder, then check against the definitions. One idea can fit more than one type.

| Type | Test | Go to |
|---|---|---|
| Network | The product gets more valuable to each user as more users join (messaging, social, team tools like Slack) | §2 |
| Marketplace | The company matches two distinct groups (buyers and sellers, consumers and merchants, shoppers and drivers) and fulfilment depends on both | §1, plus §2 for the network-effect claim |
| Platform | Others build on it; Hariharan names it as a third type with different questions but the source gives no platform checklist | §2.1 only; say the sources are thin |
| Approval-gated ("born in captivity") | Cannot be sold until a government grants an approval, waiver or rule change | §3.1 |
| Regulated buyer or regulated operation | Legal to sell, but the buyer (bank, hospital) or the operation (holding money, patient data) carries rules, fraud, uptime or audit duties | §3.2, §3.3 |
| Compliance as product | The product helps a customer meet a rule (monitoring, reporting, audit trails, filings) | §3.4, §3.5 |
| None of the above | Single-sided product, no rule in the way | Do not use this file |

- "Are you a network, or a marketplace, or a platform?" — Anu Hariharan [S93]. The questions differ, so do not let a founder blur them.
- A founder who calls a single-sided SaaS a "network" or a "marketplace" because it has many users is mislabeling growth (§2.2).

---

## 1. Marketplaces

Main sources: Hariharan (YC Continuity, doctrine) [S93]; DoorDash's Tony Xu [S94] and Instacart's Apoorva Mehta [S95] (founder anecdotes, survivor-biased).

### 1.1 Before building: test each side

- **Three questions before code:** will consumers pay, will the supply side pay, does a supply pool exist [S94]. Check: the founder names evidence for each side separately. Bad: one side assumed.
- **Demand evidence can come from the supply side's refusals.** DoorDash's idea came from a merchant's booklet of delivery orders she had turned down [S94] (anecdote).
- **Test supply cheaply and by hand.** DoorDash posted Craigslist ads and segmented whoever showed up; when 40 incumbent drivers were offered $25/hour guaranteed, one said yes, which showed its supply was a different population [S94] (anecdote). Check: "Is your supply the same people as an existing platform's, or a new pool?" Bad: the plan is to poach supply by paying more, untested.

### 1.2 Which side first

- **Demand first is the default for scaled marketplaces:** "supply always goes to where demand is" — Hariharan [S93].
- **The founders can be the first supply.** Mehta shopped and delivered the first Instacart orders himself [S95]; DoorDash founders did every delivery, and everyone at DoorDash still does deliveries every year [S94] (anecdotes). This is "be the software" applied to supply; see `validation_and_pmf.md`.
- **Chicken-and-egg escape:** check whether influential people have the problem and would switch first [S03] (PG doctrine).
- **Money side vs subsidy side:** identify the harder, price-sensitive side and subsidize it if the other side pays (Adobe: free reader, paid writer) [S93]. Check: the founder can say which side pays and why. Bad: both sides priced the same with no reasoning [S93].

### 1.3 Liquidity and balance

- **Balance, not just volume:** "If you scale one side too much, they're too fast, then the other side suffers." [S93]. Ask for a failed-fulfilment metric; Instacart tracked lost deliveries [S93].
- **Demand without supply is lethal if you cannot throttle it.** DoorDash had no way to stop orders when drivers ran short and every delivery was late [S94] (anecdote). Check: "What happens when demand spikes beyond supply?" Bad: no throttle, no refund plan [S94].
- **The listing is a contract between both sides.** A bushel-of-bananas photo for "10 bananas" broke an Instacart delivery [S95] (anecdote). For marketplaces with item catalogs, ask how listing accuracy is kept.
- **Catalog can be a manual schlep:** Instacart bought one of every Trader Joe's item to photograph it [S95] (anecdote).

### 1.4 One market at a time

- **Perfect one city, then roll out:** Instacart got its playbook right in San Francisco first [S93]. Later cities grew faster: "in 3 weeks we were doing more deliveries than we had done in 33 weeks in the Bay Area." — Mehta [S95] (anecdote).
- **Staff supply on standby based on expected demand** when entering a new city [S93].
- **Pick the first market by need, then verify in the P&L.** DoorDash chose suburbs over dense cities because need was higher; unit economics later confirmed it (bigger baskets, easier parking) [S94] (anecdote). "Listen to the customer, run the test." [S94].
- **Size the unserved set, not the served one:** about a million US restaurants, only 20,000 offered delivery [S94] (speaker's figures).

### 1.5 Evidence that the marketplace works

- **Retention without incentives:** customers who return with no ads, coupons or discounts [S94]. Retention and frequency are "one of the hardest things to ... fool" [S94].
- **Repeat orders, and supply arriving on its own where demand is** [S93].
- **Quantified benefit to the supply side:** Whatnot sellers earning a living, restaurants gaining a third of revenue [S32].
- **Low-frequency marketplaces:** measure rebookings cohort by cohort (Airbnb) [S93].
- **Expect it to be slow:** "Airbnb took 36 months or more" [S93]. Do not apply weekly-growth benchmarks to a pre-liquidity marketplace without this caveat; but Instacart, once working, grew 10% week over week for 20 weeks [S95] (anecdote).

### 1.6 Defensibility of a marketplace

- **Local on-demand has weak network effects:** highly local networks are hard to replicate nationally; do not grant social-network-grade moats [S93]. Uber and Lyft: weak city-level network effect plus supply-side economies of scale [S93].
- **Winner-take-all is also possible without network effects** through supply-side scale plus operational excellence (Amazon first party) [S93].
- **Point-to-point services trap no value,** so users leave easily: "beyond taking you from point A to point B, I don't have any other value trapped in it." [S93].
- Scaling a working marketplace becomes a hard operations problem (variable orders, shopper speed, store inventory) [S95].

### 1.7 Not covered by the sources

- **Take rate** (what share to charge) and **disintermediation** (buyers and sellers going around the platform) are not addressed in any source in this corpus. Do not invent a benchmark. If relevant, ask the founder for their numbers and reasoning and say no YC source here sets a bar.
- Supply-side liquidity metrics beyond lost deliveries are thin; Instacart's talk says little about them [S95 tensions].

---

## 2. Network effects

### 2.1 Definition

- "as my network grows the strength of my company and the value of the product or service also grows with it" — Kevin Hale [S26].
- Network effect = value; virality = speed. "virality is actually about the speed of growth. It's not about the value." — Hariharan [S93].
- Fast growth can come from a superior product alone [S93]. Airbnb grew by word of mouth, which is not virality and not proof of a network effect [S93].

### 2.2 How to test a claimed network effect

| Check | Good | Bad | Source |
|---|---|---|---|
| Cohort engagement | Older cohorts use it more over time; DAU/MAU improves as users join | Flat or decaying cohorts | [S93] |
| Barrier to exit | Users have connections, history, setup inside (Facebook, WhatsApp); destination app with rising time spent | Point-to-point service, nothing stored | [S93] |
| Barrier to entry | A copier cannot rebuild the graph (Google+ failed to copy Facebook's) | Only speed of growth | [S93] |
| Engagement trigger | A known "aha" number, e.g. 10 friends within 14 days predicted retention at Facebook | No data on what makes users stay | [S93] |
| Entry cluster | Dense start with measured penetration (Facebook at Harvard: at least 80% of students, 60-70% daily) | "Everyone" is the market | [S93] |

- "retention ... It is the single strongest sign of a network effect." — Hariharan [S93].
- Founders usually miss the exit barrier [S93]. Ask: "If an equally good competitor appeared, why would a user not switch?" [S93].
- **Do not out-grow engagement:** growing too fast can lose the older base and push the team to growth-only features [S93].
- **Critical mass is the only moat early:** with early signs of a network effect, growth to critical mass is how the moat forms [S93].

### 2.3 Applicability

- Idea stage: there is no cohort data, so the test is the plan (entry cluster, trigger hypothesis, exit barrier). Do not demand cohort curves from a pre-launch founder; do demand that they name the cluster.
- Strong networks may end with "a few players, rather than one" [S93]; do not assume winner-take-all.
- AI-era variants (eval and data flywheels) and the "verticals need network effects" argument are in `moats_and_durability.md` and `ai_era.md`.
- Second movers can win unless the first mover has strong network effects [S54] (see `idea_sources_and_quality.md` §6).

---

## 3. Regulated and compliance-driven markets

### 3.1 Approval-gated: "born free" vs "born in captivity"

- "born in captivity technologies are technologies where you're building something but you can't commercialize it or you can't take it out to market unless you get some sort of government approval" — Michael Kratsios [S87] (policy view).
- If born in captivity, the regulatory path is the critical path [S87]. Examples: commercial drones need an FAA waiver; Boom's supersonic plane needs a noise limit instead of a speed limit over land [S87].
- Check: "Can you legally sell this today, or do you need an approval, waiver or rule change? Who grants it, how long, and what do you do meanwhile?" [S87]. Bad: the founder has not checked, or the business depends on a rule change with no path or timeline [S87].
- Fragmented rules favor incumbents, who can "hire an army of lawyers" [S87].
- Label: Kratsios is a government official; his statements about future deregulation are policy positions, not evidence [S87 tensions].
- Related idea-level material: laws written before a tech shift can be valuable to challenge; plainly illegal acts are "clearly net bad" [S29]. Start in the segment with fewer bureaucratic obstacles (universities before high schools) [S03].

### 3.2 Selling into regulated buyers

**Fintech (Blomfield, two fintech founders' story [S97], anecdote):**
- Prototype without the full licence first: Monzo launched a bank prototype on a prepaid debit card in about three or four months [S97]. Bad: the plan requires a full licence before any user touches it.
- Running money brings operational duties that scale with success: outages ("even for a few seconds ... tens of thousands of payments wouldn't go through") and financial-crime and money-laundering monitoring [S97]. Check: "What is your plan for fraud, money laundering and outages?" Bad: "later" [S97].
- The source covers regulation only through anecdotes; no compliance-as-product advice [S97 tensions].

**Healthcare (Luminai, large hospitals [S96], anecdote):**
- Sell to a champion inside the institution, not to the institution [S96]; big institutions take meetings through trusted warm introductions, not cold email [S96].
- Wedge on one ugly manual workflow with fast time to value (faxed referrals into Cleveland Clinic) [S96]. Narrow vertical focus raises credibility; "I can do anything" lowers it [S96].
- The source says nothing about HIPAA or compliance as a barrier or product; do not infer it [S96 tensions].

**General regulated-market rules already in other files:**
- Launch-fast is relaxed for banking and lending; a "heavy MVP" (a website explaining what you do) is acceptable, with a steady stream of real users [S25, S19, S61] — `validation_and_pmf.md` §9.
- YC interviewers ask regulated founders "what is your regulatory strategy?" [S24] — `founders.md`.
- Enterprise compliance features (SOC 2, SSO, audit logs, compliance reports, data residency) gate the enterprise tier [S20]; is SOC 2 started? [S89] — `gtm_and_pricing.md`.

### 3.3 Regulation as a moat or schlep (summary; detail elsewhere)

- Stripe is the canonical schlep: many knew payments hurt, few took on banks, fraud and regulation [S11, S12, S34] — `moats_and_durability.md`.
- A banking licence as "the hard bit" that makes a startup durable [S75]; licences and regulatory permission as assets [S64].
- Coinbase worked with banks and regulators while the crypto crowd was anarchist; KYC makes the product worse but widens the market [S29].
- Plaid and open banking cited as regulatory capture by large banks [S29].
- Uber and Airbnb were not cloned by incumbents because of regulatory risk [S23].
- Incumbents will not do deep vertical work full of "stupid payroll regulations" [S23].

### 3.4 Compliance as product: the RFS entry (snapshot)

- YC's Fall 2026 RFS asks for "AI-Native Compliance Infrastructure" (Daivik Goel): consolidated financial compliance with AI as default, because "the cost of staying compliant grows faster than revenue" [S92].
- "The best version of this doesn't just automate existing processes" [S92]. Monitoring, flagging, reporting and audit trails are tasks AI can do faster and cheaper; a product that keeps a human-review bottleneck is exposed [S92].
- Check: "Are you replacing a process or rethinking it with AI as default?" Bad: a faithful port of the manual process [S92]. "If an incumbent just adds an agent, what remains?" Bad: a UI over the same human-review workflow [S92].
- This is a snapshot of what partners want in one season; it is not evidence that a given compliance idea has demand.

### 3.5 What the sources do NOT cover: "the law forces demand" ideas

Be explicit with the founder: no YC source in this corpus explains how to evaluate an idea whose demand comes from a legal mandate or deadline. Hale lists "mandatory" problems and "the law has changed" as attractive, citing the Affordable Care Act [S26], and Friedman counts regulation among recent changes that create openings [S34]. Neither gives a method to judge such ideas. Do not invent one. Use the checks the sources do support:

| Check | Why, from the sources | Bad answer |
|---|---|---|
| Does demand survive after the deadline? Is the need recurring or one-off? | Hale prefers frequent problems over one-time urgency for conversion [S26]; retention is the evidence that is hard to fake [S94]; RFS frames compliance cost as growing with revenue, i.e. ongoing [S92]. (The deadline framing is the evaluator's inference, not a source rule.) | Revenue collapses once customers are compliant; no use after the filing |
| What is the hard bit? | Durability comes from the hard bit, and pure software is easy to copy [S75]; mandate-driven demand attracts many identical entrants (see competition in `idea_sources_and_quality.md` §6) | "We read the regulation and built a form" |
| Who signs, and who must say yes? | Map who decides and how the organization buys [S88]; IT and security gatekeepers are not aligned with the end user [S90]; map economic buyer, technical approver, security, legal [S89] | Only the user who feels the pain is mapped |
| Is it a feature of an ERP or incumbent? | "If an incumbent just adds an agent, what remains?" [S92]; incumbents avoid deep regulatory verticals [S23], but that cuts both ways; Campfire built a whole AI-native ERP to compete with NetSuite [S29] | The incumbent the customer already pays for could ship it as a checkbox |
| Is the product legal to sell now? | Born free vs born in captivity [S87] | Depends on a rule not yet written |
| Does the founder know the rule personally? | Founder-problem fit and living the customer's work [S95, S97] | Learned it from a news article |

Also note: a law-change "why now" is valid as a why-now [S34, S26]; it is not, by itself, evidence that anyone will pay this founder.

---

## 4. Partner questions by type

**Marketplace:** Which side launches first, and what evidence does each side pay or show up? [S94, S93]. What is your lost-fulfilment rate? [S93]. What happens when demand exceeds supply? [S94]. Which city or segment first, and why? [S93, S94]. Do customers return without discounts? [S94]. Which side is the money side? [S93].

**Network:** Do older cohorts use it more? [S93]. What is the engagement trigger? [S93]. What value is trapped for the user? [S93]. Which cluster first, and what penetration there? [S93].

**Regulated:** Born free or born in captivity? [S87]. Regulatory strategy? [S24]. Fraud, money laundering, outage plan? [S97]. Who is the champion and how did you reach them? [S96]. Demand after the deadline, hard bit, who signs, incumbent feature? (§3.5).

---

## Where sources disagree

1. **Density vs need in choosing the first market.** Hariharan recommends perfecting one city before rolling out [S93]; DoorDash went to suburbs against the "density in city centers" logic and says customer need, then P&L, should decide [S94]. Not a contradiction on one-market-at-a-time, but on which market.
2. **Network effects and winner-take-all.** Hariharan says network-effect businesses tend to winner-take-all, yet also that strong networks end with "a few players, rather than one", and that local on-demand marketplaces have only weak network effects [S93]. Hale lists network effects as a monopoly advantage without that nuance [S26].
3. **Regulation as barrier vs as opening.** Kratsios: fragmented regulation favors incumbents with lawyers [S87]. Tan et al.: outdated laws and gray areas are where great ideas hide, and regulatory risk kept incumbents from cloning Uber and Airbnb [S29, S23]. Both hold: the rule protects whoever can absorb it.
4. **Launch fast in regulated markets.** Monzo shipped a prototype in three or four months on a prepaid card [S97]; Seibel says launching early in banking or lending is "just really hard" [S25]. The resolution in the sources is to find a legal prototype path, not to skip launching (see `validation_and_pmf.md` §9).
5. **Broad rethink vs narrow wedge in compliance.** The RFS asks for products that rethink operations with AI rather than automate existing processes [S92]; Luminai and the YC sales talks push a narrow wedge workflow first [S96, S89].
6. **Policy statements.** Kratsios speaks for his administration; the RFS defense request is authored by the US Secretary of the Army [S92]. Treat both as stated intent of a buyer or regulator, not as market evidence.

## Sources used

S03, S11, S12, S19, S20, S23, S24, S25, S26, S29, S32, S34, S54, S61, S64, S75, S87, S88, S89, S90, S92, S93, S94, S95, S96, S97
