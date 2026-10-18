# YC startup idea evaluator (Claude skill)

A Claude skill that evaluates a startup idea the way a Y Combinator partner would in office hours: it asks the questions that matter, checks the idea against YC's published doctrine, scores it, and proposes the cheapest test that would confirm or kill it within 14 days.

**Unofficial.** This project is not affiliated with, endorsed by, or reviewed by Y Combinator. It is built from public YC material (Paul Graham's essays, Startup School, YC partner talks, YC blog and library pages) and cites every source.

## What it does

- **Asks before judging.** If the pitch is missing the basics (who has the problem, who the founders are, what evidence exists), it asks first.
- **Cites its claims.** Every rule it applies points to a numbered source in `references/sources.md` (97 sources), each with a link and a digest of short verbatim quotes in `references/fichas/`.
- **Separates score from confidence.** The score says how good the idea is if the founder's claims hold; confidence says how much of it is verified. Missing information is asked for, not punished.
- **Applies only the lenses that fit.** AI-era criteria only for AI products, enterprise sales rules only for B2B, growth benchmarks only once launched, hardware judged by milestones.
- **Tells tarpits from unpopular-but-good ideas.** An idea is not penalized for sounding strange; it is penalized for lacking an acute problem or a credible path.
- **Shows where YC voices disagree** instead of averaging them away.

## Install

**Claude Code (plugin):**

```
/plugin install yc-startup-idea-evaluator --marketplace carlosmgv02/yc-startup-idea-evaluator
```

On older Claude Code versions, add the marketplace first:

```
/plugin marketplace add carlosmgv02/yc-startup-idea-evaluator
/plugin install yc-startup-idea-evaluator@carlosmgv02
```

**Claude Code (manual):** copy `plugins/yc-startup-idea-evaluator/skills/yc-startup-idea-evaluator/` to `~/.claude/skills/` (all your projects) or to `.claude/skills/` inside a repo (that project only).

**Claude.ai or the Claude app:** zip that same folder and upload it in Settings > Capabilities > Skills, if your plan supports skills.

## Use

Just pitch your idea:

> Evaluate my startup like a YC partner: we're building ...

> Evalúa mi startup como un partner de YC: ...

Ask for "a quick gut check" for a short verdict, or "a one-shot evaluation" if you cannot answer follow-up questions.

## Layout

Paths inside `plugins/yc-startup-idea-evaluator/skills/yc-startup-idea-evaluator/`:

| Path | What |
|---|---|
| `SKILL.md` | Workflow and stance (what Claude reads first) |
| `references/*.md` | Doctrine by topic: idea quality, tarpits, founders, validation and PMF, GTM and pricing, AI era, moats, market types, scoring rubric, question bank |
| `references/sources.md` | Source index with links |
| `references/fichas/` | One digest per source: heuristics with short verbatim quotes, partner questions, red and green flags |
| `templates/teardown_report.md` | Report format |
| `evals/cases.md` | 11 test pitches with expected verdicts, 3 of them with known real outcomes |

## How it was built and its limits

- Video digests were made from YouTube auto-captions. Quotes were checked by script against the transcript text, but captions have no punctuation and sometimes mangle names; uncertain names are marked [sic].
- Most AI-era material is from 2025-2026 talks and will date. The Requests for Startups section is a snapshot (Fall 2026).
- No YC source explains how to evaluate ideas whose demand is forced by a new law; `references/market_types.md` says so and lists the checks the sources do support.
- The score is a structured summary, not a prediction. YC partners do not score ideas with a number.

## Credits and license

All quoted material belongs to its authors and is excerpted briefly for commentary, with links to the originals. The skill's own text (workflow, rubric, synthesis) is released under the [MIT License](LICENSE).
