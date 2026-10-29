---
citekey: "guoRethinkingLanguageSRoleEfficientVLAAutonomousVehicles2026"
title: "Rethinking Language's Role in Efficient VLA for Autonomous Vehicles: Toward Smarter, Trustworthy Driving"
authors: ["Tongfei Guo", "Lili Su"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2608.30144"
doi: "10.48550/arXiv.2608.30144"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-02
---

# Rethinking Language's Role in Efficient VLA for Autonomous Vehicles: Toward Smarter, Trustworthy Driving

> Tongfei Guo, Lili Su · 2026
> [arXiv](https://arxiv.org/abs/2608.30144) · [PDF](https://arxiv.org/pdf/2608.30144)

## Abstract

Vision-Language-Action (VLA) models are reshaping autonomous driving (AD) by unifying perception, reasoning, and control through language, enabling semantic grounding, interpretable decisions, and better long-tail generalization. But language is expensive onboard: latency and memory budgets are tight, and autoregressive decoding is inherently sequential. This work reframes the central question as when and where language should act at inference, since inference cost recurs at every deployed frame while training cost is paid once. We introduce the Language Residue taxonomy to organize methods by their inference-time use of language: train-time-only supervision (L1), latent non-textual reasoning (L2), conditional invocation (L3), and full per-frame generation (L4). We review representative methods and tag each across five deployment axes (latency, parameters, memory, FLOPs, tokens), analyzing them on major open- and closed-loop driving benchmarks (e.g., nuScenes, NAVSIM, Bench2Drive). We further trace how efficient methods from NLP/LLM are adapted in AD, identifying the constraints and motivations driving these adaptations. A continuously updated repository will be available at Github.

## TL;DR

Vision-Language-Action (VLA) models are reshaping autonomous driving (AD) by unifying perception, reasoning, and control through language, enabling semantic grounding, interpretable decisions, and better long-tail generalization. But language is expensive onboard: latency and memory budgets are tight, and autoregressive decoding is inherently sequential.

## Related
<!-- [[other-paper-citekey]] -->
