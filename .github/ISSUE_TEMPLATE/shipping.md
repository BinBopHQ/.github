---
name: Shipping
about: Coordinate shipping an update across the relevant targets.
---

<!-- Answer what applies; remove or mark N/A anything that doesn't. Link target sub-issues after creating this issue. -->

## Ready

**What are we shipping, and who is it for?**

**Where is the finish line?** Which targets must be available, to which audiences, and what checks must pass?

**Which targets are involved?** Link or create a sub-issue for each target that needs its own workstream. Each should define its own finish line and gate.

| Target | Workstream | Dependencies / gate |
| --- | --- | --- |
| | | |

**What is the rollout plan?** What order, compatibility requirements, and fallback or forward-fix options matter? What can continue if one target is blocked?

**Who needs to know?** Who coordinates the shipment, gives each Go signal, and receives updates?

**Are we ready?**

## Set

- [ ] Are the required target builds and rollout controls ready?
- [ ] Have the agreed testing, reviews, submissions, and approvals happened?
- [ ] Are dependencies satisfied, including compatibility with older clients?
- [ ] Is each Go signal and its owner or source clear?

**Are we set?**

## Go

**What's happening?** Which targets have shipped, which are waiting, and what do the agreed checks show? Update the target issues as work progresses.

**If blocked:** What are we waiting on? Do we need a human's help or decision? Record the blocker and who or what can resolve it. Other targets may be able to continue.

If the finish line changes, start over and get ready again. If a human decides this attempt cannot or should not continue, record the failure; a new attempt should link to this workstream.

**Outcome:** What shipped, what checks passed, and are there any remaining issues or people to notify?
