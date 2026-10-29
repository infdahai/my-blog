---
citekey: "iwataRobustBrachiationLifeSizedDualArmWaypointGuided2026"
title: "Robust Brachiation on a Life-Sized Dual-Arm Robot Using Waypoint-Guided Reinforcement Learning"
authors: ["Ayumu Iwata", "Kento Kawaharazuka", "Keita Yoneda", "Takahiro Hattori", "Kei Okada"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2608.17320"
doi: "10.48550/arXiv.2608.17320"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-07
---

# Robust Brachiation on a Life-Sized Dual-Arm Robot Using Waypoint-Guided Reinforcement Learning

> Ayumu Iwata, Kento Kawaharazuka, Keita Yoneda, Takahiro Hattori, Kei Okada · 2026
> [arXiv](https://arxiv.org/abs/2608.17320) · [PDF](https://arxiv.org/pdf/2608.17320)

## Abstract

Brachiation is a form of locomotion in which primates move primarily using their arms, enabling traversal in environments without footholds. However, this motion requires highly coordinated whole-body movement and precise timing control for bar grasping and release. As a result, achieving robust behavior on life-sized robotic platforms remains challenging. In this study, we present a reinforcement learning-based method to realize brachiation on a life-sized dual-arm robot. The core of the proposed approach is Waypoint-Guided Reinforcement Learning (WGRL), a learning framework for inducing non-linear and complex motions. For high-difficulty tasks where imitation learning data are unavailable, WGRL guides behavior acquisition by sparsely specifying waypoints for the end-effector trajectory, while whole-body motion is generated through reinforcement learning. In addition, by integrating the waypoint-following guidance with rewards based on task success and mechanical energy, and training in an environment designed for Sim-to-Real transfer, the proposed method achieves both forward progression and motion stability. The acquired behavior is evaluated through Sim-to-Sim experiments under monkey-bar environments with geometric variations and hardware experiments, confirming robust brachiation including failure recovery behavior. This study provides effective learning design guidelines for realizing arm-based locomotion on life-sized robotic hardware and expanding the traversable workspace of robots.

## TL;DR

Brachiation is a form of locomotion in which primates move primarily using their arms, enabling traversal in environments without footholds. However, this motion requires highly coordinated whole-body movement and precise timing control for bar grasping and release.

## Related
<!-- [[other-paper-citekey]] -->
