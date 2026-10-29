---
citekey: "chenPACEStageConsistentLongHorizonManipulationProgressAligned2026"
title: "PACE: Stage-Consistent Long-Horizon Robot Manipulation via Progress-Aligned Context for Execution"
authors: ["Yenan Chen", "Junjie Shi", "Lu Chen", "Zhongxiang Zhou", "Rong Xiong"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.07917"
doi: "10.48550/arXiv.2610.07917"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-08
---

# PACE: Stage-Consistent Long-Horizon Robot Manipulation via Progress-Aligned Context for Execution

> Yenan Chen, Junjie Shi, Lu Chen, Zhongxiang Zhou, Rong Xiong · 2026
> [arXiv](https://arxiv.org/abs/2610.07917) · [PDF](https://arxiv.org/pdf/2610.07917)

## Abstract

Demonstration-conditioned policies provide a natural interface for specifying robot behavior, yet long-horizon manipulation remains difficult when visually similar states recur across different stages or when demonstrations and executions proceed at different speeds. We identify the resulting failure mode as stage confusion and introduce Progress-Aligned Context for Execution (PACE), a stateful method that continually reinterprets a complete demonstration according to realized execution progress. PACE compresses the demonstration into ordered multimodal prompt tokens and uses training-only dual-edge attention supervision to expose its latent stage structure. During execution, an episode-local fast-weight memory causally encodes realized action-observation transitions and modulates prompt cross-attention, producing a progress-aligned context for a unified diffusion action expert without test-time stage labels or stage-specific policies. PACE improves success from 88.9% to 94.0% on LIBERO-Gen Goal Chain, from 79.1% to 83.3% on Spatial Combination, and from 33.3% to 73.3% on the two-step Block Routing tasks. Failure analysis further indicates that structured demonstration alignment and causal execution memory jointly mitigate stage confusion.

## TL;DR

Demonstration-conditioned policies provide a natural interface for specifying robot behavior, yet long-horizon manipulation remains difficult when visually similar states recur across different stages or when demonstrations and executions proceed at different speeds. We identify the resulting failure mode as stage confusion and introduce Progress-Aligned Context for Execution (PACE), a stateful method that continually reinterprets a complete demonstration according to realized execution progress.

## Related
<!-- [[other-paper-citekey]] -->
