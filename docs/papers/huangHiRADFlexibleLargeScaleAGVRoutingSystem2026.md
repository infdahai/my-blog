---
citekey: "huangHiRADFlexibleLargeScaleAGVRoutingSystem2026"
title: "HiRAD: A Flexible Large-Scale AGV Routing System"
authors: ["Yunjie Huang", "Ruizhong Wu", "Mengxuan Zhang", "Frodo Kin Sun Chan", "Yan Nei Law", "Lei Li"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.09752"
doi: "10.48550/arXiv.2609.09752"
tags: [paper, embodied-ai, "cs.AI", "cs.RO"]
status: unread
rating:
created: 2026-09-11
---

# HiRAD: A Flexible Large-Scale AGV Routing System

> Yunjie Huang, Ruizhong Wu, Mengxuan Zhang, Frodo Kin Sun Chan, Yan Nei Law, Lei Li · 2026
> [arXiv](https://arxiv.org/abs/2609.09752) · [PDF](https://arxiv.org/pdf/2609.09752)

## Abstract

Automatic Guided Vehicles (AGVs) substantially boost warehouse throughput, but routing large-scale AGV fleets remains challenging. Classical Multi-Agent Pathfinding solvers suffer from exploding combinatorial complexity and super-quadratic runtime, while relying on idealized grid or piecewise-linear motion models that mismatch real-world kinematics. Recent Reinforcement Learning (RL) solutions improve flexibility via decentralized agent policies but depend on discretized spatiotemporal representations, require millions of episodes to converge, and incur full-map observation at every step, which leads to large models, slow convergence, and high inference latency that violates real-time industrial control constraints. To address these bottlenecks, we propose HiRAD, a hierarchical RL framework for continuous-space AGV routing with real-time guarantees: (1) a step-level spatiotemporal representation that translates continuous motion into a differentiable RL problem, (2) a hierarchical strategy that splits heading choice from velocity control to reduce the action space, and (3) an asynchronous event-driven decision pipeline that lowers inference complexity from O(n^2) to O(n) and cuts per-step latency by as much as 71 percent. Across random graphs and two warehouse maps, HiRAD reduces makespan by 45 percent to 63 percent and shortens end-to-end runtime.

## TL;DR

Automatic Guided Vehicles (AGVs) substantially boost warehouse throughput, but routing large-scale AGV fleets remains challenging. Classical Multi-Agent Pathfinding solvers suffer from exploding combinatorial complexity and super-quadratic runtime, while relying on idealized grid or piecewise-linear motion models that mismatch real-world kinematics.

## Related
<!-- [[other-paper-citekey]] -->
