---
name: Shipping - Web
about: Prepare and ship an update to the Web target.
---

<!-- Fill in Ready before proceeding. Remove or mark N/A checks that do not apply. Link the coordinating parent issue if there is one. -->

## Ready

**What web version is shipping?**

**Which artifact or deployment is shipping?** Include its reference and the source revision or build link.

**Which environment, routes, and audience are affected?**

**Where is the finish line?** State the intended outcome and the agreed checks for this target.

**What compatibility requirements apply?** Include API versions and relevant asset or cache behavior.

**What is the rollout plan?** Record the deployment or promotion method, order, and response if checks fail.

**Which exact checks must pass?** List URLs, key journeys, accessibility or rendering checks, and where to inspect them.

**Which workstreams, reviews, or approvals must happen first?** Link the coordinating parent and dependencies. Who or what owns each gate?

**Who or what gives the Go signal, and where will it be received?**

**Who needs the outcome, and where?**

**Are we ready?**

## Set

- [ ] Is the selected build and its assets available and identified above?
- [ ] Are configuration, access, rollout controls, and cache preparations in place?
- [ ] Have the required tests and reviews passed?
- [ ] Are dependencies satisfied and the Go signal confirmed?

**Are we set?**

## Go

- [ ] Has the web update been deployed or promoted as planned?
- [ ] Have the listed routes, journeys, and other agreed checks passed?
- [ ] Has the target finish line been reached?
- [ ] Have remaining issues been handed off and the outcome communicated?

**If blocked:** What is blocking progress, and who or what can resolve it? If human help or a decision is needed, record it as hard blocked. Other targets may continue where dependencies allow.

If the finish line changes, start over and get ready again. If a human decides this attempt cannot or should not continue, record the failure and retain this issue as context for any new attempt.
**Outcome and evidence:**
