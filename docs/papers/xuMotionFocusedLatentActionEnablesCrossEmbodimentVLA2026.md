---
citekey: "xuMotionFocusedLatentActionEnablesCrossEmbodimentVLA2026"
title: "Motion-Focused Latent Action Enables Cross-Embodiment VLA Training from Human EgoVideos"
authors: ["Runze Xu", "Yiluo Zhang", "Jian Wang", "Yu Wang", "Jincheng Yu"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2606.18955"
doi: "10.48550/arXiv.2606.18955"
tags: [paper, embodied-ai, "cs.CV", "cs.RO"]
status: unread
rating:
created: 2026-08-27
---

# Motion-Focused Latent Action Enables Cross-Embodiment VLA Training from Human EgoVideos

> Runze Xu, Yiluo Zhang, Jian Wang, Yu Wang, Jincheng Yu · 2026
> [arXiv](https://arxiv.org/abs/2606.18955) · [PDF](https://arxiv.org/pdf/2606.18955)

## Abstract

Training generalist Vision-Language-Action(VLA) models typically requires massive, diverse robotic datasets with high-fidelity action annotations. While egocentric human manipulation videos are abundant and capture significant environmental diversity, the absence of action labels makes them difficult to use in conventional training paradigms. To address this, we propose a latent-action-based framework designed to extract general action priors from unlabeled human videos. The architecture features a Hybrid Disentangled VQ-VAE that decouples motion dynamics from environmental backgrounds through physical masks, enabling the construction of a cross-embodiment action codebook. By pre-training on human videos with the codebook, the VLM backbone learns deep representations of action intent. For adaptation to specific embodiments, we introduce an intent-perception decoupling strategy where the VLM predicts the action intent while a separate frozen visual encoder provides state-specific features to the action expert, thereby reducing action hallucinations. Results in simulation and real-world environments show that our method, pre-trained exclusively on unlabeled human videos, performs competitively with state-of-the-art VLA models trained on massive annotated datasets, requiring only 50 trajectories for downstream adaptation.

## TL;DR

Training generalist Vision-Language-Action(VLA) models typically requires massive, diverse robotic datasets with high-fidelity action annotations. While egocentric human manipulation videos are abundant and capture significant environmental diversity, the absence of action labels makes them difficult to use in conventional training paradigms.

## Related
<!-- [[other-paper-citekey]] -->
