---
citekey: "yuOpenWAMOpenFrameworkComposableWorldActionModels2026"
title: "OpenWAM: An Open Framework for Composable World-Action Models"
authors: ["Heng Yu", "David D. Yuan", "Juze Zhang", "Changan Chen", "Yao Feng", "Michelle Baldonado", "Steve Cousins", "Li Fei-Fei", "Jiajun Wu", "Ehsan Adeli"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.07922"
doi: "10.48550/arXiv.2610.07922"
tags: [paper, embodied-ai, "cs.CV", "cs.RO"]
status: unread
rating:
created: 2026-10-08
---

# OpenWAM: An Open Framework for Composable World-Action Models

> Heng Yu, David D. Yuan, Juze Zhang, Changan Chen, Yao Feng, Michelle Baldonado, Steve Cousins, Li Fei-Fei, Jiajun Wu, Ehsan Adeli · 2026
> [arXiv](https://arxiv.org/abs/2610.07922) · [PDF](https://arxiv.org/pdf/2610.07922)

## Abstract

World-action models (WAMs) couple future prediction with robot control, yet existing systems often vary the video backbone, interaction structure, supervision, and inference procedure simultaneously, making their design choices difficult to compare. We introduce OPENWAM, an open world-action modeling framework built around a common causal robot-video foundation and configurable video-action interaction. Starting from Wan2.2-5B, we perform causal robot-video pretraining on over 10,000 hours of video, then integrate an action expert through a shared Mixture-of-Transformers architecture that supports joint, video-then-action, action-then-video, and decoupled generation. OPENWAM achieves high success rates on four LIBERO suites and real-world bimanual tasks; robot-video training with causal adaptation improves VTA success on LIBERO-Long from 68.4% to 97.8%. The same configurable architecture naturally extends to inverse and forward dynamics, allowing us to study how counterfactual transitions improve independently trained dynamics models beyond demonstrations alone. When only the video predictor is adapted to a new task, a frozen local-context inverse dynamics model trained on counterfactual data and demonstrations achieves 84.0% mean success across four held-out LIBERO-90 tasks, compared with 47.0% for a full-context inverse model and 21.5% for a local-context model trained only on demonstrations. For forward dynamics, counterfactual supervision reduces RGB prediction error by 34.5% and raises outcome identification from 21.1% to 71.3% among 16 same-state outcomes. OPENWAM provides a common testbed for comparing WAM interaction designs and for studying dynamics learning from video data beyond successful demonstrations.

## TL;DR

World-action models (WAMs) couple future prediction with robot control, yet existing systems often vary the video backbone, interaction structure, supervision, and inference procedure simultaneously, making their design choices difficult to compare. We introduce OPENWAM, an open world-action modeling framework built around a common causal robot-video foundation and configurable video-action interaction.

## Related
<!-- [[other-paper-citekey]] -->
