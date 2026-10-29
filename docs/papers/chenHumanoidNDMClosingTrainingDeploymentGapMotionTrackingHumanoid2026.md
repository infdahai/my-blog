---
citekey: "chenHumanoidNDMClosingTrainingDeploymentGapMotionTrackingHumanoid2026"
title: "HumanoidNDM: Closing the Training-Deployment Gap of Motion Tracking via Humanoid Neural Dynamics Model"
authors: ["Chao Chen", "Zhenrong Wang", "Jilong Wang", "Yusen Feng", "Jiangran Lyu", "Li Yi", "He Wang"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.34126"
doi: "10.48550/arXiv.2610.34126"
tags: [paper, embodied-ai, "cs.AI", "cs.LG", "cs.RO"]
status: unread
rating:
created: 2026-10-28
---

# HumanoidNDM: Closing the Training-Deployment Gap of Motion Tracking via Humanoid Neural Dynamics Model

> Chao Chen, Zhenrong Wang, Jilong Wang, Yusen Feng, Jiangran Lyu, Li Yi, He Wang · 2026
> [arXiv](https://arxiv.org/abs/2610.34126) · [PDF](https://arxiv.org/pdf/2610.34126)

## Abstract

Humanoid robots have recently achieved remarkable success in motion tracking. However, during real-world deployment, robots inevitably encounter dynamics gaps arising from either extra physical disturbances or inaccurate simulation modeling, resulting in a significant training-deployment gap. Therefore, effectively leveraging real-world data to fine-tune policies represents the crucial last mile for robust deployment. To bridge this gap, we propose HumanoidNDM, an online fine-tuning framework for humanoid motion tracking driven by a real-world-trained neural dynamics model. First, in the data collection stage, we introduce a low-frequency reference perturbation method with an adaptive intensity mechanism, balancing deployment feasibility and exploration efficiency. Second, for the model training stage, we train a robust history-based, proprioceptive neural dynamics model in Euclidean space by incorporating differentiable forward kinematics, eliminating the reliance on costly motion capture systems. Finally, in the policy fine-tuning stage, we directly fine-tune the policy via backpropagated model gradients, achieving high data efficiency. Through physical validation on the Unitree G1 robot, we demonstrate that HumanoidNDM enables rapid real-world adaptation to various perturbations, representing the first online, MoCap-free fine-tuning framework for humanoid tracking policies.

## TL;DR

Humanoid robots have recently achieved remarkable success in motion tracking. However, during real-world deployment, robots inevitably encounter dynamics gaps arising from either extra physical disturbances or inaccurate simulation modeling, resulting in a significant training-deployment gap.

## Related
<!-- [[other-paper-citekey]] -->
