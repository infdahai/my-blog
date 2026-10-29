---
citekey: "rayyanFetchManLearningVisualHumanoidLocoManipulationPoliciesSimulated2026"
title: "FetchMan: Learning Visual Humanoid Loco-Manipulation Policies from Simulated Experiences"
authors: ["Omar Rayyan", "Zhi Li", "Max Argus", "Yuxin Jiang", "Chang Yu", "Chenfanfu Jiang", "Yuchen Cui"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2608.17027"
doi: "10.48550/arXiv.2608.17027"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-07
---

# FetchMan: Learning Visual Humanoid Loco-Manipulation Policies from Simulated Experiences

> Omar Rayyan, Zhi Li, Max Argus, Yuxin Jiang, Chang Yu, Chenfanfu Jiang, Yuchen Cui · 2026
> [arXiv](https://arxiv.org/abs/2608.17027) · [PDF](https://arxiv.org/pdf/2608.17027)

## Abstract

Visual loco-manipulation policies that can generalize to novel scenes and objects have long been a goal of robotics research. However, today's data-hungry algorithms make collecting sufficient demonstrations a struggle for tabletop manipulation, and even more so for humanoids that must also walk and balance. Learning from simulated data and transferring that behavior to the real world, as is commonly done in locomotion, sidesteps this struggle, so we replicate that recipe for loco-manipulation. In doing so, we find that cloning synthetic demonstrations results in a low performance ceiling no matter the amount of training data. Reinforcement learning breaks through it, and refining the cloned policy with Flow-GRPO on a single sparse reward yields performance that synthetic behavior cloning cannot match. Together, these stages form our end-to-end sim-to-real pipeline spanning more than 150,000 scenes, which we use to train FetchMan. We evaluate it on FetchMan-Bench, a simulation benchmark we release, and deploy it zero-shot on a real Unitree G1, where our single-object reach-and-pick policy walks to and grasps a target across unseen scenes at 73.3% success. Finally, we extend this recipe to multi-object training, a first step toward loco-manipulation generalist policies at this data scale.

## TL;DR

Visual loco-manipulation policies that can generalize to novel scenes and objects have long been a goal of robotics research. However, today's data-hungry algorithms make collecting sufficient demonstrations a struggle for tabletop manipulation, and even more so for humanoids that must also walk and balance.

## Related
<!-- [[other-paper-citekey]] -->
