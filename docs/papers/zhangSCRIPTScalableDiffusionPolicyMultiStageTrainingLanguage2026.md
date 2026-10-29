---
citekey: "zhangSCRIPTScalableDiffusionPolicyMultiStageTrainingLanguage2026"
title: "SCRIPT: Scalable Diffusion Policy with Multi-stage Training for Language-driven Physics-Based Humanoid Control"
authors: ["Jingyan Zhang", "Han Liang", "Ruichi Zhang", "Bin Li", "Juze Zhang", "Xin Chen", "Jingya Wang", "Lan Xu", "Jingyi Yu"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2605.22894"
doi: "10.48550/arXiv.2605.22894"
tags: [paper, embodied-ai, "cs.GR", "cs.LG", "cs.RO"]
status: unread
rating:
created: 2026-09-08
---

# SCRIPT: Scalable Diffusion Policy with Multi-stage Training for Language-driven Physics-Based Humanoid Control

> Jingyan Zhang, Han Liang, Ruichi Zhang, Bin Li, Juze Zhang, Xin Chen, Jingya Wang, Lan Xu, Jingyi Yu · 2026
> [arXiv](https://arxiv.org/abs/2605.22894) · [PDF](https://arxiv.org/pdf/2605.22894)

## Abstract

Controlling physics-based humanoids from natural-language instructions is a critical step toward general-purpose embodied agents. However, existing methods remain constrained by a tension between semantic expressiveness and physical feasibility, often failing to jointly achieve faithful instruction following, high-quality motion, and stable long-horizon control. We propose SCRIPT, a scalable diffusion policy with a multi-stage training framework for language-driven physics-based humanoid control. The core of SCRIPT is a Joint Action-State-Text Diffusion Transformer (JAST-DiT), which represents actions, physical states, and text as dedicated token streams and couples them through joint attention, enabling direct interaction between language semantics and control dynamics. To stabilize autoregressive control, we introduce a nonlinear history conditioning mechanism, which preserves the dense recent context and samples increasingly sparse cues from long-term history. Beyond supervised imitation pre-training, we propose a post-training stage, further improving the performance using Reinforcement Learning with Hybrid Rewards (RLHR). By injecting learnable noise into the flow-sampling process, RLHR effectively improves motion quality and instruction following within closed-loop simulations using hybrid physical feedback and text rewards. Quantitative evaluations demonstrate that SCRIPT outperforms prior state-of-the-art methods, with gains across text alignment, motion quality, and physical realism metrics. Furthermore, scaling studies on the 1200-hour MotionMillion dataset demonstrate consistent performance gains with model scaling, highlighting SCRIPT's robust scalability for large-scale pre-training. Our code will be publicly available for future research.

## TL;DR

Controlling physics-based humanoids from natural-language instructions is a critical step toward general-purpose embodied agents. However, existing methods remain constrained by a tension between semantic expressiveness and physical feasibility, often failing to jointly achieve faithful instruction following, high-quality motion, and stable long-horizon control.

## Related
<!-- [[other-paper-citekey]] -->
