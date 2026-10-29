---
citekey: "yuanRecedingHorizonPushingComposableObjectCentricPolicies2026"
title: "Receding-Horizon Pushing with Composable Object-Centric Policies"
authors: ["Zhiyi Yuan", "Tianrun Hu", "Anxing Xiao", "Yuhong Deng", "David Hsu", "Hanbo Zhang"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.23439"
doi: "10.48550/arXiv.2609.23439"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-23
---

# Receding-Horizon Pushing with Composable Object-Centric Policies

> Zhiyi Yuan, Tianrun Hu, Anxing Xiao, Yuhong Deng, David Hsu, Hanbo Zhang · 2026
> [arXiv](https://arxiv.org/abs/2609.23439) · [PDF](https://arxiv.org/pdf/2609.23439)

## Abstract

Non-prehensile manipulation is practical for relocating large, heavy, or geometrically ungraspable objects. Yet, long-horizon pushing of arbitrarily-shaped 3D objects couples three problems: 1) where to push the object so as to approach the target pose, 2) whether each push is stable and reachable, 3) whether subsequent actions remain feasible. We present an object-centric pushing policy within a feedback-guided hierarchical framework. At the low level, a learning-based policy predicts contact actions from a pose- and scale-normalized point cloud, conditioned on a near single-step subgoal. A stability score is applied to evaluate the predicted contacts by a quasi-static sliding-versus-tipping analysis. At the high level, BIT$^*$ first searches for an object path, and the next several subgoals are checked by contact prediction and robot motion planning for future feasibility. Failed motion plans, as feedback, change the local path costs and trigger re-planning. During execution, only the first feasible action is executed. In simulation, we evaluate 22 objects in six different scenes, upon which we also conduct comprehensive ablation studies. Results demonstrate that our method outperforms baselines with a clear margin and can reliably achieve long-horizon object pushing tasks under different situations. We also report quantitative real-robot experiments with a Franka arm and qualitative demonstrations with a mobile manipulator for large and heavy objects, with directly zero-shot sim-to-real transfer.

## TL;DR

Non-prehensile manipulation is practical for relocating large, heavy, or geometrically ungraspable objects. Yet, long-horizon pushing of arbitrarily-shaped 3D objects couples three problems: 1) where to push the object so as to approach the target pose, 2) whether each push is stable and reachable, 3) whether subsequent actions remain feasible.

## Related
<!-- [[other-paper-citekey]] -->
