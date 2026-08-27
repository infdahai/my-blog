---
citekey: "tokekarModelFreeAdaptiveParameterTuningEfficientMultiWarehouse2026"
title: "Model-Free Adaptive Parameter Tuning for Efficient Multi-Robot Warehouse Operations"
authors: ["Pratap Tokekar", "Mouhacine Benosman", "Rahul Chandan", "Alexandre Ormiga Galvao Barbosa", "Michael Caldara", "Joseph W. Durham"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2608.21533"
doi: "10.48550/arXiv.2608.21533"
tags: [paper, embodied-ai, "cs.RO", "eess.SY"]
status: unread
rating:
created: 2026-08-27
---

# Model-Free Adaptive Parameter Tuning for Efficient Multi-Robot Warehouse Operations

> Pratap Tokekar, Mouhacine Benosman, Rahul Chandan, Alexandre Ormiga Galvao Barbosa, Michael Caldara, Joseph W. Durham · 2026
> [arXiv](https://arxiv.org/abs/2608.21533) · [PDF](https://arxiv.org/pdf/2608.21533)

## Abstract

Robotic Fulfillment Centers (FCs) store inventory on shelves (pods) arranged in dense blocks. Retrieving a target pod that is buried deep in a block requires moving obstructing pods out of the way (i.e., digout). Multi-robot planners use parameterized cost functions to control digout behavior, producing a spectrum of strategies: at one extreme, obstructing pods are sent to other blocks (using more robots in travel lanes); at the other, pods are shuffled within the block (avoiding lane congestion but increasing extraction time). Each point on this spectrum has different downstream consequences for floor congestion and throughput. The optimal operating point depends on the specific facility configuration and shifts with operational conditions such as varying station demand and congestion patterns, making offline tuning impractical. We present an adaptive parameter tuning framework based on Extremum Seeking Control (ESC) that continuously adjusts planner parameters in response to measured throughput. ESC performs model-free optimization by perturbing parameters with sinusoidal dither signals and correlating perturbations with performance changes to estimate gradients, making it robust to the multi-minute delayed effects and credit assignment challenges inherent in large FC operations. Simulation studies demonstrate that the adaptive policy improves upon fixed policies across several conditions. We observe an improvement in throughput by an average of 5.0% across map and robot fleet size variations, and by 8.4% under dynamic operating conditions. This work eliminates manual parameter provisioning and enables real-time adaptation, providing a self-tuning paradigm for FC storage operations.

## TL;DR

Robotic Fulfillment Centers (FCs) store inventory on shelves (pods) arranged in dense blocks. Retrieving a target pod that is buried deep in a block requires moving obstructing pods out of the way (i.e., digout).

## Related
<!-- [[other-paper-citekey]] -->
