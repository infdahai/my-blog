---
citekey: "leeMATEBTBehaviorTreeBasedFrameworkHierarchicallyDecentralized2026"
title: "MATE-BT: A Behavior-Tree-Based Framework for Hierarchically Decentralized Mission Autonomy in Heterogeneous Multi-Robot Teams"
authors: ["Sunbeen Lee", "Hoseon Gi", "Jik Hur", "Inmo Jang"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.35429"
doi: "10.48550/arXiv.2610.35429"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-28
---

# MATE-BT: A Behavior-Tree-Based Framework for Hierarchically Decentralized Mission Autonomy in Heterogeneous Multi-Robot Teams

> Sunbeen Lee, Hoseon Gi, Jik Hur, Inmo Jang · 2026
> [arXiv](https://arxiv.org/abs/2610.35429) · [PDF](https://arxiv.org/pdf/2610.35429)

## Abstract

Multi-robot teams executing predefined missions must adapt to runtime changes and sustain mission management despite robot failures. This paper proposes MATE-BT (Mission, Allocation, and Task Execution with Behavior Trees), a hierarchically decentralized framework that separates mission execution, allocation, and task execution. An active onboard leader manages mission progression and team-level task assignment, with authority transferable to another leader-capable robot after failure. Interchangeable decentralized methods resolve target assignments, while each robot adapts its local behavior through planning and acting with behavior trees. Webots simulations and real-robot experiments demonstrate mission continuity despite new targets and robot failures, including active-leader failure. In the physical experiments, all MATE-BT computation runs onboard. Hardware-in-the-loop resource measurements further support onboard execution on Jetson Orin Nano and Raspberry Pi 5. By updating only the affected layers without full-plan regeneration, MATE-BT maintained a response time of approximately 130 ms with 30 robots and 120 targets. Comparisons of four target-assignment plugins reveal scenario-dependent trade-offs between mission completion time and total travel distance.

## TL;DR

Multi-robot teams executing predefined missions must adapt to runtime changes and sustain mission management despite robot failures. This paper proposes MATE-BT (Mission, Allocation, and Task Execution with Behavior Trees), a hierarchically decentralized framework that separates mission execution, allocation, and task execution.

## Related
<!-- [[other-paper-citekey]] -->
