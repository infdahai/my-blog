---
citekey: "wangZeroShotSimRealContactRichAssemblyProprioception2026"
title: "Zero-Shot Sim-to-Real Contact-Rich Assembly via Proprioception-Anchored Cross-Modal Pretraining"
authors: ["Yuhan Wang", "Yurou Chen", "Hongye Jiang", "Wenzhao Lian"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.07534"
doi: "10.48550/arXiv.2609.07534"
tags: [paper, embodied-ai, "cs.AI", "cs.RO"]
status: unread
rating:
created: 2026-09-11
---

# Zero-Shot Sim-to-Real Contact-Rich Assembly via Proprioception-Anchored Cross-Modal Pretraining

> Yuhan Wang, Yurou Chen, Hongye Jiang, Wenzhao Lian · 2026
> [arXiv](https://arxiv.org/abs/2609.07534) · [PDF](https://arxiv.org/pdf/2609.07534)

## Abstract

Contact-rich assembly remains challenging because it requires submillimeter spatial accuracy and reliable interpretation of forces during sustained contact. Although simulation-based reinforcement learning offers a scalable training paradigm, discrepancies in visual observations, contact dynamics, and force/torque (F/T) measurements often limit policy transfer. We observe that proprioception is comparatively consistent across domains because calibrated joint positions and consistently computed joint velocities align closely between simulation and hardware. Based on this observation, we present PACE (Proprioception-Anchored Cross-Modal Encoder), which supervises temporal visual and F/T representations by predicting proprioceptive state transitions. Static domain-specific factors, including lighting, texture, and sensor bias, contain little information about joint motion; the proposed objective therefore encourages the encoder to suppress these factors while retaining task-relevant motion cues. Policies trained on frozen PACE features are deployed on hardware without real-world fine-tuning or object-pose tracking. Across four contact-rich assembly tasks, PACE attains an average real-world success rate of 93.3\% and only a 2.7-percentage-point sim-to-real drop, meanwhile remaining robust to perturbations that substantially degrade pose-based and learned-fusion baselines.

## TL;DR

Contact-rich assembly remains challenging because it requires submillimeter spatial accuracy and reliable interpretation of forces during sustained contact. Although simulation-based reinforcement learning offers a scalable training paradigm, discrepancies in visual observations, contact dynamics, and force/torque (F/T) measurements often limit policy transfer.

## Related
<!-- [[other-paper-citekey]] -->
