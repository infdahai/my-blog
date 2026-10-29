---
citekey: "singhContinualFieldAdaptiveModelsCFAMsPostDeploymentPhysical2026"
title: "Continual Field-Adaptive Models (CFAMs) for Post-Deployment Physical AI"
authors: ["Amarjot Singh", "Tanmay R. Pancholi", "Jainam Kothari", "Shrirang Mahajan", "Ketan Bansal", "Zackory Erickson", "Giuseppe Loianno", "Alexandre M. Bayen", "Jeff Schneider", "Vince Nakayama"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.04552"
doi: "10.48550/arXiv.2609.04552"
tags: [paper, embodied-ai, "cs.AI", "cs.RO"]
status: unread
rating:
created: 2026-09-07
---

# Continual Field-Adaptive Models (CFAMs) for Post-Deployment Physical AI

> Amarjot Singh, Tanmay R. Pancholi, Jainam Kothari, Shrirang Mahajan, Ketan Bansal, Zackory Erickson, Giuseppe Loianno, Alexandre M. Bayen, Jeff Schneider, Vince Nakayama · 2026
> [arXiv](https://arxiv.org/abs/2609.04552) · [PDF](https://arxiv.org/pdf/2609.04552)

## Abstract

Unattended interactive autonomy - machines that step into danger in place of humans and complete tasks with human tools - remains a missing capability in mission-critical operations. These domains offer scarce training data and only onboard compute, yet deployed systems must face novelty without erasing prior competence. We introduce Continual Field-Adaptive Models (CFAMs), which learn efficiently in the lab and continue learning after deployment through autonomous, gradient-free, on-device updates. CFAM uses a complementary learning architecture with a frozen slow-learning component and a fast-learning Capsule Field. The slow component contains three cortices: Sensor, which maps multimodal input into 3D-grounded geometry; Reasoning, which decomposes tasks into skills and evaluates outcomes; and Action, which executes geometric skills. The Capsule Field stores field learning one-shot and gradient-free as Competence Capsules. Skill installation is few-shot in the lab and continual in the field; open-world novelty is outside scope. We evaluate CFAM across five embodiments: manipulator, quadruped, humanoid, quadrotor, and off-road vehicle. Baselines (pi0, CogACT, SpatialVLA) use the same in-house multi-embodiment dataset for physical-platform comparisons. CFAM reaches the operating point of a standard policy trained on the full prior-training dataset using 40% of the data, or 2.5x fewer trajectories. At test time, autonomous capture of verified near-OOD cases improves action success by 13.9 percentage points. In sequential simulation, backward transfer is -0.5 percentage points versus -11.4 for LoRA. CFAM therefore provides a bounded form of post-deployment physical intelligence: few-shot skill learning, autonomous field growth from verified near-OOD experience, and retention of prior competence.

## TL;DR

Unattended interactive autonomy - machines that step into danger in place of humans and complete tasks with human tools - remains a missing capability in mission-critical operations. These domains offer scarce training data and only onboard compute, yet deployed systems must face novelty without erasing prior competence.

## Related
<!-- [[other-paper-citekey]] -->
