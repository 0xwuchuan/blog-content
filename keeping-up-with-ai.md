---
title: Am I keeping up with AI?
date: 2026-01-20
tags: ai
---

I've had the privilege to use AI tools at my work at OKX. Trying them out has been exhilarating. Everything changes and moves so fast, which is similar to how fast the blockchain space moves as well, except AI is moving even faster. It's crazy to think about it because there is a whole portion of people in the world that has no idea how fast AI is moving. Not trying to say we are in a bubble but most of what I'm experiencing is because of the occassional (more truthfully -> constant) doomscrolling I've been doing on Twitter. Feels like one week a prompting or workflow technique feels like it has cracked the code, and then another week it's suddenly irrelevant.

I wanted to document some of the insights I've gained and read about working with these tools.

### Context is King
With the current models, as the context window fills up, the model performance degrades. It is important to keep sessinos focused and context minimal. This is the philosophy of a very popular technique (Ralph) that was all the hype. Probably skill difference but i rather steer the model myself and validate it's outputs before moving on to the new task. However, having it working while you are asleep gives crazy amount of dopamine when you wake up to a shit ton of work done. 

If Context is King, context rot is corruption. When the LLM starts hallucinating, don't bother correcting it. I find it easier to just start a new session and make the corresponding adjustments.

### Agents Need Backpressure

Agents work best with feedback loops. Type checks, linting, and test cases provide the necessary backpressure to keep agents on track. Without these guardrails, agents drift. 

### MCPs vs Direct CLI

Not really convinced about MCPs yet. Agents seem to work better with direct CLI access. CLI simply feels cleaner (?) I find most workflows that are popular are simply mimicking a human workflow. As humans, we just run the cli tool help command or just look directly at the documentation. But I'm not sure, haven't had a convincing argument for either yet. 

### The End of Writing Code

The era of writing code seems to be over. It is a tough pill to swallow honestly. I love spending time to ponder about the implementation and writing clean code. But now everyone gets to show their competence and taste through other things: system design, architecture decisions, product thinking. AI tools provides a higher level of abstraction that allows us to focus on more important things. 

## Different Agents, Different Personalities

Different agents and models have distinct "personalities" and working styles. Context files like AGENTS.md and CLAUDE.md ideally shouldn't be the same - each should be tailored to how that specific agent operates. The configuration is really messy though, why does everyone gotta decide on a different standard :(
