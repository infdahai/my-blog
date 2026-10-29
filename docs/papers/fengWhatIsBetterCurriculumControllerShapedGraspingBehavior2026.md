---
citekey: "fengWhatIsBetterCurriculumControllerShapedGraspingBehavior2026"
title: "What is the Better Curriculum: Controller-Shaped Grasping Behavior for Contact Force-Sensitive Manipulation"
authors: ["Ziyan Feng", "Zizhao Yuan", "Yulong Fu", "Yuxin He", "Zhiyuan Zhang", "Zhengjie Zhang", "Jinni Zhou", "Renjing Xu", "Qiang Nie"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.25887"
doi: "10.48550/arXiv.2609.25887"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-23
---

# What is the Better Curriculum: Controller-Shaped Grasping Behavior for Contact Force-Sensitive Manipulation

> Ziyan Feng, Zizhao Yuan, Yulong Fu, Yuxin He, Zhiyuan Zhang, Zhengjie Zhang, Jinni Zhou, Renjing Xu, Qiang Nie · 2026
> [arXiv](https://arxiv.org/abs/2609.25887) · [PDF](https://arxiv.org/pdf/2609.25887)

## Abstract

How should a robot learn to manipulate objects so fragile that sub-Newton contact forces can cause irreversible damage? Existing visuo-tactile policy learning typically treats tactile sensing as an additional policy input. In direct-contact force-sensitive manipulation, however, the bottleneck can arise earlier, during data collection: manual gripper control is too delayed and coarse-grained to reliably maintain the narrow force range required for stable grasping. We therefore use a deterministic 25 Hz tactile reflex controller as a collection-time teacher, producing demonstrations with controller-shaped grasping behavior for tactile-free policy learning. On Action Chunking with Transformers (ACT), policies trained from reflex-shaped demonstrations recover the teacher's grasping profile and achieve 95% stable grasps on the nominal plastic-cup task, substantially outperforming visually screened manual demonstrations. The same intervention improves in-distribution stability on $π_{0.5}$ and shows a favorable exploratory trend on an unseen paper-cup variant. Under randomized external disturbance, however, the reflex-data $π_{0.5}$ policy still fails in 45% of policy-only trials, whereas a deployment-time reflex arbiter retains all grasps. These results reveal a new role for tactile feedback in force-sensitive manipulation: rather than integrating tactile into the policy, we use it as a collection-time teacher that shapes grasping behavior in demonstrations for policy learning, while disturbance rejection remains controller-dependent, revealing the boundary of tactile-free policy.

## TL;DR

How should a robot learn to manipulate objects so fragile that sub-Newton contact forces can cause irreversible damage? Existing visuo-tactile policy learning typically treats tactile sensing as an additional policy input.

## Related
<!-- [[other-paper-citekey]] -->
