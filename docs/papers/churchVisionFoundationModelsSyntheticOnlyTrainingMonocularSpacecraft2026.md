---
citekey: "churchVisionFoundationModelsSyntheticOnlyTrainingMonocularSpacecraft2026"
title: "Vision Foundation Models with Synthetic-Only Training for Monocular Spacecraft Pose Estimation"
authors: ["John Church", "Vazghen Nikolian"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.26561"
doi: "10.48550/arXiv.2609.26561"
tags: [paper, embodied-ai, "cs.CV", "cs.RO"]
status: unread
rating:
created: 2026-09-24
---

# Vision Foundation Models with Synthetic-Only Training for Monocular Spacecraft Pose Estimation

> John Church, Vazghen Nikolian · 2026
> [arXiv](https://arxiv.org/abs/2609.26561) · [PDF](https://arxiv.org/pdf/2609.26561)

## Abstract

We present an improvement on previous spacecraft pose estimation architectures that results in the lowest published mean rotation errors we know of on the SPEED+ lightbox and sunlamp test sets for a known, non-cooperative spacecraft. By using a previously established heatmap-based pose estimation architecture and adapting a large self-supervised ViT foundation model (DINOv3) in place of the smaller convolutional and ViT encoders of previous work, we show that pose estimation accuracy improves from 300M to 840M parameters with no saturation yet observed. We also evaluate our 840M model on a Jetson Orin NX 16GB, measuring single-pass network inference at 133.8 ms per crop with a board draw of 32.0 W. These measurements demonstrate embedded inference feasibility on a processor family with orbital flight heritage. Our resulting model outperforms previous models across lightbox and sunlamp domains while training only on synthetic data. Our best model, using DINOv3 840M adapted with LoRA as the encoder (rank 64, three-seed ensemble with four-rotation test-time augmentation), results in $1.56^\circ$ mean rotation error on sunlamp and $1.17^\circ$ on lightbox, compared to the previous best mean rotation errors we know of on these test sets, $2.66^\circ$ and $1.75^\circ$ by EagerNet.

## TL;DR

We present an improvement on previous spacecraft pose estimation architectures that results in the lowest published mean rotation errors we know of on the SPEED+ lightbox and sunlamp test sets for a known, non-cooperative spacecraft. By using a previously established heatmap-based pose estimation architecture and adapting a large self-supervised ViT foundation model (DINOv3) in place of the smaller convolutional and ViT encoders of previous work, we show that pose estimation accuracy improves from 300M to 840M parameters with no saturation yet observed.

## Related
<!-- [[other-paper-citekey]] -->
