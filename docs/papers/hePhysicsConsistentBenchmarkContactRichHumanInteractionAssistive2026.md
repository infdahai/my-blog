---
citekey: "hePhysicsConsistentBenchmarkContactRichHumanInteractionAssistive2026"
title: "A Physics-Consistent Benchmark for Contact-Rich Human-Robot Interaction in Assistive Care"
authors: ["Chengxiao He", "Shanghai Yuan", "Liuqun Fan", "Shenzhen Zhu"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.02402"
doi: "10.48550/arXiv.2609.02402"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-04
---

# A Physics-Consistent Benchmark for Contact-Rich Human-Robot Interaction in Assistive Care

> Chengxiao He, Shanghai Yuan, Liuqun Fan, Shenzhen Zhu · 2026
> [arXiv](https://arxiv.org/abs/2609.02402) · [PDF](https://arxiv.org/pdf/2609.02402)

## Abstract

Conventional task-level evaluation asks whether a robot policy completes a specified action, but can miss failures that emerge only during physical human contact. This limitation is critical in contact-rich assistive tasks, where meaningful evaluation requires a physically responsive human, interaction-quality assessment beyond task success, and a leak-free observer-scorer protocol. We introduce a physics-consistent benchmark for contact-rich human-robot interaction, instantiated in robot-assisted bathing. The benchmark combines a deformable, passively responding human, physics-aware scores alongside task-level success, and a frozen vision-only / scorer-only evaluation protocol. To establish physical validity, region-wise simulated responses are calibrated against force-indentation measurements from Franka impedance pushes on a medical-care manikin. Under a frozen T1-T7 protocol with 140 runs per method, an LLM-augmented state machine (State Machine) achieves 72.9% task success but drops to 56.4% after correct-region and force-safety screening; VoxPoser produces lighter and more stable contact but completes only 27.9% of trials; and zero-shot pi0.5 achieves 0.7% task success with no correct-region or safety-gated successes. These results show that task completion alone does not imply physically valid contact and motivate physics-aware screening before deployment of contact-rich assistive robot policies.

## TL;DR

Conventional task-level evaluation asks whether a robot policy completes a specified action, but can miss failures that emerge only during physical human contact. This limitation is critical in contact-rich assistive tasks, where meaningful evaluation requires a physically responsive human, interaction-quality assessment beyond task success, and a leak-free observer-scorer protocol.

## Related
<!-- [[other-paper-citekey]] -->
