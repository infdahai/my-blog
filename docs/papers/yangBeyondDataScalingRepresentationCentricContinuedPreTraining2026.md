---
citekey: "yangBeyondDataScalingRepresentationCentricContinuedPreTraining2026"
title: "Beyond Data Scaling: Representation-Centric Continued Pre-training for Vision-Language-Action Models"
authors: ["Senqiao Yang", "Chengyao Wang", "Yuxin Chen", "Zixuan Wang", "Longxiang Tang", "Haokun Gui", "Jinhui Ye", "Changsheng Lu", "Xiaoyang Wu", "Mingkang Zhu", "Pengguang Chen", "Shu Liu", "Zhuotao Tian", "Hengshuang Zhao", "Bei Yu", "Jiaya Jia"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2608.27550"
doi: "10.48550/arXiv.2608.27550"
tags: [paper, embodied-ai, "cs.CV", "cs.RO"]
status: unread
rating:
created: 2026-08-31
---

# Beyond Data Scaling: Representation-Centric Continued Pre-training for Vision-Language-Action Models

> Senqiao Yang, Chengyao Wang, Yuxin Chen, Zixuan Wang, Longxiang Tang, Haokun Gui, Jinhui Ye, Changsheng Lu, Xiaoyang Wu, Mingkang Zhu, Pengguang Chen, Shu Liu, Zhuotao Tian, Hengshuang Zhao, Bei Yu, Jiaya Jia · 2026
> [arXiv](https://arxiv.org/abs/2608.27550) · [PDF](https://arxiv.org/pdf/2608.27550)

## Abstract

Scaling robot data is crucial for building generalist Vision-Language-Action (VLA) models, yet robot trajectories are harder to scale than web-scale image-text data because embodied collection is costly and sparsely covers the physical world. This makes representation quality a central bottleneck: under a fixed robot-data budget, continued pre-training must turn limited trajectories into transferable visual-action knowledge rather than merely fit actions. We propose VLAct, a VLA-oriented VLM backbone trained on broad, heterogeneous, multi-embodiment robot data before task-specific fine-tuning. VLAct preserves the broad VLM prior and encourages shared action semantics across embodiments through VLM-prior preservation, multi-head continuous action co-supervision, and a partially unified cross-embodiment action layout, while allowing task-specific action heads during fine-tuning. Across simulation, real-world, and unseen-embodiment transfer, VLAct consistently improves downstream performance under fixed fine-tuning protocols. On LIBERO-Plus and RoboTwin 2.0, VLAct surpasses industrial VLA systems including ABot-M0 and LingBot-VLA, achieving success rates of 82.6% and 92.5%. On RoboDojo, VLAct ranks sixth among all policies by success rate and outperforms all explicitly designated world-action model (WAM) entries on both metrics. Most notably, on RoboCasa-GR1, an unseen humanoid embodiment, VLAct using only 20% of downstream trajectories outperforms the full-data GR00T-N1.6 baseline. These results are obtained using fully open-source data and only a 16-GPU training setup, showing that representation-centric continued pre-training can deliver highly competitive performance under a modest compute budget and is an important independent axis of VLA progress beyond data scaling.

## TL;DR

Scaling robot data is crucial for building generalist Vision-Language-Action (VLA) models, yet robot trajectories are harder to scale than web-scale image-text data because embodied collection is costly and sparsely covers the physical world. This makes representation quality a central bottleneck: under a fixed robot-data budget, continued pre-training must turn limited trajectories into transferable visual-action knowledge rather than merely fit actions.

## Related
<!-- [[other-paper-citekey]] -->
