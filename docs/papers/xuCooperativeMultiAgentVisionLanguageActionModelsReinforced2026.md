---
citekey: "xuCooperativeMultiAgentVisionLanguageActionModelsReinforced2026"
title: "Cooperative Multi-Agent Vision-Language-Action Models via Reinforced Fine Tuning"
authors: ["Ruixiao Xu", "Wong Lik Hang Kenny", "Zhiqian Liu", "Jianing Guo", "Hanxiao Li", "Kejian Shi", "Shuning Zhang", "Pu Feng", "Yongjia Ma", "Yuqing Ma", "Kai Chen", "Qi Dou", "Yaodong Yang", "Xianglong Liu", "Simin Li"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.36588"
doi: "10.48550/arXiv.2609.36588"
tags: [paper, embodied-ai, "cs.AI", "cs.MA", "cs.RO"]
status: unread
rating:
created: 2026-09-30
---

# Cooperative Multi-Agent Vision-Language-Action Models via Reinforced Fine Tuning

> Ruixiao Xu, Wong Lik Hang Kenny, Zhiqian Liu, Jianing Guo, Hanxiao Li, Kejian Shi, Shuning Zhang, Pu Feng, Yongjia Ma, Yuqing Ma, Kai Chen, Qi Dou, Yaodong Yang, Xianglong Liu, Simin Li · 2026
> [arXiv](https://arxiv.org/abs/2609.36588) · [PDF](https://arxiv.org/pdf/2609.36588)

## Abstract

We study reinforcement learning (RL) methods for cooperative multi-agent Vision-Language-Action (VLA) models. This problem is challenging because VLAs are pretrained on large-scale single-agent data and therefore lack the fine-grained coordination skills required for inter-robot collaboration. Supervised fine-tuning (SFT) on multi-robot demonstrations partially bridges this gap, but its performance is bounded by the demonstration data and cannot improve from its own experience. We present a three-stage reinforced fine-tuning (RFT) pipeline for multi-agent VLAs. First, initialization-aware data collection sweeps over initial configurations and invokes human demonstrations only when the pretrained VLA repeatedly fails, yielding robustness to initialization shift with reduced human cost. Second, offline credit-filtered tuning assigns credit to individual agents and fine-tunes on per-agent trajectories with positive advantage rather than on entire joint rollouts. Third, we find existing online RL for VLAs are less effective for hard multi-agent tasks, which we attribute to noisy co-exploration and unstable updates. We instead use online latent-space fine tuning, which freeze the VLA and perform RL in its latent noise space. We evaluate our multi-agent VLA with both $π_0$ and $π_{0.5}$ backbones across 11 tasks in RoboTwin, RoboFactory and real-world manipulation with two Franka robots. Our multi-agent VLA improves the average success rate by $+23.1\%$, $+16.4\%$, and $+44\%$ on RoboTwin, RoboFactory, and real-world tasks, respectively. Code available at https://anonymous.4open.science/r/mavla_rft-2BC0/.

## TL;DR

We study reinforcement learning (RL) methods for cooperative multi-agent Vision-Language-Action (VLA) models. This problem is challenging because VLAs are pretrained on large-scale single-agent data and therefore lack the fine-grained coordination skills required for inter-robot collaboration.

## Related
<!-- [[other-paper-citekey]] -->
