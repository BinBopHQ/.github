---
name: Shipping - API
about: Prepare and ship an update to the API target.
---

<!-- Fill in Ready before proceeding. Remove or mark N/A checks that do not apply. Link the coordinating parent issue if there is one. -->

## Ready

**What API version is shipping?**

**Which artifact or deployment is shipping?** Include its reference and the source revision or build link.

**Which environment and consumers are affected?**

**Where is the finish line?** State the intended outcome and the agreed checks for this target.

**What API compatibility must be maintained?** List supported clients or contract versions.

**What is the deployment and migration order?** Include data migrations, prerequisites, and forward-fix or recovery steps.

**Which exact checks must pass?** Record endpoints, health signals, thresholds, and where to inspect them.

**Which workstreams, reviews, or approvals must happen first?** Link the coordinating parent and dependencies. Who or what owns each gate?

**Who or what gives the Go signal, and where will it be received?**

**Who needs the outcome, and where?**

**Are we ready?**

## Set

- [ ] Is the selected artifact available and identified above?
- [ ] Are configuration, secrets, access, and migration preparations in place?
- [ ] Have the required tests, migration checks, reviews, and approvals passed?
- [ ] Are dependencies satisfied and the Go signal confirmed?

**Are we set?**

## Go

- [ ] Has the API been deployed or promoted in the agreed order?
- [ ] Have the listed functional and operational checks passed?
- [ ] Has the target finish line been reached?
- [ ] Have remaining issues been handed off and the outcome communicated?

**If blocked:** What is blocking progress, and who or what can resolve it? If human help or a decision is needed, record it as hard blocked. Other targets may continue where dependencies allow.

If the finish line changes, start over and get ready again. If a human decides this attempt cannot or should not continue, record the failure and retain this issue as context for any new attempt.
**Outcome and evidence:**
