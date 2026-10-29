---
citekey: "kotbDreamFormerDreamImitationTransformerWorldModelLanguageConditioned2026"
title: "DreamFormer: Dream Imitation with a Transformer World Model for Language-Conditioned Robotic Manipulation"
authors: ["Mostafa Kotb", "Cornelius Weber", "Muhammad Burhan Hafez", "Stefan Wermter"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.04540"
doi: "10.48550/arXiv.2610.04540"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-07
---

# DreamFormer: Dream Imitation with a Transformer World Model for Language-Conditioned Robotic Manipulation

> Mostafa Kotb, Cornelius Weber, Muhammad Burhan Hafez, Stefan Wermter · 2026
> [arXiv](https://arxiv.org/abs/2610.04540) · [PDF](https://arxiv.org/pdf/2610.04540)

## Abstract

We introduce DreamFormer, a model-based agent that acquires language-conditioned, multi-task skills by imitating expert demonstrations within the latent imagination of a learned world model. DreamFormer first learns a task-agnostic Transformer world model from unstructured play data, then acquires task-specific behaviors by optimizing an intrinsic reward that aligns agent-generated rollouts with expert demonstrations in latent space. Since the policy is trained on-policy inside imagination, it is exposed to its own errors during training, mitigating the covariate shift inherent to offline behavioral cloning. To make long-horizon imagination affordable, DreamFormer encodes a high-resolution multi-view robotic observation into a single input token, avoiding both spatial downsampling and the multi-token representations used by prior Transformer world models. On the long-horizon CALVIN benchmark, DreamFormer outperforms LUMOS, the comparable model-based agent, on single-environment evaluation (2.52 vs 2.34 average tasks completed per chain of five) while keeping imagination rollouts tractable. Against HULC, the behavior cloning baseline, it nearly doubles performance on zero-shot transfer to an unseen environment (1.30 vs 0.67), indicating that dynamics learned by the world model transfer more readily than a directly cloned policy. This is consistent with the role attributed to internal models in biological agents, where a model of environment dynamics supports behavior in situations not previously encountered.

## TL;DR

We introduce DreamFormer, a model-based agent that acquires language-conditioned, multi-task skills by imitating expert demonstrations within the latent imagination of a learned world model. DreamFormer first learns a task-agnostic Transformer world model from unstructured play data, then acquires task-specific behaviors by optimizing an intrinsic reward that aligns agent-generated rollouts with expert demonstrations in latent space.

## Related
<!-- [[other-paper-citekey]] -->
