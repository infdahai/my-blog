---
citekey: "linLearningHandObjectReachingGeneral6DPoses2026"
title: "Learning In-Hand Object Reaching to General 6D Poses"
authors: ["Junxiao Lin", "Tianyue Wu", "Jie Yin", "Jia Pan", "Kaifeng Zhang", "Weiming Zhi"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.13761"
doi: "10.48550/arXiv.2609.13761"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-16
---

# Learning In-Hand Object Reaching to General 6D Poses

> Junxiao Lin, Tianyue Wu, Jie Yin, Jia Pan, Kaifeng Zhang, Weiming Zhi · 2026
> [arXiv](https://arxiv.org/abs/2609.13761) · [PDF](https://arxiv.org/pdf/2609.13761)

## Abstract

In-hand manipulation allows multi-fingered dexterous hands to reconfigure grasped objects without releasing and regrasping them. This improves manipulation efficiency by reducing repeated grasp acquisition and large arm motions. However, most learning-based methods focus on reorientation, continuous rotation, or translation, whereas many tasks require joint control of object position and orientation. We formulate this capability as in-hand 6D object pose reaching: starting from an existing grasp, coordinated finger motions move the object to a palm-relative target pose. We present POISE (Palm-relative Object reaching In SE(3)), a sim-to-real reinforcement learning framework for this task. POISE combines diverse stable-grasp initialization, goal- and geometry-conditioned control, an adaptive 6D goal curriculum, and a compact reward scheme for pose reaching and grasp preservation. In simulation, diverse initialization raises held-out-grasp success from 40.1% to 51.5% and post-drop recovery from 33.8% to 72.9%; the curriculum raises full-range success from 6.2% to 59.5%. On hardware, the grasp-maintenance reward improves three-target sequence success from 20% to 80%. In real-world experiments, POISE reaches successive 6D targets without manual reset across multiple object geometries and wrist orientations, and recovers from external disturbances. To support further research in dexterous manipulation, we will release our code at https://junxiaolin.github.io/poise-website/.

## TL;DR

In-hand manipulation allows multi-fingered dexterous hands to reconfigure grasped objects without releasing and regrasping them. This improves manipulation efficiency by reducing repeated grasp acquisition and large arm motions.

## Related
<!-- [[other-paper-citekey]] -->
