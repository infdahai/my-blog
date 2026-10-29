---
citekey: "zhouSubspaceInferenceEnablesEfficientActiveRewardLearningPreferences2026"
title: "Subspace Inference Enables Efficient Active Reward Learning from Preferences"
authors: ["Yutai Zhou", "Erdem Bıyık"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.04066"
doi: "10.48550/arXiv.2609.04066"
tags: [paper, embodied-ai, "cs.AI", "cs.LG", "cs.RO"]
status: unread
rating:
created: 2026-09-07
---

# Subspace Inference Enables Efficient Active Reward Learning from Preferences

> Yutai Zhou, Erdem Bıyık · 2026
> [arXiv](https://arxiv.org/abs/2609.04066) · [PDF](https://arxiv.org/pdf/2609.04066)

## Abstract

Reinforcement learning from human feedback (RLHF) has emerged as a powerful yet sample-inefficient approach for learning reward models from human preferences, making active learning a critical component in synthesizing informative preference queries. However, effective uncertainty quantification required for active learning remains a key challenge for large neural network reward models. In this paper, we introduce PreferenceEKF, a sample-efficient approach that tracks reward model uncertainty by framing active preference learning as a sequential Bayesian filtering problem. Instead of relying on computationally prohibitive posterior inference over the full neural network parameter space, our method performs sequential inference via an extended Kalman filter within a low-dimensional parameter subspace, continuously updating the reward model posterior as new preference queries arrive. Our approach enables scalable sampling of neural network parameters to efficiently compute acquisition functions for active reward learning. Experiments on the D4RL and V-D4RL benchmarks demonstrate that our approach achieves better sample efficiency, runtime, scalability, and calibration compared to other Bayesian deep learning approaches, and the learned reward models lead to competitive offline reinforcement learning policy performance. This highlights the potential of scalable Bayesian methods for preference-based reward modeling in RLHF. Our code is available at https://github.com/yutaizhou/bnn_pref.

## TL;DR

Reinforcement learning from human feedback (RLHF) has emerged as a powerful yet sample-inefficient approach for learning reward models from human preferences, making active learning a critical component in synthesizing informative preference queries. However, effective uncertainty quantification required for active learning remains a key challenge for large neural network reward models.

## Related
<!-- [[other-paper-citekey]] -->
