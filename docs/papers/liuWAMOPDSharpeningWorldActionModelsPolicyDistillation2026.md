---
citekey: "liuWAMOPDSharpeningWorldActionModelsPolicyDistillation2026"
title: "WAM-OPD: Sharpening World Action Models via On-Policy Distillation"
authors: ["Panjun Liu", "Xiaohan Lei", "Shiqi Zhang", "Yikun Wang", "Yongxin Zhang", "Mingyi Hu", "Shida Sun", "Jiateng Shou", "Wengang Zhou", "Jiajun Deng", "Zhiwei Xiong"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.34250"
doi: "10.48550/arXiv.2609.34250"
tags: [paper, embodied-ai, "cs.AI", "cs.RO"]
status: unread
rating:
created: 2026-09-30
---

# WAM-OPD: Sharpening World Action Models via On-Policy Distillation

> Panjun Liu, Xiaohan Lei, Shiqi Zhang, Yikun Wang, Yongxin Zhang, Mingyi Hu, Shida Sun, Jiateng Shou, Wengang Zhou, Jiajun Deng, Zhiwei Xiong · 2026
> [arXiv](https://arxiv.org/abs/2609.34250) · [PDF](https://arxiv.org/pdf/2609.34250)

## Abstract

Pretrained world action models (WAMs) provide generalist capabilities across diverse robotic manipulation tasks, yet improving target-task performance to an expert level without degrading pretrained skills remains challenging. We explore on-policy distillation (OPD) for WAMs and introduce WAM-OPD. WAM-OPD inherits the advantage of OPD methods that transfer task-specific teacher knowledge under the student's own induced distribution, rather than directly fitting the student to a narrow task-specific data distribution. However, in closed-loop manipulation, the observation histories change as the student policy evolves, requiring fresh environment rollouts to remain on-policy. Applying OPD to WAMs entails repeated data collection, which is costly even in simulation and often impractical on real robots. To avoid repeated environment rollouts during distillation, we introduce prefix-weighted trajectory replay (PWTR). PWTR uses a fixed trajectory pool composed primarily of initial-student rollouts, supplemented with task-specific teacher rollouts to broaden trajectory coverage. For each trajectory replayed from this pool, PWTR conditions the current policy on successive stored histories to generate fresh denoising paths, along which the task-specific teacher provides supervision. Although these denoising paths are refreshed as the policy evolves, the replayed environment trajectories remain fixed. PWTR therefore reweights per-decision distillation losses using proxy importance weights derived from path scores accumulated over the trajectory prefix preceding each decision to mitigate the resulting shift in the history distribution. Simulated and real-world experiments demonstrate task adaptation without additional environment interaction during distillation. In both settings, WAM-OPD improves target-task performance while retaining near-initial performance on tasks excluded from adaptation.

## TL;DR

Pretrained world action models (WAMs) provide generalist capabilities across diverse robotic manipulation tasks, yet improving target-task performance to an expert level without degrading pretrained skills remains challenging. We explore on-policy distillation (OPD) for WAMs and introduce WAM-OPD.

## Related
<!-- [[other-paper-citekey]] -->
