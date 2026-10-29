---
citekey: "niuSkelWAMSkeletonGuidedWorldActionModelZeroShot2026"
title: "SkelWAM: A Skeleton-Guided World-Action Model for Zero-Shot Cross-Embodiment Manipulation"
authors: ["Pengjun Niu", "Yujia Xie", "Rui Peng", "Hang Zhao", "Ke Liu"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.21983"
doi: "10.48550/arXiv.2609.21983"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-22
---

# SkelWAM: A Skeleton-Guided World-Action Model for Zero-Shot Cross-Embodiment Manipulation

> Pengjun Niu, Yujia Xie, Rui Peng, Hang Zhao, Ke Liu · 2026
> [arXiv](https://arxiv.org/abs/2609.21983) · [PDF](https://arxiv.org/pdf/2609.21983)

## Abstract

Reusing manipulation experience across robot embodiments is important for scaling robot learning and reducing repeated task-specific data collection. However, changes in embodiment alter visual appearance, action dimensionality and semantics, and the whole-body configurations that can realize the same tool pose. We present SkelWAM, a skeleton-guided world-action model that couples perception and control through one explicit geometric representation for single-source cross-embodiment manipulation. Arm centerline geometry, tool-center-point (TCP) pose, and parallel-jaw commands form a shared 25-D state. The same definition underlies canonical third-person and wrist observations and future whole-body action targets. Trained with predictive visual supervision, a video-action mixture of transformers predicts canonical skeleton action chunks, which embodiment-specific constrained decoders convert into joint or continuum-robot controls. This formulation requires no one-to-one joint correspondence and uses no target-task demonstrations or target policy updates. We introduce LIBERO-Cross10, a source-only cross-embodiment transfer benchmark covering ten tasks and ten target embodiments across four morphological groups. On this benchmark, Franka-trained SkelWAM achieves 43.3% success over 1,000 episodes, exceeding the best-performing evaluated baseline by 36.2 percentage points. We further deploy a JAKA mini2-trained policy on the Feagine A03 continuum robot for three tabletop manipulation tasks, illustrating the approach's potential for real-world cross-embodiment manipulation. Project page: http://www.liukepku.com/skelwam/index.html

## TL;DR

Reusing manipulation experience across robot embodiments is important for scaling robot learning and reducing repeated task-specific data collection. However, changes in embodiment alter visual appearance, action dimensionality and semantics, and the whole-body configurations that can realize the same tool pose.

## Related
<!-- [[other-paper-citekey]] -->
