---
citekey: "chenModelPredictiveControlTensegrityContactAwareGraphNeural2026"
title: "Model Predictive Control of Tensegrity Robots via Contact-Aware Graph Neural Dynamics Model"
authors: ["Nelson Chen", "Patrick Meng", "Charles Tang", "Angelina Degay", "Zachary Brei", "Rebecca Kramer-Bottiglio", "Kostas E. Bekris", "Mridul Aanjaneya"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.08958"
doi: "10.48550/arXiv.2609.08958"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-11
---

# Model Predictive Control of Tensegrity Robots via Contact-Aware Graph Neural Dynamics Model

> Nelson Chen, Patrick Meng, Charles Tang, Angelina Degay, Zachary Brei, Rebecca Kramer-Bottiglio, Kostas E. Bekris, Mridul Aanjaneya · 2026
> [arXiv](https://arxiv.org/abs/2609.08958) · [PDF](https://arxiv.org/pdf/2609.08958)

## Abstract

Tensegrity robots offer lightweight, compliant mobility over challenging terrain but remain difficult to model and control due to complex contact-rich dynamics and partial observability. This work presents a model predictive path integral (MPPI) controller for a three-bar tensegrity robot driven by a learned graph neural network (GNN) dynamics model. This work first extends prior GNN-based models with a differentiable contact detection module. The extension allows the dynamics model to reason over non-horizontal planar terrains, obstacles, as well as self-collisions. Then, the learned dynamics model and the MPPI controller operate in a closed data-collection loop, iteratively improving model accuracy and control performance. This work further introduces a hybrid MPPI strategy that combines MPPI with turning motion primitives to improve maneuverability. Experiments are performed in MuJoCo across five navigation tasks, which include, wall obstacles, inclines, narrow corridors, low-clearance structures, and a composite 3D obstacle course. The experiments demonstrate that the hybrid MPPI controller operating over the learned GNN dynamics model improves predictive accuracy over a flat-ground baseline model and achieves superior navigation performance compared to $A^*$-based re-planning and MPPI-only variants. Results show that the contact-aware learned dynamics combined with the sampling-based model predictive control enable robust tensegrity navigation in complex, contact-rich environments.

## TL;DR

Tensegrity robots offer lightweight, compliant mobility over challenging terrain but remain difficult to model and control due to complex contact-rich dynamics and partial observability. This work presents a model predictive path integral (MPPI) controller for a three-bar tensegrity robot driven by a learned graph neural network (GNN) dynamics model.

## Related
<!-- [[other-paper-citekey]] -->
