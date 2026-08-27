---
citekey: "hanSRLMPCShapeAwareReinforcementLearnedModelPredictive2026"
title: "SRL-MPC: Shape-Aware Reinforcement Learned Model Predictive Control"
authors: ["Ruihua Han", "Rui Gao", "Zhe Liu", "Xinyi Wang", "Chang Chen", "Shuai Wang", "Qi Hao", "Jia Pan", "Hengshuang Zhao"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2608.21175"
doi: "10.48550/arXiv.2608.21175"
tags: [paper, embodied-ai, "cs.AI", "cs.RO"]
status: unread
rating:
created: 2026-08-27
---

# SRL-MPC: Shape-Aware Reinforcement Learned Model Predictive Control

> Ruihua Han, Rui Gao, Zhe Liu, Xinyi Wang, Chang Chen, Shuai Wang, Qi Hao, Jia Pan, Hengshuang Zhao · 2026
> [arXiv](https://arxiv.org/abs/2608.21175) · [PDF](https://arxiv.org/pdf/2608.21175)

## Abstract

Safe and efficient shape-aware navigation in heterogeneous crowds and robot fleets remains challenging. Traditional approaches often assume homogeneous robots, sparse workspaces, simplified geometry, offline computation, or handcrafted parameters to make the problem tractable, which limits their deployment in dense crowd scenarios. Toward this end, we propose Shape-Aware Reinforcement Learned Model Predictive Control (SRL-MPC), a method for safe, efficient, and adaptive navigation in crowds with heterogeneous shapes without geometry simplification. To encode shape-aware safety, we formulate high-order control barrier function (HOCBF) constraints from geometric separation features (GSFs) based on support function transformation. A reinforcement learning (RL) framework then learns a neural policy that reads GSFs and outputs real-time MPC parameter updates, enabling the MPC solver to adapt to neighboring crowd geometries. The key advantage of SRL-MPC is that it preserves the safety structure and generalizability of MPC while integrating the adaptability and intelligence of RL. Experiments in randomized crowd scenarios with arbitrary shaped robot fleets demonstrate the effectiveness, scalability, and robustness of SRL-MPC. The results show that SRL-MPC substantially outperforms representative baselines in safety and adaptability. Project website: https://hanruihua.github.io/srl_mpc_project/

## TL;DR

Safe and efficient shape-aware navigation in heterogeneous crowds and robot fleets remains challenging. Traditional approaches often assume homogeneous robots, sparse workspaces, simplified geometry, offline computation, or handcrafted parameters to make the problem tractable, which limits their deployment in dense crowd scenarios.

## Related
<!-- [[other-paper-citekey]] -->
