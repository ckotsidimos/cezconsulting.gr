+++
title = "Decision Latency"
summary = "The elapsed time between intent and coordinated action across an organisation. The interval in which a decision waits, rather than the time it takes to do the work."
description = "The time between intent and coordinated action, and why it is the constraint technology investment keeps failing to touch."
date = 2026-06-14
featured = false
readingTime = "5 min read"
draft = false
diagram = "decision-latency"
diagramCaption = "Latency is the interval the decision waits, not the time the work takes. The work is ready in days; the decision keeps travelling through queues, reviews, committees and change windows."

definition = "Decision latency is the elapsed time between intent and coordinated action across an organisation. It measures the interval in which a decision waits, in queues, approvals, and committees, rather than the time it takes to do the work itself. In most large organisations it is the dominant constraint on execution, and it is a property of the operating model, not of the people inside it."

whyItMatters = "Every technology investment accelerates how fast work can be done. Almost none of them touch how fast the organisation can decide. As operating tempo rises, the distance between the two becomes the binding constraint, and the return on the technology is absorbed by the latency around it. This is why capable systems so often produce disappointing results: the bottleneck has moved from execution to decision, and the investment addressed the wrong one."

operationalImplications = [
  "Measure the interval between intent and action, not just delivery velocity. Latency hides in the gaps between teams, not inside them.",
  "Treat approval chains as a cost, not a safety measure. Each layer adds latency that is paid on every decision cycle, indefinitely.",
  "Move decision rights to where the information already sits, with clear ownership of the consequence, rather than escalating to a committee that is structurally too far from the work to judge it in time.",
  "Replace point-in-time approval with assurance that runs at the system's tempo. Anything slower controls the organisation's speed, not its risk.",
  "Expect latency to surface as a cultural complaint, that the organisation is too slow or that nothing gets decided, long before it is recognised as structural."
]

[[relatedEssays]]
title = "The Production Gap"
href = "/essays/the-production-gap/"
+++

Most executives have felt this without naming it. A decision that should take a week takes a quarter. Not because anyone is idle, but because the decision has to travel: up to a committee, across to risk, back for clarification, out to a board. The work was ready in days. The decision was not.

That interval is decision latency, and it is structural. It is built into the approval chains, governance layers, and coordination mechanisms that large organisations construct to manage risk and hold control. At low operating tempo the latency is tolerable, often invisible. Under sustained speed it becomes the dominant constraint, because the environment now moves faster than the decision can.

The cause is an inherited assumption. Industrial operating models centralise authority on the belief that the best information and the best judgment sit at the centre. In stable conditions that holds. Under speed it inverts. The team closest to the work has better information than the committee reviewing it, and by the time a decision has travelled up the hierarchy and back down, the context that justified it has changed. The approval is always slightly behind the problem it was meant to govern.

I watched this play out on a delivery at a global bank. We had built an import process for container data, and the code was finished and working. The delay had nothing to do with the engineering. Governance arrived after the build was complete rather than alongside it, and added roughly a month while finished work sat waiting for review. Then, even once it was approved, deployment had to wait for an open change window. Two separate latencies, neither of them technical, stacked on top of a system that had been ready for weeks. The work was never the constraint. The decision architecture around it was.

This is why technology so often disappoints. Investment raises how fast work can be done. It rarely touches how fast the organisation can decide. Throughput improves, latency does not move, and the return is absorbed by the friction around the system rather than released by the system itself.

The full account of decision latency as a governing variable, alongside the limits of industrial operating models and the conditions for structural coherence under speed, is set out in [The Kinetic Enterprise](https://kineticorganization.com). This page is the applied view: what latency looks like inside a specific organisation, and what reducing it actually requires.

Reducing it is not a matter of working faster or injecting urgency. It is structural. It means moving decision rights to where the information already sits, with clear ownership of the consequence, and replacing point-in-time approval with assurance that runs at the same tempo as the system it governs. CEZ Consulting works with executives to locate where latency is concentrated in their operating model, and to redesign the decision architecture around it.
