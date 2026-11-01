---
name: Shipping - API
about: Prepare and ship an update to the API target.
---

<!-- Answer the questions as the shipment takes shape. Add tasks, links, evidence, etc. as useful; mark questions that do not apply. -->

## Ready

*Get ready.*

**What are we getting ready for, precisely?** Which API version, endpoints, changes, and consumers are involved?

**What do we need to know?** What compatibility, deployed-client, environment, and data or migration constraints matter?

**Where is the finish line, exactly?** What does availability mean for the affected consumers, and which health, error, latency, and functional checks must pass?

**The finish line should never move. If it does, start over and get ready again.**

**What should we prepare before starting?** What builds, tests, reviews, etc. are needed?

**What is our final plan?** What is the deployment and migration order? How will we respond if a change needs a fix?

**Are there any gates?** Who or what is responsible for checks, reviews, approvals, etc.?

**Is this part of a larger shipment?** Where is the coordinating issue, and what are the dependencies?

**Are we ready?**

## Set

*Get set.*

**What needs to be in place before we go?** Are the intended artifact, configuration, access, and migration preparations ready?

**What needs to happen before we go?** Have the agreed tests, migration checks, reviews, and approvals happened?

**Who or what confirms that we're set to go?** How and where will we receive the signal?

**Are we sure we're ready?** Have we double-checked everything? Triple-checked?

**Are we set?**

## Go

*Go!*

**Where are we now?** Has the API change been deployed or promoted in the agreed order? What do the health and consumer-facing checks show? What remains to reach the finish line?

**Keep going until finished. If blocked:**

- **Are we hard blocked?** Do we need a human's help or decision to continue? If so, ask for help.
- **How can we get unblocked?** If we're not hard blocked, can we resolve the blocker, wait for a result, use another workstream, etc.?

Once unblocked, continue toward the same finish line. If a human decides the attempt cannot or should not continue, it has failed. Preserve the workstream and its outcome; a new attempt should have the original available as context.

Before stopping:

**Are there any remaining issues?** Have we addressed them and prepared them for hand off?

**Is the outcome clear to those who need to know?** Do we need to communicate with the coordinating workstream, make announcements, etc.?
