# Facilitator Guide

## Delivery principle

Do not teach the acts as disconnected product features. Connect every act to the same production questions:

- What context is available?
- What authority exists?
- What can change?
- What can fail?
- Who approves?
- What evidence is recorded?
- How is blast radius contained?
- How is the system stopped or rolled back?

## Assignment facilitation

1. Explain the scenario without revealing the answer.
2. Ask participants to run or inspect the baseline.
3. Require a plan before implementation.
4. Ask one architecture question during the exercise.
5. Require a two-minute defense.
6. Reveal or discuss the model answer only afterward.
7. Convert the lesson into a repository, CI, platform, or runtime control.

## Common weak patterns to challenge

- green tests treated as proof;
- policy placed only in prompts;
- broad service credentials;
- retries at multiple layers;
- no idempotency for writes;
- retrieved text treated as authority;
- no source ownership or freshness;
- no rollback or incident evidence;
- aggregate score used to hide hard blockers.
