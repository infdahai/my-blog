---
citekey: "gudaComplianceFreeLearningIdentifiableImpedanceBilateralTeleoperation2026"
title: "Compliance for Free: Learning Identifiable Impedance via Bilateral Teleoperation"
authors: ["Harsha Guda", "Adrià Colomé", "Carme Torras"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.19976"
doi: "10.48550/arXiv.2609.19976"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-18
---

# Compliance for Free: Learning Identifiable Impedance via Bilateral Teleoperation

> Harsha Guda, Adrià Colomé, Carme Torras · 2026
> [arXiv](https://arxiv.org/abs/2609.19976) · [PDF](https://arxiv.org/pdf/2609.19976)

## Abstract

Vision-language-action models tell a robot where to move, but not how hard to push. Contact-rich tasks depend on that second quantity, compliance, yet no widely used demonstration interface records it. The obstacle is identifiability as realized pose and measured force cannot separate the operator's intended equilibrium from their stiffness, so VR controllers, SpaceMouse and handheld grippers cannot supply compliance supervision even in principle. Prior compliance-output policies work around this with hand-specified task structure, privileged simulation contact state, or dedicated force and tactile hardware. Four-channel bilateral teleoperation removes the ambiguity directly by using the leader arm as a separate measurement of the intended equilibrium, making per-axis stiffness identifiable by regression using only the joint-torque sensing already on the manipulator. This yields per-timestep, direction-dependent compliance labels at zero annotation cost, which we use to fine-tune a VLA to emit stiffness alongside pose. On a Franka Research 3 wiping task, ours is the only policy of five whose contact force changes when the instruction asks for a firm wipe rather than a normal one (6.4N (normal) to 9.1N (firm) RMS, Cohen's d = 0.89, p = 0.023

## TL;DR

Vision-language-action models tell a robot where to move, but not how hard to push. Contact-rich tasks depend on that second quantity, compliance, yet no widely used demonstration interface records it.

## Related
<!-- [[other-paper-citekey]] -->
