---
citekey: "wangDemonstrationSynthesisSingleScanGaussianSplattingVisuomotorPolicy2026"
title: "Demonstration Synthesis from a Single Scan via Gaussian Splatting for Visuomotor Policy Learning"
authors: ["Beichen Wang", "Yuen-Hei Yeung", "V. R. Sridhar Devarakonda", "Xuesu Xiao"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.21112"
doi: "10.48550/arXiv.2609.21112"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-22
---

# Demonstration Synthesis from a Single Scan via Gaussian Splatting for Visuomotor Policy Learning

> Beichen Wang, Yuen-Hei Yeung, V. R. Sridhar Devarakonda, Xuesu Xiao · 2026
> [arXiv](https://arxiv.org/abs/2609.21112) · [PDF](https://arxiv.org/pdf/2609.21112)

## Abstract

Training a visuomotor policy calls for abundant demonstrations that closely match the target environment, yet collecting them anew remains expensive. Existing demonstration synthesis methods reduce this cost but remain constrained by high manual effort, limited visual fidelity, or heavy reliance on physics simulators. This paper introduces GaussianFactory, a high-fidelity data engine that mass-produces demonstrations with a single video scan as its only human input and no physics engine in the generation loop. Specifically, GaussianFactory reconstructs the scene as an editable 3D Gaussian Splatting (3DGS) replica and samples from the object-combination tasks the scene affords. For each task, it plans grasps and trajectories purely kinematically on the geometric reconstruction, rendering photorealistic demonstrations that visually match the target environment. Physical dynamics enter the pipeline only where contact force interactions dictate the outcome---during grasp formation, via a learned contact model pretrained once on an interaction dataset. To evaluate the downstream utility of the synthesized demonstrations, we implement an end-to-end scan-to-deployment workflow in two setups: a simulated scene that stands in for the real world to enable reproducibility, and a real-world workspace with a physical UR10e robot. In each setup, a standard diffusion policy trained solely on the synthesized demonstrations achieves 95.1% and 84.2% success rates, respectively.

## TL;DR

Training a visuomotor policy calls for abundant demonstrations that closely match the target environment, yet collecting them anew remains expensive. Existing demonstration synthesis methods reduce this cost but remain constrained by high manual effort, limited visual fidelity, or heavy reliance on physics simulators.

## Related
<!-- [[other-paper-citekey]] -->
