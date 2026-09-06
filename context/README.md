# Context System

Context is the minimum authoritative information an agent needs to act safely.

## Context order

1. Product/domain intent
2. Approved specification
3. Architecture and contracts
4. Relevant repository files
5. Current runtime/test evidence
6. Task-specific constraints and acceptance criteria

## Rules

- Prefer current repository evidence over stale notes.
- Keep context task-scoped; do not dump the whole repository into every task.
- Record unknowns instead of filling gaps with guesses.
- Link decisions to their source.
- Refresh context after meaningful repository changes.

## Files

- `project-context.md` — stable product/system context.
- `architecture-context.md` — architecture and boundary context.
- `task-context.md` — per-task working context and evidence.