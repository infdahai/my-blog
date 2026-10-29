---
citekey: "liuRefineActionsIfNeededAdaptiveActionChunkRefinement2026"
title: "Refine Actions If Needed: Adaptive Action Chunk Refinement for Robot Manipulation"
authors: ["Hanlin Liu", "Zichen Zhou", "Jiacheng Zhang", "Liuyuan Na", "Jin Jin", "Guangyan Chen", "Yufeng Yue", "Gen Li", "Fangqiang Ding"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.19765"
doi: "10.48550/arXiv.2610.19765"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-16
---

# Refine Actions If Needed: Adaptive Action Chunk Refinement for Robot Manipulation

> Hanlin Liu, Zichen Zhou, Jiacheng Zhang, Liuyuan Na, Jin Jin, Guangyan Chen, Yufeng Yue, Gen Li, Fangqiang Ding · 2026
> [arXiv](https://arxiv.org/abs/2610.19765) · [PDF](https://arxiv.org/pdf/2610.19765)

## Abstract

Computationally lightweight manipulation policies predict executable actions with low inference latency, but prediction errors can limit task success. Iterative generative policies can achieve higher task success rates, but repeated network evaluations increase inference latency. Refining action proposals from computationally lightweight policies can combine these strengths, but the amount of refinement needed varies across states. We introduce RAIN (Refine Actions If Needed), a framework that predicts action errors at different refinement levels to decide whether and how much to refine each executable proposal, before performing any refinement. We train an ensemble to predict these errors by comparing action proposals and their refined versions with expert actions from offline demonstrations, without requiring explicit labels of refinement needs. Calibration balances uncertainty, computation, and temporal consistency. We evaluate RAIN on eight ManiSkill tasks and four real-robot tasks. In simulation, our policy achieves 66.6% success, approaching the best evaluated diffusion-policy success rate with 5.71 times lower policy latency. On the real robot, success increases from 55.0% with Action Chunking with Transformers (ACT) to 72.5%, with comparable average successful completion time. Matched controls show that dynamic routing maintains the strongest observed fixed-refinement success level with 26.6% fewer refiner evaluations. Project page: https://rain-policy.github.io/.

## TL;DR

Computationally lightweight manipulation policies predict executable actions with low inference latency, but prediction errors can limit task success. Iterative generative policies can achieve higher task success rates, but repeated network evaluations increase inference latency.

## Related
<!-- [[other-paper-citekey]] -->
