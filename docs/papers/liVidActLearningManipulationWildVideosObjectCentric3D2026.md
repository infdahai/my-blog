---
citekey: "liVidActLearningManipulationWildVideosObjectCentric3D2026"
title: "VidAct: Learning Manipulation from In-the-Wild Videos with Object-Centric 3D Awareness"
authors: ["Hang Li", "Mingxin Zhang", "Zihan Wu", "Yang Tian", "Dong Chen", "Fengyi Shen", "Yuan Meng", "Xiangtong Yao", "Heng Zhang", "Ziyuan Liu", "Zhenshan Bing", "Alois Knoll"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.36870"
doi: "10.48550/arXiv.2609.36870"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-30
---

# VidAct: Learning Manipulation from In-the-Wild Videos with Object-Centric 3D Awareness

> Hang Li, Mingxin Zhang, Zihan Wu, Yang Tian, Dong Chen, Fengyi Shen, Yuan Meng, Xiangtong Yao, Heng Zhang, Ziyuan Liu, Zhenshan Bing, Alois Knoll · 2026
> [arXiv](https://arxiv.org/abs/2609.36870) · [PDF](https://arxiv.org/pdf/2609.36870)

## Abstract

Video demonstrations offer a scalable alternative to costly robot data for learning manipulation, yet existing reconstruction-based approaches often rely on constrained camera viewpoints or human-to-robot retargeting, while the reconstructed trajectories are difficult to adapt to new objects configurations without distorting the trajectory shape. Another key limitation is that the resulting policies often lack precise object-level 3D geometry awareness, limiting object grounding and object shape awareness critical for precise manipulation. To bridge these gaps, we propose VidAct, an efficient video-to-robot framework that learns object-centric, 3D-aware manipulation policies from a single monocular video per task and enables zero-shot real-world deployment. VidAct consists of three key components. First, VidAct reconstructs object meshes and motion from arbitrary demo videos and canonicalizes the motion in the static object frame, avoiding embodiment-specific retargeting and accommodating diverse camera viewpoints. Second, VidAct employ residual trajectory transfer for adapting the reconstructed motion to novel object configurations while preserving its motion shape. Finally, as the key policy-learning component, VidAct predicts simulation-provided privileged complete-object point clouds at each frame as an auxiliary task while retaining RGB-only deployment, providing dense object-centric supervision over both object pose and 3D geometry. Experiments on human, robot, generated, and internet videos demonstrate broad video applicability and zero-shot deployment. Per-frame complete-object 3D supervision improves policy generalization and sim-to-real success, while residual trajectory transfer enables reliable trajectory adaptation with better shape preservation.

## TL;DR

Video demonstrations offer a scalable alternative to costly robot data for learning manipulation, yet existing reconstruction-based approaches often rely on constrained camera viewpoints or human-to-robot retargeting, while the reconstructed trajectories are difficult to adapt to new objects configurations without distorting the trajectory shape. Another key limitation is that the resulting policies often lack precise object-level 3D geometry awareness, limiting object grounding and object shape awareness critical for precise manipulation.

## Related
<!-- [[other-paper-citekey]] -->
