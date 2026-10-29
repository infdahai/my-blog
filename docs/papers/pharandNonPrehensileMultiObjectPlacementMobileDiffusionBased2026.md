---
citekey: "pharandNonPrehensileMultiObjectPlacementMobileDiffusionBased2026"
title: "Non-Prehensile Multi-Object Placement with Mobile Robots via Diffusion-Based Trajectory Planning"
authors: ["Lance Pharand", "Megnath Ramesh", "Mark Chiu", "Yash Vardhan Pant", "Stephen L. Smith"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.12684"
doi: "10.48550/arXiv.2610.12684"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-13
---

# Non-Prehensile Multi-Object Placement with Mobile Robots via Diffusion-Based Trajectory Planning

> Lance Pharand, Megnath Ramesh, Mark Chiu, Yash Vardhan Pant, Stephen L. Smith · 2026
> [arXiv](https://arxiv.org/abs/2610.12684) · [PDF](https://arxiv.org/pdf/2610.12684)

## Abstract

Non-prehensile manipulation with mobile robots has primarily targeted placement in coarse goal regions. Precision placement has been studied with manipulators on benchmarks such as Push-T, where an omnidirectional end effector can readily re-approach an object from any side. For a mobile robot, correcting the same placement errors may require wide repositioning maneuvers around the object. We formalize multi-object pushing with a mobile robot as a multi-target assignment problem at tight tolerances. We propose a diffusion planner with a causal factorization: each robot denoising step is followed by an object step conditioned on the current clean robot estimate. This factorization allows us to sample multiple object outcomes for a single robot plan, capturing the multi-modality of pushing. We also design a set of pushing-specific costs for mobile robots, used for both guidance and best-of-$N$ sampling at inference. On Push-T, our planner attains the highest success rate of the methods we compare, while having the lowest rate of implausible object motion. Across three multi-box pushing environments resembling warehouse scenarios, it raises the fraction of boxes placed by $21.5$ percentage points over an unguided baseline, and replans $1.8\times$ faster than a planner that denoises the two trajectories together. Lastly, we deploy the guided planner on a TurtleBot 3 Burger with object shapes absent from the training data, where it places $85.0\%$ of objects within tolerance against Diffusion Policy's $37.5\%$.

## TL;DR

Non-prehensile manipulation with mobile robots has primarily targeted placement in coarse goal regions. Precision placement has been studied with manipulators on benchmarks such as Push-T, where an omnidirectional end effector can readily re-approach an object from any side.

## Related
<!-- [[other-paper-citekey]] -->
