---
source_id: video__e5-6rEwzxLs
title: Dot Plots: How to Actually See What Your Users Are Doing
speaker: David Lieb
year: 2026
url: https://www.youtube.com/watch?v=e5-6rEwzxLs
kind: video
---

## One-line thesis
Aggregate metrics hide whether individual users get value; a per-user, per-day grid of value events (dot plot) is the best early product-market-fit signal and should be your only dashboard until you have hundreds of users.

## Evaluation heuristics
- **Aggregates lie**: growing DAU/MAU charts can coexist with users who dislike the product, so never accept them as validation. Quote: "if you have any amount of growth those graphs tend to be going up and to the right um even if users aren't actually enjoying using your product"
- **Individual-user usage is the signal**: ask for frequency and pacing per user, not totals. Quote: "I think it's the most important signal to figure out if you've built something that people want"
- **Pick a value event, not a vanity event**: the charted event must represent value created ("listen to a song", "shared a photo"); "opened the app" or "signed in" is bad. Quote: "pick something that actually represents value being created for the user"
- **Day granularity or finer**: weekly buckets hide the pattern. Quote: "it's way harder to figure out what's actually going on unless you look at it at the day or maybe even like subday granularity"
- **One-and-done rows**: many rows with a single dot on first day mean an onboarding or value problem. Quote: "do we see a lot of users like user 4 that try the app on one day and then never come back"
- **Cohort curves tell whether, dot plots tell how**: use both. Quote: "cohort retention curves teach you in aggregate whether groups of users that you acquire stick with you over time"
- **Feature to behavior inference**: mark feature use and look for features that precede long streaks, as a hypothesis for causal value. Quote: "maybe the playlist feature is really causal to having people be really active in our product"
- **Segment sorting**: sort rows by platform, geography or income to find valuable segments. Quote: "sort your rows based on whatever attributes you want to sort them by"
- **B2B seat activation**: compare seats bought versus seats that ever activated; one champion is a single point of failure. Quote: "the company bought 10 seats but only three seats ever activated"
- **Champion-leaves churn**: contract risk is visible in the usage pattern before renewal. Quote: "as soon as the champion left a new person came in"
- **Pattern-spotting beats predefined hypotheses**: look first, then dig in, the PayPal fraud method. Quote: "they were able to look at the screen and say that thing happening there that's different and uh probably fraud"
- **Cheap to build**: it is only a log visualization, so no excuse for not having it. Quote: "this is a thing that modern AI coding tools can whip up in like 10 minutes"
- **Early-stage rule**: with few users, read every user every day. Quote: "until you have hundreds of users the dot plot could be your only dashboard"

## Questions a YC partner would ask (derived from this source)
- Show me one row per user per day for your core value event. — Cannot produce it, or only shows DAU/MAU.
- Which event do you count as value, and why is it not "logged in"? — Counts opens or sign-ins.
- Of the seats you sold, how many were ever activated, and by how many distinct people? — Unknown, or usage concentrated in one champion.
- What fraction of users appear once and never again? — No idea.
- Which feature do your heaviest users touch first? — No hypothesis.

## Red flags / kill signals
- Founder reports only aggregate growth charts — they hide dislike of the product.
- Value event is the easiest to inflate (open, sign-in).
- B2B contract with many unused seats and sporadic use (nobody used it more than 2 days per week in the example) — churn at renewal.
- Single champion drives adoption.

## Green flags
- Long consecutive-day streaks among a visible user subset.
- Founder can name usage patterns by segment (weekday vs weekend users).
- Founder inspects individual users routinely and has a small bespoke dashboard.

## Named examples
- Spotify (hypothetical): weekday versus weekend listeners as different user types.
- Bump: different symbols for contact versus photo shares.
- Google Photos: printed dot plots for samples of a billion users.
- PayPal / Max Levchin: humans staring at transaction graphs to spot unknown fraud patterns.
- YC batch company with an $80,000 per year contract, 10 seats bought, 3 activated, churned.

## Tensions
- Contradicts reliance on DAU/MAU and weekly cohorts that many founders show to investors.
- Opposes "build the dashboard later": the claim is that this one tool is enough until hundreds of users.
