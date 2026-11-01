---
name: Shipping - API
about: Prepare and ship an update to the API target.
---

<!-- Fill in Ready before proceeding. If a step cannot apply, record why rather than silently checking it. -->

## Ready

The finish line is reached when the specified version is available in production to its intended audience and the checks below have passed.

**Shipping version:**

**Artifact or deployment reference:**

**Source revision or build link:**

**Production environment:**

**Parent shipping issue:**

**Go signal: who or what, and where?**

**Are we ready?**

## Set

- [ ] Confirm the version and artifact reference match the shipping matrix.
- [ ] Confirm the test suite and preview checks pass for the selected change.
- [ ] Confirm changes remain compatible with deployed clients; complete required migration checks.
- [ ] Confirm the artifact, production configuration, credentials, and deployment access are ready.
- [ ] Confirm the required reviews and approvals are complete.
- [ ] Receive the Go signal.

**Are we set?**

## Go

- [ ] Deploy or promote the identified API artifact; apply required migrations in their safe order.
- [ ] Verify `GET /api/v1/listings` returns a successful response with the expected response structure.
- [ ] Verify the changed endpoints behave as expected for their supported consumers.
- [ ] Check production logs and error signals for failures introduced by the deployment.
- [ ] Record the deployment and verification evidence below; notify the parent workstream.

If blocked, record the blocker and how it can be resolved. If human help or a decision is required, mark the workstream hard blocked. Other targets may continue when their dependencies permit.

If the finish line changes, start over and get ready again. If a human decides this attempt cannot or should not continue, record the failure and preserve this issue as context for a new attempt.

**Outcome and evidence:**
