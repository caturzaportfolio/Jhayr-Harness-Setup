# Delivery Workflow

Use the delivery gate:

`WORKING TREE → DIFF → VERIFY → COMMIT → PUSH → PR → CI → DEPLOY`

Before delivery:

1. Confirm acceptance criteria.
2. Inspect the final diff.
3. Confirm only intended files changed.
4. Run and record relevant verification.
5. Keep commits coherent and traceable to the engineering objective.
6. Surface unresolved risks or verification gaps.

Production release remains subject to human approval.
