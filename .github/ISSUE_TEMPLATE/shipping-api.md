---
name: Shipping - API
about: Prepare and ship an update to the API target.
---

<!-- Answer what applies; remove or mark N/A anything that doesn't. Link the coordinating parent issue if there is one. -->

## Ready

**What are we shipping?** Which API version, endpoints, environment, and consumers are affected?

**Where is the finish line?** What must be available to which consumers, and what checks must pass?

**What is the plan?** What is the deployment and migration order? What compatibility with existing clients and data matters? How will we respond to a bad rollout?

**What else must happen first?** Which dependencies, checks, reviews, or approvals are required, and who or what owns each gate? Where is the coordinating issue?

**Are we ready?**

## Set

- [ ] Is the intended build or artifact identified and available?
- [ ] Are configuration, secrets, access, and migration preparations in place?
- [ ] Have the agreed tests, reviews, approvals, and migration checks passed?
- [ ] Are the Go signal and its owner or source clear?

**Are we set?**

## Go

**What's happening?** Has the API change been deployed or promoted in the agreed order? What do functional checks, error rates, latency, and health signals show? What remains before the finish line?

**If blocked:** What are we waiting on? Do we need a human's help or decision? Record the blocker and who or what can resolve it. Other targets may be able to continue.

If the finish line changes, start over and get ready again. If a human decides this attempt cannot or should not continue, record the failure; a new attempt should link to this workstream.

**Outcome:** What shipped, what checks passed, and are there any remaining issues or people to notify?
