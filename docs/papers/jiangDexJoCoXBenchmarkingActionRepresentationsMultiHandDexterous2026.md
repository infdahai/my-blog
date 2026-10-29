---
citekey: "jiangDexJoCoXBenchmarkingActionRepresentationsMultiHandDexterous2026"
title: "DexJoCo-X: Benchmarking Action Representations for Multi-Hand Dexterous Manipulation"
authors: ["Xiangwei Jiang", "Yao Mu", "Lixin Duan", "Wen Li"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.03278"
doi: "10.48550/arXiv.2610.03278"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-06
---

# DexJoCo-X: Benchmarking Action Representations for Multi-Hand Dexterous Manipulation

> Xiangwei Jiang, Yao Mu, Lixin Duan, Wen Li · 2026
> [arXiv](https://arxiv.org/abs/2610.03278) · [PDF](https://arxiv.org/pdf/2610.03278)

## Abstract

As dexterous hands proliferate, collecting data and training policies separately for every morphology becomes increasingly impractical. Scalable cross-embodiment learning therefore requires a unified representation that captures shared manipulation structure while preserving morphology-specific control. Differences in hands, tasks, datasets, and control interfaces prevent existing studies from isolating the effects of representation, pretraining, and architecture. We introduce DexJoCo-X, a benchmark and toolkit for controlled comparison across seven representative dexterous hands, six single-arm and bimanual tasks, and 2,100 balanced demonstrations. DexJoCo-X provides a matched multi-hand, multi-task protocol with common scenes, success criteria, and execution interfaces, redesigned glove-to-hand mappings, and an automated pipeline that expands reviewed demonstrations across randomized scenes. Using $π_{0.5}$, Ego-Pi, and Being-H0.5, we examine whether a shared action interface is sufficient for multi-hand learning. Expanding $π_{0.5}$ to an 80-dimensional bimanual output yields near-zero success. Ego-Pi preserves the pretrained action head through interleaved prediction and supports per-hand multi-task learning, but remains ineffective for seven-hand joint training. By contrast, Being-H0.5 combines cross-embodiment pretraining, a unified action space, and embodiment-aware experts, enabling one policy to control all seven hands. Within this architecture, function-aligned action slots achieve 47.7% mean success, compared with 47.0% for native coordinates and 33.1% for DexLatent. These results show that cross-embodiment representation depends on the entire learning system: action coordinates, pretraining, and architecture must jointly separate shared manipulation structure from embodiment-specific control.

## TL;DR

As dexterous hands proliferate, collecting data and training policies separately for every morphology becomes increasingly impractical. Scalable cross-embodiment learning therefore requires a unified representation that captures shared manipulation structure while preserving morphology-specific control.

## Related
<!-- [[other-paper-citekey]] -->
