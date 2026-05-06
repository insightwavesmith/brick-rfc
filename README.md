# Brick RFC: Human-AI Work Orchestration

Brick is an early idea for a human-AI work orchestration engine.

This RFC is intentionally short. The goal is to test the framing, not to present
a finished product.

## Thesis

For the next few years, humans will likely keep final judgment and creative
direction, while AI agents increasingly execute, analyze, review, and report.

The missing layer may not be another chatbot. It may be a shared operating layer
for human+AI teams: a way to delegate work, review outputs, approve decisions,
preserve evidence, and learn from how work actually happened.

## Core Model

- Brick: a unit of work
- Agent: a human or AI executor
- Link: review, approval, retry, rollback, and next-step flow
- Storage: evidence, artifacts, logs, and status
- Wiki: organizational memory candidates

The core constraint is that humans and AI agents can both execute work, but final
judgment and creative direction often remain human-owned. Brick tries to make
that boundary explicit instead of hiding it inside chat history.

## Why Existing Tools Feel Insufficient

Project management tools track tasks.
Chat tools hold conversations.
GitHub tracks code changes.
LLMs produce outputs.

But mixed human+AI work creates a missing middle layer:

- Who or what performed each step?
- Which output was reviewed?
- Which evidence justified approval?
- Which decision was human-owned?
- Which retry or rollback happened, and why?
- What did the team learn from this Building?

Most tools preserve fragments of this process. Brick tries to keep the work
process and the work result connected.

## What It Does

Brick lets a small team run work as Buildings:

1. define the work
2. delegate to humans or AI agents
3. review outputs
4. approve, reject, or retry decisions
5. preserve evidence and artifacts
6. learn from past work

## Solo vs Team Use

In solo use, Brick behaves like agent orchestration.

In team use, Brick becomes human orchestration.

The same model can describe a founder working with AI agents, or a small team
where people and AI agents collaborate on one project.

## What A Building Records

A Building is not only a task. It records the process around the task:

- goal
- work units
- human and AI agents
- review results
- decisions
- artifacts
- evidence
- failures
- retries
- final outcome

The hope is that many Buildings become a useful organizational memory: a graph of
how the team actually plans, executes, reviews, approves, fails, retries, and
learns.

## Why This Might Matter

Teams already use AI to produce code, plans, analysis, and reviews. But the work
often disappears into chats, pull requests, documents, and private context.

Brick tries to keep the process and the output together:

- who or what did the work
- what evidence was produced
- what was reviewed
- what was approved or rejected
- where the work got stuck
- what similar past work can teach us

The long-term goal is not just automation. It is an organizational work graph
that shows how successful work actually happened.

## Question

Does this feel like a real missing layer for human+AI teams, or just another
workflow tool?

More specific feedback would be helpful:

1. Does the framing of human-AI work orchestration make sense?
2. Is "Building" a useful abstraction, or does it feel too heavy?
3. What would make this clearly different from project management or workflow tools?

## Example

See [docs/example-building.md](docs/example-building.md).
