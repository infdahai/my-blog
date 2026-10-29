---
citekey: "taoExtendingSpeedLimitQuadrupedalLocomotionRefinedActuatorModeling2026"
title: "Extending the Speed Limit of Quadrupedal Locomotion via Refined Actuator Modeling and Adaptive Command Scheduling"
authors: ["Yucheng Tao", "Shaowen Cheng", "Guorong Lan", "Yanyan Yuan", "Yongbin Jin", "Hongtao Wang"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.13289"
doi: "10.48550/arXiv.2609.13289"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-16
---

# Extending the Speed Limit of Quadrupedal Locomotion via Refined Actuator Modeling and Adaptive Command Scheduling

> Yucheng Tao, Shaowen Cheng, Guorong Lan, Yanyan Yuan, Yongbin Jin, Hongtao Wang · 2026
> [arXiv](https://arxiv.org/abs/2609.13289) · [PDF](https://arxiv.org/pdf/2609.13289)

## Abstract

Achieving high-speed locomotion in quadrupedal robots remains highly challenging, as actuators operate near their physical limits and exhibit pronounced nonlinearities. However, many existing methods neglect actuator nonlinearities and physical constraints during training, leading to a significant sim-to-real gap under highly dynamic motions and limiting achievable performance. To address this issue, we propose a high-speed locomotion framework that reduces sim-to-real discrepancies and stabilizes learning over a wide command distribution. A refined actuator model explicitly captures high-speed voltage coupling and magnetic saturation, enabling a more accurate representation of the torque-speed envelope. In addition, a reinforcement learning framework incorporating a two-stage curriculum and adaptive command scheduling (ACS) ensures stable training. Experiments on the 36.5 kg quadruped BlackPanther2 (BP2) demonstrate speeds of up to 13.2 m/s on a treadmill and 11.65 m/s outdoors, establishing a new state-of-the-art and, to the best of our knowledge, a world record for quadrupedal robot locomotion. The results further highlight the importance of accurate actuator modeling in preventing non-physical policy exploitation, and show that ACS improves robustness without sacrificing performance.

## TL;DR

Achieving high-speed locomotion in quadrupedal robots remains highly challenging, as actuators operate near their physical limits and exhibit pronounced nonlinearities. However, many existing methods neglect actuator nonlinearities and physical constraints during training, leading to a significant sim-to-real gap under highly dynamic motions and limiting achievable performance.

## Related
<!-- [[other-paper-citekey]] -->
