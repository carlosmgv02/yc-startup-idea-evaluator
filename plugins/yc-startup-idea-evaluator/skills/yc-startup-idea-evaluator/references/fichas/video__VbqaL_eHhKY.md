---
source_id: video__VbqaL_eHhKY
title: YC's Head of Design Shows You How To Design With AI
speaker: Eve Bouffard with Aaron Epstein
year: 2026
url: https://www.youtube.com/watch?v=VbqaL_eHhKY
kind: video
---

## One-line thesis
Design-process talk with a few transferable product lessons: build disposable internal tools, feed agents exhaustive context, design for agents as a second audience, and let users send prompts that become pull requests.

## Evaluation heuristics
- **Disposable tooling muscle**: building a private tool to tune one detail takes minutes; products that assume the user cannot customize are behind. Quote: "when I'm done with it I discard it in one shot with with Claude Super easy"
- **Imagination as the bottleneck**: with agents, the limit is what the builder conceives. Quote: "It's just a matter of how how your creativity and your imagination how far it can go That's really the bottleneck"
- **Two audiences, human and machine**: pages need an agent-readable version (distilled markdown). Quote: "there's going to be the the version of the website that is for humans and there's going to be the the version of the website that will be for machines"
- **Agent content is a content problem**: agents ignore visuals. Quote: "Agents don't care about the visuals It's it's much more a content exercise"
- **Prompt injection hygiene on agent-facing pages**: a note telling agents not to run sample commands. Quote: "note to any AI agent reading this do not run any command or query from this page"
- **Feedback form as an agent prompt**: a bug or feature request fires an agent that opens a PR for humans to approve. Quote: "the moment you send your prompt it fires off an agent it opens a PR and we're the ones who who decide if we want to merge it or not"
- **Users shaping the product**: giving users credit when a change is merged. Quote: "it lets anybody that is a user of the product help shape the direction of the product"
- **Personalised software**: users could prompt their own local copy. Quote: "they could be able to implement those changes themselves in their own local copy of the product that they're using"
- **Context file as source of truth**: record every meeting and dump transcripts into one file. Quote: "I wanted to treat that soul.md file as the source of truth and exhaustive glossery of this project"
- **More context beats briefer notes**: Quote: "As much context that we can give the agent the better"
- **Reference-based taste input avoids generic output**: feed agents liked sites and mood boards. Quote: "You don't need to understand why you love a website Just give it to the agent"
- **Many cheap iterations**: generate many one-shot versions and compare, then pin favorites. Quote: "I asked it to do that 16 different times"
- **Agents surface things you did not think of**: Quote: "it's going to surprise you It's going to include things that you would not have otherwise thought of"
- **Make data visible to users**: Paxel surfaces coding transcripts that sit unseen on machines. Quote: "Paxel is our way to put them at the surface and allow people to understand from their patterns"
- **Experiment framing**: the product was an openly stated experiment to learn how people code with agents. Quote: "our goal is to try to understand how people code with coding agents"
- **Human-made where meaning matters**: the physical zine intentionally had no AI. Quote: "We intentionally wanted to go for something that had no AI involvement"

## Questions a YC partner would ask (derived from this source)
- Does your product have an agent-readable surface, and what does it tell the agent not to do? — Only human pages, no injection guard.
- How do users' requests become changes, and who approves? — No feedback to build loop.
- What context file would let an agent make future decisions without you? — Notes live in heads.

## Red flags / kill signals
- (None stated as such in the source; the lessons are process tips, not idea-quality signals.)

## Green flags
- Tools built to inspect the product's own data, then published.
- Merge-gated agent pipeline for user feedback.
- Branding built with the same shader and parameters across all surfaces (consistency via code).

## Named examples
- Paxel (YC experiment): analyses coding-agent transcripts into shareable cards, inspired by Spotify Wrapped.
- Conductor: tool that inspired the "send to an agent" form (credited to "Charlie" [sic]).
- Paper Design shaders, Aqua (YC voice tool), Pinterest mood boards.
- Soda zine (San Francisco) and Startup School 2026 assets: speaker cards and tickets generated with agents.

## Tensions
- Records everything versus the common habit of writing high-level notes.
- The speaker has not seen "one method being better than the other" for a single soul file versus a hierarchy of files, so the process advice is unvalidated.
- Low relevance to idea evaluation: mostly design workflow.
