---
citekey: "zhuMINTUnifiedModelWorldSpaceCameraHandMotion2026"
title: "MINT: A Unified Model for World-Space Camera and Hand Motion Estimation from Scalable Egocentric Pipeline Supervision"
authors: ["Zijie Zhu", "Weiren Cai", "Yizhou Wang", "Zhenjie Yang", "Yide Liu", "Jiahao Chen", "Guanqi He"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.04958"
doi: "10.48550/arXiv.2609.04958"
tags: [paper, embodied-ai, "cs.CV", "cs.RO"]
status: unread
rating:
created: 2026-09-08
---

# MINT: A Unified Model for World-Space Camera and Hand Motion Estimation from Scalable Egocentric Pipeline Supervision

> Zijie Zhu, Weiren Cai, Yizhou Wang, Zhenjie Yang, Yide Liu, Jiahao Chen, Guanqi He · 2026
> [arXiv](https://arxiv.org/abs/2609.04958) · [PDF](https://arxiv.org/pdf/2609.04958)

## Abstract

Recovering camera and hand motion in world coordinates from egocentric video is a key capability for activity understanding, robot learning, and augmented reality. Existing systems typically decompose this problem into separate stages for camera motion, depth, hand reconstruction, and trajectory refinement, resulting in substantial computational overhead and preventing the joint modeling of camera and hand motion. We introduce MINT (Minting IN-the-Wild Trajectories), the first foundation model that directly produces complete world-space two-hand trajectories from ego-centric RGB video. From a single shared spatiotemporal video representation, MINT jointly predicts the camera trajectory, camera-frame hand states, and per-frame hand presence, and then produces world-space hand motion via explicit coordinate transformations. Training such a model at scale is challenging, since paired world-space camera and hand annotations are scarce. We therefore develop an open-source labeling EGOPIPELINE that converts large collections of public egocentric videos into structured camera-and-hand trajectory supervision. MINT is first pretrained on these large-scale pseudo-labels and then fine-tuned on a small set of high-quality joint annotations. Across public benchmarks, MINT achieves [xxx] improvement in world-space hand trajectory accuracy, [xxx] improvement in camera trajectory estimation, and [xxx] faster end-to-end trajectory generation than the labeling pipeline, while generalizing zero-shot to unseen egocentric datasets. We release the model, training and inference code, labeling pipeline, and a curated 1,021-hour egocentric trajectory dataset.

## TL;DR

Recovering camera and hand motion in world coordinates from egocentric video is a key capability for activity understanding, robot learning, and augmented reality. Existing systems typically decompose this problem into separate stages for camera motion, depth, hand reconstruction, and trajectory refinement, resulting in substantial computational overhead and preventing the joint modeling of camera and hand motion.

## Related
<!-- [[other-paper-citekey]] -->
