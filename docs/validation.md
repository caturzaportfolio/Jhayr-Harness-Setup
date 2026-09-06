# Harness Validation

The harness is considered structurally valid when:

- `AGENTS.md` exists and states the agent contract.
- `harness.yaml` defines the lifecycle, authority, scope, and truth hierarchy.
- Every lifecycle stage maps to a workflow, skill, or documented artifact.
- Task, plan, review, acceptance, and delivery templates exist.
- Verification and security gates exist.
- Context rules define authoritative evidence and conflict handling.
- A sample task can pass through discovery, planning, implementation, verification, review, and delivery without requiring undocumented process.

Validation must test the harness against a real repository before claiming production readiness.