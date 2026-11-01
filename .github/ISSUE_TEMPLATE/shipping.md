---
name: Shipping
about: Coordinate shipping an update across the relevant targets.
---

<!-- Complete the version matrix and links before shipping. Mark unaffected targets N/A. -->

## Ready

The finish line is reached when every included target has reached the finish line in its linked issue.

| Target | Current version | Shipping version | Target issue |
| --- | --- | --- | --- |
| API | | | |
| Web | | | |
| iOS | | | |
| Android | | | |

**Coordinator:**

**Where will the outcome be shared?**

- [ ] Create or link a target issue for each included target and record its version above.
- [ ] Confirm the API and existing clients remain compatible throughout the rollout; record any blocking dependencies in the target issues.

**Are we ready?**

## Set

- [ ] Check each included target issue and record any outstanding preparations, checks, or approvals there.
- [ ] Confirm each included target's Go signal and responsible person or system are identified in its issue.

**Are we set?**

## Go

Start included targets in this order: **API → Web → iOS → Android**. Skip unaffected targets. Start each target only after its own preparations and Go signal are complete. A blocked target does not stop an independent target; wait when a recorded dependency requires it.

- [ ] Start API shipping, if included.
- [ ] Start web shipping, if included.
- [ ] Start iOS shipping, if included.
- [ ] Start Android shipping, if included.
- [ ] Confirm each included target has reached its finish line in its target issue.
- [ ] Share the outcome and hand off remaining issues.

If blocked, record the blocker and how it can be resolved. If human help or a decision is required, mark the workstream hard blocked. Other targets may continue when their dependencies permit.

If the finish line changes, start over and get ready again. If a human decides this attempt cannot or should not continue, record the failure and preserve this issue as context for a new attempt.

**Outcome:**
