# Claude Production Architecture Bootcamp

## Claude Code, APIs, Agent SDK, MCP, RAG, Evals, Security, and Production Governance

This repository contains the complete hands-on material for a nine-act workshop on designing, governing, securing, evaluating, and operating production-ready Claude systems.

The workshop is built around one principle:

> Claude is not merely a model or coding assistant. It becomes part of a production architecture with context, tools, authority, evidence, controls, and operational responsibility.

## What participants will learn

Participants will learn how to:

- move from vibe coding to governed engineering;
- use `CLAUDE.md` as a repository control plane;
- apply plan-first development and ARCH-GATE reviews;
- design structured Claude API contracts;
- build bounded agent workflows with budgets and stop conditions;
- expose enterprise tools safely through MCP;
- build trusted RAG pipelines with security, evals, and observability;
- design CI/CD, rollout, rollback, and incident controls;
- defend a Go, Conditional Go, or No-Go architecture decision.

## Repository structure

| Directory | Act | Focus |
|---|---:|---|
| `act-1/` | 1 | The Day Vibe Coding Hit Production |
| `act-2/` | 2 | Claude Architecture Landscape |
| `act-3/` | 3 | Claude Code and Repository Control Plane |
| `act-4/` | 4 | Governed Engineering Workflows and ARCH-GATE |
| `act-5/` | 5 | Claude APIs and Structured Application Contracts |
| `act-6/` | 6 | Agent SDK and Bounded Autonomous Workflows |
| `act-7/` | 7 | MCP and Controlled Enterprise Agency |
| `act-8/` | 8 | Trusted RAG, Security, Evals, and Observability |
| `act-9/` | 9 | Production Delivery and Architecture Defense |

## Start here

1. Read [`START_HERE.md`](START_HERE.md).
2. Review [`PREREQUISITES.md`](PREREQUISITES.md).
3. Follow the workshop sequence in [`WORKSHOP_AGENDA.md`](WORKSHOP_AGENDA.md).
4. Open each act's `README.md` or `START_HERE.md`.
5. Run the baseline code and tests before completing assignments.
6. Present your answer before reading any model answer.

## How each act is organized

Most acts contain some combination of:

- Java source code;
- assignments;
- participant worksheets;
- model answers;
- facilitator guides;
- Claude Code configuration;
- architecture templates;
- tests and evaluation datasets;
- workshop slides or references.

## Recommended participant workflow

```text
Read → Inspect → Baseline → Plan → Execute → Verify → Defend → Reflect
```

Do not treat passing tests as sufficient evidence. A strong solution also explains architecture boundaries, security, ownership, failure handling, observability, and rollback.

## Intended audience

- enterprise and solution architects;
- senior developers and technical leads;
- platform and DevSecOps engineers;
- AI application and agent builders;
- security, risk, and governance practitioners;
- teams preparing for Claude architecture or production-readiness assessments.

## Workshop outcome

By the end of the workshop, participants should be able to defend a production architecture using evidence rather than feature memorization.
