---
citekey: "terrileFEMValidatedRealTimeModellingSoftTactileDeformation2026"
title: "FEM-Validated Real-Time Modelling of Soft Tactile Deformation"
authors: ["Silvia Terrile", "Kaichen Shi", "Taejun Kwon", "Jiseok Lee", "Nathan Lepora", "Yeejin Lee", "Saekwang Nam", "Efi Psomopoulou"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.16667"
doi: "10.48550/arXiv.2610.16667"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-16
---

# FEM-Validated Real-Time Modelling of Soft Tactile Deformation

> Silvia Terrile, Kaichen Shi, Taejun Kwon, Jiseok Lee, Nathan Lepora, Yeejin Lee, Saekwang Nam, Efi Psomopoulou · 2026
> [arXiv](https://arxiv.org/abs/2610.16667) · [PDF](https://arxiv.org/pdf/2610.16667)

## Abstract

Accurate modelling of soft tactile sensors remains difficult because finite element methods (FEM) are computa- tionally expensive, while real-time simulators often lack fidelity for hyperelastic deformation. Large physical datasets are also impractical to collect because repeated testing can damage fragile sensors. We present a data-efficient framework that combines limited real-world validation, high-fidelity FEM, and graph neural networks (GNNs) for accurate real-time prediction of two-dimensional tactile deformation in a planar soft tactile structure. The key idea is to decouple validation from training: 82 camera-tracked contact configurations are used only to tune and validate an ANSYS FEM model, which then generates 768 synthetic contact scenarios for GNN training. We evaluate both forward prediction from marker deformation to contact localisation and inverse inference from contact configuration to marker deformation. The validated FEM achieves sub-0.5 mm error in more than 90% of validation cases, while the learned GNN surrogate reaches a mean absolute error of 0.32 mm with millisecond-scale inference, compared with minute-scale FEM simulation. Models trained entirely on synthetic FEM data retain sub-millimetre accuracy on real measurements from the 2D tactile structure, demonstrating strong sim-to-real transfer within the tested planar setting. We further integrate the learned model into a real-time visualisation pipeline, enabling rapid deformation prediction for virtual prototyping and simulator-based design exploration without extensive physical testing.

## TL;DR

Accurate modelling of soft tactile sensors remains difficult because finite element methods (FEM) are computa- tionally expensive, while real-time simulators often lack fidelity for hyperelastic deformation. Large physical datasets are also impractical to collect because repeated testing can damage fragile sensors.

## Related
<!-- [[other-paper-citekey]] -->
