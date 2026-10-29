---
citekey: "yangDexTaGTactileGuidanceReinforcementLearningDexterousManipulation2026"
title: "DexTaG: Tactile-as-Guidance in Reinforcement Learning for Dexterous Manipulation"
authors: ["Han Yang", "Yian Wang", "Yunlong Song", "Zhenjia Xu", "Chuang Gan"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.33882"
doi: "10.48550/arXiv.2609.33882"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-30
---

# DexTaG: Tactile-as-Guidance in Reinforcement Learning for Dexterous Manipulation

> Han Yang, Yian Wang, Yunlong Song, Zhenjia Xu, Chuang Gan · 2026
> [arXiv](https://arxiv.org/abs/2609.33882) · [PDF](https://arxiv.org/pdf/2609.33882)

## Abstract

Glove-based motion capture is emerging as a scalable approach to collecting dexterous-hand demonstration data. However, due to the kinematic gap between the human and robot hand, the recorded human motions cannot be executed directly on the robot, especially for contact-rich tool-use tasks involving in-hand reorientation. Prior work bridges this gap in simulation through reinforcement learning (RL) or trajectory optimization, but the human contact pattern is hard to preserve under such formulations, often producing unnatural manipulation and unstable functional grasps. These methods also train a separate policy or solve a separate optimization for each reference trajectory, which is inefficient. To solve these problems, we propose DexTaG, a tactile-guided RL framework for dexterous manipulation. During training, tactile signals captured by the glove guide policy search toward the measured human contact pattern, reducing reliance on precise reference geometry for contact supervision. To improve efficiency, we train a single generalizable retargeter jointly on all training trajectories of the same object. The retargeter is further distilled into a tactile-free student controller conditioned on the target object trajectory for real-world deployment. On marker-pen and hammer manipulation tasks, DexTaG learns natural, contact-rich behaviors that baselines with distance-based contact heuristics fail to learn, generalizes to held-out trajectories of the same object and task, and outperforms single-trajectory baselines on OakInk2.

## TL;DR

Glove-based motion capture is emerging as a scalable approach to collecting dexterous-hand demonstration data. However, due to the kinematic gap between the human and robot hand, the recorded human motions cannot be executed directly on the robot, especially for contact-rich tool-use tasks involving in-hand reorientation.

## Related
<!-- [[other-paper-citekey]] -->
