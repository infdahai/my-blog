---
citekey: "zhangBeyondNoiseSteeringDualLatentSpaceReinforcementLearning2026"
title: "Beyond Noise Steering: Dual-Latent Space Reinforcement Learning for Generative Robot Policy"
authors: ["Pengfei Zhang", "Teng Sun", "Xianchao Xiu"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.11270"
doi: "10.48550/arXiv.2609.11270"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-12
---

# Beyond Noise Steering: Dual-Latent Space Reinforcement Learning for Generative Robot Policy

> Pengfei Zhang, Teng Sun, Xianchao Xiu · 2026
> [arXiv](https://arxiv.org/abs/2609.11270) · [PDF](https://arxiv.org/pdf/2609.11270)

## Abstract

Pretrained generative robot policies learn expressive action priors from demonstrations. However, existing reinforcement learning methods only steer the noisy space but fail to modulate intermediate action representations during the generation process, resulting in performance degradation and inefficiency. To address this limitation, we propose a novel Dual-Latent Space Reinforcement Learning (DLSRL) framework, which complements initial-noise steering with representation-level control inside the frozen generator. Specifically, our actor network predicts two distinct latent variables: an initial-noise latent variable that steers behavior generation, and an action-representation latent variable for intermediate feature modulation. Moreover, this representation latent variable is mapped to adapter features and ingeniously injected into the hidden states of intermediate action tokens via residual connections. Our dual-control design enables direct adjustment of action representations without updating the base policy. Experiments across generative policy architectures and robotic manipulation tasks show that DLSRL effectively accelerates online robot policy adaptation and achieves competitive performance. Our code is available at \href{https://github.com/xianchaoxiu/DLSRL}{https://github.com/xianchaoxiu/DLSRL}.

## TL;DR

Pretrained generative robot policies learn expressive action priors from demonstrations. However, existing reinforcement learning methods only steer the noisy space but fail to modulate intermediate action representations during the generation process, resulting in performance degradation and inefficiency.

## Related
<!-- [[other-paper-citekey]] -->
