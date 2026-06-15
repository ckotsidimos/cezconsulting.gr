+++
title = "Can Your Organisation Actually Govern Agentic AI?"
summary = "Most AI governance assessments test the technology. This one tests whether anyone in your organisation can interpret what it flags and act with authority."
description = "A five-dimension self-assessment for executives accountable for enterprise AI. It tests the operating model around the technology, because that is where governance fails in practice."
date = 2026-06-14
readingTime = "8 min read"
draft = false
tags = ["AI governance", "operating models", "agentic AI", "diagnostic"]
topics = ["AI governance", "enterprise operating models"]
+++

Most AI governance assessments test the technology. This one tests the operating model around it, because that is where governance fails in practice. A technically sound architecture still fails if there is no one in the organisation able to interpret what it flags and act on it with authority.

Work through the five dimensions below. For each, answer honestly against your own organisation, not the policy document. The interpretation guide at the end tells you where the real exposure sits.

{{< diagram name="agentic-ai-readiness" caption="The five dimensions, and the three result bands. The score is the number of weak-signal answers. Two to three is the most dangerous range, because the architecture can pass audit while the diagnostic function quietly has no owner." >}}

## Dimension 1 — The two functions of oversight

The first failure is conceptual: treating all human oversight as one thing.

- When you say "human in the loop", can you separate decision approval (a person signs off a specific decision) from diagnostic judgement (a person interprets a system-level anomaly)? Or are both buried in one word?
- Are these two functions owned by the same people and the same process today?
- If a reviewer is approving hundreds of AI decisions a day, is their sign-off genuine judgement or a ceremonial stamp?

**Weak signal:** oversight is described as a single undifferentiated activity, and the same approval workflow is expected to catch both a threshold breach and a novel failure mode.

## Dimension 2 — The escalation destination

When monitoring surfaces something it cannot classify, the anomaly has to go somewhere.

- Name the role that receives an unclassifiable anomaly from your AI monitoring. Does it exist on the org chart, or are you naming a person you hope will pick it up?
- Does that role have the authority to commission an investigation and act on the result, or only to escalate further?
- When you trace the path, does it lead to the operational layer (close to the work, no diagnostic context) or the strategic layer (has context, no operational proximity)? Either alone is a dead end.

**Weak signal:** the honest answer is "it would get escalated to leadership" or "the platform team would look at it". Both mean the diagnostic function has no real owner.

## Dimension 3 — Diagnostic ownership

Diagnosis is not detection. Detecting that something is wrong and knowing what kind of wrong it is are different problems.

- For each consequential model in production, is there one named individual accountable for it from deployment to decommissioning? One person, not a committee, not a shared function?
- Does that person have the literacy to tell whether specialists are routing an anomaly correctly, for example distinguishing a data shift from an adversarial pattern, even if they do not perform the analysis themselves?
- Could they explain, to a regulator, why a consequential decision happened, not just what happened?

**Weak signal:** accountability for models is collective, rotating, or lives with whoever deployed the system. No named owner means no answerable entity when something goes wrong.

## Dimension 4 — The delayering exposure

The diagnostic function has a natural organisational home that many enterprises have spent a decade removing.

- Over the past ten years, has your organisation flattened hierarchy and reduced middle management on efficiency grounds?
- If so, what absorbed the contextual pattern-recognition work those roles used to do? Be specific. "The teams self-manage" is not an answer.
- Has anyone reconnected AI anomaly diagnosis to whatever remains of that layer, or is it assumed to happen by itself?

**Weak signal:** the middle layer was optimised away and nothing deliberate replaced its sense-making function. AI governance now needs a capacity the organisation actively dismantled.

## Dimension 5 — Reversibility and pre-deployment assurance

Some AI decisions cannot be undone for the person affected. The governance has to account for that before execution, not after.

- Do you classify decisions by reversibility, not only by consequence? A high-consequence decision that can be reversed and one that cannot are different governance objects.
- Where a decision is irreversible, does the system create a reversible intermediate state, for example placing a hold rather than executing a transfer, drafting a denial rather than issuing it?
- For genuinely irreversible decisions, do you rely on tight envelopes and staged, evidence-generating rollout, or on learning from failure after the fact? Learning after the fact is only safe when harm is recoverable.

**Weak signal:** the governance model assumes failures can be rolled back and corrected, with no separate treatment for decisions that cannot be undone.

## Reading your result

Count the dimensions where your honest answer landed on the weak signal.

**Zero to one.** You are in a small minority. The likely remaining work is calibration and documentation, not structural repair. The exposure is in proving the architecture to regulators, not in whether it functions.

**Two to three.** Your technical governance is probably ahead of your organisational capacity to run it. The architecture may pass audit while the diagnostic function quietly has no owner. This is the most common and most dangerous position, because it feels covered. The gap is invisible until an anomaly arrives with nowhere to go.

**Four to five.** The operating model cannot currently support the AI you are deploying or planning to deploy. Adding more engineering will not help. The work is structural: naming diagnostic ownership, restoring the layer that interprets anomalies, and treating reversibility as a design decision. This is an operating-model problem wearing a technology costume.

## What the diagnostic is really measuring

Across all five dimensions, the question underneath is the same. **Does your organisation still have a place for judgement exercised precisely where the rules run out?**

That capacity is not an AI feature. It is a property of the operating model, and it is the structural condition [The Kinetic Enterprise](https://kineticorganization.com) describes: organisations built for stable environments suppressed this layer by design, and environments defined by uncertainty and adversarial pressure require it back. AI governance is simply the first force that makes its absence expensive and visible.

---

**Evidence base.** The control architecture these dimensions assume is converging in the market: Forrester's AEGIS framework (2025) and Kyndryl's policy-as-code capability (2026). Deployment and maturity context: Gartner (2025) and Deloitte's *State of AI in the Enterprise, 2026*. What this diagnostic adds is the sociotechnical test those frameworks understate, whether the organisation retains the diagnostic capacity the architecture presupposes.

A structured walkthrough of these dimensions against your actual deployment, and what to repair first, is a standard advisory entry point. [Start a conversation](/contact/).
