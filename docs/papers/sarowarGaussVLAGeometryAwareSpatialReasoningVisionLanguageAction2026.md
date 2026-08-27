---
citekey: "sarowarGaussVLAGeometryAwareSpatialReasoningVisionLanguageAction2026"
title: "GaussVLA: Geometry-Aware Spatial Reasoning for Vision-Language-Action Model"
authors: ["Md Selim Sarowar", "Md Tanvir Islam", "Sungho Kim", "Sangtae Ahn"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2608.24959"
doi: "10.48550/arXiv.2608.24959"
tags: [paper, embodied-ai, "cs.CV", "cs.RO"]
status: unread
rating:
created: 2026-08-27
---

# GaussVLA: Geometry-Aware Spatial Reasoning for Vision-Language-Action Model

> Md Selim Sarowar, Md Tanvir Islam, Sungho Kim, Sangtae Ahn · 2026
> [arXiv](https://arxiv.org/abs/2608.24959) · [PDF](https://arxiv.org/pdf/2608.24959)

## Abstract

Vision-Language-Action (VLA) models encode visual observations as flat 2D patch tokens that carry no intrinsic geometric structure, and augmenting them with dense monocular depth injects per-pixel scalar values that encode neither surface orientation nor geometric confidence. This leaves the policy with limited structured spatial reasoning for action prediction. We propose GaussVLA, a Mamba-based VLA that incorporates two custom modules: Gaussian Spatial Tokenizer (GST) to lift frozen semantic and depth features into compact 3D Gaussian tokens, pools geometrically salient regions with learned queries, and \emph{Depth-Aware Chain-of-Thought (DA-CoT)} that performs structured, non-autoregressive geometric reasoning under language and flow-time conditioning. Across both simulation and real-world evaluations, GaussVLA demonstrates strong spatial-manipulation performance while remaining parameter-efficient. On LIBERO, it achieves 93.5% average success and 100.0% success on the Spatial suite with only 200M parameters, improving over SpatialVLA by 19.7% relative average success while remaining significantly more parameter-efficient.

## TL;DR

Vision-Language-Action (VLA) models encode visual observations as flat 2D patch tokens that carry no intrinsic geometric structure, and augmenting them with dense monocular depth injects per-pixel scalar values that encode neither surface orientation nor geometric confidence. This leaves the policy with limited structured spatial reasoning for action prediction.

## Related
<!-- [[other-paper-citekey]] -->
