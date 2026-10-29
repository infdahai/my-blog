---
citekey: "liuGALAGeometryAwareLatentActionModelingVisionLanguage2026"
title: "GALA: Geometry-Aware Latent Action Modeling for Vision-Language-Action Model Pretraining across Embodiments"
authors: ["Yichen Liu", "Puzhen Yuan", "Xiang Zhu", "Yanjiang Guo", "Jianyu Chen"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.21948"
doi: "10.48550/arXiv.2609.21948"
tags: [paper, embodied-ai, "cs.CV", "cs.RO"]
status: unread
rating:
created: 2026-09-22
---

# GALA: Geometry-Aware Latent Action Modeling for Vision-Language-Action Model Pretraining across Embodiments

> Yichen Liu, Puzhen Yuan, Xiang Zhu, Yanjiang Guo, Jianyu Chen · 2026
> [arXiv](https://arxiv.org/abs/2609.21948) · [PDF](https://arxiv.org/pdf/2609.21948)

## Abstract

Learning large-scale vision-language-action (VLA) models from multi-embodiment datasets remains challenging due to heterogeneous action spaces across end effectors. Although latent action models (LAMs) can learn embodiment-agnostic action representations from diverse video data, existing image-based LAMs often fail to capture fine-grained end-effector articulation, particularly finger-level geometric changes in human and dexterous robot hands. To address this limitation, we propose GALA, a Geometry-Aware Latent-Action modeling framework that augments image-based latent actions with 3D end-effector geometric motion. However, naively incorporating point clouds yields fine-grained action representations with limited shared semantics, hindering cross-embodiment pretraining. To address this issue, we introduce the Unified End-effector Motion Representation (UEMR), which preserves fine-grained motion information while improving the cross-embodiment generalizability of latent actions. Building upon UEMR, GALA combines visual latent actions that capture scene-level dynamics with geometric latent actions that capture shared fine-grained end-effector articulation, providing effective supervision for VLA pretraining from multi-embodiment data, including action-free ego-centric human videos. Experiments on fine-grained motion probing, cross-embodiment retrieval, and downstream VLA evaluation demonstrate GALA's effectiveness in modeling generalizable fine-grained motions across embodiments, achieving 68.3% RoboCasa-GR1 success rate and 75.5% real-world success rate. Code, appendix, and demos are available at https://puzhenyuan.github.io/GALA-website/.

## TL;DR

Learning large-scale vision-language-action (VLA) models from multi-embodiment datasets remains challenging due to heterogeneous action spaces across end effectors. Although latent action models (LAMs) can learn embodiment-agnostic action representations from diverse video data, existing image-based LAMs often fail to capture fine-grained end-effector articulation, particularly finger-level geometric changes in human and dexterous robot hands.

## Related
<!-- [[other-paper-citekey]] -->
