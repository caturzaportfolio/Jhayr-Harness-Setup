# Jhayr Harness Setup

A reusable, agent-neutral engineering harness derived from the **Agentic Engineering OS — ChatGPT Harness** and designed to operate inside real software repositories.

## Purpose

This repository turns engineering cognition into executable guidance for AI coding agents and human engineers. The broader **FULL Engineering OS for large scale systems** provides governance and lifecycle context; this repository provides the fast operational harness used during implementation work.

## Core principle

> Don't code first. Understand → Specify → Investigate → Plan → Execute → Verify → Review → Deliver → Learn.

## Operating lifecycle

`DISCOVER → DEFINE → SPECIFY → MODEL → ARCHITECT → PLAN → CONTEXTUALIZE → IMPLEMENT → VERIFY → REVIEW → SECURE → DELIVER → DEPLOY → OBSERVE → LEARN → ITERATE`

## Operating contract

Agents must inspect before modifying, use authoritative evidence, preserve existing patterns, stay within explicit scope, verify meaningful changes, inspect the final diff, and report uncertainty. Humans retain authority over product intent, scope, business rules, major architecture trade-offs, security-sensitive decisions, breaking changes, and production release approval.

## Repository map

- `AGENTS.md` — agent operating contract.
- `harness.yaml` — machine-readable lifecycle and principles.
- `constitution/` — authority, truth, engineering, and scope rules.
- `workflows/` — lifecycle procedures.
- `skills/` — specialized engineering roles.
- `context/` — project, architecture, and task context.
- `verification/` — acceptance, security, contract, regression, and completion gates.
- `templates/` — reusable task, plan, review, acceptance, and delivery artifacts.
- `docs/` — usage and lifecycle documentation.
- `validation/` — self-validation fixture and checklist.

## How to use

1. Read `AGENTS.md`.
2. Create a task using `templates/task.md`.
3. Investigate before editing.
4. Plan meaningful changes.
5. Implement the smallest coherent vertical slice.
6. Verify acceptance, contracts, regressions, and security as applicable.
7. Review the final diff.
8. Complete the delivery report.
9. Commit only after evidence supports completion.

## Validation status

The harness is **structurally complete and self-documented**, but structural completeness is not proof that it works optimally on every repository. Use `validation/sample-task.md` against a real application repository and record the result in `validation/harness-checklist.md` before treating the harness as production-proven.

## Boundary

`FULL Engineering OS → Agentic Engineering Harness → Coding Agent → Target Repository → Runtime`

Notion can remain the semantic/control plane. Git, tests, and observed runtime remain executable evidence.