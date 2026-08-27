---
citekey: "tangVideo2DoorTraversalPushDoorTraversalSimulatedDoorTwins2026"
title: "Video2DoorTraversal: Push Door Traversal via Simulated Door Twins"
authors: ["Xincheng Tang", "Yiji Chen", "Youhan Xie", "Wanyu Li", "Zhengjie Shu", "Lai Jiang", "Wenkang Hu", "Yitong Li", "Jinchuang Zhang", "Xibin Song", "Ruigang Yang"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2608.20251"
doi: "10.48550/arXiv.2608.20251"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-08-27
---

# Video2DoorTraversal: Push Door Traversal via Simulated Door Twins

> Xincheng Tang, Yiji Chen, Youhan Xie, Wanyu Li, Zhengjie Shu, Lai Jiang, Wenkang Hu, Yitong Li, Jinchuang Zhang, Xibin Song, Ruigang Yang · 2026
> [arXiv](https://arxiv.org/abs/2608.20251) · [PDF](https://arxiv.org/pdf/2608.20251)

## Abstract

Door opening and traversal is a long-horizon loco-manipulation task that requires precise handle interaction and coordinated base-arm control. We present Video2DoorTraversal, a single-video real-to-sim-to-real framework for wheel-legged mobile manipulators. Given one RGB video of a real door, DoorTwin reconstructs an instance-aligned, articulated, and simulation-ready door twin with realistic geometry and appearance. A simulation-in-the-loop agent converts the recovered articulation into a parameterized skill program and iteratively refines failed rollouts to generate physically executable demonstrations. These demonstrations are used to train ArticuACT, a dual-depth policy that predicts coordinated base, arm, and gripper commands using robot-centric camera conditioning and interaction-aware supervision. With all perception and policy inference running onboard, the system achieves a 96.57% average success rate across five real doors and an 80.95% zero-shot success rate on structurally similar unseen doors, while completing the full approach, opening, and traversal sequence in approximately 13s on average. Project Page: https://video2doortraversal.github.io/.

## TL;DR

Door opening and traversal is a long-horizon loco-manipulation task that requires precise handle interaction and coordinated base-arm control. We present Video2DoorTraversal, a single-video real-to-sim-to-real framework for wheel-legged mobile manipulators.

## Related
<!-- [[other-paper-citekey]] -->
