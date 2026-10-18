---
source_id: video__4YWO4sSRrTE
title: Circleback CEO Ali Haghani: Why Your Company Should Be Recording More Meetings
speaker: Ali Haghani
year: 2026
url: https://www.youtube.com/watch?v=4YWO4sSRrTE
kind: video
---

## One-line thesis
As AI agents do more company work, captured conversation context becomes the scarce input, so recording and sharing everything (with trustworthy permissions) becomes the default; the CEO's own tooling shows an agent-first startup operating model.

## Evaluation heuristics
- **Agents need context, so the context layer is a product**: test whether the product captures proprietary context agents lack. Quote: "otherwise your AI agent is working in isolation It doesn't know what was said earlier today or what a customer said"
- **Rising opportunity cost of not capturing data**: a "system of record" bet is stronger if the cost of absence grows with agent adoption. Quote: "the opportunity cost of not recording is already pretty high and it's only going to become higher and higher"
- **Trust and permissioning as the adoption gate**: for capture-everything products, check whether users can trust nothing is shared inadvertently. Quote: "giving our customers confidence that the things that are captured will be shared with the right people uh and nothing will be shared inadvertently"
- **Evals for the quantifiable, taste rules for the rest**: AI product quality needs regression evals, or each improvement breaks another part. Quote: "if you don't have good systems in place to make incremental improvements you're constantly playing this game of whack-a-ole"
- **Output style as product surface**: opinionated quality rules in the main surface (e.g. banning "discussed" in notes). Quote: "we really try to never have our notes say the word discussed cuz it's fully pointless"
- **Human gates on irreversible actions**: agents draft, humans send/architect. Quote: "Never send an email on its own of draft is okay"
- **Bottleneck shifts from writing code to review and decisions**: Quote: "the bottleneck then becomes code review"
- **Value moves from shipping speed to choosing what to build**: Quote: "what matters more is not how fast you ship but what you decide to build and how you decide to build it"
- **Founder time reallocation by automation**: Quote: "I'm doing a lot less of the things that I didn't like as part of being a founder which is the ops related work"
- **Dogfooding as a growth loop**: the product runs the company's own hiring, customers and CRM-like tracking. Quote: "I kind of use it as my ATS"
- **Support by engineers**: Quote: "a weekly run rotation when where an engineer is handling all the incoming support and talks to our customers"
- **Customer mix signal**: Quote: "a lot of more traditional businesses that like sit in cubicles and we're the only non-Microsoft product they use"

## Questions a YC partner would ask (derived from this source)
- What context does your product capture that an agent cannot get elsewhere? — Red flag: the data is available to any model via public sources or existing integrations.
- How do users know the captured data will not leak to the wrong people? — Red flag: privacy is an afterthought.
- Do you have evals so a prompt or model change does not regress other outputs? — Red flag: quality judged by eyeballing.
- What does an agent never do in your own company? — Red flag: no human gate on production copy, email or data access.

## Red flags / kill signals
- Recording/context products with no permission model: users will not capture "every single one of your conversations".
- No evals when swapping models or prompts: "whack-a-mole" improvement.
- Unlimited AI budget acknowledged as possibly non-scalable: "Maybe that doesn't scale when we're like 10x the size".

## Green flags
- Both traditional and startup customers use the product.
- Engineers talk to customers weekly; customer feedback captured and searchable.
- Agents run ops work so the founder spends time on high-leverage items.

## Named examples
- Circleback: AI note taker, "company brain" connecting agents, CRM, issue tracker, Slack.
- Temu onboarding: used as a study of onboarding "dopamine injection".
- OpenClaw/Telegram agents (main, finance, customers, people ops) being moved to Slack channels.

## Tensions
- "Record everything by default" vs. privacy: the source resolves it only via permissioning.
- Much of the talk is gear and personal workflow; little hard data (no revenue, growth or retention numbers).
