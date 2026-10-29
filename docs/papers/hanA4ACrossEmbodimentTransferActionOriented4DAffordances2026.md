---
citekey: "hanA4ACrossEmbodimentTransferActionOriented4DAffordances2026"
title: "A4A: Cross-Embodiment Transfer of Action-Oriented 4D Affordances from Human Demonstrations"
authors: ["Yifan Han", "Litao Liu", "Yuqi Gu", "Ye Lu", "Hanqing Wang", "Sidney Wai", "Ishaan Myrie", "Qi Zhang", "Jingjin Yu", "Gen Li"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.05892"
doi: "10.48550/arXiv.2609.05892"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-11
---

# A4A: Cross-Embodiment Transfer of Action-Oriented 4D Affordances from Human Demonstrations

> Yifan Han, Litao Liu, Yuqi Gu, Ye Lu, Hanqing Wang, Sidney Wai, Ishaan Myrie, Qi Zhang, Jingjin Yu, Gen Li · 2026
> [arXiv](https://arxiv.org/abs/2609.05892) · [PDF](https://arxiv.org/pdf/2609.05892)

## Abstract

Human demonstrations contain rich manipulation knowledge, but it remains unclear what information can be transferred effectively to robot control. Existing affordance representations are typically formulated as 2D masks, 3D regions, contact points, or actionability scores, and therefore primarily identify where interaction may occur. However, effective manipulation also requires modeling how interaction-relevant geometry evolves during task execution. To bridge this gap, we introduce action-oriented 4D affordances, which represent the language-conditioned future trajectories of interaction-relevant 3D points. These trajectories capture task-conditioned geometric evolution rather than embodiment-specific actions, enabling transferable interaction priors across humans and robots. Based on this representation, we construct a large-scale action-oriented 4D affordance dataset from existing human--object interaction video data and complementary RGB-D demonstrations, and introduce A4A, an affordance-to-action framework that uses 4D affordance trajectory prediction to pretrain robot policies before manipulation fine-tuning. Experiments in both simulation and the real world validate the effectiveness of A4A, showing that pretraining with action-oriented 4D affordance data consistently improves the manipulation performance of diverse VLA policies. These results establish action-oriented 4D affordances as an effective cross-embodiment representation for transferring manipulation knowledge from human demonstrations to robot control.

## TL;DR

Human demonstrations contain rich manipulation knowledge, but it remains unclear what information can be transferred effectively to robot control. Existing affordance representations are typically formulated as 2D masks, 3D regions, contact points, or actionability scores, and therefore primarily identify where interaction may occur.

## Related
<!-- [[other-paper-citekey]] -->
