---
citekey: "rasulOnlinePlanningSparseGroundTargetSearchHighAltitude2026"
title: "Online Planning for Sparse Ground Target Search from a High-Altitude UAV under Partial Observability"
authors: ["Ashik E Rasul", "Hyung-Jin Yoon"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.01067"
doi: "10.48550/arXiv.2610.01067"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-03
---

# Online Planning for Sparse Ground Target Search from a High-Altitude UAV under Partial Observability

> Ashik E Rasul, Hyung-Jin Yoon · 2026
> [arXiv](https://arxiv.org/abs/2610.01067) · [PDF](https://arxiv.org/pdf/2610.01067)

## Abstract

Unmanned aerial vehicles (UAVs) searching for ground targets from a high altitude face a unique challenge, particularly when the target is already within the field of view but effectively unobservable because of its small apparent scale. Standard object detectors often underperform in such scenarios because of resolution downscaling and limited context. In contrast, active object search frameworks address this challenge by directing the agent to a suitable pose to gather richer visual information. However, flight regulations in urban airspace often restrict such physical movements for UAVs. As an alternative active sensing approach, the UAV can leverage the pan-tilt-zoom (PTZ) mechanism of the onboard camera to dynamically adjust its field of view and sequentially gather enhanced visual information from specific regions of interest. Once the candidate locations of the target are identified, it can deploy more expensive object detection schemes, such as an ensemble of multiple models, to get better reasoning at a fixed scale. In this work, we formulate the sequential exploration with PTZ operation as a partially observable Markov decision process (POMDP), in which the agent maintains a belief state over the target's true location. To solve the POMDP, we deploy partially observable Monte Carlo planning (POMCP), where we condition the sensing reliability on target object scale and deploy selective ensemble detection as an additional reasoning step. We validate our methodology with experiments in a photorealistic simulator under different environmental conditions and vehicle states, showing detection of ground targets at variable scales with significantly fewer steps and minimal dependence on sensor resolution compared to baseline methods.

## TL;DR

Unmanned aerial vehicles (UAVs) searching for ground targets from a high altitude face a unique challenge, particularly when the target is already within the field of view but effectively unobservable because of its small apparent scale. Standard object detectors often underperform in such scenarios because of resolution downscaling and limited context.

## Related
<!-- [[other-paper-citekey]] -->
