---
name: Shipping
about: Coordinate shipping an update across the relevant targets.
---

<!-- Adapt these questions to the shipment. Add answers, tasks, links, etc. as useful. Check a box when it has been addressed, including when it does not apply. -->

## Ready

*Get ready.*

- [ ] **What are we getting ready for, precisely?** What is changing, and who is it for?

- [ ] **What do we need to know?** Which targets are involved? What are the requirements, constraints, dependencies, compatibility needs, etc.?

- [ ] **Where is the finish line, exactly?** What does available mean for each target, and how will we know the agreed rollout checks have passed?

**The finish line should never move. If it does, start over and get ready again.**

- [ ] **What should we prepare before starting?** What needs to be built, tested, submitted, reviewed, etc.?

- [ ] **What is our final plan?** How will we coordinate the rollout, including work that can proceed independently and any follow-up if something goes wrong?

- [ ] **Are there any gates?** What reviews, approvals, automated checks, etc. are needed? Who or what is responsible for each one?

- [ ] **Which workstreams need their own issues?** Create or link sub-issues for the relevant targets, such as API, web, iOS, Android, etc. Define their finish lines and any dependencies.

### Rollout coordination

- [ ] Identify the version or change and the targets included in this shipment.
- [ ] Create or link a sub-issue for each target that needs independent tracking; record its finish line and gate owner there.
- [ ] Identify ordering and compatibility requirements, including older app versions and API support.
- [ ] Agree on rollout checks, the response to a partial rollout, and who needs updates.

**Are we ready?**

## Set

*Get set.*

- [ ] **What needs to be in place before we go?** People, access, builds, rollout settings, etc.?

- [ ] **What needs to happen before we go?** Testing, submissions, approvals, reviews, etc.?

- [ ] **Who or what confirms that we're set to go?** How and where will we receive the signal?

- [ ] **Are we sure we're ready?** Have we double-checked everything? Triple-checked?

- [ ] Confirm each target is prepared as agreed, including store submission and approval where needed.
- [ ] Confirm access, deployment or release controls, and the agreed Go signal for each target.

**Are we set?**

## Go

*Go!*

- [ ] Coordinate the target rollouts as their gates and dependencies allow.
- [ ] Verify each required target outcome and its agreed rollout checks.
- [ ] Reach the parent finish line, including the agreed overall checks.

**Keep going until finished. If blocked:**

- **Are we hard blocked?** Do we need a human's help or decision to continue? If so, ask for help.
- **How can we get unblocked?** If we're not hard blocked, can we resolve the blocker, wait for a result, use another workstream, etc.?

A blocked target doesn't necessarily stop the others. Once unblocked, continue toward the same finish line.

**If a human decides the attempt cannot or should not continue, it has failed.** Preserve the workstream and its outcome. If we try again, start a new workstream with the original available as context.

Before stopping:

- [ ] **Are there any remaining issues?** Have we addressed them and prepared them for hand off?
- [ ] **Is the outcome clear to those who need to know?** Do we need to do any communication, announcements, etc.?
