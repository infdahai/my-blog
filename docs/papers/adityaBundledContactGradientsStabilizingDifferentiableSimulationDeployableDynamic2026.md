---
citekey: "adityaBundledContactGradientsStabilizingDifferentiableSimulationDeployableDynamic2026"
title: "Bundled Contact Gradients: Stabilizing Differentiable Simulation for Deployable Dynamic Tasks"
authors: ["Dyuman Aditya", "Jin Cheng", "Clemens Schwarke", "Quan Nguyen", "Gaurav Sukhatme", "Stelian Coros", "Gabriele Fadini"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.30951"
doi: "10.48550/arXiv.2609.30951"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-29
---

# Bundled Contact Gradients: Stabilizing Differentiable Simulation for Deployable Dynamic Tasks

> Dyuman Aditya, Jin Cheng, Clemens Schwarke, Quan Nguyen, Gaurav Sukhatme, Stelian Coros, Gabriele Fadini · 2026
> [arXiv](https://arxiv.org/abs/2609.30951) · [PDF](https://arxiv.org/pdf/2609.30951)

## Abstract

Differentiable simulation provides analytic gradients of robot dynamics, enabling fast and sample-efficient first-order policy optimization. However, obtaining smooth and informative gradients through rigid-body contact typically requires softened contact models, often at the expense of physical fidelity and thereby limiting learned policies largely to simulation. This trade-off becomes particularly consequential for dynamic humanoid motions, where accurate contact dynamics are critical for transferring policies to the real world. Increasing contact stiffness in rigid-body simulation improves the fidelity of interactions, but also makes the dynamics increasingly sensitive to small state perturbations, producing high-variance gradients that can destabilize first-order policy learning. To address this, we propose \emph{Bundled Contact Gradients (BCG)}, a contact-local randomized smoothing framework for differentiable policy learning. When stiff contact is detected, our method evaluates a local bundle of randomized perturbation rollouts around the stiff contact configuration and aggregates their gradient signal thereby reducing gradient variance. We demonstrate the effectiveness of our method by successfully training and transferring dynamic motions zero-shot onto a real-world Unitree G1 humanoid platform. Videos and supplementary information can be found at https://bundledcontactgradients.github.io/

## TL;DR

Differentiable simulation provides analytic gradients of robot dynamics, enabling fast and sample-efficient first-order policy optimization. However, obtaining smooth and informative gradients through rigid-body contact typically requires softened contact models, often at the expense of physical fidelity and thereby limiting learned policies largely to simulation.

## Related
<!-- [[other-paper-citekey]] -->
