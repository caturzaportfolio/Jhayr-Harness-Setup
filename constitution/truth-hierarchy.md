# Truth Hierarchy

When engineering sources disagree, do not silently choose the most convenient source. Investigate the conflict.

Highest to lowest authority:

1. Observed production/runtime behavior
2. Executable repository + tests
3. Approved architecture/specification
4. Planning notes
5. Agent assumptions

A lower-level assumption must never silently override stronger executable or approved evidence.

If the conflict materially affects scope, architecture, security, data integrity, compatibility, or release behavior, stop and request human direction after documenting the evidence.
