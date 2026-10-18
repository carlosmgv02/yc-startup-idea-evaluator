---
source_id: video__xpeRVyFFy_Q
title: Solving the Blank Canvas Problem: Gusto's AI Co-Founder
speaker: Eddie Kim
year: 2026
url: https://www.youtube.com/watch?v=xpeRVyFFy_Q
kind: video
---

## One-line thesis
For non-technical business users, an AI agent should start from the recurring processes the incumbent already owns and has data on, not from a powerful but blank canvas; the moat is system-of-record data plus trusted, deterministic automations.

## Evaluation heuristics
- **Blank canvas problem**: general agents with many capabilities leave non-technical users not knowing what to do. Check whether the product starts from known recurring tasks. Quote: "it has a main has a pro has a problem which I call the blank canvas problem"
- **Start from the incumbent's data**: the prototype that ignored customer data was less valuable than the version using it. Quote: "it didn't like really leverage anything about what we knew about the customer"
- **Recurring painful task sells itself**: customers instantly recognize weekly manual processes. Quote: "when you like actually talk about this to a customer they actually instantly get it because they have so many of these"
- **Little selling needed**: when the pain is on the calendar, selling takes little. Quote: "it doesn't really take much like selling at all"
- **Pre-work is the real work**: payroll's last step is simple; export, transform and commission calculations are the time sink. Quote: "it's all like kind of like this work before the work that takes them a lot of time"
- **Hands-on use beats reading**: founders learn by setting up the tool themselves. Quote: "there's this big gap between like what you read about and what you actually experience"
- **Chat as interface**: reduce UI and make the agent smarter. Quote: "people just really underestimate chat as the interface"
- **Determinism where money is involved**: heartbeat (LLM on a schedule) is not enough for payroll; add scheduled jobs. Quote: "there's some things you actually want to be deterministic and so like payroll probably one of those things"
- **Cost of "LLM every 30 minutes"**: choose cron versus prompt by task. Quote: "running a you know a prompt every 30 minutes which also can get pretty expensive"
- **Surprise use cases outside the core**: customers automate things unrelated to the product (rain alert plus customer email). Quote: "a lot of the automations don't necessarily have to do with things that Gusto is already doing for them"
- **Proactive co-founder value**: surface opportunities the owner does not know (R&D tax credit, $50,000 found for one customer). Quote: "we actually found them $50,000 in R&D tax credit they didn't really know that that was possible"
- **Connector breadth by vertical**: long tail of vertical systems (dental practice software) as next roadmap. Quote: "hundreds of connectors that we could be um"
- **Small business as AI buyer**: no job-loss resistance, so adoption is easy. Quote: "they just want to be able to do more with less"
- **Distribution data point**: new business starts rising and a founder-friendly market. Quote: "one in five new businesses started today are Gusto customers"
- **Speed via no process**: five builders, ten weeks, no Jira, specs or Figma, one always-on Zoom. Quote: "it was almost more defined by like what we didn't do versus like what we changed in in how we build software"
- **Prototype-first decision making**: throw away code at a 50% hit rate beats writing PRDs. Quote: "hit rate of 50% it actually is significantly faster than like trying to like you know write a PRD and a Figma"
- **Discipline is harder when building is cheap**: more things to say no to. Quote: "you have to be much more disciplined than than before"
- **Customer conversations still needed**: implementations do not replace watching users. Quote: "just high bandwidth one conversations with customers and watching"
- **Expansion to pre-company users**: data model lets someone without an EIN use it, then help register as an employer. Quote: "even if you don't have a EIN yet"

## Questions a YC partner would ask (derived from this source)
- What is the first thing a new user sees: a blank prompt or their own recurring tasks already suggested? — Blank prompt.
- Which of your automations must be deterministic and how do you guarantee it? — Everything runs through an LLM schedule.
- What data do you hold about the customer that a general agent lacks? — None.
- How much of the pre-work (data export, transform) do you take over, not just the final step? — Only automates the easy last step.
- What did customers automate that you did not expect? — No observation of real use.
- How many prototypes did you throw away this month? — One carefully specified build.

## Red flags / kill signals
- Powerful agent with no starting point for non-technical users.
- Non-deterministic scheduling for money-critical tasks.
- Agent loops costing tokens every few minutes without a cost check.
- No proprietary customer data feeding the automation.

## Green flags
- Customers who say the task is "on my calendar".
- Approval step by SMS or Slack (human yes or no) at the end of an automated process.
- Surprising off-core automations discovered by users.
- Small, cross-functional team shipping tier-one launch in weeks.

## Named examples
- Gusto Co-founder: launched with 500 customers added; pre-launch small-business council of about 20 customers.
- Massage spa customer: exports MindBody to Google Sheets, calculations for commissions and tips, then payroll.
- Cabana Pools: $50,000 R&D tax credit found.
- OpenClaw (personal agent) used as inspiration: Telegram chat and a cron job running an LLM every 30 minutes.
- Curve Dental: example of a vertical connector.

## Tensions
- Contradicts "specs and design first": the team skipped docs, Figma and sprint planning, though he says not for all parts of an organization.
- YC debate quoted: with cheap code, build many things versus one or two well; the speaker argues for discipline and building every permutation to choose.
- Claim of ease of selling to small businesses is anecdotal and from an incumbent with an existing base.
