# Harness Usage

This repository is an agent-neutral operating harness for software engineering.

## Start a task

1. Read `AGENTS.md`.
2. Read the applicable workflow and skill files.
3. Fill `templates/task.md`.
4. Investigate the target repository before editing.
5. Create an implementation plan for meaningful changes.
6. Execute only the approved scope.
7. Run applicable verification and security gates.
8. Inspect the final diff.
9. Complete `templates/review.md` and `templates/delivery.md`.
10. Commit only after verification.

## Role selection

- Researcher: unknowns and evidence.
- Architect: system design and trade-offs.
- Implementer: bounded code changes.
- Tester: acceptance and regression evidence.
- Reviewer: independent challenge of the diff.
- Security: attack-surface and control review.
- DevOps: build, deployment, migration, and operations.

One agent may perform multiple roles, but role changes should be explicit in its reasoning/output.

## Completion rule

Done means the acceptance boundary is satisfied and the relevant evidence is recorded. A clean-looking diff, successful compilation, or agent confidence is not sufficient by itself.