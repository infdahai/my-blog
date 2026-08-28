---
citekey: "kimCrossPlatformBenchmarkNeural3DReconstructionAutonomousLaboratory2026"
title: "Cross-Platform Benchmark of Neural 3D Reconstruction for Autonomous Laboratory Robots"
authors: ["Yongho Kim", "Mengjiao Han", "Victor Mateevitsi", "Silvio Rizzi", "Michael E. Papka", "Nicola Ferrier"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2608.26383"
doi: "10.48550/arXiv.2608.26383"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-08-28
---

# Cross-Platform Benchmark of Neural 3D Reconstruction for Autonomous Laboratory Robots

> Yongho Kim, Mengjiao Han, Victor Mateevitsi, Silvio Rizzi, Michael E. Papka, Nicola Ferrier · 2026
> [arXiv](https://arxiv.org/abs/2608.26383) · [PDF](https://arxiv.org/pdf/2608.26383)

## Abstract

Autonomous robots performing laboratory tasks depend on 3D reconstruction pipelines that can turn raw camera streams into actionable object representations within the latency budget of a physical control loop. Neural 3D reconstruction methods have demonstrated high-quality view synthesis, but their real-time viability across the compute platforms on which laboratory robots actually run remains poorly characterized. In this work, we present a systematic compute-platform benchmark of neural 3D reconstruction methods, evaluating NeRF and 3D Gaussian Splatting training and rendering on GPU-enabled computing devices ranging from single-board computers to server-class nodes, and place Meta's SAM3D single-image reconstruction on the same axes to quantify its latency and fidelity gap relative to per-scene optimization. Our results show that Gaussian Splatting yields higher rendering quality than NeRF at greater GPU cost, and that onboard compute is insufficient for full per-scene optimization at interactive rates. Our preliminary assessment on SAM3D indicates that it delivers plausible object geometry within seconds, but with detail mismatches that can compromise downstream manipulation. Together, these findings motivate tiered pipelines in which lightweight feed-forward reconstruction sustains the real-time perception-and-tracking loop for laboratory robots, while heavier neural reconstruction is scheduled selectively on suitable compute.

## TL;DR

Autonomous robots performing laboratory tasks depend on 3D reconstruction pipelines that can turn raw camera streams into actionable object representations within the latency budget of a physical control loop. Neural 3D reconstruction methods have demonstrated high-quality view synthesis, but their real-time viability across the compute platforms on which laboratory robots actually run remains poorly characterized.

## Related
<!-- [[other-paper-citekey]] -->
