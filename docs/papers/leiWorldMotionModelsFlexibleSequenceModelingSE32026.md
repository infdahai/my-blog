---
citekey: "leiWorldMotionModelsFlexibleSequenceModelingSE32026"
title: "World Motion Models: Flexible Sequence Modeling of SE(3) Trajectories"
authors: ["Jiahui Lei", "Qianqian Wang", "Trevor Darrell", "Angjoo Kanazawa"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.01742"
doi: "10.48550/arXiv.2610.01742"
tags: [paper, embodied-ai, "cs.CV", "cs.RO"]
status: unread
rating:
created: 2026-10-03
---

# World Motion Models: Flexible Sequence Modeling of SE(3) Trajectories

> Jiahui Lei, Qianqian Wang, Trevor Darrell, Angjoo Kanazawa · 2026
> [arXiv](https://arxiv.org/abs/2610.01742) · [PDF](https://arxiv.org/pdf/2610.01742)

## Abstract

Equipping artificial agents with spatial intelligence requires a comprehensive generative prior over the dynamic 3D world. We propose World Motion Models (WMMs) that capture "what was, is, and will be where across time" via sparse SE(3) pose trajectories. WMMs are built on the observation that elements of dynamic scenes can be well approximated by a set of rigid SE(3) trajectories, a minimal yet expressive primitive for 4D modeling. This representation unifies articulated objects, human bodies, hand-object interactions, piecewise-rigid scene dynamics, camera motion, and even robot states and actions into a single shared space. Given this representation, we cast the joint distribution of these entities as a flexible sequence modeling problem, utilizing flow-matching with per-token noise levels. Coupled with a context token mechanism for non-sequential conditioning, this formulation supports any-to-any marginal conditioning across an arbitrary number of entities and time steps. Tasks such as future prediction, motion infilling, model-predictive control, inverse kinematics, cross-embodiment retargeting, and policy learning all reduce to the application of different masks over the same network. Experiments on 6 diverse applications of 3D vision and robotics demonstrate the versatility and flexibility of WMMs with strong performance.

## TL;DR

Equipping artificial agents with spatial intelligence requires a comprehensive generative prior over the dynamic 3D world. We propose World Motion Models (WMMs) that capture "what was, is, and will be where across time" via sparse SE(3) pose trajectories.

## Related
<!-- [[other-paper-citekey]] -->
