---
citekey: "millanromeraGenerationHighLevelConcepts3DSceneGraphsAutoregressive2026"
title: "Generation of High-Level Concepts in 3D Scene Graphs via Autoregressive Diffusion"
authors: ["Jose Andres Millan-Romera", "Samuel Cognolato", "Holger Voos", "Jose Luis Sanchez-Lopez", "Luciano Serafini"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2608.28733"
doi: "10.48550/arXiv.2608.28733"
tags: [paper, embodied-ai, "cs.LG", "cs.RO"]
status: unread
rating:
created: 2026-09-02
---

# Generation of High-Level Concepts in 3D Scene Graphs via Autoregressive Diffusion

> Jose Andres Millan-Romera, Samuel Cognolato, Holger Voos, Jose Luis Sanchez-Lopez, Luciano Serafini · 2026
> [arXiv](https://arxiv.org/abs/2608.28733) · [PDF](https://arxiv.org/pdf/2608.28733)

## Abstract

Indoor 3D Scene Graphs (3DSGs) represent environments as multi-layer hierarchies that connect observed geometric primitives (e.g., planes) to higher-level metric-semantic concepts (e.g., rooms, floors, buildings), enabling incremental spatial reasoning for robotic perception and SLAM. However, classical high-level concept generation approaches rely on hand-crafted rules for specific concept classes, while learning-based methods require separate models for graph structure and spatial node features (e.g., centroids), which limits scalability to novel classes and more complex hierarchies. We propose a unified autoregressive diffusion-based graph generative model that jointly learns structure and features, constructing complete 3DSGs bottom-up from observed vertical planes across arbitrary hierarchy depths. Our method consistently surpasses all learning-based and random baselines across 3DSG datasets spanning synthetic scenes, real architectural floor plans, and robotic sensor data, with varying layout complexity and hierarchy depth, and surpasses a one-shot model with oracle access to the target graph size on the largest hierarchy and on real single-floor data. Finally, we propose an adaptation of the Fused Gromov--Wasserstein distance for principled graph-level evaluation of generated 3DSGs against ground truth.

## TL;DR

Indoor 3D Scene Graphs (3DSGs) represent environments as multi-layer hierarchies that connect observed geometric primitives (e.g., planes) to higher-level metric-semantic concepts (e.g., rooms, floors, buildings), enabling incremental spatial reasoning for robotic perception and SLAM. However, classical high-level concept generation approaches rely on hand-crafted rules for specific concept classes, while learning-based methods require separate models for graph structure and spatial node features (e.g., centroids), which limits scalability to novel classes and more complex hierarchies.

## Related
<!-- [[other-paper-citekey]] -->
