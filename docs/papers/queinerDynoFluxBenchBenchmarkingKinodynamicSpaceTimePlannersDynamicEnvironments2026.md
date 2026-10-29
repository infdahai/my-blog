---
citekey: "queinerDynoFluxBenchBenchmarkingKinodynamicSpaceTimePlannersDynamicEnvironments2026"
title: "DynoFluxBench: Benchmarking Kinodynamic Space-Time Planners in Dynamic Environments"
authors: ["Franz Queißner", "Andreas Orthey", "Wolfgang Hönig"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.18549"
doi: "10.48550/arXiv.2609.18549"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-17
---

# DynoFluxBench: Benchmarking Kinodynamic Space-Time Planners in Dynamic Environments

> Franz Queißner, Andreas Orthey, Wolfgang Hönig · 2026
> [arXiv](https://arxiv.org/abs/2609.18549) · [PDF](https://arxiv.org/pdf/2609.18549)

## Abstract

Robots that leave structured, static environments must plan motions that are kinodynamically feasible and safe among moving obstacles. However, there are no dedicated benchmark frameworks that combine both aspects. To overcome this, we present DynoFluxBench, a framework to compare kinodynamic planners in known, dynamic environments with unbounded arrival time. To demonstrate its utility and establish strong baselines, we develop three dedicated planners, named ST-Db-RRT, ST-GBRRT, and KIST, that fuse kinodynamic and space-time methods, covering different kinodynamic search paradigms: ST-Db-RRT expands with randomly selected discontinuity-bounded motion primitives using trajectory optimization, whereas KIST and ST-GBRRT maintain a kinodynamically feasible tree with different heuristic guidance. We analyze the probabilistic completeness guarantees of those new planners in dynamic environments. Finally, we evaluate ST-Db-RRT, ST-GBRRT, and KIST using DynoFluxBench, showing that ST-Db-RRT reaches a first solution up to 32 times faster, while KIST and ST-GBRRT remain valuable where trajectory optimization is fragile. Videos and further analysis can be found at https://dynofluxbench.github.io/dynofluxbench/.

## TL;DR

Robots that leave structured, static environments must plan motions that are kinodynamically feasible and safe among moving obstacles. However, there are no dedicated benchmark frameworks that combine both aspects.

## Related
<!-- [[other-paper-citekey]] -->
