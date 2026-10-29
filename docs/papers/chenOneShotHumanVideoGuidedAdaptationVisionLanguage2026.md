---
citekey: "chenOneShotHumanVideoGuidedAdaptationVisionLanguage2026"
title: "One-shot Human Video-Guided Adaptation for Vision-Language-Action Models"
authors: ["Qi Chen", "Yuwei Wu", "Quan Chen", "Kunpeng Gao", "Jin Chen", "Che Sun", "Zhi Gao", "Yunde Jia"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.19746"
doi: "10.48550/arXiv.2610.19746"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-16
---

# One-shot Human Video-Guided Adaptation for Vision-Language-Action Models

> Qi Chen, Yuwei Wu, Quan Chen, Kunpeng Gao, Jin Chen, Che Sun, Zhi Gao, Yunde Jia · 2026
> [arXiv](https://arxiv.org/abs/2610.19746) · [PDF](https://arxiv.org/pdf/2610.19746)

## Abstract

Vision-language-action (VLA) models have recently achieved remarkable progress by leveraging large-scale robot datasets and foundation models for general-purpose robot manipulation. However, their ability to rapidly adapt to novel manipulation tasks beyond the training distribution remains limited. Existing approaches often require task-specific robot demonstrations and additional training, which are labor- and compute-intensive, limiting the scalability of VLA adaptation to open-world scenarios. To reduce this dependence on target-task robot data, we propose CapPro, a framework that enables a VLA policy to adapt to previously unseen manipulation tasks using only a single human demonstration video. CapPro consists of two components. First, a phase-aware human video representation module constructs a compact video representation through learned visual token selection and learns task-relevant query representations under phase-caption supervision. Second, a video-conditioned adaptation module jointly incorporates the compact video and query-derived representations into the action-conditioning context of the pretrained VLA policy. % This design introduces task-specific guidance while largely preserving the original VLA action-generation backbone. In this way, the human demonstration provides task-specific execution guidance rather than an embodiment-aligned trajectory to imitate, without requiring target-task robot demonstrations or target-task fine-tuning. Experiments across source and unseen target tasks show that CapPro improves average performance across unseen target groups while maintaining comparable performance on the source tasks. These results demonstrate the effectiveness of human-video guidance for cross-task VLA adaptation.

## TL;DR

Vision-language-action (VLA) models have recently achieved remarkable progress by leveraging large-scale robot datasets and foundation models for general-purpose robot manipulation. However, their ability to rapidly adapt to novel manipulation tasks beyond the training distribution remains limited.

## Related
<!-- [[other-paper-citekey]] -->
