---
citekey: "shenLD4WAMLearningLatentDynamicsHumanVideosWorldAction2026"
title: "LD4WAM: Learning Latent Dynamics from Human Videos for World Action Models"
authors: ["Zhenhao Shen", "Jiaqi Liang", "Jasper Lu", "Feng Jiang", "Yuran Wang", "Chuanbo Wei", "Jiayi Liu", "Jianchun Yang", "Qize Yu", "Jiadi You", "Ce Hao", "Guanqi He", "Chen Xie", "Ruihai Wu"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2608.22403"
doi: "10.48550/arXiv.2608.22403"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-08-27
---

# LD4WAM: Learning Latent Dynamics from Human Videos for World Action Models

> Zhenhao Shen, Jiaqi Liang, Jasper Lu, Feng Jiang, Yuran Wang, Chuanbo Wei, Jiayi Liu, Jianchun Yang, Qize Yu, Jiadi You, Ce Hao, Guanqi He, Chen Xie, Ruihai Wu · 2026
> [arXiv](https://arxiv.org/abs/2608.22403) · [PDF](https://arxiv.org/pdf/2608.22403)

## Abstract

Human video is playing an increasingly central role in training World Action Models (WAMs), owing to its diversity and low collection cost relative to teleoperated robot data. However, most WAMs learn from such video only by predicting pixel-level future frames, giving dynamics that are not directly actionable, whereas motion retargeting recovers directly actionable actions but leaves a large visual gap across embodiments. We therefore propose motion-aligned latent dynamics as an embodiment-agnostic representation to bridge video priors and low-level actions. We further present LD4WAM, which pairs a Latent Dynamics Model trained with semantic reconstruction and real motion alignment with a World Dynamics Action Model built as a mixture-of-transformers (MoT), which preserves full future-video generation and uses learnable queries to distill these latent dynamics from generated futures for action conditioning. Pretrained on our curated unified dataset of over 5{,}000 hours of human and robot data, LD4WAM performs strongly in RoboTwin simulation and on real robots equipped with both grippers and dexterous hands, while generalizing well to unseen objects and backgrounds.

## TL;DR

Human video is playing an increasingly central role in training World Action Models (WAMs), owing to its diversity and low collection cost relative to teleoperated robot data. However, most WAMs learn from such video only by predicting pixel-level future frames, giving dynamics that are not directly actionable, whereas motion retargeting recovers directly actionable actions but leaves a large visual gap across embodiments.

## Related
<!-- [[other-paper-citekey]] -->
