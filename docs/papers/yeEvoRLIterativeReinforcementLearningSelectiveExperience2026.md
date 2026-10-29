---
citekey: "yeEvoRLIterativeReinforcementLearningSelectiveExperience2026"
title: "Evo-RL: Iterative Robot Reinforcement Learning from Selective Experience"
authors: ["Kai Ye", "Yifan Jin", "Qianhang Luo", "Hongru Zhang", "Jiedong Zhang", "Shuyuan Hu", "Song-Yuan Wu", "Jihai Xu", "Jie Zhao", "Bo Zhao"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.13345"
doi: "10.48550/arXiv.2610.13345"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-13
---

# Evo-RL: Iterative Robot Reinforcement Learning from Selective Experience

> Kai Ye, Yifan Jin, Qianhang Luo, Hongru Zhang, Jiedong Zhang, Shuyuan Hu, Song-Yuan Wu, Jihai Xu, Jie Zhao, Bo Zhao · 2026
> [arXiv](https://arxiv.org/abs/2610.13345) · [PDF](https://arxiv.org/pdf/2610.13345)

## Abstract

Existing real-world reinforcement learning methods improve robot policies by combining human corrections with autonomous rollouts. However, accumulated experience varies in its value for policy improvement, and even successful trajectories can contain inefficient or redundant behavior, motivating more selective experience reuse. To this end, we propose Evo-RL, an iterative reinforcement learning method that combines human interventions with advantage-guided experience selection. Evo-RL uses human corrections and experience with positive estimated advantages from successful trajectories to iteratively refine the policy. To support learning from these different experience sources, we introduce RW-RL-Dataset, which spans over 1,000 hours across four robot embodiments. On a real-world high-precision manipulation task, Evo-RL improves attempt success rate over RECAP by 30.46\%. Our code, model checkpoints, and dataset are publicly available.

## TL;DR

Existing real-world reinforcement learning methods improve robot policies by combining human corrections with autonomous rollouts. However, accumulated experience varies in its value for policy improvement, and even successful trajectories can contain inefficient or redundant behavior, motivating more selective experience reuse.

## Related
<!-- [[other-paper-citekey]] -->
