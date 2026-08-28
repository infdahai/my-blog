---
citekey: "weiLearningAccelerateVisionLanguageActionModelsThroughAdaptive2026"
title: "Learning to Accelerate Vision-Language-Action Models through Adaptive Visual Token Caching"
authors: ["Yujie Wei", "Jiahan Fan", "Jiyu Guo", "Ruichen Zhen", "Rui Shao", "Xiu Su", "Zeke Xie", "Hongxun Yao", "Shuo Yang"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2602.00686"
doi: "10.48550/arXiv.2602.00686"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-08-28
---

# Learning to Accelerate Vision-Language-Action Models through Adaptive Visual Token Caching

> Yujie Wei, Jiahan Fan, Jiyu Guo, Ruichen Zhen, Rui Shao, Xiu Su, Zeke Xie, Hongxun Yao, Shuo Yang · 2026
> [arXiv](https://arxiv.org/abs/2602.00686) · [PDF](https://arxiv.org/pdf/2602.00686)

## Abstract

Vision-Language-Action (VLA) models have demonstrated remarkable generalization capabilities in robotic manipulation tasks, yet their substantial computational overhead remains a critical obstacle to real-world deployment. Improving inference efficiency is therefore essential for practical robotic applications. Existing acceleration methods often rely on heuristic or static strategies--such as rule-based token caching or pruning--that are decoupled from task objectives and fail to adapt to dynamic scene changes. In this work, we reformulate inference acceleration as a learnable policy optimization problem and propose a novel framework that integrates a dynamic, task-aware decision-making process directly into the VLA model. At its core are two lightweight, cooperative modules: a Cached Token Selector, which determines which tokens should be reused, and a Cache Ratio Predictor, which controls how many tokens to reuse. Training these modules is non-trivial due to their discrete decisions. We address this by adopting a differentiable relaxation that allows gradient-based end-to-end optimization. Extensive experiments on the LIBERO and SIMPLER benchmarks, as well as real-robot evaluations, show that our method achieves a 1.76x wall-clock inference speedup while simultaneously improving the average success rate by 1.9 percentage points (from 75.0% to 76.9%) on LIBERO and by 5.0 percentage points on real-world tasks, significantly outperforming existing baselines. This work highlights the potential of learning task-aware computational allocation policies, paving the way for VLA models that are both powerful and efficient.

## TL;DR

Vision-Language-Action (VLA) models have demonstrated remarkable generalization capabilities in robotic manipulation tasks, yet their substantial computational overhead remains a critical obstacle to real-world deployment. Improving inference efficiency is therefore essential for practical robotic applications.

## Related
<!-- [[other-paper-citekey]] -->
