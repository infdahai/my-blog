---
citekey: "yuanLearningAbsorbCorrectionsCriticWeightedResidualFlowVision2026"
title: "Learning to Absorb Corrections: Critic-Weighted Residual Flow for Vision-Based Insertion"
authors: ["Yiqing Yuan", "Zhi Li", "Jinrong Yang", "Mingshan Sun", "Mei Yu Zhi", "Yong Zhao", "Liangliang Ren", "Hui Cheng"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.29117"
doi: "10.48550/arXiv.2610.29117"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-22
---

# Learning to Absorb Corrections: Critic-Weighted Residual Flow for Vision-Based Insertion

> Yiqing Yuan, Zhi Li, Jinrong Yang, Mingshan Sun, Mei Yu Zhi, Yong Zhao, Liangliang Ren, Hui Cheng · 2026
> [arXiv](https://arxiv.org/abs/2610.29117) · [PDF](https://arxiv.org/pdf/2610.29117)

## Abstract

Vision-based insertion requires correcting alignment errors while retaining useful behavior learned from demonstrations. We present ACT--Flow, an online learning framework that couples an adaptive Action Chunking Transformer (ACT) with a conditional residual flow policy. Following anchor-guided warmup, ACT absorbs successful executed actions through behavioral cloning, while residual targets are recomputed relative to the updated prior. A chunk-level critic learns from successful and failed interactions and evaluates final composed actions. Its estimates weight generated residual candidates for flow matching, complemented by supervision from successful real executions. Candidate scoring is confined to training; deployment uses RGB observations and samples one residual per action chunk. We evaluate the framework on power-plug, USB, and key insertion, together with cable routing and needle threading. Results show a five-task mean success rate of 66% at 20,000 post-initialization interaction steps, exceeding the strongest baseline by 18 percentage points at this checkpoint. Evaluations at matched checkpoints with the residual disabled show ACT's mean success increasing from 16% to 76%. Component ablations further support the complementary roles of behavior absorption, value weighting, and successful-action supervision.

## TL;DR

Vision-based insertion requires correcting alignment errors while retaining useful behavior learned from demonstrations. We present ACT--Flow, an online learning framework that couples an adaptive Action Chunking Transformer (ACT) with a conditional residual flow policy.

## Related
<!-- [[other-paper-citekey]] -->
