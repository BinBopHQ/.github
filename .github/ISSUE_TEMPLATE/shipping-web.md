---
name: Shipping - Web
about: Prepare and ship an update to the Web target.
---

<!-- Answer what applies; remove or mark N/A anything that doesn't. Link the coordinating parent issue if there is one. -->

## Ready

**What are we shipping?** Which web version or build, routes, and audiences are affected?

**Where is the finish line?** What must be available to whom, and what checks must pass?

**What is the plan?** How will the update roll out? What API compatibility, asset and cache behavior, and response to a bad rollout matter?

**What else must happen first?** Which dependencies, checks, reviews, or approvals are required, and who or what owns each gate? Where is the coordinating issue?

**Are we ready?**

## Set

- [ ] Is the intended build and its assets identified and available?
- [ ] Are configuration, access, rollout controls, and cache behavior ready?
- [ ] Have the agreed tests and reviews passed, including relevant accessibility and rendering checks?
- [ ] Are the Go signal and its owner or source clear?

**Are we set?**

## Go

**What's happening?** Has the update been deployed or promoted? What do the agreed route, key journey, rendering, and other checks show? What remains before the finish line?

**If blocked:** What are we waiting on? Do we need a human's help or decision? Record the blocker and who or what can resolve it. Other targets may be able to continue.

If the finish line changes, start over and get ready again. If a human decides this attempt cannot or should not continue, record the failure; a new attempt should link to this workstream.

**Outcome:** What shipped, what checks passed, and are there any remaining issues or people to notify?
