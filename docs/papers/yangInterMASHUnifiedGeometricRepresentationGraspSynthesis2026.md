---
citekey: "yangInterMASHUnifiedGeometricRepresentationGraspSynthesis2026"
title: "InterMASH: A Unified Geometric Representation for Grasp Synthesis"
authors: ["Xuanze Yang", "Yumeng Liu", "Haiyang Xin", "Changhao Li", "Haowei Shen", "Kai Xu", "Ligang Liu", "Ruizhen Hu"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.18504"
doi: "10.48550/arXiv.2609.18504"
tags: [paper, embodied-ai, "cs.GR", "cs.RO"]
status: unread
rating:
created: 2026-09-17
---

# InterMASH: A Unified Geometric Representation for Grasp Synthesis

> Xuanze Yang, Yumeng Liu, Haiyang Xin, Changhao Li, Haowei Shen, Kai Xu, Ligang Liu, Ruizhen Hu · 2026
> [arXiv](https://arxiv.org/abs/2609.18504) · [PDF](https://arxiv.org/pdf/2609.18504)

## Abstract

Grasp synthesis aims to generate stable and physically plausible hand--object interactions, and has become a fundamental problem in both human hand modeling and robotic manipulation. However, a unified representation across human and robotic hands is still lacking, mainly due to differences in hand morphology and surface modeling. Prior methods typically rely on either contact maps or dense implicit descriptors to represent interaction, but these representations are often incomplete or computationally expensive and redundant. We propose InterMASH, a unified geometric representation that establishes cross-embodiment correspondence using sphere-fixed anchors. At each anchor, low-degree spherical harmonics compactly encode local hand geometry, object geometry, and contact, forming an explicit and interpretable token sequence. Building on this natively tokenized structure, we introduce a conditional Diffusion Transformer that operates directly in the proposed InterMASH representation space and jointly generates hand geometry and contact, improving consistency and physical plausibility. Our method achieves competitive performance with state-of-the-art methods on key physical feasibility metrics in a large-scale ShadowHand benchmark, supports joint training across multiple hands, and shows that cross-embodiment fine-tuning with human grasp data can improve robotic grasp success and diversity. Project page is available at https://inter-mash.github.io/.

## TL;DR

Grasp synthesis aims to generate stable and physically plausible hand--object interactions, and has become a fundamental problem in both human hand modeling and robotic manipulation. However, a unified representation across human and robotic hands is still lacking, mainly due to differences in hand morphology and surface modeling.

## Related
<!-- [[other-paper-citekey]] -->
