# Scoring rubric

## How to use this file

- The score is a summary of the evidence, not a substitute for it. YC partners do not score ideas with a number; this rubric exists so the evaluation is consistent and comparable across ideas. Say so if the founder treats the number as a verdict.
- Score each dimension from its anchors, then apply stage adjustments, then caps. Write one line of evidence per dimension, tagged Observed / Claimed / Assumed.
- "Rungs" refer to the evidence ladder in `validation_and_pmf.md` section 1.

## Evidence and missing information

The score answers "how good is this if what the founder told us is true?". The confidence answers "how much of it have we verified?". Keep them separate.

| Input | How to score | Effect on confidence |
|---|---|---|
| Observed (you saw data, a contract, the product in use) | At face value | Raises it |
| Specific, checkable claim (numbers, named customers, a signed LOI, prior jobs) | At face value, as if true; list it under "to verify" | Caps confidence at medium |
| Vague claim ("everyone loves it", "huge demand", "we're experts") | As rung 0-1 evidence: no credit | None |
| Missing (the pitch does not say) | Mark the dimension "?" and give the midpoint of the middle anchor | Lowers it; ask the question |
| Contradicted (evidence shows the opposite: churn, no one returns, nothing built) | Low anchor | Raises it |

- Absence of evidence in a short pitch is not evidence of absence. Penalize what is shown to be weak, not what was not said. Otherwise a terse founder with a good idea scores like a bad idea.
- If three or more dimensions are "?", the score is **provisional**: lead the report with the questions, write the band as "Provisional: <band>", and say the band reflects missing information, not a structural flaw. A fully unknown dimension set lands around 60-65 by design: unknown is neither promising nor bad.
- Round midpoints down (9.5 becomes 9).
- A pitch that starts from a technology or solution with no user whose problem it solves ("AI is cool, what can we do with it") is the solution-in-search-of-a-problem signal, scored low on dimension 1 [S34, S12]. If the problem is obvious from the product (a ride service implies people who need rides) but its acuteness is not described, that is missing information: mark "?".
- "Sitcom idea" means a social network or portal for an interest group ("for pet owners"); a new mechanic for an existing social graph is judged as a consumer social idea, not a sitcom idea [S12].
- Ideas that are famous in hindsight are scored as pitched; do not use what happened later.
- Unprompted requests to pay (users asking for a paid version) count as rung 3 evidence, like a card entered for a feature that does not exist yet [S31, S01].
- Outside knowledge about the world (for example which technology changed when) may be used to judge "why now" or market facts, labelled as outside knowledge and never attributed to YC.
- The sources say founders matter more than the initial idea, and ideas change a lot early [S02, S09]. That is why founders and problem carry the most weight, and why moats weigh less at idea stage [S35, S01].

## Dimensions (100 points)

### 1. Problem: acute, frequent, and someone pays today (20)

Reference: `idea_sources_and_quality.md` sections 2 and 7.

| Points | Anchor |
|---|---|
| 17-20 | A specific group has the problem acutely and often; they already pay for, or hack together, a workaround; evidence at rung 2+ from conversations about past incidents [S26, S31, S37]. Narrow and deep: a small group would be desperate to have it [S12, S02]. |
| 10-16 | Real problem, but one of: infrequent, not urgent, broad and shallow, or evidence only from the founder's own experience without other users checked [S26, S12]. |
| 0-9 | Nice to have, made-up or "sitcom" problem, solution in search of a problem, or only rung 0-1 evidence (compliments, hypotheticals) [S12, S34, S31]. |

### 2. Insight and why now (15)

Reference: `idea_sources_and_quality.md` sections 1, 3 and 5.

| Points | Anchor |
|---|---|
| 13-15 | Organic idea from living the problem or working at the leading edge; the founder can state a non-obvious belief and a recent, specific change (technology, regulation, behavior) that makes it possible or bigger now [S12, S10, S26, S08]. |
| 7-12 | Plausible insight or a credible why-now, but not both; or industry knowledge without a clear non-obvious angle [S26, S34]. |
| 0-6 | Brainstormed to fit a startup template, "why now" is just "AI is cool" or a trend, or the founder cannot say why others have not done it [S12, S05, S34]. |

### 3. Founders and founder-market fit (20)

Reference: `founders.md`.

| Points | Anchor |
|---|---|
| 17-20 | Founders have built and shipped things; direct domain access or experience with this customer; cofounders with real shared history; evidence of determination plus flexibility and speed [S07, S09, S34, S01]. |
| 10-16 | Capable builders with partial domain access, or strong domain founder without a builder, or a new cofounder relationship [S01, S09]. Solo founders: judge per `founders.md` section 6, not by automatic penalty. |
| 0-9 | Nothing built; no way to reach or understand the customer; plans to outsource the core build; red flags in `founders.md` section 10 [S01, S09, S05]. |

### 4. Market: beachhead and path to big (15)

Reference: `idea_sources_and_quality.md` section 4.

| Points | Anchor |
|---|---|
| 13-15 | A narrow first market the team can win quickly, plus a credible path from it to a large market; either a big market today or a small, fast-growing one [S34, S03, S06]. |
| 7-12 | Big market but no clear beachhead, or clear beachhead with an unclear way out. |
| 0-6 | Market bounded by geography or niche with no expansion path (a fine business, not a startup: say so, do not insult it) [S08]; or the size claim is top-down TAM only, which is at most an indicator [S29, S12]. |

### 5. Evidence and path to first customers (15)

References: `validation_and_pmf.md`, `gtm_and_pricing.md`.

Score against the stage, not against an absolute bar:

| Stage | 13-15 | 7-12 | 0-6 |
|---|---|---|---|
| Idea | Founder can name the first 10 customers and has talked to them about past incidents; an unscalable plan to get them [S06, S53] | Knows the segment, has not reached them | "Launch and see", ads, virality, partnerships as plan [S06] |
| Building | Users or design partners using a prototype; enterprise LOI before code [S01] | Interviews done, nothing in users' hands | Months of building with no user contact [S19, S25] |
| Pilots (B2B) | Paid or live pilots on real customer data plus a signed LOI or contract for the post-pilot price [S01] | Unpaid pilots or design partners, no commitment on price | Pilots that never convert, or pilots above the buyer's signing authority [S20] |
| Launched | Retention evidence (rung 4+); growth stated as a weekly ratio at YC benchmarks [S08, S44] | Some users return; growth slow or unmeasured | Signups without retention; growth bought [S01, S08] |
| Revenue | Paying, renewing customers; B2B 10+ paying [S01] | Revenue from few customers or pilots | Revenue that depends on a few customers turning you into a consultancy [S08] |
| Hard tech (any stage) | A working step that de-risks the core physics or engineering, plus customer commitments in the proof sequence (LOIs, then technical proof, then pre-orders) [S73, S40] | Credible team and plan for the first demonstrator; interest from customers but nothing signed | No small working step; the plan jumps to the full product; no customer conversations [S03, S74] |

Stage definitions: **idea** = nothing built and no users; **building** = a prototype or demonstrator exists or is being built, no real users; **launched** = real users can use it; **revenue** = someone pays. B2B companies running live pilots with customers are scored on the "Pilots (B2B)" row whatever their nominal stage. Use the most advanced stage the evidence supports.

### 6. Durability (15)

Reference: `moats_and_durability.md` section 8; for AI products also `ai_era.md` sections 3 and 6.

| Points | Anchor |
|---|---|
| 13-15 | Durable: a power is forming (switching costs, counter-positioning, network or data flywheel [S35]; regulatory permission or licences [S75, S64]; an earned trust record [S74]). |
| 7-12 | Defensible-in-progress: a named hard bit the team is taking on, plus speed [S75, S11]. At idea stage this is the normal top. |
| 0-6 | Fragile: no hard bit; cloneable in a weekend; for AI, value disappears when the next model ships [S75, S41]. |

## Stage adjustments

- Idea stage: dimension 6 is capped at 10, because the sources say moats are built later and early speed matters more [S35, S01]. Report this.
- Hard tech and deep tech: judge dimension 5 by technical milestones and binding commitments, not weekly growth [S08 note on databases, S73]. Do not apply software growth benchmarks.
- Non-AI products: never deduct for "AI architecture". Run the AI lens only if `ai_era.md` section 0 says it applies.

## Caps (applied after summing)

| Condition | Cap | Source |
|---|---|---|
| Tarpit: the idea matches a row typed **Tarpit** or **Sitcom idea** in the catalogue in `tarpits_and_kill_signals.md` section 2 (not "Low hit-rate space", "Structural", "Trap" or "Crowded": those inform the score, they do not cap it), and the founder shows neither a change that hits the structural reason (step 3) nor real customer pull (step 5). An unresearched founder does not escape this cap | 44 | [S28, S34] |
| Nobody desperately needs it: the founder has looked for users beyond friends and family and the best evidence is still rung 0-1, or the evidence contradicts acuteness (users tried it and did not return). Missing evidence alone does not trigger this cap | 50 | [S12, S31] |
| No founder can build the product and the plan is to outsource the core | 55 | [S01, S09] |
| AI product whose value disappears with the next frontier model (fails the next-model test) | 55 | [S23, S41] |

Caps are ceilings, not deductions: they matter when an idea scores well on other dimensions despite one of these flaws, so never subtract them from an already low sum. A cap is not a death sentence: say what evidence would lift it.

## Bands

| Score | Band | What to tell the founder |
|---|---|---|
| 80-100 | Strong | Lean in. The remaining risks are execution risks; name the one to watch. |
| 65-79 | Promising | Worth pursuing if the riskiest assumption survives a 14-day test. |
| 45-64 | High risk | Something structural is missing (problem, founders or path). Fix it or pivot within the founders' area of knowledge. |
| 0-44 | Tarpit or not yet an idea | Stop building. Go talk to users or pick a problem the founders have lived. |

## Confidence

- High: most points rest on Observed evidence.
- Medium: a mix; the score could move a band either way with one answer.
- Low: most inputs Claimed or Assumed. Lead the report with the questions, not the score.

## Calibration notes

- An idea that sounds crazy, illegal-looking or toy-like is not penalized for that. Run `idea_sources_and_quality.md` section 7 and `tarpits_and_kill_signals.md` section 3 before deducting [S01, S07, S29].
- A good small business scores low on "market" but should be told it may be a good business, just not a venture-scale startup [S08].
- Check yourself against `evals/cases.md` after changing anchors or caps.
