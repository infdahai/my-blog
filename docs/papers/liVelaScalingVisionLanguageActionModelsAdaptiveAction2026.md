---
citekey: "liVelaScalingVisionLanguageActionModelsAdaptiveAction2026"
title: "Vela: Scaling Vision-Language-Action Models with Adaptive Action Curve Parametrization"
authors: ["Yifan Li", "Jiaxu Wang", "Dongming Wu", "Yicheng Jiang", "Ryan Ji", "Xiangyu Yue", "Yanwei Fu"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.05230"
doi: "10.48550/arXiv.2610.05230"
tags: [paper, embodied-ai, "cs.AI", "cs.RO"]
status: unread
rating:
created: 2026-10-07
---

# Vela: Scaling Vision-Language-Action Models with Adaptive Action Curve Parametrization

> Yifan Li, Jiaxu Wang, Dongming Wu, Yicheng Jiang, Ryan Ji, Xiangyu Yue, Yanwei Fu · 2026
> [arXiv](https://arxiv.org/abs/2610.05230) · [PDF](https://arxiv.org/pdf/2610.05230)

## Abstract

Most vision-language-action models represent future motion as fixed-rate action chunks, tying temporal resolution and prediction horizon to a fixed output budget. This pointwise representation wastes capacity on highly correlated neighboring actions, leaves temporal continuity and smoothness to be learned implicitly, and forces a tradeoff between long-horizon coverage and the local precision required for contact-rich manipulation. To address these limitations, we introduce Vela, a vision-language-action foundation model that represents future robot behavior as continuous trajectories. Vela combines a compact spline-based action representation with motion-dependent temporal support and a shared action interface for heterogeneous embodiments, allowing a fixed output budget to adapt its temporal resolution across motions. We pretrain Vela on large-scale multi-embodiment robot data and evaluate it on LIBERO-X, EBench, and two real-world long-horizon tasks, egg-cake cooking and potato shredding, obtaining promising results across simulation and physical manipulation. These results highlight the potential of continuous action representations as a foundation for future embodied foundation models. Project page and more results: https://clementine24.github.io/Vela/ .

## TL;DR

Most vision-language-action models represent future motion as fixed-rate action chunks, tying temporal resolution and prediction horizon to a fixed output budget. This pointwise representation wastes capacity on highly correlated neighboring actions, leaves temporal continuity and smoothness to be learned implicitly, and forces a tradeoff between long-horizon coverage and the local precision required for contact-rich manipulation.

## Related
<!-- [[other-paper-citekey]] -->
