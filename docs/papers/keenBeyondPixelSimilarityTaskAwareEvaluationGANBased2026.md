---
citekey: "keenBeyondPixelSimilarityTaskAwareEvaluationGANBased2026"
title: "Beyond Pixel Similarity: Task-Aware Evaluation of GAN-Based Synthetic Sonar Data for Robotic Perception"
authors: ["Hannan Ejaz Keen", "Muhammad Moazam Fraz", "Karsten Berns"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.18100"
doi: "10.48550/arXiv.2609.18100"
tags: [paper, embodied-ai, "cs.CV", "cs.LG", "cs.RO"]
status: unread
rating:
created: 2026-09-17
---

# Beyond Pixel Similarity: Task-Aware Evaluation of GAN-Based Synthetic Sonar Data for Robotic Perception

> Hannan Ejaz Keen, Muhammad Moazam Fraz, Karsten Berns · 2026
> [arXiv](https://arxiv.org/abs/2609.18100) · [PDF](https://arxiv.org/pdf/2609.18100)

## Abstract

Synthetic data can reduce the cost of collecting and annotating training data for robotic perception, but generating sensor observations that preserve the characteristics relevant to downstream perception remains challenging, particularly for sonar imagery. In this work, we investigate whether conventional image-fidelity metrics adequately reflect the downstream perception performance of GAN-generated synthetic sonar data. We employ a Pix2Pix conditional generative adversarial network with four discriminator configurations characterized by different receptive fields: PixelGAN, PatchGAN-16, PatchGAN-70, and ImageGAN. The models are trained using sonar imagery from two datasets and evaluated using conventional image-fidelity metrics, including Structural Similarity Index (SSIM), Peak Signal-to-Noise Ratio (PSNR), and Mean Squared Error (MSE). To complement these pixel-level measures with task-oriented evaluation, YOLOX-S, YOLOX-L, and Faster R-CNN detectors are trained exclusively on real sonar imagery and subsequently evaluated on the GAN-generated images using identical test samples and annotations across all discriminator configurations. The results reveal a discrepancy between image-fidelity and downstream object-detection performance: the configuration achieving the best SSIM, PSNR, and MSE does not consistently yield the best detection performance. In particular, PatchGAN configurations achieve strong downstream detection results despite not achieving the highest pixel-level similarity scores. These findings suggest, for the datasets and models considered, pixel-level image-fidelity metrics alone may not consistently capture the task-relevant realism of synthetic sonar observations and motivate the use of task-aware evaluation for synthetic sensor data intended for robotic perception.

## TL;DR

Synthetic data can reduce the cost of collecting and annotating training data for robotic perception, but generating sensor observations that preserve the characteristics relevant to downstream perception remains challenging, particularly for sonar imagery. In this work, we investigate whether conventional image-fidelity metrics adequately reflect the downstream perception performance of GAN-generated synthetic sonar data.

## Related
<!-- [[other-paper-citekey]] -->
