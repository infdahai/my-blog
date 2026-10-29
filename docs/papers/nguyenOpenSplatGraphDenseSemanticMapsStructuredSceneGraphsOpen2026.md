---
citekey: "nguyenOpenSplatGraphDenseSemanticMapsStructuredSceneGraphsOpen2026"
title: "OpenSplatGraph: From Dense Semantic Maps to Structured Scene Graphs for Open-Vocabulary Robot Perception"
authors: ["Binh Long Nguyen", "Kien Nguyen", "Clinton Fookes", "Peyman Moghadam"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.07569"
doi: "10.48550/arXiv.2610.07569"
tags: [paper, embodied-ai, "cs.AI", "cs.CV", "cs.RO"]
status: unread
rating:
created: 2026-10-08
---

# OpenSplatGraph: From Dense Semantic Maps to Structured Scene Graphs for Open-Vocabulary Robot Perception

> Binh Long Nguyen, Kien Nguyen, Clinton Fookes, Peyman Moghadam · 2026
> [arXiv](https://arxiv.org/abs/2610.07569) · [PDF](https://arxiv.org/pdf/2610.07569)

## Abstract

Dense 3D mapping with semantic understanding is essential for robotic perception in complex environments. Recent 3D Gaussian Splatting-based mapping approaches enable high-fidelity geometry and efficient open-vocabulary perception, but typically represent semantics as unstructured feature fields that limit object-centric reasoning. In contrast, 3D scene graphs explicitly model objects and their relationships for structured reasoning, but are commonly constructed from sparse geometric representations that do not fully exploit dense semantic maps. In this work, we present OpenSplatGraph, a unified framework that constructs persistent 3D scene graphs directly from an online Gaussian-based open-vocabulary semantic map. The proposed framework augments the dense semantic map with a reliability-aware semantic field that maintains lightweight observation statistics for confidence-aware, query-conditioned object extraction. Extracted object instances are associated with persistent graph nodes, allowing object attributes and relationships to be incrementally updated across observations and queries. By tightly coupling dense semantic mapping with persistent object-centric representations, our framework supports both language-guided object grounding and structured relational reasoning while preserving the geometric fidelity of Gaussian-based mapping. Comprehensive evaluations on standard 3D scene understanding benchmarks and real-world robotic experiments demonstrate that OpenSplatGraph achieves competitive performance for online open-vocabulary perception and downstream robotic tasks. Project page: https://csiro-robotics.github.io/OpenSplatGraph.

## TL;DR

Dense 3D mapping with semantic understanding is essential for robotic perception in complex environments. Recent 3D Gaussian Splatting-based mapping approaches enable high-fidelity geometry and efficient open-vocabulary perception, but typically represent semantics as unstructured feature fields that limit object-centric reasoning.

## Related
<!-- [[other-paper-citekey]] -->
