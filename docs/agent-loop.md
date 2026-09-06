# Agent Operating Loop

Use this loop for meaningful engineering work:

`UNDERSTAND → INVESTIGATE → SPECIFY → PLAN → EXECUTE → VERIFY → REVIEW → DELIVER`

## Before action
- Read the task and constraints.
- Inspect the relevant repository state.
- Identify acceptance criteria and stop conditions.

## During action
- Work within the approved scope.
- Reuse existing patterns.
- Keep changes small and reversible.
- Verify incrementally.

## Before completion
- Inspect the final diff.
- Run the relevant verification gates.
- Review security and regression risk.
- Report exactly what changed and what was verified.

If a stop condition is reached, stop the affected work and surface the decision instead of guessing.