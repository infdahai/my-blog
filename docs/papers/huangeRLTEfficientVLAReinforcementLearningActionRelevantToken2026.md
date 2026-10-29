---
citekey: "huangeRLTEfficientVLAReinforcementLearningActionRelevantToken2026"
title: "eRLT: Efficient VLA Reinforcement Learning via Action-Relevant Token Routing"
authors: ["Dehao Huang", "Jianbang Liu", "Jianpan Gao", "Chao Tang", "Zilang Cen", "Zedong Dan", "Jiaheng Wang", "Tingguang Li", "Yue Wang", "Hong Zhang"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.00913"
doi: "10.48550/arXiv.2610.00913"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-03
---

# eRLT: Efficient VLA Reinforcement Learning via Action-Relevant Token Routing

> Dehao Huang, Jianbang Liu, Jianpan Gao, Chao Tang, Zilang Cen, Zedong Dan, Jiaheng Wang, Tingguang Li, Yue Wang, Hong Zhang · 2026
> [arXiv](https://arxiv.org/abs/2610.00913) · [PDF](https://arxiv.org/pdf/2610.00913)

## Abstract

Vision-Language-Action (VLA) models provide strong behavioral priors for robotic manipulation, yet efficiently adapting them to downstream tasks remains challenging. Recent work addresses this challenge by adapting frozen VLAs through online reinforcement learning (RL), whose sample efficiency depends on the quality of the state representation used by the actor and critic. Existing methods construct such representations either with VLA-independent visual encoders or through fixed compression of internal VLA representations. Neither design explicitly extracts the task-specific action-relevant VLA features most useful for downstream action refinement and action-value estimation, therefore limiting sample efficiency. To address this limitation, we introduce eRLT, which constructs an effective state representation by routing task-specific action-relevant information across both tokens and layers of the frozen VLA. Specifically, learned routing tokens dynamically aggregate visual-language features at multiple depths, while a lightweight layer router combines these summaries into a fixed-dimensional RL token. The routing module is initialized using expert demonstrations to capture features predictive of expert actions and then refined using critic feedback from online interactions for action-value estimation. Across seven LIBERO and RoboTwin tasks, eRLT improves mean normalized learning-curve AUC by up to 23.7% over representative baselines. Real-robot experiments on USB connector insertion and motherboard ribbon-cable insertion further show AUC improvements of 108.9% and 46.7%, respectively, over the strongest baseline.

## TL;DR

Vision-Language-Action (VLA) models provide strong behavioral priors for robotic manipulation, yet efficiently adapting them to downstream tasks remains challenging. Recent work addresses this challenge by adapting frozen VLAs through online reinforcement learning (RL), whose sample efficiency depends on the quality of the state representation used by the actor and critic.

## Related
<!-- [[other-paper-citekey]] -->
