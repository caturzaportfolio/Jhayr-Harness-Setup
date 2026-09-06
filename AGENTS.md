# Agent Contract

This repository is a reusable engineering harness. Any coding agent operating in a repository that adopts this harness MUST follow the rules below.

## Before acting

1. Inspect the repository, relevant documentation, dependencies, existing implementation, tests, schema, and configuration.
2. Establish current behavior and existing patterns from executable evidence.
3. State objective, scope, constraints, unknowns, and acceptance criteria.
4. Do not invent requirements when they can be investigated or clarified.
5. For meaningful or cross-cutting changes, present a bounded implementation plan before editing.

## While acting

- Prefer existing patterns over new abstractions.
- Modify only the necessary scope.
- Make small, reversible changes.
- Do not redesign unrelated UI.
- Do not refactor unrelated code.
- Do not upgrade dependencies without a demonstrated need.
- Do not remove existing behavior unless explicitly required.
- Keep commits coherent and traceable to an engineering objective.

## Before declaring done

Run the strongest appropriate verification: type checks, lint, unit/integration/E2E tests, build, and runtime or acceptance verification where applicable.

Inspect the final diff for correctness, maintainability, architecture, security, regressions, and scope.

Report what changed, what was verified, what remains uncertain, and any follow-up that is genuinely required.

Stop when acceptance criteria are satisfied. Do not expand scope merely because additional improvements are possible.
