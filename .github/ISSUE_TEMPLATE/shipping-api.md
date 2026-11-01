---
name: Shipping - API
about: Prepare and ship an update to the API target.
---

<!-- Adapt the checks to this shipment. Record answers, links, evidence, owners, etc. Check a box when addressed, including when it does not apply. -->

## Ready

*Get ready.*

**What are we getting ready for?**

**Where is the finish line, exactly?** The agreed API change is available to its intended consumers and its rollout checks pass. Define endpoints, environment, and availability.

**The finish line should never move. If it does, start over and get ready again.**

- [ ] Identify the API version, changes, affected consumers, and compatibility with deployed clients.
- [ ] Plan database or data migrations, deployment order, and a forward fix if needed.
- [ ] Define health, error, latency, and functional checks appropriate to the change.
- [ ] Identify dependencies, gates, and who or what is responsible for each one.
- [ ] Link the coordinating parent issue if this work is part of a larger shipment.

**Are we ready?**

## Set

*Get set.*

- [ ] Confirm the selected build or deployment artifact, configuration, secrets, and access are ready.
- [ ] Confirm tests, migration readiness, approvals, and the person or system giving the Go signal.
- [ ] Confirm how and where the Go signal will be received and double-check that we're ready.

**Are we set?**

## Go

*Go!*

- [ ] Deploy or promote the agreed API change and apply migrations in the agreed order.
- [ ] Verify API health and consumer-facing behavior using the agreed checks.
- [ ] Confirm the finish line has been reached.

**Keep going until finished. If blocked:**

- **Are we hard blocked?** Do we need a human's help or decision to continue? If so, ask for help.
- **How can we get unblocked?** If we're not hard blocked, can we resolve the blocker, wait for a result, use another workstream, etc.?

Once unblocked, continue toward the same finish line. If a human decides the attempt cannot or should not continue, it has failed. Preserve the workstream and its outcome; a new attempt should have the original available as context.

Before stopping:

- [ ] Address or hand off remaining issues.
- [ ] Communicate the outcome to those who need to know, including the coordinating workstream if applicable.
