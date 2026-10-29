---
citekey: "zhenWBAGWholeBodyAttachedGeometrySafetyFrameworkVision2026"
title: "WBAG: A Whole-Body and Attached-Geometry Safety Framework for Vision-Language-Action Manipulation"
authors: ["Samuel Zhen", "Siwon Jo", "Yanze Zhang", "Wenhao Luo"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.01083"
doi: "10.48550/arXiv.2610.01083"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-03
---

# WBAG: A Whole-Body and Attached-Geometry Safety Framework for Vision-Language-Action Manipulation

> Samuel Zhen, Siwon Jo, Yanze Zhang, Wenhao Luo · 2026
> [arXiv](https://arxiv.org/abs/2610.01083) · [PDF](https://arxiv.org/pdf/2610.01083)

## Abstract

Vision-language-action (VLA) policies have demonstrated impressive capabilities in generalizable robotic manipulation, but their deployment in the real world remains challenging due to potential collisions involving different parts of the robot, manipulated objects, and the surrounding environment. Existing inference-time VLA safety frameworks typically rely on simplified end-effector-centered representations that do not explicitly model the full articulated robot and attached-object geometry. In this paper, we present WBAG, a safety framework that models the robot's whole-body and grasp-dependent attached geometry. WBAG constructs a grasp-conditioned safe set that adapts the protected geometry as objects are grasped, then converts this evolving geometry into differentiable CBF constraints that minimally modify the VLA's native six-dimensional operational-space action for collision avoidance across robot, scene, and attached geometry. On the SafeLIBERO benchmark, a variant of LIBERO augmented with obstacles for safety evaluation, WBAG achieves the best overall safety and safe task success among the evaluated methods under a scene-level safety evaluator that monitors all eligible non-task objects, reaching 97.38\% aggregate Scene Safety and 59.38\% Safe Success.

## TL;DR

Vision-language-action (VLA) policies have demonstrated impressive capabilities in generalizable robotic manipulation, but their deployment in the real world remains challenging due to potential collisions involving different parts of the robot, manipulated objects, and the surrounding environment. Existing inference-time VLA safety frameworks typically rely on simplified end-effector-centered representations that do not explicitly model the full articulated robot and attached-object geometry.

## Related
<!-- [[other-paper-citekey]] -->
