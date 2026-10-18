---
source_id: video__sG5aB79TE44
title: How Supabase Became One Of The Fastest Growing DevTool Companies In The World
speaker: Paul Copplestone
year: 2026
url: https://www.youtube.com/watch?v=sG5aB79TE44
kind: video
---

## One-line thesis
Supabase won by betting on a neutral, community-owned technology (Postgres), positioning as "the open source Firebase alternative", obsessing over time-to-value, and then recognising that AI app builders and agents were its new default users; money alone does not win.

## Evaluation heuristics
- **Pick the tech nobody owns**: Check whether the underlying platform has a flywheel where no single owner controls it, so everyone including hyperscalers must support it. Quote: "no one owns Postgress which means that everyone contributes to Postgress then all the hyperscalers have to have the best Postgress offering"
- **Founder-market signal from a real migration**: The idea came from hitting scaling limits on Firebase and migrating to Postgres in a prior company, then open-sourcing the tool. Check that the idea comes from a lived problem. Quote: "when we um hit some scaling limits on the Firebase side I decided to migrate it across to Postgress and I wrote an open- source tool"
- **Positioning by familiar reference**: A technical description did not take off; "open source Firebase alternative" did. Test whether a one-line comparison to a known product unlocks adoption. Quote: "we switched the tagline to open source firebased alternative and then from that point on it really took off"
- **Trusted foundation reputation**: A database company needs reputation; borrowing a technology with built-in credibility shortens the trust gap. Quote: "if you are going to build a database company you have to have a good reputation because to build a database is incredibly difficult"
- **Moat that grows by itself**: Infrastructure at the bottom of a customer's stack grows without extra selling. Quote: "if you start a business and your business is going well you go to sleep and your business continues to grow the thing underneath that is a database"
- **ICP = fast-growing startups**: Choose customers who will expand with you. Quote: "the ideal ICP was someone who is venturebacked and was likely to grow fast"
- **Open source against the clone threat**: A stack of tools working together is hard for a hyperscaler to reproduce, unlike hosting a single Redis or Elasticsearch instance. Quote: "it's actually incredibly difficult to manage all these different tools together"
- **Counter-position the incumbent**: Position against the hyperscaler's own offering rather than competing quietly. Quote: "we just started counterpositioning against RDS and um and Aurora"
- **Time to value as the core metric**: Measure the incumbent's time (8.5 minutes to launch an RDS instance, connect and insert a row) and drive yours below one minute; now about 5 seconds. Quote: "we decided well we have to get that at least under a minute for us to get time to value"
- **Listen where users live**: Poll the community constantly across Reddit, Twitter and Hacker News. Quote: "your community will ideally live anywhere so we're on Reddit we're on Twitter we're on uh Hacken News"
- **Slow early revenue is normal**: First revenue took a year and a half; about 1 million ARR the first year of revenue, then 7.5 million. Quote: "let's be careful about what you read in the press because you only read about the crazy outliers"
- **Debate whether small customers will grow**: The AI app builders produced tiny apps, so the question was whether they would grow. Look at whether a new segment's volume matters at scale. Quote: "each app is too small to matter"
- **Agent-as-user**: Check whether the majority of users are now agents using CLIs and MCP rather than dashboards. Quote: "we can measure 60% of databases get launched by an agent but more likely it's like 90%"
- **Ignore the build stage, solve operate**: Easy-to-replicate startups sit in the build stage; harder problems live in operating what was built. Quote: "you want to focus on hard problems right and the operate stages one of those harder areas"
- **Money is not the constraint**: Competing with a bigger-cash incumbent is possible on other vectors. Quote: "money will not solve your problems and that's a good thing for for startups as well"

## Questions a YC partner would ask (derived from this source)
- What is the time to first value for a new user and how does it compare to the incumbent's, measured? — No number.
- What technology does your product sit on, and does anyone own it? — A closed dependency that could cut you off.
- Are agents already choosing your product, and what if they only choose three tools? — No plan for the agent default problem.
- What is the hard part after the build stage that your product handles? — Only the easy generation step.
- If a hyperscaler hosts your open-source code, what stops them? — No answer beyond "they won't".

## Red flags / kill signals
- Technical positioning that nobody repeats (the real-time Postgres tagline) — it "actually didn't really take off".
- Competing in the "build" step of the agent workflow — easy to replicate.
- Dependence on becoming the agent default by luck — the speaker says it is rare and not worth betting on.

## Green flags
- 60% or more of every YC batch using the product (speaker's claim).
- User growth with conversion and activation rising at the same time (said of the AI period).
- Everything written down in Slack and Notion for six years, so agents can answer questions about past decisions.

## Named examples
- Supabase: started 2020 as open-source Postgres hosting, about 360 people in over 60 countries, 10 million developers (from 6.5 million), raised 500 million at over 10 billion valuation (speaker's figures).
- Bolt and Lovable: AI app builders that looked like a DDoS in December 24 and led to "Supabase for platforms" (over 50 companies building on it, millions of databases).
- Snap Specs: back end is Supabase (speaker's claim).
- Redis, Elasticsearch: examples of hosted-by-hyperscaler outcomes cited as the risk of open source.

## Tensions
- Against "run out of money is why startups fail": the host cites YC data that founders give up and lack product-market fit while still holding cash.
- Open source by philosophy rather than as a go-to-market tactic: the CEO says there was little discussion, which differs from advice to treat open source as a distribution strategy.
- The "agents choose three defaults" worry: his answer is to keep doing word of mouth and ease of use and hope, not a proven playbook.
