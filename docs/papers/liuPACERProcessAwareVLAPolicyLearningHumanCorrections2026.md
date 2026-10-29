---
citekey: "liuPACERProcessAwareVLAPolicyLearningHumanCorrections2026"
title: "PACER: Process-Aware VLA Policy Learning from Human Corrections for Robotic Disassembly"
authors: ["Chang Liu", "Sibo Tian", "Litian Gong", "Zhiwen Fan", "Jiachen Li", "Xiao Liang", "Minghui Zheng"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.19248"
doi: "10.48550/arXiv.2610.19248"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-16
---

# PACER: Process-Aware VLA Policy Learning from Human Corrections for Robotic Disassembly

> Chang Liu, Sibo Tian, Litian Gong, Zhiwen Fan, Jiachen Li, Xiao Liang, Minghui Zheng · 2026
> [arXiv](https://arxiv.org/abs/2610.19248) · [PDF](https://arxiv.org/pdf/2610.19248)

## Abstract

Robotic disassembly of end-of-life (EoL) products requires robots to accommodate product variation, follow prerequisite sequences, and approach components precisely for contact-rich manipulation. Supervised fine-tuning (SFT) provides a practical path for adaptation, but limited and costly disassembly data cannot capture the distribution shifts arising from changing environments and product uncertainties. The policy's own rollouts record its approach attempts, and human corrections demonstrate recovery from its errors, but turning these experiences into better policy performance remains challenging. We introduce PACER, a Process-Aware Correction and Evidence Reweighting framework that learns from these experiences through SFT, using progress toward the target and each trace's source and outcome to weight valid action chunks in the native supervised action loss. PACER trains one policy per weighting setting and selects one of the resulting policies through held-out validation. We evaluate PACER on UR5e motherboard disassembly across five component classes, where it achieves 87/100 successful approach-and-handoff trials on the held-out benchmark, compared with 54/100 for vanilla post-SFT.

## TL;DR

Robotic disassembly of end-of-life (EoL) products requires robots to accommodate product variation, follow prerequisite sequences, and approach components precisely for contact-rich manipulation. Supervised fine-tuning (SFT) provides a practical path for adaptation, but limited and costly disassembly data cannot capture the distribution shifts arising from changing environments and product uncertainties.

## Related
<!-- [[other-paper-citekey]] -->
