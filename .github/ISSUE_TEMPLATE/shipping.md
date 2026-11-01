---
name: Shipping
about: Coordinate shipping an update across the relevant targets.
---

<!-- Answer the questions as the shipment takes shape. Add target issues, tasks, links, evidence, etc. as useful; mark questions that do not apply. -->

## Ready

*Get ready.*

**What are we getting ready for, precisely?** What is changing, and who is it for?

**What do we need to know?** Which targets, requirements, constraints, dependencies, compatibility needs, etc. matter?

**Where is the finish line, exactly?** What does availability mean for each target, and which rollout checks must pass?

**The finish line should never move. If it does, start over and get ready again.**

**What should we prepare before starting?** What needs to be built, tested, submitted, reviewed, etc.?

**What is our final plan?** What is the rollout order? Which targets can proceed independently? How will we handle a partial rollout, older clients, and issues that arise?

**Are there any gates?** What checks, reviews, or approvals are needed? Who or what is responsible for each one?

**Which workstreams need their own issues?** Link the relevant API, web, iOS, Android, etc. sub-issues and record their dependencies. What is each target's finish line?

**Are we ready?**

## Set

*Get set.*

**What needs to be in place before we go?** Are the people, access, builds, rollout controls, etc. ready for each target?

**What needs to happen before we go?** Are testing, submissions, approvals, reviews, etc. complete where needed?

**Who or what confirms that we're set to go?** How and where will we receive the signal for each target?

**Are we sure we're ready?** Have we double-checked everything? Triple-checked?

**Are we set?**

## Go

*Go!*

**Where are we now?** Which targets have shipped, which checks have passed, and what remains to reach the parent finish line?

A blocked target doesn't necessarily stop the others.

**Keep going until finished. If blocked:**

- **Are we hard blocked?** Do we need a human's help or decision to continue? If so, ask for help.
- **How can we get unblocked?** If we're not hard blocked, can we resolve the blocker, wait for a result, use another workstream, etc.?

Once unblocked, continue toward the same finish line. If a human decides the attempt cannot or should not continue, it has failed. Preserve the workstream and its outcome; a new attempt should have the original available as context.

Before stopping:

**Are there any remaining issues?** Have we addressed them and prepared them for hand off?

**Is the outcome clear to those who need to know?** Do we need to communicate with the coordinating workstream, make announcements, etc.?
