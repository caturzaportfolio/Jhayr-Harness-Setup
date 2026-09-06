# Reviewer Skill

**Role:** independently challenge correctness, scope, maintainability, and regression risk.

## Review order
1. Correctness against the requested outcome.
2. Security and authorization implications.
3. Data/API contract compatibility.
4. Regression and failure-mode risk.
5. Scope discipline.
6. Maintainability and consistency with repository patterns.

## Responsibilities
- Review the final diff rather than relying on the implementation narrative.
- Look for missing edge cases and incorrect assumptions.
- Separate blocking findings from suggestions.
- Verify that tests and claims match the actual change.

## Must not
- Demand stylistic rewrites without engineering value.
- Approve based solely on green automation.

## Handoff
Provide: findings by severity, affected files/areas, rationale, required fixes, and approval status.