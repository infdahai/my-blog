---
citekey: "gottamInfiNoVAInfiniteNovelViewAugmentationViewpointInvariantPolicies2026"
title: "InfiNoVA: Infinite Novel View Augmentation for Viewpoint Invariant Robot Policies"
authors: ["Sai Puneeth Reddy Gottam", "Elmar Rueckert", "Vedant Dave"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.27734"
doi: "10.48550/arXiv.2609.27734"
tags: [paper, embodied-ai, "cs.AI", "cs.RO"]
status: unread
rating:
created: 2026-09-25
---

# InfiNoVA: Infinite Novel View Augmentation for Viewpoint Invariant Robot Policies

> Sai Puneeth Reddy Gottam, Elmar Rueckert, Vedant Dave · 2026
> [arXiv](https://arxiv.org/abs/2609.27734) · [PDF](https://arxiv.org/pdf/2609.27734)

## Abstract

Vision-Language-Action (VLA) policies often rely strongly on the camera viewpoints seen during training, causing substantial performance degradation when deployed from unseen perspectives. Collecting demonstrations from sufficiently diverse physical viewpoints is expensive and still provides only sparse coverage of the viewpoint space. We introduce InfiNoVA, a data-augmentation framework that converts synchronized multi-camera demonstrations into a dense distribution of geometrically consistent training views. InfiNoVA reconstructs each manipulation trajectory as a time-varying 3D Gaussian representation and renders novel observations from sampled camera poses while preserving the original state-action correspondence. This explicit scene representation improves frame-level fidelity and temporal consistency while reducing task-critical hallucinations observed in generative novel-view synthesis. Across four real-world manipulation tasks, policies trained with InfiNoVA achieve 5.4x higher average success under unseen randomized viewpoints than both VISTA-based augmentation and the unaugmented policy. InfiNoVA further achieves 1.7x higher success than training directly on all five physical camera views. These results show that dense, geometrically grounded viewpoint augmentation provides a practical route toward camera-robust robot policies without modifying the underlying policy architecture.

## TL;DR

Vision-Language-Action (VLA) policies often rely strongly on the camera viewpoints seen during training, causing substantial performance degradation when deployed from unseen perspectives. Collecting demonstrations from sufficiently diverse physical viewpoints is expensive and still provides only sparse coverage of the viewpoint space.

## Related
<!-- [[other-paper-citekey]] -->
