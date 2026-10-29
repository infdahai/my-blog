---
citekey: "heReconstructionAugmentedVisuomotorPreTraining3DGroundedBimanual2026"
title: "Reconstruction-Augmented Visuomotor Pre-Training of 3D-Grounded Bimanual Dexterity from RGB-Only Human Videos"
authors: ["Xingyi He", "Zhiwen Qiu", "Adhitya Polavaram", "Yunhao Cao", "Cory Fan", "Julius Samwer", "Saleh Kalantari", "Kuan Fang"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.29716"
doi: "10.48550/arXiv.2610.29716"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-23
---

# Reconstruction-Augmented Visuomotor Pre-Training of 3D-Grounded Bimanual Dexterity from RGB-Only Human Videos

> Xingyi He, Zhiwen Qiu, Adhitya Polavaram, Yunhao Cao, Cory Fan, Julius Samwer, Saleh Kalantari, Kuan Fang · 2026
> [arXiv](https://arxiv.org/abs/2610.29716) · [PDF](https://arxiv.org/pdf/2610.29716)

## Abstract

We present SpatialDex, a framework that learns 3D-grounded bimanual dexterity from RGB-only human videos through reconstruction-augmented visuomotor pre-training. The central idea is to learn human behavior together with its spatial context. From each video, we reconstruct the scene geometry and estimate the hand motion, align them at a shared video-level scale using the hand-size prior of 3D hand estimates. We retain the reconstructed geometry as both a policy input and a prediction target. The policy grounds the token grid of a pre-trained vision-language model in this geometry through gated residual fusion, is trained to predict future scene geometry alongside wrist and finger actions, and generates finger motion conditioned on the predicted trajectories of both wrists. Pre-trained on 1M human-video clips and fine-tuned with a small number of robot demonstrations, SpatialDex outperforms the state-of-the-art methods by 16.5 points on nine simulated dexterous tasks across two embodiments and by 38.3 points on six real-world bimanual dexterous tasks. Under a matched comparison, pre-training with reconstructed geometry improves success by 14.2 points over pre-training on hand motion alone.

## TL;DR

We present SpatialDex, a framework that learns 3D-grounded bimanual dexterity from RGB-only human videos through reconstruction-augmented visuomotor pre-training. The central idea is to learn human behavior together with its spatial context.

## Related
<!-- [[other-paper-citekey]] -->
