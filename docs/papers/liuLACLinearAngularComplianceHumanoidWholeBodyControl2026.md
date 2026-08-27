---
citekey: "liuLACLinearAngularComplianceHumanoidWholeBodyControl2026"
title: "LAC: Linear and Angular Compliance for Humanoid Whole-body Control"
authors: ["Yang Liu", "Zhongkai Gu", "Wei Zhu", "Mitsuhiro Hayashibe"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2608.25405"
doi: "10.48550/arXiv.2608.25405"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-08-27
---

# LAC: Linear and Angular Compliance for Humanoid Whole-body Control

> Yang Liu, Zhongkai Gu, Wei Zhu, Mitsuhiro Hayashibe · 2026
> [arXiv](https://arxiv.org/abs/2608.25405) · [PDF](https://arxiv.org/pdf/2608.25405)

## Abstract

Real-world humanoid tasks involve physical interaction with objects and humans, yet current controllers either reject external forces as disturbances or restrict compliance to limited body links while ignoring angular effects. We present LAC, a general whole-body controller that simultaneously realizes commanded Linear and Angular Compliance for wrenches applied to the upper body. First, we synthesize whole-body compliant responses into a large-scale augmented dataset. Sampled force and couple events are imposed on contact frames extracted from human interaction data. At each contact link, the external force and a virtual torque from the passively yielding kinematic chain drive a virtual admittance under the commanded stiffness. Subsequently, teacher-student reinforcement learning trains a single policy to track the compliant motions under external wrenches. Finally, extensive simulation and real-world experiments demonstrate whole-body compliant responses to wrenches across the upper body, monotonic modulation over the full range of both stiffness commands, and applicability to teleoperated loco-manipulation tasks. Project website: https://lac-humanoid.github.io/

## TL;DR

Real-world humanoid tasks involve physical interaction with objects and humans, yet current controllers either reject external forces as disturbances or restrict compliance to limited body links while ignoring angular effects. We present LAC, a general whole-body controller that simultaneously realizes commanded Linear and Angular Compliance for wrenches applied to the upper body.

## Related
<!-- [[other-paper-citekey]] -->
