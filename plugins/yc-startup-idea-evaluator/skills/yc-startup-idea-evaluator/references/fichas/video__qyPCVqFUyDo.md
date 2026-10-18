---
source_id: video__qyPCVqFUyDo
title: Boris Cherny: We Cut 80% of Claude Code's Prompt
speaker: Boris Cherny with Diana Hu
year: 2026
url: https://www.youtube.com/watch?v=qyPCVqFUyDo
kind: video
---

## One-line thesis
Models improve so fast that the harness, prompts and even evals have a short shelf life; the opportunity is "product overhang", building the thing that unhobbles capabilities today's model already has.

## Evaluation heuristics
- **Product overhang test**: ask what today's model can already do that no current product lets it express; an idea that merely removes scaffolding to unlock that is the strongest AI-era wedge. Quote: "the model is able to do all sorts of things with today's models not a future model but today's model that we have not yet realized"
- **Hobbling check**: if your product's rigid steps constrain the model, you are the bottleneck. Good: simplest possible harness. Quote: "the product gets in the way And this getting in the way we call this hobbling"
- **Claude Code origin as template**: competitors did autocomplete and read-only chat; the winner gave the model write access and a terminal. Check what incumbents' products forbid the model from doing. Quote: "if we get rid of all the scaffolding and just give the model the simplest possible harness so it can write an entire file at a time and build an"
- **Shelf life of the harness**: assume anything built to patch model weaknesses gets deleted. Moat cannot be prompt or scaffolding. Quote: "something that you did for one model maybe three months ago it just might not translate at all to the next model"
- **Delete then re-add on evidence**: do not guess instructions; add back only after repeated failure. Quote: "only when you see it repeatedly stumble on the same thing that's when you add it back"
- **Evals outlive code, but not by much**: durable assets are evals, and even those saturate. Quote: "an EVO might live for maybe one two three model generations"
- **Re-test the "impossible" every model release**: keep a list of tasks that failed before and re-run them on each new model. Quote: "you should just keep throwing the latest model at it to see if it'll just do it because even if a previous model didn't the new one might"
- **Give slightly-too-hard tasks**: over-specifying steps underuses the model; specify goal, guardrails and exit criteria. Quote: "describe the task you want to describe the guardrails you want to describe like the exit criteria and then just go let the model cook"
- **Verification is the key skill**: a task the model can verify itself can run for days. Evaluate whether your product gives the agent a way to check its work. Quote: "Give it a way to verify the output of its work so it doesn't get stuck and it'll just go"
- **Existing test suite as enabler**: large rewrites become feasible when the test suite already defines correctness. Quote: "it's easy to know if you did the right thing"
- **Empirical over theoretical**: no trick exists; run, observe, adjust. Quote: "it's not a theoretical science it's become an empirical science"
- **Overengineering by veterans**: engineers trained on past systems over-specify, a failure mode when judging founder fit. Quote: "this is a really really common failure mode is trying to oversp specify"
- **Leverage via thousands of agents**: best users run tasks that fan out to thousands of agents; a product assuming one agent in a chat window may be underbuilt. Quote: "the best cloud users are able to spawn tasks that are really providing you a lot of leverage like thousands of agents"
- **Automating maintenance as a product wedge**: recurring routines (dead code, tests, duplicated abstractions) doing the work of many engineers. Quote: "It's doing the work of you know dozens or hundreds of engineers"
- **Builder-first**: learn by solving your own practical problem, then apply to others. Quote: "learn how to apply it And often this is about building startups"

## Questions a YC partner would ask (derived from this source)
- What would your product look like if you deleted 80% of it when the next model ships? — Most of the value sits in prompts or orchestration that a smarter model absorbs.
- What can the current model do that your users cannot get today, and why? — No concrete capability gap.
- How does your agent verify its own work? — Humans must check every step.
- Which evals do you keep, and when did you last discard one? — No evals, or evals never refreshed.
- What did you try six months ago that failed and have you retried it? — Stale beliefs about model limits.

## Red flags / kill signals
- Moat built on prompt engineering or harness scaffolding — rewritten with every model.
- Rigid step-by-step workflows imposed on the model — "hobbling".
- No self-verification loop — agent cannot run long unattended.
- Founders whose priors about what models can do are a year old.

## Green flags
- Idea that removes constraints on a capable model instead of adding layers.
- A built-in correctness signal (existing test suite, pixel comparison, spec).
- Long-running, multi-agent tasks producing results previously costing months of human work.
- Founder uses own product daily and builds from a personal practical need.

## Named examples
- Claude Code: born from unhobling Sonnet 3.5 with terminal access when others did autocomplete.
- Bun Zig to Rust rewrite: one dynamic workflow, 11 days, with steering; test suite defined success.
- Claude desktop app Swift rewrite: task running over two weeks with pixel-by-pixel screenshot comparison as verification.
- Anthropic internal routines: dead code, experiments cleanup, "abstraction police".
- Model drawing with OpenCV: capability found by accidental play, not trained.

## Tensions
- Contradicts the classic "design the system up front" engineering habit: models are treated as "a living creature", so heavy architecture is a liability.
- Claims "coding is solved" for his own kind of coding but concedes deep systems code, distributed systems and pixel-level UI still struggle.
- Source is a vendor describing its own product, so capability claims (e.g. that prompt injection can no longer be demonstrated) are unverified by the transcript.
