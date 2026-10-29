---
citekey: "chenDualProcessAtomicSkillLearningDecouplingSemanticReasoning2026"
title: "Dual-Process Atomic Skill Learning: Decoupling Semantic Reasoning and Real-Time Control"
authors: ["Jun Chen", "Erdemt Bao", "Wenlong Dong", "Jierui Liu", "Qi Cai", "Hao Wan", "Shaopeng Li", "Weijun Qin", "Jing Liang", "Huiping Zhuang"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2607.10625"
doi: "10.48550/arXiv.2607.10625"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-15
---

# Dual-Process Atomic Skill Learning: Decoupling Semantic Reasoning and Real-Time Control

> Jun Chen, Erdemt Bao, Wenlong Dong, Jierui Liu, Qi Cai, Hao Wan, Shaopeng Li, Weijun Qin, Jing Liang, Huiping Zhuang · 2026
> [arXiv](https://arxiv.org/abs/2607.10625) · [PDF](https://arxiv.org/pdf/2607.10625)

## Abstract

Language-conditioned Imitation Learning (IL) is essential for enabling robots to perform complex tasks following natural language instructions. However, generalizing to multi-step compositional tasks remains a significant challenge. While hierarchical approaches attempt to address this by decomposing tasks into atomic skills, existing methods often suffer from training instability and codebook collapse due to the tight coupling between high-level skill reasoning and low-level action generation in joint training paradigms. Inspired by the Dual-Process Theory of cognition, we propose Dual-Process Atomic Skill Learning (DASL), a novel asynchronous hierarchical imitation learning framework that decouples slow semantic reasoning from fast, real-time motion control. DASL comprises a Slow-Frequency Policy that predicts interpretable, discrete skills via Vector Quantization, and a High-Frequency Policy that leverages a latent diffusion model and a Decision Transformer to generate precise actions conditioned on these latent skills. By asynchronously coordinating these modules and utilizing diffusion to structure the latent space, our framework mitigates the skill codebook interference problem common in joint training paradigms. Evaluations across simulation benchmarks and experiment demonstrate that DASL significantly outperforms state-of-the-art baselines, excelling in skill acquisition and compositional generalization to unseen instructions. GitHub page: https://github.com/Hatakekaka/DASL

## TL;DR

Language-conditioned Imitation Learning (IL) is essential for enabling robots to perform complex tasks following natural language instructions. However, generalizing to multi-step compositional tasks remains a significant challenge.

## Related
<!-- [[other-paper-citekey]] -->
