---
citekey: "yuanJEPLOJointEmbeddingPredictiveLearningLiDARBasedLegged2026"
title: "JEPLO: Joint-Embedding Predictive Learning for LiDAR-Based Legged Locomotion"
authors: ["Qihao Yuan", "Yixuan Qiu", "Ziyu Cao", "Ming Cao", "Kailai Li"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.15770"
doi: "10.48550/arXiv.2609.15770"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-16
---

# JEPLO: Joint-Embedding Predictive Learning for LiDAR-Based Legged Locomotion

> Qihao Yuan, Yixuan Qiu, Ziyu Cao, Ming Cao, Kailai Li · 2026
> [arXiv](https://arxiv.org/abs/2609.15770) · [PDF](https://arxiv.org/pdf/2609.15770)

## Abstract

Light detection and ranging (LiDAR) remains less explored than RGB-D sensing for perceptive legged locomotion, and existing LiDAR-based approaches often rely on explicit mapping. We present JEPLO (Joint-Embedding Predictive learning for legged LOcomotion), a single-stage learning framework for mapping-free, LiDAR-based perceptive locomotion for legged robots. We introduce a proprio-exteroceptive JEPA (PE-JEPA) world model to learn predictive egocentric terrain representations from onboard observations, including raw LiDAR scans. A concurrent JEPA-teacher-student (CJTS) pipeline is further proposed to train a locomotion policy informed by JEPA latent representations in simulation using deep reinforcement learning with a simple reward formulation. The framework achieves successful sim-to-real transfer, enabling omnidirectional traversal of diverse terrains, including long staircases and high boxes, with lightweight onboard computation. Evaluations demonstrate greater robustness than existing perceptive locomotion frameworks, particularly under degraded perception caused by occlusion, sparsity and noise. Further analysis validates JEPLO's ability to retain task-relevant information under these challenging conditions. We open-source our implementation, experimental datasets, and hardware setup designs https://github.com/ASIG-X/JEPLO.

## TL;DR

Light detection and ranging (LiDAR) remains less explored than RGB-D sensing for perceptive legged locomotion, and existing LiDAR-based approaches often rely on explicit mapping. We present JEPLO (Joint-Embedding Predictive learning for legged LOcomotion), a single-stage learning framework for mapping-free, LiDAR-based perceptive locomotion for legged robots.

## Related
<!-- [[other-paper-citekey]] -->
