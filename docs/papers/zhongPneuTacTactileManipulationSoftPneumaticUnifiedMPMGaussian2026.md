---
citekey: "zhongPneuTacTactileManipulationSoftPneumaticUnifiedMPMGaussian2026"
title: "PneuTac: Tactile Manipulation with Soft Pneumatic Robots via Unified MPM-Gaussian Splatting Simulation"
authors: ["Shaohong Zhong", "Marco Pontin", "Joe Watson", "Perla Maiolino", "Ingmar Posner"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.38418"
doi: "10.48550/arXiv.2609.38418"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-03
---

# PneuTac: Tactile Manipulation with Soft Pneumatic Robots via Unified MPM-Gaussian Splatting Simulation

> Shaohong Zhong, Marco Pontin, Joe Watson, Perla Maiolino, Ingmar Posner · 2026
> [arXiv](https://arxiv.org/abs/2609.38418) · [PDF](https://arxiv.org/pdf/2609.38418)

## Abstract

Soft robots and tactile sensors have demonstrated great potential in delicate manipulation tasks. Soft pneumatic robots enable safe contact through compliance, and vision-based tactile sensors offer high-resolution touch perception. However, learning tactile manipulation with compliant robots has been challenging, bottlenecked by the lack of efficient simulation. Existing simulators typically model them in isolation, and exhibit large calibration gaps that are difficult to overcome efficiently. We present PneuTac, a unified framework for tactile-feedback manipulation with soft pneumatic robots. We leverage the material point method (MPM) for modelling the dynamics of the soft robot and the deformable tactile membrane, and 3D Gaussian splatting (3DGS) for rendering. Real-to-sim modelling is done with a simple vision-based method, to then train action and perception networks for efficient simulation with surrogate models. We use the framework to drive a tactile-guided pipeline to collect demonstrations in simulation. Through experiments on a custom-designed pneumatic soft finger with a tactile sensing tip, together with additional cross-device evaluations, we show that PneuTac is capable of accurately modelling soft robots with tactile sensors, and that policies trained with simulation-augmented demonstrations outperform baselines trained on the same real data on three real-world contact-rich compliant manipulation tasks, making it a practical framework for tactile manipulation on compliant hardware.

## TL;DR

Soft robots and tactile sensors have demonstrated great potential in delicate manipulation tasks. Soft pneumatic robots enable safe contact through compliance, and vision-based tactile sensors offer high-resolution touch perception.

## Related
<!-- [[other-paper-citekey]] -->
