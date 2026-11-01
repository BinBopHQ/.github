---
name: Shipping - iOS
about: Prepare and ship an update to the iOS target.
---

<!-- Answer what applies; remove or mark N/A anything that doesn't. Link the coordinating parent issue if there is one. -->

## Ready

**What are we shipping?** Which app version and build, audience, and App Store listing changes are involved?

**Where is the finish line?** What must be available in the App Store to which audience, and what checks must pass? Availability does not mean every user has installed it.

**What is the plan?** How will the build be tested, submitted, reviewed, and made available? What API compatibility and response to a bad rollout matter?

**What else must happen first?** Which dependencies, checks, reviews, or approvals are required, and who or what owns each gate? Where is the coordinating issue?

**Are we ready?**

## Set

- [ ] Is the intended version and build identified and tested?
- [ ] Has the build been submitted and approved by Apple, as required for the agreed rollout?
- [ ] Are App Store listing details, release settings, and access ready?
- [ ] Are the Go signal and its owner or source clear?

**Are we set?**

## Go

**What's happening?** Has the approved build been made available using the agreed settings? What do App Store availability and post-release checks show? What remains before the finish line?

**If blocked:** What are we waiting on? Do we need a human's help or decision? Record the blocker and who or what can resolve it. Other targets may be able to continue.

If the finish line changes, start over and get ready again. If a human decides this attempt cannot or should not continue, record the failure; a new attempt should link to this workstream.

**Outcome:** What shipped, what checks passed, and are there any remaining issues or people to notify?
