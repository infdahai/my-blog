---
citekey: "wangEmbodiedMindAdaptiveDataCurationPrefixTreeReinforcementLearning2026"
title: "EmbodiedMind: Adaptive Data Curation and Prefix-Tree Reinforcement Learning for Efficient Embodied Intelligence"
authors: ["Feifan Wang", "Zongbing Zhang", "Yu Zhang", "Lingfeng Wang", "Yurui Zhu", "Jin Deng", "Mingliang Zhang", "Zhengguang Gao", "Yongcheng Wang", "Jin Xu", "Ri Yang"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.19659"
doi: "10.48550/arXiv.2609.19659"
tags: [paper, embodied-ai, "cs.LG", "cs.RO"]
status: unread
rating:
created: 2026-09-18
---

# EmbodiedMind: Adaptive Data Curation and Prefix-Tree Reinforcement Learning for Efficient Embodied Intelligence

> Feifan Wang, Zongbing Zhang, Yu Zhang, Lingfeng Wang, Yurui Zhu, Jin Deng, Mingliang Zhang, Zhengguang Gao, Yongcheng Wang, Jin Xu, Ri Yang · 2026
> [arXiv](https://arxiv.org/abs/2609.19659) · [PDF](https://arxiv.org/pdf/2609.19659)

## Abstract

Training embodied foundation models typically requires massive-scale datasets and extensive computational resources, yet often suffers from three critical limitations: (1) inefficient sample utilization due to low-informative samples; (2) imbalanced gradient contributions across heterogeneous tasks; and (3) severe credit assignment problem in long-horizon planning, where trajectory-level rewards indiscriminately penalize all tokens. To address these issues, we propose an efficient training paradigm that achieves state-of-the-art average performance through strategic data selection and hierarchical policy optimization. Our approach consists of three synergistic stages. First, Rejection Sampling-based Fine-Tuning (RSFT) filters out low-informative samples to establish robust behavioral priors while preventing distributional collapse. Second, Iterative Rejection GRPO (IR-GRPO) employs task-specific queues stratified by difficulty to keep datasets balanced across reinforcement learning iterations, coupled with a hybrid reward mechanism for precise cross-task feedback. Third, to enhance long-horizon task planning, we introduce Trie-GRPO, a novel reinforcement learning algorithm based on action prefix trees, which enables step-level advantage estimation. This resolves the credit assignment problem by isolating intermediate correct decisions from downstream errors, while effectively balancing exploration efficiency and depth compared to conventional search trees. As a result, EmbodiedMind achieves a state-of-the-art average performance of 70.02% across 18 benchmarks, and significantly outperforms other embodied foundation models in long-horizon task planning accuracy. Our project will be released for reproducibility.

## TL;DR

Training embodied foundation models typically requires massive-scale datasets and extensive computational resources, yet often suffers from three critical limitations: (1) inefficient sample utilization due to low-informative samples; (2) imbalanced gradient contributions across heterogeneous tasks; and (3) severe credit assignment problem in long-horizon planning, where trajectory-level rewards indiscriminately penalize all tokens. To address these issues, we propose an efficient training paradigm that achieves state-of-the-art average performance through strategic data selection and...

## Related
<!-- [[other-paper-citekey]] -->
