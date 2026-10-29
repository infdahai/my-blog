---
citekey: "ojalaMappingTireRoadFrictionCoefficientsAlongDrivenTrajectories2026"
title: "Mapping Tire-Road Friction Coefficients Along Driven Trajectories"
authors: ["Risto Ojala"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.14235"
doi: "10.48550/arXiv.2610.14235"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-15
---

# Mapping Tire-Road Friction Coefficients Along Driven Trajectories

> Risto Ojala · 2026
> [arXiv](https://arxiv.org/abs/2610.14235) · [PDF](https://arxiv.org/pdf/2610.14235)

## Abstract

Information of the tire-road friction coefficient is critical for intelligent vehicle systems, as friction establishes the limits at which the vehicle can be manoeuvred without loss of control. While there is extensive literature on online friction estimation, no previous studies have explored post-processing and mapping friction coefficients along a driven trajectory based on recorded sensor data. Mapped friction information could be shared by connected vehicles, enabling proactive measures in low-friction areas. This paper presents an offline post-processing method, FrictionMap, for mapping friction coefficients from recorded driving data. The method operates on commonly available on-board vehicle sensor information, and requires only a basic vehicle parameter set and a slip threshold as prior knowledge. FrictionMap runs an extended Kalman filter combined with a Rauch-Tung-Striebel smoother to estimate vehicle dynamics. Data points where the friction limit is observable are identified by filtering points based on tire slip. A Gaussian process is fitted to these points to acquire a continuous estimate of the friction coefficient along the trajectory. FrictionMap is validated via a simulation study, and shown to outperform commonly used online friction estimation techniques. The code implementation and the simulation benchmark are released as open-source after paper acceptance to enable further research.

## TL;DR

Information of the tire-road friction coefficient is critical for intelligent vehicle systems, as friction establishes the limits at which the vehicle can be manoeuvred without loss of control. While there is extensive literature on online friction estimation, no previous studies have explored post-processing and mapping friction coefficients along a driven trajectory based on recorded sensor data.

## Related
<!-- [[other-paper-citekey]] -->
