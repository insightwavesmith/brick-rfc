# Example Building

This is a simplified example of one Building.

## Context

A small team is building a product feature.

- Founder: owns product direction and final approval
- Developer: owns implementation judgment
- Planning agent: turns the goal into a brief
- Coding agent: proposes code changes
- Review agent: checks risks, tests, and missing evidence

## Building Flow

1. The founder defines the goal.
2. The planning agent writes a brief.
3. The developer reviews and adjusts the brief.
4. The coding agent implements a narrow slice.
5. The review agent checks the result.
6. The developer fixes issues.
7. The founder approves or rejects the outcome.
8. The Building records artifacts, decisions, evidence, and follow-up work.

## 3-Axis Data

Brick records the work contract:

- feature goal
- expected artifacts
- done criteria
- retry budget

Agent records execution facts:

- who or what executed the work
- what was produced
- what failed
- what evidence was available

Link records flow decisions:

- review passed or failed
- retry, rollback, or continue
- human approval required
- next step selected

## Why The Log Matters

Later, the team can ask:

- Which kinds of work usually get stuck?
- Which review checks catch the most issues?
- Which human+AI combinations produce good results?
- Which past Building is similar to this new one?
- What decisions led to a successful outcome?

The value is not only that the work got done. The value is that the team can
see how the work happened.
