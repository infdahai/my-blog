---
citekey: "teamLambda0ScalingOpenWorldEgocentricHumanData2026"
title: "$\lambda_0$: Scaling Open-World Egocentric Human Data for Humanoid Loco-Manipulation"
authors: ["humanoid Team"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.18950"
doi: "10.48550/arXiv.2610.18950"
tags: [paper, embodied-ai, "cs.CV", "cs.RO"]
status: unread
rating:
created: 2026-10-16
---

# $\lambda_0$: Scaling Open-World Egocentric Human Data for Humanoid Loco-Manipulation

> humanoid Team · 2026
> [arXiv](https://arxiv.org/abs/2610.18950) · [PDF](https://arxiv.org/pdf/2610.18950)

## Abstract

Humanoid loco-manipulation requires coordinated whole-body interaction with the physical world, yet collecting robot demonstrations at scale remains costly. Human demonstrations offer a scalable alternative, but existing egocentric human supervision often omits locomotion and posture, while embodiment differences and controller dynamics hinder accurate end-effector execution. We introduce HumanVerse, a 500-hour dataset of open-world human loco-manipulation pairing egocentric video with synchronized body and hand motion. Our human-to-humanoid pipeline aligns camera viewpoints and arm appearance, and refines motion references and controller inputs offline to reduce end-effector errors while preserving whole-body coordination. We validate the pipeline through zero-shot transfer to Unitree G1 on representative whole-body manipulation and long-range loco-manipulation tasks, without target-task robot demonstrations. Building on this pipeline, we develop $\lambda_0$, a humanoid foundation model for whole-body loco-manipulation, with robot-aligned human demonstrations providing supervision for mid-training. Increasing whole-body human data consistently improves downstream task progress. $\lambda_0$ achieves 90.0% success on SIMPLE and 62.5% across real-world loco-manipulation tasks. We expect this study to guide scalable whole-body human data collection toward humanoid foundation models for richer interaction with the physical world. Homepage: https://lambdahumanoid.github.io/

## TL;DR

Humanoid loco-manipulation requires coordinated whole-body interaction with the physical world, yet collecting robot demonstrations at scale remains costly. Human demonstrations offer a scalable alternative, but existing egocentric human supervision often omits locomotion and posture, while embodiment differences and controller dynamics hinder accurate end-effector execution.

## Related
<!-- [[other-paper-citekey]] -->
