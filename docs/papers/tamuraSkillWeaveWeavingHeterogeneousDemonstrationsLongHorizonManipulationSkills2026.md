---
citekey: "tamuraSkillWeaveWeavingHeterogeneousDemonstrationsLongHorizonManipulationSkills2026"
title: "SkillWeave: Weaving Heterogeneous Demonstrations into Long-Horizon Manipulation Skills"
authors: ["Ryosei Tamura", "Xiaoxiang Dong", "Uksang Yoo", "Yuemin Mao", "Romina Mir", "Jonathan Francis", "Jeffrey Ichnowski"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.12046"
doi: "10.48550/arXiv.2610.12046"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-10
---

# SkillWeave: Weaving Heterogeneous Demonstrations into Long-Horizon Manipulation Skills

> Ryosei Tamura, Xiaoxiang Dong, Uksang Yoo, Yuemin Mao, Romina Mir, Jonathan Francis, Jeffrey Ichnowski · 2026
> [arXiv](https://arxiv.org/abs/2610.12046) · [PDF](https://arxiv.org/pdf/2610.12046)

## Abstract

Dexterous manipulation requires both large-scale task progression and precise contact-rich interaction, making it challenging to collect demonstrations that effectively support both regimes. We present SkillWeave, a heterogeneous demonstration framework for long-horizon dexterous manipulation that combines teleoperation for coarse reaching and transport with kinesthetic teaching for precise, contact-rich skills. To address the visual mismatch introduced by the demonstrator's presence during kinesthetic data collection, we propose an object-mask-conditioned diffusion policy that uses offline object segmentation for training supervision and a lightweight learned mask predictor at deployment, avoiding online segmentation and image inpainting. To mitigate distribution shift between independently trained sub-task policies, we introduce successor-aware terminal steering, which selects among actions sampled from the predecessor policy to guide the system toward states supported by the successor's demonstrated initial-state distribution. Across three real-world long-horizon tasks, SkillWeave achieves 27% average end-to-end success. Mask-conditioned kinesthetic policies improve dexterous sub-task success to an average of 65%, while successor-aware handoffs achieve an average composition efficiency of 87%. These results show that matching demonstration modality to interaction regime, explicitly addressing kinesthetic visual mismatch, and steering policy handoffs toward successor-supported states substantially improves long-horizon dexterous manipulation. Videos and code are available at skillweave-authors.github.io .

## TL;DR

Dexterous manipulation requires both large-scale task progression and precise contact-rich interaction, making it challenging to collect demonstrations that effectively support both regimes. We present SkillWeave, a heterogeneous demonstration framework for long-horizon dexterous manipulation that combines teleoperation for coarse reaching and transport with kinesthetic teaching for precise, contact-rich skills.

## Related
<!-- [[other-paper-citekey]] -->
