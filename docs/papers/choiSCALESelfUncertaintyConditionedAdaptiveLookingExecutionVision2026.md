---
citekey: "choiSCALESelfUncertaintyConditionedAdaptiveLookingExecutionVision2026"
title: "SCALE: Self-uncertainty Conditioned Adaptive Looking and Execution for Vision-Language-Action Models"
authors: ["Hyeonbeom Choi", "Daechul Ahn", "Youhan Lee", "Taewook Kang", "Seongwon Cho", "Jonghyun Choi"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2602.04208"
doi: "10.48550/arXiv.2602.04208"
tags: [paper, embodied-ai, "cs.AI", "cs.LG", "cs.RO"]
status: unread
rating:
created: 2026-09-01
---

# SCALE: Self-uncertainty Conditioned Adaptive Looking and Execution for Vision-Language-Action Models

> Hyeonbeom Choi, Daechul Ahn, Youhan Lee, Taewook Kang, Seongwon Cho, Jonghyun Choi · 2026
> [arXiv](https://arxiv.org/abs/2602.04208) · [PDF](https://arxiv.org/pdf/2602.04208)

## Abstract

Vision-Language-Action (VLA) models have emerged as a promising paradigm for general-purpose robotic control, with test-time scaling (TTS) gaining attention to enhance robustness beyond training. However, existing TTS methods for VLAs require additional training, verifiers, and multiple forward passes, making them impractical for deployment. Moreover, they intervene only at action decoding while keeping visual representations fixed-insufficient under perceptual ambiguity, where reconsidering how to perceive is as important as deciding what to do. To address these limitations, we propose SCALE, a simple inference strategy that jointly modulates visual perception and action based on 'self-uncertainty', inspired by uncertainty-driven exploration in Active Inference theory-requiring no additional training, no verifier, and only a single forward pass. SCALE broadens exploration in both perception and action under high uncertainty, while focusing on exploitation when confident-enabling adaptive execution across varying conditions. Experiments on simulated and real-world benchmarks demonstrate that SCALE improves state-of-the-art VLAs and outperforms existing TTS methods while maintaining single-pass efficiency.

## TL;DR

Vision-Language-Action (VLA) models have emerged as a promising paradigm for general-purpose robotic control, with test-time scaling (TTS) gaining attention to enhance robustness beyond training. However, existing TTS methods for VLAs require additional training, verifiers, and multiple forward passes, making them impractical for deployment.

## Related
<!-- [[other-paper-citekey]] -->
