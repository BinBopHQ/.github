---
name: Shipping
about: Coordinate shipping an update across the relevant targets.
---

<!-- Fill in Ready before proceeding. Remove unused rows or mark N/A; link target sub-issues after this issue exists. Check items only when complete. -->

## Ready

**What is the update?**

**What is the finish line?** For each target below, specify its version, intended audience or environment, and link to its target issue. State any additional overall checks beneath the table.

| Target | Current version | Shipping version | Audience / environment | Target issue |
| --- | --- | --- | --- | --- |
| API | | | | |
| Web | | | | |
| iOS | | | | |
| Android | | | | |

**What overall checks must pass?**

**In what order will targets ship?** Which must wait for another, and which can proceed independently?

**Which compatibility constraints matter?** Include supported API and client versions and any migration sequencing.

**What happens if a target fails or is delayed?** Identify the response and who decides whether this attempt can continue.

**Who coordinates this shipment?** Who or what gives each target's Go signal, and where will it be received?

**Who needs updates, and where?**

**Are we ready?**

## Set

- [ ] Are the target versions and target issues recorded above?
- [ ] Have required builds, tests, reviews, store submissions, and approvals been completed in each target issue?
- [ ] Are the rollout order, dependencies, and compatibility requirements satisfied?
- [ ] Are the target Go signals, owners, and communication channels confirmed?

**Are we set?**

## Go

- [ ] Have the target workstreams started in the agreed order as their gates allow?
- [ ] Has each required target reached its own finish line, as recorded in its issue?
- [ ] Have the additional overall checks passed?
- [ ] Have remaining issues been handed off and the outcome communicated?

**If blocked:** What is blocking progress, and who or what can resolve it? If human help or a decision is needed, record it as hard blocked. Other targets may continue where dependencies allow.

If the finish line changes, start over and get ready again. If a human decides this attempt cannot or should not continue, record the failure and retain this issue as context for any new attempt.
**Outcome and evidence:**
