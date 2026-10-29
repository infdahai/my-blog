---
citekey: "zhangNIDARNIRGuidedIntrinsicDecompositionScalableSceneAgnostic2026"
title: "NIDAR: NIR-Guided Intrinsic Decomposition for Scalable Scene-Agnostic LiDAR Intensity Reconstruction"
authors: ["Junjie Zhang", "Jie Yin", "Kefei Qian", "Jie Li", "Mengpei Jia", "Yajuan Dun", "Wenbo Chu", "Guofa Li"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.36878"
doi: "10.48550/arXiv.2609.36878"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-30
---

# NIDAR: NIR-Guided Intrinsic Decomposition for Scalable Scene-Agnostic LiDAR Intensity Reconstruction

> Junjie Zhang, Jie Yin, Kefei Qian, Jie Li, Mengpei Jia, Yajuan Dun, Wenbo Chu, Guofa Li · 2026
> [arXiv](https://arxiv.org/abs/2609.36878) · [PDF](https://arxiv.org/pdf/2609.36878)

## Abstract

LiDAR return intensity provides complementary surface-response cues for robotic perception and state estimation, yet many simulation pipelines omit it or reproduce it using reconstruction methods that require real intensity supervision and per-scene optimization. These requirements increase data-collection and fitting costs and limit reuse across simulated scenes. We present NIDAR, a feed-forward framework that synthesizes dense intensity-like observations from RGB appearance and simulator geometry. NIDAR combines pretrained pseudo-NIR translation, hierarchical intrinsic decomposition, geometry-aware modulation, and source-domain distribution calibration to transfer reflectance-related image cues to simulated point clouds. Its learned components are trained offline using Waymo data; their weights and calibration remain fixed during evaluation on Waymo and nuScenes. Deployment therefore requires neither target-scene intensity labels nor target-scene gradient-based fitting. The reported comparisons show competitive pixel-wise accuracy and favorable structural and perceptual fidelity against the evaluated reconstruction baselines. A controlled pseudo-NIR-versus-RGB diagnostic further shows that the pseudo-NIR prior is most beneficial when used through the paper-aligned reflectance-and-remapping route, rather than as a simple direct intensity regressor. We further integrate NIDAR with Unreal Engine 5, Isaac Sim, and a generative LiDAR pipeline. Two intensity-aware SLAM systems evaluated in two simulated indoor scenes suggest potential downstream utility, but do not constitute real-robot validation. NIDAR therefore offers a scalable intensity-synthesis interface for the evaluated settings; cross-wavelength, camera-configuration, embedded, and real-sensor validation remain future work.

## TL;DR

LiDAR return intensity provides complementary surface-response cues for robotic perception and state estimation, yet many simulation pipelines omit it or reproduce it using reconstruction methods that require real intensity supervision and per-scene optimization. These requirements increase data-collection and fitting costs and limit reuse across simulated scenes.

## Related
<!-- [[other-paper-citekey]] -->
