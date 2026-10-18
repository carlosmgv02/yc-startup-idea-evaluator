# Evaluation cases

Use these to check that the skill judges well, not just at length. Run each pitch through the skill as if it came from a real founder (do not reveal the case notes). Then compare against "Expected". A good run lands in the expected band and raises the must-raise points; a run that praises a tarpit, or kills an unpopular-but-good idea for looking strange, fails.

Cases are anonymized versions of patterns named in the sources. Bands use the rubric in `references/scoring_rubric.md`.

---

## C1. Restaurant picker for friend groups (tarpit)

**Pitch:** "My friends and I waste 30 minutes every Friday deciding where to eat. We're building an app where the group swipes on restaurants and it picks the match. Everyone we've shown it to says they'd use it. Two technical cofounders, no users yet."

**Expected:** Tarpit band. Must raise:
- Classic tarpit: friends praise it, yet the problem is not acute or frequent enough to change behavior [S28, S34].
- "Everyone says they'd use it" is not evidence; past behavior and money are [S31, S37].
- Ask what made the many previous attempts fail before building [S28, S34].
- Next step: test real usage with one friend group for weeks, not more building [S06, S19].

## C2. AI copywriting wrapper (model-steamroller risk)

**Pitch:** "A web app where marketers paste a brief and get 10 ad variations from GPT. $29/month per seat. We have 300 signups from a Product Hunt launch, 4% still active after a month."

**Expected:** High risk or Tarpit band. Must raise:
- Retention collapse: signups without retention is the classic error [S01, S08].
- Capability already present in frontier models, so the next model release erodes it; contrast with targeting tasks models fail at today [S55, S35].
- Seat pricing on a generic horizontal tool vs owning an outcome in a vertical [S35, S64].
- What would have to be true for a moat; propose a vertical with proprietary workflow/data or kill [S35, S75].

## C3. Vertical AI agent for a regulated back office (strong)

**Pitch:** "I ran claims operations at a mid-size insurer for 8 years. Our team of 40 manually reviews medical bills against policy rules. We built an agent that does the first review end to end and flags exceptions. Two insurers are piloting it on live claims; one signed an LOI to pay per claim processed. My cofounder was the ML lead at a health-tech company."

**Expected:** Strong band (not perfect: pilots, not yet scaled revenue). Must raise:
- Founder-market fit and an organic, noticed idea [S34, S12].
- Vertical agent replacing a team [S23], priced per outcome [S35].
- Verify the LOI turns into paid usage; enterprise test is a letter of intent then paying customers [S01].
- Reliability and exception handling as the hard part, and what the incumbents' software lacks [S75, S35].

## C4. Ride-sharing in private cars, early smartphone era (unpopular but good)

**Pitch:** "We want regular people to give rides to strangers in their own cars, booked and paid by phone. Taxi regulations probably forbid it. Investors tell us nobody will get into a stranger's car."

**Expected:** Promising, or Provisional High risk with low confidence because the pitch is thin. Fails if it lands in the Tarpit band or gets a cap. Must raise:
- Distinguish "sounds bad but is good" from a tarpit: the objection is social/regulatory, not "nobody needs this" [S29, S01].
- A platform shift (smartphones) making an old bad idea newly possible [S08, S29].
- The real risks to test: safety, regulatory exposure, supply/demand liquidity in one city [S29, S06].
- The evaluator must NOT score it low just because it sounds crazy or illegal-looking.

## C5. "Spotify for X" consumer subscription with no founder edge (weak)

**Pitch:** "Netflix for online courses: one subscription, all the best courses. Huge market, $300B education spend. We'll grow through TikTok and influencers. Solo non-technical founder, plans to hire an agency to build it."

**Expected:** Tarpit or high risk band. Must raise:
- Top-down market size is at most an indicator, not evidence [S29, S12].
- Growth plan relies on channels instead of founder-led unscalable effort [S06].
- Solo, non-technical, outsourcing the build: team red flags [S01, S09, S07].
- Ask which narrow group desperately needs this and why the founder knows them [S12, S06].

## C6. Hard-tech moonshot with credible first step (ambitious)

**Pitch:** "We're building a supersonic passenger airliner. Team of former aerospace engineers. First milestone: a one-third-scale demonstrator. We have pre-orders interest from two airlines."

**Expected:** Promising band, scored on its own terms, not penalized for not being software or AI. Must raise:
- Ambitious ideas can be easier to recruit and sell for [S79, S40, S03].
- The small first step that already works and the expansion path [S03].
- Capital and timeline risk; what is evidence at this stage (LOIs, then technical proof, then pre-orders) [S73, S40].
- AI-era criteria do not apply here.

## C7. Tool the founder built for themselves, already growing (strong, early)

**Pitch:** "I'm a developer. I built a CLI to keep our team's environment variables in sync because we kept breaking prod. I put it on GitHub; 2,000 developers use it weekly, growing ~8% a week, and three companies asked for a paid team version."

**Expected:** Promising or Strong (the category has existing tools, so durability is a fair deduction). Must raise:
- Organic idea from the founder's own need [S10, S12].
- Weekly growth rate as the key metric, against YC benchmarks [S08].
- Unprompted demand for a paid version; turn it into revenue and measure [S01, S20].
- Risks: who else does this today, and whether it is a feature of a larger platform [S35, S75].

## C8. Consumer social app, idea stage, strong founder (judge founder and idea separately)

**Pitch:** "A new kind of social network for close friends only, no public posts. I previously grew a student app to 50k users at my university. Not launched yet."

**Expected:** High risk to promising, depending on the founder evidence surfaced. Must raise:
- Consumer is hard and often seen as uninvestable, which is also why it can be open [S86, S21].
- Prior proof the founder can get users matters; ask for specifics [S07, S24].
- The test is launch fast and measure retention/love, not polish [S02, S21].
- The rubric must separate founder strength from idea risk instead of blending them.

---

## How to score a run

For each case: band correct (yes/no), must-raise points hit (count), any invented facts or citations that do not exist in `references/sources.md` (each one is a failure).

---

# Real-outcome cases

Pitches written as they could have sounded at the time, without the name. The outcome is known from the sources; the skill must not use hindsight (see the rubric's rule on famous ideas).

## C9. License-plate cameras for neighborhoods and police (small TAM, won big)

**Pitch:** "Our neighborhood had a string of break-ins and the police had no leads. We're building cheap solar license-plate cameras that HOAs and police departments can install in a day, with software that searches plates. The market looks small, maybe $50-60M a year. We've installed a few in Atlanta and the police already solved a case with them."

**Expected:** Promising. Outcome: Flock Safety, later valued at about $7.5B [S29]. Must raise:
- Acute problem with an observed result (a solved case) beats TAM math; TAM is only an indicator [S29].
- Founder lived the problem; hardware plus software schlep [S34, S11].
- Risks to test: sales cycle with police departments and privacy objections; do not score it low for small TAM alone.

## C10. Web calendar right before a giant enters (crushed by incumbent)

**Pitch:** "We're building an AJAX web calendar, much nicer than desktop calendars. Two technical founders, launched, some users like it. We think a big company may launch a calendar too, but ours is better."

**Expected:** High risk. Outcome: Kiko, crushed by Google Calendar, sold on eBay [S09]. Must raise:
- Feature that a platform owner can add; what is the hard bit or power [S75, S35].
- "Some users like it" is like, not love [S01].
- What happens when the incumbent ships; ask for evidence of users who would not switch.

## C11. Corporate card for startups, founders with no banking experience (won)

**Pitch:** "We're a startup and no bank would give us a corporate credit card, because we have no credit history. We want to build a card for startups underwritten on the cash in their bank account, not on personal guarantees. One of us previously sold a fintech company in Brazil. Our first idea was VR, but this is the problem we kept hitting."

**Expected:** Promising or Strong. Outcome: Brex, YC W17 [S34, S22]. Must raise:
- Acute problem where the alternative is nothing [S34].
- Founder-market fit through prior fintech exit; a pivot driven by a problem the founders hit [S22, S24].
- Risks: regulated partner bank, credit losses, and why incumbents ignored this segment [S75].
