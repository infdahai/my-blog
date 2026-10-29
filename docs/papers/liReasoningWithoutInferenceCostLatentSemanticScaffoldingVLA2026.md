---
citekey: "liReasoningWithoutInferenceCostLatentSemanticScaffoldingVLA2026"
title: "Reasoning Without Inference Cost: Latent Semantic Scaffolding for Robot VLA Policies"
authors: ["Andrew Ting Yan Li", "Zhuo Li", "Zhelin Yang", "Zhipeng Dong", "Quentin Rouxel", "Fei Chen"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.04893"
doi: "10.48550/arXiv.2609.04893"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-08
---

# Reasoning Without Inference Cost: Latent Semantic Scaffolding for Robot VLA Policies

> Andrew Ting Yan Li, Zhuo Li, Zhelin Yang, Zhipeng Dong, Quentin Rouxel, Fei Chen · 2026
> [arXiv](https://arxiv.org/abs/2609.04893) · [PDF](https://arxiv.org/pdf/2609.04893)

## Abstract

Vision-language-action (VLA) models are trained by imitation and capture what action to take but not why; adding causal reasoning improves manipulation, but current methods pay for it at inference time - generating reasoning tokens or rolling out predicted future states at every step, a cost that compounds over long horizons. We ask whether this benefit can instead be captured during training and discarded before deployment. We introduce Latent Semantic Scaffolding (LSS), an auxiliary loss applied during human-demonstration pretraining that aligns a VLA's action-token representations to text embeddings of physical-reasoning rationales through a small projection head. The head is dropped at inference, leaving the unmodified base policy with zero added cost. Our central finding concerns alignment granularity: aligning each action token to the rationale of its own manipulation phase (Dense LSS) rather than to a single pooled episode-level embedding (Pooled LSS) yields representations that transfer markedly better to held-out tasks. Dense LSS attains both the best in-distribution success and the best transfer to tasks unseen during alignment, whereas pooled alignment over-specializes to the training task. A representational probe shows Dense LSS induces roughly twice the per-phase separability in the backbone, supporting that phase-local alignment is the operative mechanism.

## TL;DR

Vision-language-action (VLA) models are trained by imitation and capture what action to take but not why; adding causal reasoning improves manipulation, but current methods pay for it at inference time - generating reasoning tokens or rolling out predicted future states at every step, a cost that compounds over long horizons. We ask whether this benefit can instead be captured during training and discarded before deployment.

## Related
<!-- [[other-paper-citekey]] -->
