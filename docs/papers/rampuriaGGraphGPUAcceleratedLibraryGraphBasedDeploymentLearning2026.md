---
citekey: "rampuriaGGraphGPUAcceleratedLibraryGraphBasedDeploymentLearning2026"
title: "GGraph: A GPU-Accelerated Library for Graph-Based Robot Deployment and Learning"
authors: ["Yash Rampuria", "Rohan Garg", "Daniele Gammelli", "Marco Pavone"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.28953"
doi: "10.48550/arXiv.2610.28953"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-22
---

# GGraph: A GPU-Accelerated Library for Graph-Based Robot Deployment and Learning

> Yash Rampuria, Rohan Garg, Daniele Gammelli, Marco Pavone · 2026
> [arXiv](https://arxiv.org/abs/2610.28953) · [PDF](https://arxiv.org/pdf/2610.28953)

## Abstract

Autonomous mobile robots require spatial representations that capture geometry and semantics while staying sparse enough for planning in large, unknown environments. Graphs provide a natural representation for this purpose and underpin both classical planning methods and a growing class of reinforcement-learning (RL) policies. However, RL training needs hundreds to thousands of parallel environments, each constructing and updating its own graph. Existing graph libraries are typically designed for either single-robot deployment or fixed graphs, and CPU-based graph construction limits scalable training to only a few dozen environments. We introduce GGraph, an open-source GPU-accelerated graph library for both robot deployment and large-scale learning. GGraph supports real robots through ROS 2 interfaces and vectorized GPU-based policy training, with built-in support for tasks including 3-D navigation, exploration, and loop-closure integration. For single-robot operation, GGraph updates graphs in milliseconds. At scale, it enables graph-based exploration policies to train across hundreds of parallel robots, reducing wall-clock training time by one order of magnitude. Across simulation and real-world experiments, these results establish GGraph as a unified graph infrastructure for both large-scale robot learning and deployment.

## TL;DR

Autonomous mobile robots require spatial representations that capture geometry and semantics while staying sparse enough for planning in large, unknown environments. Graphs provide a natural representation for this purpose and underpin both classical planning methods and a growing class of reinforcement-learning (RL) policies.

## Related
<!-- [[other-paper-citekey]] -->
