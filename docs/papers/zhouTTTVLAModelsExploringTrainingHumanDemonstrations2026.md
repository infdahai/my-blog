---
citekey: "zhouTTTVLAModelsExploringTrainingHumanDemonstrations2026"
title: "TTT in VLA Models: Exploring Training with Human Demonstrations"
authors: ["Qiangong Zhou", "Jiafeng Liang", "Yimin Dong", "Yang He", "Hongxiang Li"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.32094"
doi: "10.48550/arXiv.2610.32094"
tags: [paper, embodied-ai, "cs.AI", "cs.CV", "cs.RO"]
status: unread
rating:
created: 2026-10-27
---

# TTT in VLA Models: Exploring Training with Human Demonstrations

> Qiangong Zhou, Jiafeng Liang, Yimin Dong, Yang He, Hongxiang Li · 2026
> [arXiv](https://arxiv.org/abs/2610.32094) · [PDF](https://arxiv.org/pdf/2610.32094)

## Abstract

Long-horizon robot tasks require retaining and using past information. We integrate Test-Time Training (TTT), which stores context in fast weights, into InternVLA-A1 and Pi0.5 to study action generation conditioned on human demonstrations through training on paired demonstrations and robot trajectories. We implement memory transfer between the two phases and truncated backpropagation, and examine training objectives, gradient coverage, and contrastive regularization across video, short-video, and single-frame cue tasks. In our experiments, adding TTT and training on paired data at the current scale did not lead to consistent target selection based on demonstrations. Under the tested settings, shorter sequences, full trajectory gradient connectivity, and contrastive regularization did not clearly improve responsiveness to demonstrations. When demonstrations were reduced to single-frame cues, real-robot execution still showed a preference for cups at fixed positions. We document the implementation, training configurations, and observations to support further inspection and replication.

## TL;DR

Long-horizon robot tasks require retaining and using past information. We integrate Test-Time Training (TTT), which stores context in fast weights, into InternVLA-A1 and Pi0.5 to study action generation conditioned on human demonstrations through training on paired demonstrations and robot trajectories.

## Related
<!-- [[other-paper-citekey]] -->
