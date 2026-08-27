---
citekey: "maDECOWAMDecoupledWholeBodyWorldActionModelLegged2026"
title: "DECOWAM: Decoupled Whole-Body World-Action Model for Legged Mobile Manipulation"
authors: ["Siyuan Ma", "Boshi Zhang", "Yutian Zhang", "Qinglian Wu", "Jiaqi Zhai", "Dong Wei", "Qiaojun Yu"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2608.20114"
doi: "10.48550/arXiv.2608.20114"
tags: [paper, embodied-ai, "cs.AI", "cs.RO"]
status: unread
rating:
created: 2026-08-27
---

# DECOWAM: Decoupled Whole-Body World-Action Model for Legged Mobile Manipulation

> Siyuan Ma, Boshi Zhang, Yutian Zhang, Qinglian Wu, Jiaqi Zhai, Dong Wei, Qiaojun Yu · 2026
> [arXiv](https://arxiv.org/abs/2608.20114) · [PDF](https://arxiv.org/pdf/2608.20114)

## Abstract

Mobile manipulation requires a robot to predict how locomotion and arm motion jointly alter future observations and control. Existing world-action models, developed largely for fixed-base platforms, do not explicitly distinguish camera ego-motion from base and arm actions. Here we introduce DECOWAM, a whole-body world-action model that separates these factors through dedicated conditional interfaces. DECOWAM freezes an adapted FastWAM backbone and trains residual adapters, an action-equivalent future bottleneck distilled from privileged observations, adversarially separated base and arm latents, and base-velocity conditioning for video prediction. We further introduce ARMDOG, a real-robot dataset that synchronizes video, whole-body state and action, and language. On a fixed replay protocol, DECOWAM improved both future-video and action prediction over FastWAM, reducing action MSE by 21.7% with 25.95M trainable adaptation parameters. Across 79 closed-loop trials per method, it achieved the highest observed whole-body coordination and base-displacement robustness among the compared systems, while task completion remained comparable to the strongest baseline. These results show that embodiment-aware factorization can support parameter-efficient joint visual prediction and whole-body control under moving viewpoints.

## TL;DR

Mobile manipulation requires a robot to predict how locomotion and arm motion jointly alter future observations and control. Existing world-action models, developed largely for fixed-base platforms, do not explicitly distinguish camera ego-motion from base and arm actions.

## Related
<!-- [[other-paper-citekey]] -->
