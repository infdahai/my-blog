---
citekey: "liChainSLAMGloballyConsistentBackendMultiSessionLiDAR2026"
title: "Chain-SLAM: Globally Consistent Backend for Multi-Session LiDAR SLAM via Chained Loop Closure"
authors: ["Zhiheng Li", "Xinhao Liu", "Juexiao Zhang", "Yongqing Liang", "Chen Feng"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.12221"
doi: "10.48550/arXiv.2609.12221"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-15
---

# Chain-SLAM: Globally Consistent Backend for Multi-Session LiDAR SLAM via Chained Loop Closure

> Zhiheng Li, Xinhao Liu, Juexiao Zhang, Yongqing Liang, Chen Feng · 2026
> [arXiv](https://arxiv.org/abs/2609.12221) · [PDF](https://arxiv.org/pdf/2609.12221)

## Abstract

Maintaining consistency over long spatial and temporal horizons remains a fundamental challenge in large-scale LiDAR SLAM, particularly when integrating maps collected across multiple sessions. We present Chain-SLAM, a LiDAR SLAM backend enabling online multi-session map alignment and reuse with global consistency at large scale. We implement a chained loop closure mechanism that efficiently propagates geometric constraints across inter-session keyframes through an adjacency graph, enabling robust long-horizon consistency triggered by reliable short-horizon loop closures. The system initializes inter-session alignment with GNSS-proximity place recognition, then performs on-the-fly loop closure detections and joint optimization of loaded maps and newly acquired trajectories within a unified factor graph, maintaining both inter- and intra-session geometric consistency without dynamic object removal, and cross-platform robustness with minimal hyperparameter tuning. Experimental results show improved trajectory accuracy and robust multi-session integration on large-scale datasets. We release our source code to support reproducible research in large-scale multi-session LiDAR SLAM. Project site: https://ai4ce.github.io/Chain-SLAM/

## TL;DR

Maintaining consistency over long spatial and temporal horizons remains a fundamental challenge in large-scale LiDAR SLAM, particularly when integrating maps collected across multiple sessions. We present Chain-SLAM, a LiDAR SLAM backend enabling online multi-session map alignment and reuse with global consistency at large scale.

## Related
<!-- [[other-paper-citekey]] -->
