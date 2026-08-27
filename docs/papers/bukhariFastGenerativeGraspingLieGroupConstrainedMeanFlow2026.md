---
citekey: "bukhariFastGenerativeGraspingLieGroupConstrainedMeanFlow2026"
title: "Fast Generative Grasping via Lie Group-Constrained MeanFlow"
authors: ["S. Talha Bukhari", "Yi Wei", "Ruiqi Ni", "Zachary Kingston", "Aniket Bera"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2608.26076"
doi: "10.48550/arXiv.2608.26076"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-08-27
---

# Fast Generative Grasping via Lie Group-Constrained MeanFlow

> S. Talha Bukhari, Yi Wei, Ruiqi Ni, Zachary Kingston, Aniket Bera · 2026
> [arXiv](https://arxiv.org/abs/2608.26076) · [PDF](https://arxiv.org/pdf/2608.26076)

## Abstract

Grasp synthesis is a core task in robotic manipulation, for which the solution typically forms a multimodal distribution rather than a point estimate. Generative robotic grasping aims to learn this distribution with deep generative models such as diffusion and flow-based approaches. The iterative nature of such generative models makes them flexible and generalizable; however, multi-step sampling impedes the time-critical operation required in robotics. We devise an approach to fast generative grasping based on MeanFlow on the product Lie group $\mathcal{G} = \mathrm{SO}(3) \times \mathbb{R}^3$. The training objective couples a purely algebraic semigroup consistency condition with Riemannian Conditional Flow Matching on $\mathcal{G}$ that anchors the average velocity to the data distribution. The resulting Lie Group-constrained MeanFlow formulation samples reliable grasps in $\leq 5$ network evaluations, matching the grasp generation performance of state-of-the-art diffusion and flow-based models on the ACRONYM dataset at millisecond-scale inference latency (up to $39\times$ speed-up). We further demonstrate that the approach directly translates to real-world robotic grasping without additional training or domain adaptation, exhibiting robust grasp synthesis under observation noise.

## TL;DR

Grasp synthesis is a core task in robotic manipulation, for which the solution typically forms a multimodal distribution rather than a point estimate. Generative robotic grasping aims to learn this distribution with deep generative models such as diffusion and flow-based approaches.

## Related
<!-- [[other-paper-citekey]] -->
