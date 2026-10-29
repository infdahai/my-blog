---
citekey: "zhangStackGen3DStable3DBlockStackGenerationMultiviewSilhouettes2026"
title: "StackGen3D: Stable 3D Block Stack Generation from Multiview Silhouettes"
authors: ["Xiaopeng Zhang", "Luzhe Sun", "Yiqing Xu", "Matthew R. Walter"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.31803"
doi: "10.48550/arXiv.2610.31803"
tags: [paper, embodied-ai, "cs.CV", "cs.RO"]
status: unread
rating:
created: 2026-10-27
---

# StackGen3D: Stable 3D Block Stack Generation from Multiview Silhouettes

> Xiaopeng Zhang, Luzhe Sun, Yiqing Xu, Matthew R. Walter · 2026
> [arXiv](https://arxiv.org/abs/2610.31803) · [PDF](https://arxiv.org/pdf/2610.31803)

## Abstract

Generating physically stable 3D structures from visual specifications requires resolving geometric ambiguity while accounting for physical interactions among objects. We present StackGen3D, a framework for generating stable block assemblies conditioned on a given block inventory and three orthographic silhouettes. Our approach consists of two stages. First, we develop a physics-informed graph neural network (PI-GNN) that models support relations between blocks and serves as a fast stability predictor for curating a diverse dataset of stable structures. Second, we train a conditional flow-matching model on this dataset to capture the multimodal distribution of block configurations consistent with the target silhouettes. At inference time, lightweight geometric selection and refinement reduce inter-block penetration without physics simulation. Preliminary experiments show that the PI-GNN generalizes from simple stacks to complex structures substantially better than a parameter-matched multilayer perceptron. For structure generation, Best-of-10 selection improves physical stability from 45.3% to 72.4% while achieving a silhouette IoU of 0.970. These results highlight the potential of combining relational physical reasoning, scalable data curation, and conditional generative modeling for creative 3D assembly. Project website: [https://ripl.github.io/StackGen3D-web/](https://ripl.github.io/StackGen3D-web/)

## TL;DR

Generating physically stable 3D structures from visual specifications requires resolving geometric ambiguity while accounting for physical interactions among objects. We present StackGen3D, a framework for generating stable block assemblies conditioned on a given block inventory and three orthographic silhouettes.

## Related
<!-- [[other-paper-citekey]] -->
