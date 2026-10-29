---
citekey: "mustafaNonPrehensileThrowingReinforcementLearningPerspective2026"
title: "Non-Prehensile Throwing: A Reinforcement Learning Perspective"
authors: ["Abdullah Mustafa", "Ryo Hanai", "Ixchel G. Ramirez-Alpizar", "Floris Erich", "Ryoichi Nakajo", "Yukiyasu Domae", "Tetsuya Ogata"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.00771"
doi: "10.48550/arXiv.2609.00771"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-07
---

# Non-Prehensile Throwing: A Reinforcement Learning Perspective

> Abdullah Mustafa, Ryo Hanai, Ixchel G. Ramirez-Alpizar, Floris Erich, Ryoichi Nakajo, Yukiyasu Domae, Tetsuya Ogata · 2026
> [arXiv](https://arxiv.org/abs/2609.00771) · [PDF](https://arxiv.org/pdf/2609.00771)

## Abstract

Robotic throwing enables fast object transport and extends a robot's reachable workspace beyond traditional pick-and-place. While prehensile (grasp-based) throwing works well for graspable items, non-prehensile (grasp-free) throwing is better suited for large, heavy, and/or deformable objects. Existing approaches rely on model-based optimization with simplified contact models (e.g., dynamic grasping) and low-dimensional trajectory parameterizations, which limit solution quality and reachable workspace. We propose a reinforcement learning approach that additionally leverages sliding and rolling contact modes and directly optimizes joint-space trajectories without analytical contact models or custom parameterizations. The Markov Decision Process (MDP) is formulated as a dynamical system that evolves the robot's joint state conditioned on the throwing target, object model, and initial configuration. Joint-jerk trajectories are planned offline at a low control rate and upsampled into smooth, high-rate velocity commands for deployment. For sim-to-real transfer, we minimize the robot-dynamics gap through minimum-jerk system identification and train uncertainty-aware policies to mitigate object-modeling errors, particularly sensitivity to dynamic friction. In simulation, the policy achieves 99% success across thousands of configurations and generalizes to unseen objects. Sensitivity analysis shows robustness to mass uncertainty but high sensitivity to dynamic friction, consistent with the sliding-based release mechanism. Deployed zero-shot on a UR5e operating near its physical limits (5 m/s end-effector velocity), our method throws diverse objects including heavy (790 g) and large (20x20x28 cm) items to targets up to 350 cm distance or 180 cm elevation, achieving a 97% real-world success rate.

## TL;DR

Robotic throwing enables fast object transport and extends a robot's reachable workspace beyond traditional pick-and-place. While prehensile (grasp-based) throwing works well for graspable items, non-prehensile (grasp-free) throwing is better suited for large, heavy, and/or deformable objects.

## Related
<!-- [[other-paper-citekey]] -->
