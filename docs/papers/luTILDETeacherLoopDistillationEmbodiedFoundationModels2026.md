---
citekey: "luTILDETeacherLoopDistillationEmbodiedFoundationModels2026"
title: "TILDE: Teacher-in-the-Loop Distillation from Embodied Foundation Models"
authors: ["Yuxiang Lu", "Yantong Liu", "Jinghua Hou", "Xueli Sun", "Ruihua Han", "Zhe Liu", "Hengshuang Zhao"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.25376"
doi: "10.48550/arXiv.2610.25376"
tags: [paper, embodied-ai, "cs.LG", "cs.RO"]
status: unread
rating:
created: 2026-10-22
---

# TILDE: Teacher-in-the-Loop Distillation from Embodied Foundation Models

> Yuxiang Lu, Yantong Liu, Jinghua Hou, Xueli Sun, Ruihua Han, Zhe Liu, Hengshuang Zhao · 2026
> [arXiv](https://arxiv.org/abs/2610.25376) · [PDF](https://arxiv.org/pdf/2610.25376)

## Abstract

Large-scale action pretraining equips Embodied Foundation Models (EFMs) with strong manipulation capabilities, with particular strengths in generalization and closed-loop robustness, but reproducing such pretraining requires substantial robot data and computation. To transfer these capabilities from pretrained EFMs to policies without action pretraining, we introduce TILDE (Teacher-In-the-Loop Distillation from EFMs), which synergizes on-policy distillation at student-induced states with learning from teacher-executed recovery trajectories. We further propose AutoDAgger, an autonomous data aggregation pipeline in which a robotic reward model is utilized to monitor task progress and trigger teacher intervention, thereby collecting recovery experience without human monitoring or manual control. AutoDAgger accelerates recovery-trajectory collection by more than $2\times$ compared with the human-in-the-loop method. By unifying learning from demonstrations, on-policy teacher supervision, and teacher's corrective behavior, TILDE improves task performance by up to $4.1\times$ over behavior cloning across three real-world tasks and supports effective cross-architecture distillation.

## TL;DR

Large-scale action pretraining equips Embodied Foundation Models (EFMs) with strong manipulation capabilities, with particular strengths in generalization and closed-loop robustness, but reproducing such pretraining requires substantial robot data and computation. To transfer these capabilities from pretrained EFMs to policies without action pretraining, we introduce TILDE (Teacher-In-the-Loop Distillation from EFMs), which synergizes on-policy distillation at student-induced states with learning from teacher-executed recovery trajectories.

## Related
<!-- [[other-paper-citekey]] -->
