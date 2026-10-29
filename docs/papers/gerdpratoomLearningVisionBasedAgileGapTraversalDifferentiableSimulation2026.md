---
citekey: "gerdpratoomLearningVisionBasedAgileGapTraversalDifferentiableSimulation2026"
title: "Learning Vision-Based Agile Gap Traversal: Differentiable Simulation with a Warm-Started Critic"
authors: ["Nuthasith Gerdpratoom", "Tianchen Sun", "Yichao Gao", "Lin Zhao"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.30696"
doi: "10.48550/arXiv.2609.30696"
tags: [paper, embodied-ai, "cs.RO", "eess.SY"]
status: unread
rating:
created: 2026-09-29
---

# Learning Vision-Based Agile Gap Traversal: Differentiable Simulation with a Warm-Started Critic

> Nuthasith Gerdpratoom, Tianchen Sun, Yichao Gao, Lin Zhao · 2026
> [arXiv](https://arxiv.org/abs/2609.30696) · [PDF](https://arxiv.org/pdf/2609.30696)

## Abstract

Traversing narrow gaps is challenging for autonomous quadrotors, especially when control commands come directly from high-dimensional visual observations. Existing end-to-end methods often rely on behavior cloning or full-rollout backpropagation through time (BPTT) via differentiable simulation, which can limit policy performance or incur high training costs. We propose a two-stage reinforcement learning framework for more efficient ego-centric visuomotor gap-traversal policy training, leveraging quasi-analytical policy gradients (QPG) via differentiable simulation and critic warm-starting. The framework utilizes QPG to avoid backpropagation through visual rendering, reducing computation and memory costs while improving sample efficiency. In the first stage, an expert actor and critic are trained using privileged observations, including gap geometry. Unlike prior gap-traversal approaches, our training utilizing QPG does not require resetting the agent along optimized reference trajectories. In the second stage, a visual policy is trained using binary gap masks from two ego-centric cameras and low-dimensional observations, while its privileged critic is warm-started from the first stage. This substantially improves training efficiency and traversal success compared with cold-starting the critic or using full-rollout BPTT. Our framework does not require retraining the expert actor when system parameters change, enabling more efficient generalization across drone platforms than state-of-the-art visual gap-traversal methods based on action supervision. The learned visual policy also generalizes to gaps with unseen shapes. Extensive real-world experiments further demonstrate robust gap traversal using binary masks rendered online. Beyond gap traversal, the proposed framework is generic and can be extended to other visuomotor robot learning tasks.

## TL;DR

Traversing narrow gaps is challenging for autonomous quadrotors, especially when control commands come directly from high-dimensional visual observations. Existing end-to-end methods often rely on behavior cloning or full-rollout backpropagation through time (BPTT) via differentiable simulation, which can limit policy performance or incur high training costs.

## Related
<!-- [[other-paper-citekey]] -->
