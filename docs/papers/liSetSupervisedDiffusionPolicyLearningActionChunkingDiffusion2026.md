---
citekey: "liSetSupervisedDiffusionPolicyLearningActionChunkingDiffusion2026"
title: "Set-Supervised Diffusion Policy: Learning Action-Chunking Diffusion through Corrections"
authors: ["Zhaoting Li", "Gang Chen", "Javier Alonso-Mora", "Cosimo Della Santina", "Jens Kober"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2606.01865"
doi: "10.48550/arXiv.2606.01865"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-08-27
---

# Set-Supervised Diffusion Policy: Learning Action-Chunking Diffusion through Corrections

> Zhaoting Li, Gang Chen, Javier Alonso-Mora, Cosimo Della Santina, Jens Kober · 2026
> [arXiv](https://arxiv.org/abs/2606.01865) · [PDF](https://arxiv.org/pdf/2606.01865)

## Abstract

Diffusion policies have recently emerged as a powerful framework for robotic manipulation. However, like other behavior cloning methods, they remain vulnerable to distributional shift, often requiring human-in-the-loop interventions to correct failures during deployment. These interactions naturally provide paired supervision in the form of the robot's undesired actions and the human teacher's corrective actions. Yet existing data aggregation pipelines and standard behavior cloning losses largely ignore this negative signal from undesired actions, leading to overfitting to teacher's actions and an increasing reliance on costly expert data. To address this limitation, we propose Set-Supervised Diffusion Policy (SDP), a novel learning framework that utilizes contrastive action-chunk data to train diffusion policies from human corrections. From paired positive and negative action-chunks, SDP constructs a set of desired action-chunks and designs a training pipeline that encourages the diffusion policy to align with the set. Through extensive experiments across multiple robotic manipulation tasks, we demonstrate that SDP consistently improves policy performance, with particularly strong gains in robustness to noisy data. Moreover, SDP induces high-quality aggregated datasets, enabling more efficient and reliable policy learning from human-in-the-loop corrections. Our code is available at https://set-supervised-diffusion-policy.github.io/.

## TL;DR

Diffusion policies have recently emerged as a powerful framework for robotic manipulation. However, like other behavior cloning methods, they remain vulnerable to distributional shift, often requiring human-in-the-loop interventions to correct failures during deployment.

## Related
<!-- [[other-paper-citekey]] -->
