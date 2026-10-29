---
citekey: "yinTacBPMTactileConditionedBehaviorPriorModelDexterousReorientation2026"
title: "TacBPM: A Tactile-conditioned Behavior Prior Model for Dexterous Reorientation"
authors: ["Jie Yin", "Wanli Xing", "Zeyuan Zhao", "Xuezhou Zhu", "Zhijie Deng", "Kaifeng Zhang"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.18174"
doi: "10.48550/arXiv.2609.18174"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-17
---

# TacBPM: A Tactile-conditioned Behavior Prior Model for Dexterous Reorientation

> Jie Yin, Wanli Xing, Zeyuan Zhao, Xuezhou Zhu, Zhijie Deng, Kaifeng Zhang · 2026
> [arXiv](https://arxiv.org/abs/2609.18174) · [PDF](https://arxiv.org/pdf/2609.18174)

## Abstract

Dexterous in-hand manipulation requires policies that coordinate high-DoF hand joints through intermittent, contact-rich interaction. Beyond target-orientation tracking, such policies must discover finger gaits that preserve object stability while adapting to geometry, anisotropy, pose, contact, and sensing changes. We propose \method, a tactile-conditioned behavior prior model for dexterous reorientation. \method distills multi-scale sphere specialists into a latent controller and lets downstream policies reuse the fixed tactile prior through residual latent actions, reducing renewed exploration from raw joint commands. The prior conditions on tactile-proprioceptive history so latent behavior reflects the current hand-object interaction. We evaluate arbitrary-pose transfer across anisotropic objects, commanded-axis rotation, and an arm-hand Grasp-to-AnyPose task in which the robot must grasp, lift, transport, and reach goal poses for novel tool geometries and generalized placements. Extensive experiments demonstrate that the proposed method accelerates training and enables stable policies where matched raw-action PPO remains near failure, with successful sim-to-real transfer in in-hand and arm-hand tasks.

## TL;DR

Dexterous in-hand manipulation requires policies that coordinate high-DoF hand joints through intermittent, contact-rich interaction. Beyond target-orientation tracking, such policies must discover finger gaits that preserve object stability while adapting to geometry, anisotropy, pose, contact, and sensing changes.

## Related
<!-- [[other-paper-citekey]] -->
