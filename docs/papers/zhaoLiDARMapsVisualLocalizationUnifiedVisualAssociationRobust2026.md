---
citekey: "zhaoLiDARMapsVisualLocalizationUnifiedVisualAssociationRobust2026"
title: "From LiDAR Maps to Visual Localization: Unified Visual Association for Robust Point-Line-Plane Pose Estimation"
authors: ["Wentao Zhao", "Zikun Chen", "Yihe Niu", "Haoyu Chen", "Jingchuan Wang"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.27363"
doi: "10.48550/arXiv.2609.27363"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-25
---

# From LiDAR Maps to Visual Localization: Unified Visual Association for Robust Point-Line-Plane Pose Estimation

> Wentao Zhao, Zikun Chen, Yihe Niu, Haoyu Chen, Jingchuan Wang · 2026
> [arXiv](https://arxiv.org/abs/2609.27363) · [PDF](https://arxiv.org/pdf/2609.27363)

## Abstract

Camera localization in a prior LiDAR map provides a persistent geometric reference for long-term robotic navigation, yet remains challenging because of the substantial modality gap between camera images and point-cloud maps. We present a unified localization framework that makes the LiDAR map visually addressable rather than relying on a dedicated image-LiDAR correspondence model. Map geometry and reflectivity are rendered into LiDAR-derived quasi-images with explicit 2D-3D provenance, enabling camera observations and rendered map views to share mature visual features and matchers for both global localization and continuous pose tracking. Point and line correspondences are established through this common visual interface, while the retained provenance recovers metric LiDAR geometry and line-supported planar constraints for pose estimation. To improve robustness under ambiguous associations and weak geometry, we further introduce a distribution-aware, observability-complementary optimization strategy. Instead of reducing matching ambiguity to a scalar confidence, candidate association distributions are propagated into directional pose-information uncertainty, and reliable structural factors are selectively reinforced according to their ability to complement the currently weak pose directions. Experiments on the EuRoC MAV benchmark and self-collected real-world sequences demonstrate accurate global localization and robust continuous 6-DoF tracking using only a pre-built LiDAR map as the persistent prior, including under severe illumination variations and dynamic occlusions.

## TL;DR

Camera localization in a prior LiDAR map provides a persistent geometric reference for long-term robotic navigation, yet remains challenging because of the substantial modality gap between camera images and point-cloud maps. We present a unified localization framework that makes the LiDAR map visually addressable rather than relying on a dedicated image-LiDAR correspondence model.

## Related
<!-- [[other-paper-citekey]] -->
