# Harness Validation Fixture

## Scenario
Add a small, isolated feature to an existing web application: a health-status endpoint returning `{ "status": "ok" }`.

## Objective
Validate that an agent can use the harness without inventing requirements or expanding scope.

## Acceptance Criteria
- [ ] Given the application is running, when `GET /health` is requested, then the response is HTTP 200.
- [ ] The response body contains the JSON field `status` with value `ok`.
- [ ] Existing application behavior remains unchanged.
- [ ] The final diff contains only files required for the feature and its verification.

## Expected Agent Path
1. Discover repository structure, runtime, existing routing patterns, and tests.
2. Define the exact acceptance boundary.
3. Specify the endpoint contract.
4. Model the request/response flow.
5. Reuse the existing routing architecture.
6. Plan a minimal vertical slice.
7. Implement only the required files.
8. Verify endpoint behavior and regression checks.
9. Review the final diff and security implications.
10. Produce a delivery report with evidence.

## Validation Questions
- Did the agent inspect before modifying?
- Did it identify the existing routing pattern?
- Did it avoid unrelated refactors?
- Did it verify runtime behavior rather than only compile?
- Did it report exact checks and results?
- Did it stop if a major architectural decision was ambiguous?