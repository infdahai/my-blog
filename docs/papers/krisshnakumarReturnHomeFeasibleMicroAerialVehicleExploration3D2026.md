---
citekey: "krisshnakumarReturnHomeFeasibleMicroAerialVehicleExploration3D2026"
title: "Return-to-Home Feasible Micro-Aerial Vehicle Exploration for 3D Gaussian Splatting Reconstruction"
authors: ["Prajit Krisshnakumar", "Fan Yang", "Koichiro Niinuma"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.04013"
doi: "10.48550/arXiv.2610.04013"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-07
---

# Return-to-Home Feasible Micro-Aerial Vehicle Exploration for 3D Gaussian Splatting Reconstruction

> Prajit Krisshnakumar, Fan Yang, Koichiro Niinuma · 2026
> [arXiv](https://arxiv.org/abs/2610.04013) · [PDF](https://arxiv.org/pdf/2610.04013)

## Abstract

Micro aerial vehicles (MAVs) enable rapid indoor 3D reconstruction for inspection and time-critical situational awareness, but must operate under strict flight-time budgets and safety constraints that require explicit return-to-home (RTH) feasibility with a conservative margin. We present a topology-first active reconstruction framework that decouples high-fidelity rendering from navigation. A dense 3D Gaussian Splatting (3DGS) map is optimized as the reconstruction target, while a lightweight Truncated Signed Distance Field (TSDF)/occupancy scaffold supports conservative collision checking and online construction of a sparse 3D Voronoi skeleton roadmap. Since directly extracting roadmaps from TSDF geometry can be unstable under noisy and incomplete online fusion, we validate nodes and edges using carved free-space consistency and dense visibility checks, which suppress behind-wall phantom structure and stabilize planning. Viewpoints are selected on the roadmap using a flight-time-budget-aware objective and a lightweight receding-horizon lookahead to improve non-myopic exploration behavior. We evaluate on photorealistic indoor simulation benchmarks (ReplicaCAD, Gibson, and HM3D), reporting reconstruction coverage/error, RTH success, and computational cost. Results demonstrate improved or competitive performance relative to recent GS-based baselines under identical flight-time budgets.

## TL;DR

Micro aerial vehicles (MAVs) enable rapid indoor 3D reconstruction for inspection and time-critical situational awareness, but must operate under strict flight-time budgets and safety constraints that require explicit return-to-home (RTH) feasibility with a conservative margin. We present a topology-first active reconstruction framework that decouples high-fidelity rendering from navigation.

## Related
<!-- [[other-paper-citekey]] -->
