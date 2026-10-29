---
citekey: "xieLieSplineDPLieGroupBSplineDiffusionPolicy2026"
title: "LieSpline-DP: Lie-Group B-Spline Diffusion Policy for Smooth Robot Manipulation"
authors: ["Erxuan Xie", "Bang Liu", "Pingyun Nie", "Xingkai Liu", "Zhuang Fu", "Bo Zhang"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.15162"
doi: "10.48550/arXiv.2609.15162"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-16
---

# LieSpline-DP: Lie-Group B-Spline Diffusion Policy for Smooth Robot Manipulation

> Erxuan Xie, Bang Liu, Pingyun Nie, Xingkai Liu, Zhuang Fu, Bo Zhang · 2026
> [arXiv](https://arxiv.org/abs/2609.15162) · [PDF](https://arxiv.org/pdf/2609.15162)

## Abstract

Diffusion Policy (DP) is a powerful Learning from Demonstration (LfD) method for robotic manipulation, yet it suffers from discontinuous and non-smooth trajectories. Spline-based action representations promote smooth motion within individual action chunks, but existing spline-based methods neither guarantee cross-chunk $C^2$ continuity nor account for the group structure of $\mathrm{SE}(3)$. We therefore propose LieSpline-DP, a Lie-group B-spline diffusion policy that generates end-effector trajectories directly on $\mathrm{SE}(3)$ and couples consecutive plans by sharing their boundary control poses, ensuring $C^2$ continuity throughout the entire planned trajectory. Across three real-robot tasks, LieSpline-DP produces lower trajectory jerk and higher task success rates than the DP baseline. The gains are particularly pronounced in real-world tasks involving liquids and flexible objects: in our real-robot experiments, LieSpline-DP achieved a 100% success rate on both pouring and bucket hooking, whereas the DP baseline achieved only 10% and 30%, respectively.

## TL;DR

Diffusion Policy (DP) is a powerful Learning from Demonstration (LfD) method for robotic manipulation, yet it suffers from discontinuous and non-smooth trajectories. Spline-based action representations promote smooth motion within individual action chunks, but existing spline-based methods neither guarantee cross-chunk $C^2$ continuity nor account for the group structure of $\mathrm{SE}(3)$.

## Related
<!-- [[other-paper-citekey]] -->
