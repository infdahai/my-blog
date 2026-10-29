---
citekey: "bergerDearLLaVAPleaseDriveDepthAwareVisionLanguage2026"
title: "\"Dear LLaVA, Please Drive\": A Depth-Aware Vision-Language Agent for Closed-Loop Robotic Control"
authors: ["Sebastian Berger", "Katharina Winter", "Fabian B. Flohr"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.22925"
doi: "10.48550/arXiv.2609.22925"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-22
---

# "Dear LLaVA, Please Drive": A Depth-Aware Vision-Language Agent for Closed-Loop Robotic Control

> Sebastian Berger, Katharina Winter, Fabian B. Flohr · 2026
> [arXiv](https://arxiv.org/abs/2609.22925) · [PDF](https://arxiv.org/pdf/2609.22925)

## Abstract

Vision-language models (VLMs) provide a compelling foundation for reasoning-driven mobile navigation, offering rich contextual understanding and strong generalization from large-scale pretraining. Most existing navigation frameworks rely on imitation learning and therefore require substantial labeled trajectory data, limiting their scalability and robustness. In this work, we propose a parameter-efficient approach to fine-tune a pretrained VLM for autonomous navigation using an Imperative Learning paradigm. By optimizing against differentiable geometric cost fields rather than labeled trajectories, our model learns to generate collision-free paths exclusively from stereoscopic depth observations. We introduce a unified end-to-end navigation pipeline for natural-language-driven robotic control. This system leverages a shared VLM backbone with task-specific Low-Rank Adaptation (LoRA) modules, effectively bridging the gap from semantic target selection to low-level trajectory planning. Our approach achieves competitive Success weighted by Path Length (SPL) in unseen environments while updating less than 1% of the model's total parameters. Qualitative real-world experiments validate sim-to-real generalization and stable path planning without fine-tuning on real-world data. These results highlight a practical approach for deploying VLM-based agents on mobile robots, enabling high-level semantic navigation without the prohibitive requirement for large-scale, labeled trajectory data.

## TL;DR

Vision-language models (VLMs) provide a compelling foundation for reasoning-driven mobile navigation, offering rich contextual understanding and strong generalization from large-scale pretraining. Most existing navigation frameworks rely on imitation learning and therefore require substantial labeled trajectory data, limiting their scalability and robustness.

## Related
<!-- [[other-paper-citekey]] -->
