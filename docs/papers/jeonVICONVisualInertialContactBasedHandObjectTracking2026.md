---
citekey: "jeonVICONVisualInertialContactBasedHandObjectTracking2026"
title: "VICON: Visual-Inertial-Contact based Hand-Object Tracking for Manipulation Datasets"
authors: ["Yubin Jeon", "Uiseong Shin", "Hwanchul La", "Jaeseong Kang", "Hyelim Choi", "Yongseok Lee"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.05180"
doi: "10.48550/arXiv.2610.05180"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-07
---

# VICON: Visual-Inertial-Contact based Hand-Object Tracking for Manipulation Datasets

> Yubin Jeon, Uiseong Shin, Hwanchul La, Jaeseong Kang, Hyelim Choi, Yongseok Lee · 2026
> [arXiv](https://arxiv.org/abs/2610.05180) · [PDF](https://arxiv.org/pdf/2610.05180)

## Abstract

Learning dexterous manipulation benefits from human demonstration datasets that capture diverse and natural hand-object interactions. In particular, contact points and forces provide supervision on where and how strongly to interact, which cannot be fully captured by motion trajectories alone. However, methods for jointly capturing hand and object motion, contact points, and forces remain limited. Moreover, severe occlusion from hand-object interaction challenges accurate tracking of both hands and objects. To address these limitations, we present a Visual-Inertial-CONtact based hand-object tracking (VICON) framework. It holistically captures both hand and object motion along with contact information during manipulation, even under severe occlusion. First, we adopt a visual-inertial glove and an RGB-D camera for accurate hand tracking, and redesign the glove to incorporate contact sensing. Specifically, force-sensitive resistors (FSRs) are placed on the glove based on human grasp frequency to synchronously record contact states and calibrated normal forces. Second, without requiring pre-existing CAD models, we estimate object poses using RGB-D images and a mesh reconstructed from a monocular video. We propose factor-graph-based object trajectory estimation that fuses object-pose estimates weighted by visibility under hand-object occlusion, FSR measurements, and a hand-motion prior. Across 40 motion-capture sessions with five objects, VICON achieves a 2.5% failed-frame rate compared with 50.9-64.6% for the baselines, with median errors of 3.9 mm and 3.0 degrees under occlusion. Using VICON, we construct a dataset containing synchronized hand-object motion, contact points, and normal forces, and will publicly release an expanded dataset covering 10 object categories at https://github.com/VICON-dataset/dataset.

## TL;DR

Learning dexterous manipulation benefits from human demonstration datasets that capture diverse and natural hand-object interactions. In particular, contact points and forces provide supervision on where and how strongly to interact, which cannot be fully captured by motion trajectories alone.

## Related
<!-- [[other-paper-citekey]] -->
