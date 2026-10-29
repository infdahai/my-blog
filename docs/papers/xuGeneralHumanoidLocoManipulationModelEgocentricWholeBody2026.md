---
citekey: "xuGeneralHumanoidLocoManipulationModelEgocentricWholeBody2026"
title: "Towards a General Humanoid Loco-Manipulation Model via Egocentric Whole-Body Human Data Pretraining"
authors: ["Chongyang Xu", "Zhao Wu", "Jin Chen", "Yiming Jiang", "Jinhui Ye", "Yuming Jiang", "Shifeng Zhang", "Ziliang Feng", "Mu Xu", "Yilun Chen", "Li Lu", "Steven C. H. Hoi"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.00438"
doi: "10.48550/arXiv.2610.00438"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-03
---

# Towards a General Humanoid Loco-Manipulation Model via Egocentric Whole-Body Human Data Pretraining

> Chongyang Xu, Zhao Wu, Jin Chen, Yiming Jiang, Jinhui Ye, Yuming Jiang, Shifeng Zhang, Ziliang Feng, Mu Xu, Yilun Chen, Li Lu, Steven C. H. Hoi · 2026
> [arXiv](https://arxiv.org/abs/2610.00438) · [PDF](https://arxiv.org/pdf/2610.00438)

## Abstract

Humanoid whole-body manipulation has advanced rapidly, enabling policies to coordinate locomotion, posture, bimanual interaction, and dexterous hand movements. Meanwhile, egocentric human videos provide diverse examples of everyday interactions across objects and scenes, offering scalable supervision without robot operation. However, existing supervision from these videos provides limited coverage of whole-body movement and coordination with hand-object interaction, while obtaining such supervision through humanoid teleoperation is also costly and difficult to scale. We therefore explore how human experience can support scalable learning of humanoid loco-manipulation. To support this study, we introduce HumanVerse-500, a 500-hour dataset of diverse human loco-manipulation behaviors in open-world environments, collected with a lightweight wearable system that synchronizes egocentric video with body and hand motion. Building on this dataset, we develop $\lambda_0$, a whole-body humanoid vision-language-action policy, through three-stage training that first learns interaction from diverse egocentric datasets, then coordinates body and hand motion using HumanVerse-500, and finally adapts the policy to downstream tasks and robot embodiments. Across these stages, $\lambda_0$ learns a shared representation space for human experience transfer, while domain-specific interfaces handle differences between human and robot states and actions. We evaluate $\lambda_0$ on SIMPLE and 4 real-world loco-manipulation tasks, achieving state-of-the-art performance, and further analyze its scaling behavior, generalization, and training-stage contributions to understand how human data support downstream whole-body humanoid control. We will release our code, models, and data to support further research.

## TL;DR

Humanoid whole-body manipulation has advanced rapidly, enabling policies to coordinate locomotion, posture, bimanual interaction, and dexterous hand movements. Meanwhile, egocentric human videos provide diverse examples of everyday interactions across objects and scenes, offering scalable supervision without robot operation.

## Related
<!-- [[other-paper-citekey]] -->
