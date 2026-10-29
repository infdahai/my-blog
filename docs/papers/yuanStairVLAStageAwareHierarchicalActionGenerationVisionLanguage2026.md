---
citekey: "yuanStairVLAStageAwareHierarchicalActionGenerationVisionLanguage2026"
title: "StairVLA: Stage-Aware Hierarchical Action Generation for Vision-Language-Action Models"
authors: ["Shangyuan Yuan", "Xinda Qi", "Yujiang Pu", "Wenliang Guo", "Xiaobo Tan"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.07756"
doi: "10.48550/arXiv.2610.07756"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-08
---

# StairVLA: Stage-Aware Hierarchical Action Generation for Vision-Language-Action Models

> Shangyuan Yuan, Xinda Qi, Yujiang Pu, Wenliang Guo, Xiaobo Tan · 2026
> [arXiv](https://arxiv.org/abs/2610.07756) · [PDF](https://arxiv.org/pdf/2610.07756)

## Abstract

Vision-language-action (VLA) models increasingly rely on diffusion- or flow-matching-based action heads to generate continuous robot actions. These action heads typically process the denoising trajectory in a largely uniform manner. However, we observe that the conditioning focus naturally shifts across denoising stages: early stages combine language instructions and visual observations to establish a coarse action trajectory, whereas later stages place greater emphasis on current visual observations for action alignment. Based on this insight, we introduce StairVLA, a stage-aware hierarchical action generation framework that uses partially denoised actions as a natural interface between coarse long-horizon action generation and local refinement. A high-level VLA performs early denoising to produce a reusable long-horizon partially denoised action trajectory, while a lightweight refiner operates at a higher frequency to refine local action chunks using the latest observations. This design amortizes expensive high-level VLA computation while preserving frequent closed-loop correction. On LIBERO, our GR00T-style instantiation improves average success from 96.5% to 97.8% while reducing amortized inference latency from 115.0 ms to 44.2 ms per action chunk. More broadly, across two VLA backbones, simulation benchmarks, and real-robot tasks, StairVLA consistently reduces inference cost while maintaining strong task performance.

## TL;DR

Vision-language-action (VLA) models increasingly rely on diffusion- or flow-matching-based action heads to generate continuous robot actions. These action heads typically process the denoising trajectory in a largely uniform manner.

## Related
<!-- [[other-paper-citekey]] -->
