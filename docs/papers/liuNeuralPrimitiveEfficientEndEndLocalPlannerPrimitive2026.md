---
citekey: "liuNeuralPrimitiveEfficientEndEndLocalPlannerPrimitive2026"
title: "Neural-Primitive: An Efficient End-to-end Local Planner with Primitive-based Imitation Learning for Autonomous Flight"
authors: ["Zhitao Liu", "Guangtong Xu", "Zihan Wang", "Jialiang Hou", "Chao Xu", "Fei Gao"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2608.20948"
doi: "10.48550/arXiv.2608.20948"
tags: [paper, embodied-ai, "cs.AI", "cs.RO"]
status: unread
rating:
created: 2026-09-07
---

# Neural-Primitive: An Efficient End-to-end Local Planner with Primitive-based Imitation Learning for Autonomous Flight

> Zhitao Liu, Guangtong Xu, Zihan Wang, Jialiang Hou, Chao Xu, Fei Gao · 2026
> [arXiv](https://arxiv.org/abs/2608.20948) · [PDF](https://arxiv.org/pdf/2608.20948)

## Abstract

Autonomous flight in unknown cluttered environments is hindered by the computation-quality-memory trilemma of onboard trajectory generation. In this paper, we propose an efficient end-to-end local planner via imitation learning. A lightweight offline-primitive-based dataset collection framework is designed to produce safe and high-quality trajectory primitives in non-convex environments. A compact neural network directly maps sensory inputs to polynomial coefficients that inherently encode higher-order dynamical information. The learned policy generates smooth, empirically collision-free and dynamically feasible trajectories in real time without back-end solving. It achieves ultra-fast computation (below 1ms on a standard desktop and average 3.68ms during onboard flight), while maintaining low onboard memory requirements (less than 1.5MiB). Extensive simulation benchmarks demonstrate superiority in both planning latency and target-reaching progress quality. Zero-shot deployment in real-world experiments further validates the robust sim-to-real transfer capability of the proposed method.

## TL;DR

Autonomous flight in unknown cluttered environments is hindered by the computation-quality-memory trilemma of onboard trajectory generation. In this paper, we propose an efficient end-to-end local planner via imitation learning.

## Related
<!-- [[other-paper-citekey]] -->
