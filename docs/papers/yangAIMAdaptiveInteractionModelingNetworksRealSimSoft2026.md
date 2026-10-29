---
citekey: "yangAIMAdaptiveInteractionModelingNetworksRealSimSoft2026"
title: "AIM: Adaptive Interaction Modeling Networks for Real-to-Sim Soft-Body Simulation"
authors: ["Tiancheng Yang", "Dingshuo Chen", "Tianle Chen", "Zhaocheng Liu", "Qiang Liu"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.07116"
doi: "10.48550/arXiv.2610.07116"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-08
---

# AIM: Adaptive Interaction Modeling Networks for Real-to-Sim Soft-Body Simulation

> Tiancheng Yang, Dingshuo Chen, Tianle Chen, Zhaocheng Liu, Qiang Liu · 2026
> [arXiv](https://arxiv.org/abs/2610.07116) · [PDF](https://arxiv.org/pdf/2610.07116)

## Abstract

Deformable-object manipulation is essential for robotic tasks such as folding laundry and handling food, where robots must control shape changes as well as object motion. Predictive soft-body simulation supports these tasks by anticipating deformation under external interactions. However, spatial neighborhoods can misrepresent deformation dependencies, introducing local errors that accumulate over successive predictions. Models fitted to individual scenes must also accommodate changes in object geometry and manipulation conditions. In this work, we propose AIM, an Adaptive Interaction Modeling framework that treats real-to-sim soft-body simulation as a local-global interaction modeling problem. AIM uses motion history and geometry to adapt particle relations over current spatial neighbors and retained connections, while geometry-conditioned global communication coordinates object-wide responses. A unified kinematic control-point interface represents different manipulation configurations, and multi-step autoregressive supervision trains the model on its own predicted trajectories. Experiments on PhysTwin and PGND demonstrate improved motion accuracy and visual fidelity, with a 20.0% reduction in future-prediction tracking error relative to PhysTwin and a 22.8% reduction in mean long-horizon particle error across six object categories relative to PGND. The framework further supports transfer across actions, object instances, and scenes, including zero-shot transfer from robot interactions to human manipulation without target-domain dynamics fitting.

## TL;DR

Deformable-object manipulation is essential for robotic tasks such as folding laundry and handling food, where robots must control shape changes as well as object motion. Predictive soft-body simulation supports these tasks by anticipating deformation under external interactions.

## Related
<!-- [[other-paper-citekey]] -->
