---
citekey: "qiuLearningKeypointConstraintsVisualDemonstrationsSafeMotionPlanning2026"
title: "Learning Keypoint Constraints from Visual Demonstrations for Safe Motion Planning"
authors: ["Zheng Qiu", "Zhouyu Zhang", "Ninghan Zhong", "Glen Chou"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.19295"
doi: "10.48550/arXiv.2610.19295"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-16
---

# Learning Keypoint Constraints from Visual Demonstrations for Safe Motion Planning

> Zheng Qiu, Zhouyu Zhang, Ninghan Zhong, Glen Chou · 2026
> [arXiv](https://arxiv.org/abs/2610.19295) · [PDF](https://arxiv.org/pdf/2610.19295)

## Abstract

We present Keypoint Constraint Learning (KCL), a framework for learning task-relevant motion constraints from visual demonstrations and for planning safely with the extracted constraints. To make constraint learning tractable from RGB-D observations, we represent demonstrations using sparse 3D object-centric keypoints and semantic mask centroids extracted through segmentation, visual feature clustering, and point tracking. In this reduced geometric space, we learn keypoint dynamics and infer distance- and orientation-based constraints that make the expert trajectories feasible and approximately locally optimal by enforcing KKT optimality conditions in the reduced state space. We then plan with the learned constraints under uncertainty, using robustness margins derived from accumulated prediction error, and provide a theoretical analysis of how keypoint perception error and learned dynamics error affect the recovered constraints. We evaluate KCL on visual demonstrations from navigation to rigid/deformable manipulation, showing that it recovers multi-stage geometric constraints and outperforms baselines in downstream safe planning.

## TL;DR

We present Keypoint Constraint Learning (KCL), a framework for learning task-relevant motion constraints from visual demonstrations and for planning safely with the extracted constraints. To make constraint learning tractable from RGB-D observations, we represent demonstrations using sparse 3D object-centric keypoints and semantic mask centroids extracted through segmentation, visual feature clustering, and point tracking.

## Related
<!-- [[other-paper-citekey]] -->
