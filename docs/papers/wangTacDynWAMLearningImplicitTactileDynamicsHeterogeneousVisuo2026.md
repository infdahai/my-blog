---
citekey: "wangTacDynWAMLearningImplicitTactileDynamicsHeterogeneousVisuo2026"
title: "TacDyn-WAM: Learning Implicit Tactile Dynamics in a Heterogeneous Visuo-Tactile World Action Model"
authors: ["Enyi Wang", "Mingxin Wang", "Quan Shi", "Hetian Guo", "Hongyu Wang", "Xi Wang", "Bin Qian", "Yupeng Zheng", "Wenxuan Song", "Houde Liu", "Yong Xu", "Cheng Chi", "Wenchao Ding", "Yilun Chen", "Yan Wang"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.00638"
doi: "10.48550/arXiv.2610.00638"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-03
---

# TacDyn-WAM: Learning Implicit Tactile Dynamics in a Heterogeneous Visuo-Tactile World Action Model

> Enyi Wang, Mingxin Wang, Quan Shi, Hetian Guo, Hongyu Wang, Xi Wang, Bin Qian, Yupeng Zheng, Wenxuan Song, Houde Liu, Yong Xu, Cheng Chi, Wenchao Ding, Yilun Chen, Yan Wang · 2026
> [arXiv](https://arxiv.org/abs/2610.00638) · [PDF](https://arxiv.org/pdf/2610.00638)

## Abstract

World action models improve robotic manipulation by conditioning actions on predicted futures, yet existing tactile variants largely inherit video-generation pipelines that reconstruct future tactile observations through iterative denoising. Such prediction can become unreliable under deployment drift: small changes in contact position or force may substantially alter tactile pixels even when the underlying contact evolution remains predictable. We introduce TacDyn-WAM, a heterogeneous visuo-tactile world action model that predicts implicit tactile dynamics rather than reconstructing future tactile observations. It learns TacRep, a dynamics-aware tactile target space trained through masked spatio-temporal prediction on tactile clips and regularized by relational structure distillation. A visual expert and an Implicit Tactile Dynamics Expert predict future visual and tactile representations in separate target spaces while interacting through joint attention; the tactile expert predicts future representations and their changes at multiple horizons in a single forward pass, and a read-only tactile memory supplies the current tactile state. On UniVTAC, TacDyn-WAM achieves an average success rate of 81.5% using only the provided demonstrations, reaching state-of-the-art-level performance and remaining competitive with models pretrained on large-scale visuo-tactile trajectories. Ablations confirm the benefits of both tactile pathways and TacRep over pixel-reconstruction and static alternatives. On five real-robot tasks, TacDyn-WAM reaches 71.0% average success, and modest-scale pretraining raises it to 85.0%, further validating our method.

## TL;DR

World action models improve robotic manipulation by conditioning actions on predicted futures, yet existing tactile variants largely inherit video-generation pipelines that reconstruct future tactile observations through iterative denoising. Such prediction can become unreliable under deployment drift: small changes in contact position or force may substantially alter tactile pixels even when the underlying contact evolution remains predictable.

## Related
<!-- [[other-paper-citekey]] -->
