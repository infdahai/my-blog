---
citekey: "zhaoLightVLNEfficientAerialVisionLanguageNavigationCompactMemory2026"
title: "LightVLN: Efficient Aerial Vision-and-Language Navigation with Compact Memory and History-Guided Local Aggregation"
authors: ["Yiming Zhao", "Tianshun Li", "Jingle He", "Ruonan Chai", "Xinhu Zheng"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.05024"
doi: "10.48550/arXiv.2610.05024"
tags: [paper, embodied-ai, "cs.CV", "cs.RO"]
status: unread
rating:
created: 2026-10-08
---

# LightVLN: Efficient Aerial Vision-and-Language Navigation with Compact Memory and History-Guided Local Aggregation

> Yiming Zhao, Tianshun Li, Jingle He, Ruonan Chai, Xinhu Zheng · 2026
> [arXiv](https://arxiv.org/abs/2610.05024) · [PDF](https://arxiv.org/pdf/2610.05024)

## Abstract

Aerial vision-and-language navigation (VLN) enables unmanned aerial vehicles to execute long-horizon natural-language instructions from visual observations in complex three-dimensional environments. However, recent aerial VLN models often rely on large-scale vision-language backbones and dense visual histories, imposing substantial computation and memory costs that hinder onboard deployment. We propose LightVLN, a lightweight history-aware aerial VLN framework that combines a compact 0.5B language backbone with compact representations of both historical and current observations. LightVLN compresses each historical frame into a single token using visual features already computed by the policy. It further introduces history- and instruction-conditioned local aggregation to reduce the current observation from 256 to 32 visual tokens while preserving navigation-relevant spatial information. With up to 16 historical frames, the policy uses at most 48 observation-derived tokens. On the public OpenFly dataset, LightVLN achieves 50.93% Test-Seen and 36.14% Test-Unseen success rates (SR), outperforming the evaluated 7B language-backbone baselines on most reported metrics. It also achieves 25.83% SR on AerialVLN-S Val-Seen. In a reconstructed unseen campus, we deploy LightVLN on a DJI M350 RTK with an external Jetson Orin NX 16 GB for closed-loop onboard-compute real-to-sim hardware-in-the-loop (HIL) evaluation, achieving 14.61 Hz model inference and 11.13 Hz end-to-end decision updates. These results demonstrate the effectiveness and efficiency of LightVLN for aerial navigation.

## TL;DR

Aerial vision-and-language navigation (VLN) enables unmanned aerial vehicles to execute long-horizon natural-language instructions from visual observations in complex three-dimensional environments. However, recent aerial VLN models often rely on large-scale vision-language backbones and dense visual histories, imposing substantial computation and memory costs that hinder onboard deployment.

## Related
<!-- [[other-paper-citekey]] -->
