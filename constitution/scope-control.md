# Scope Control

## Allowed

- Files directly necessary for the requested change
- Tests required to prove the change
- Documentation required to keep the system accurate
- Small supporting changes required for correctness or compatibility

## Not allowed without explicit need

- Unrelated refactors
- Unrelated UI redesigns
- Dependency upgrades
- Renaming unrelated files or symbols
- Speculative abstractions
- Feature additions not requested
- Removing existing functionality
- Broad cleanup unrelated to the acceptance criteria

## Scope rule

If an adjacent improvement is discovered, record it as a follow-up rather than silently implementing it.
