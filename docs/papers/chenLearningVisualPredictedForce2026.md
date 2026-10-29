---
citekey: "chenLearningVisualPredictedForce2026"
title: "Robot Learning with Visual Predicted Force"
authors: ["Haonan Chen", "Feiyang Wu", "Yuxiang Ma", "Mustafa Mete", "Pengfei Ye", "Junxuan Shen", "Cheng Zhu", "Aurora Ruggeri", "Kelvin Cheung", "Jiayuan Mao", "Edward Adelson", "Jiajun Wu", "Robert D. Howe", "Yilun Du"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.04741"
doi: "10.48550/arXiv.2610.04741"
tags: [paper, embodied-ai, "cs.AI", "cs.RO"]
status: unread
rating:
created: 2026-10-07
---

# Robot Learning with Visual Predicted Force

> Haonan Chen, Feiyang Wu, Yuxiang Ma, Mustafa Mete, Pengfei Ye, Junxuan Shen, Cheng Zhu, Aurora Ruggeri, Kelvin Cheung, Jiayuan Mao, Edward Adelson, Jiajun Wu, Robert D. Howe, Yilun Du · 2026
> [arXiv](https://arxiv.org/abs/2610.04741) · [PDF](https://arxiv.org/pdf/2610.04741)

## Abstract

Force-aware manipulation typically relies on specialized force or tactile sensors. We show that force-aware manipulation can instead be achieved through visual force prediction from the deformation of a compliant Fin Ray gripper. Our approach trains two models. First, we train a visual force estimator on calibration data and use it to annotate task demonstrations with force estimates. Second, we train an action--force proposal policy on these force-augmented demonstrations to jointly generate candidate robot actions and their associated forces. At test time, we sample candidate actions and the forces they are expected to produce, then execute the action whose predicted force is closest to a target from the demonstrations. We evaluate our approach on berry picking, empty-can grasping, in-hand reorientation, and plug insertion. Our results show that visual force prediction can guide inference-time action selection for contact-rich manipulation without requiring force or tactile sensors at deployment.

## TL;DR

Force-aware manipulation typically relies on specialized force or tactile sensors. We show that force-aware manipulation can instead be achieved through visual force prediction from the deformation of a compliant Fin Ray gripper.

## Related
<!-- [[other-paper-citekey]] -->
