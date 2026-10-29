---
citekey: "penikaGPUResidentPipelineMulti3DInspectionLimitedPerception2026"
title: "A GPU-Resident Pipeline for Multi-Robot 3D Inspection with Limited Perception"
authors: ["Kryštof Pšenička", "Stefan Edelkamp"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.26106"
doi: "10.48550/arXiv.2610.26106"
tags: [paper, embodied-ai, "cs.MA", "cs.RO"]
status: unread
rating:
created: 2026-10-22
---

# A GPU-Resident Pipeline for Multi-Robot 3D Inspection with Limited Perception

> Kryštof Pšenička, Stefan Edelkamp · 2026
> [arXiv](https://arxiv.org/abs/2610.26106) · [PDF](https://arxiv.org/pdf/2610.26106)

## Abstract

We present a complete, GPU-resident pipeline for multi-robot 3D inspection of underwater structures. Given a triangle mesh and a fleet of $K$ robots, each carrying a short-range, limited field-of-view camera, the pipeline computes 6-DOF trajectories that jointly cover a target fraction of the surface while minimizing a linearly interpolated makespan/total-cost objective. The joint problem is NP-hard, so we decompose it into five core stages - candidate viewpoint generation, visibility computation, set cover, min-max vehicle routing solved as a mixed integer program (MIP) with lifted Miller-Tucker-Zemlin subtour elimination, and priority-based multi-agent path finding with continuous-time inter-robot conflict checking - flanked by mesh loading and surface sampling as preprocessing and by trajectory smoothing as postprocessing. Our contributions are: an end-to-end GPU-accelerated integration of the five stages, with its kernel design documented; a GPU batch adaptation of Lien's $\varepsilon$-visibility with four custom CUDA kernels; a $β$-aware per-vehicle tour upper bound derived from the interpolated objective, supplementing the Desrochers-Laporte coefficient lift with forbidden-pair cuts; a 4D space-time extension of Zhou and Zeng's GPU parallel-frontier A*; and an experimental evaluation on 14 meshes (up to $7.2$M faces) that ablates the routing cuts and the parallel-frontier search, audits collision freedom and waypoint attainment \emph{after} trajectory smoothing, and measures the end-to-end gap against analytical and LP-relaxation lower bounds. Code and raw results are publicly available.

## TL;DR

We present a complete, GPU-resident pipeline for multi-robot 3D inspection of underwater structures. Given a triangle mesh and a fleet of $K$ robots, each carrying a short-range, limited field-of-view camera, the pipeline computes 6-DOF trajectories that jointly cover a target fraction of the surface while minimizing a linearly interpolated makespan/total-cost objective.

## Related
<!-- [[other-paper-citekey]] -->
