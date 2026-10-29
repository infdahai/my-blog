---
citekey: "fanE2DRLEndEndDifferentiableReinforcementLearning3DObstacle2026"
title: "E2DRL: End-to-End Differentiable Reinforcement Learning for 3D Obstacle Avoidance in Quadruped Robots"
authors: ["Cheng Fan", "Bingyang Zhou", "Gang Yang", "Zixuan Zhuang", "Aoqian Zhang", "Pengzhi Yang", "Xin Liu", "Chunzheng Wang", "Yan Rui Tan", "Fan Shi"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.19627"
doi: "10.48550/arXiv.2610.19627"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-16
---

# E2DRL: End-to-End Differentiable Reinforcement Learning for 3D Obstacle Avoidance in Quadruped Robots

> Cheng Fan, Bingyang Zhou, Gang Yang, Zixuan Zhuang, Aoqian Zhang, Pengzhi Yang, Xin Liu, Chunzheng Wang, Yan Rui Tan, Fan Shi · 2026
> [arXiv](https://arxiv.org/abs/2610.19627) · [PDF](https://arxiv.org/pdf/2610.19627)

## Abstract

Differentiable reinforcement learning shows strong promise for robot policy learning, but its application to legged locomotion has remained limited to blind walking or simulated 2D tasks. Extending it to end-to-end visual obstacle avoidance is challenging because hard collision constraints and early termination upon contact corrupt first-order gradients, trapping optimizers in local minima. We present E2DRL, which addresses this with a soft differentiable obstacle-interaction formulation: penetration penalties across multiple body keypoints with velocity-conditioned stop-gradient shaping to provide the first-order training signals for 3D obstacle avoidance. To realize a deployable perception-control system, a privileged teacher trained via Soft Analytic Policy Optimization (SAPO) in a differentiable simulator is distilled into a recurrent depth-based student via DAgger, then blended with a base locomotion policy using a terrain-aware gating module for deployment. In simulation, E2DRL achieves higher sample efficiency than PPO and demonstrates superior velocity-tracking performance and 3D obstacle-avoidance capability compared with both PPO and Duality-based DCBF NMPC. We present the first sim-to-real validation of end-to-end differentiable RL for 3D obstacle avoidance on a Unitree Go2 in static and dynamic environments.

## TL;DR

Differentiable reinforcement learning shows strong promise for robot policy learning, but its application to legged locomotion has remained limited to blind walking or simulated 2D tasks. Extending it to end-to-end visual obstacle avoidance is challenging because hard collision constraints and early termination upon contact corrupt first-order gradients, trapping optimizers in local minima.

## Related
<!-- [[other-paper-citekey]] -->
