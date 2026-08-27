---
citekey: "luoPassiveVideoEditableExperiencePhysicallyGroundedExperienceSynthesis2026"
title: "From Passive Video to Editable Experience: Physically Grounded Experience Synthesis for Embodied Intelligence"
authors: ["Jia Luo"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2607.26903"
doi: "10.48550/arXiv.2607.26903"
tags: [paper, embodied-ai, "cs.AI", "cs.RO"]
status: unread
rating:
created: 2026-08-27
---

# From Passive Video to Editable Experience: Physically Grounded Experience Synthesis for Embodied Intelligence

> Jia Luo · 2026
> [arXiv](https://arxiv.org/abs/2607.26903) · [PDF](https://arxiv.org/pdf/2607.26903)

## Abstract

The key bottleneck in embodied AI is not model architecture but data. Although billions of human manipulation videos exist online, robots cannot directly learn from them due to the embodiment gap between human morphology and robot hardware. We introduce Pegasus, a low-resource framework that bridges this gap by translating human demonstrations into robot-learnable data through structured knowledge transfer. Instead of relying on raw video prompts, Pegasus constructs a graph-based intermediate representation: a Task Graph extracted from human videos is transformed through Affordance and Constraint Graphs into a Robot Planning Graph for robot-conditioned video generation. A hierarchical affordance latent space models the relationship between object states, affordances, and tasks, enabling generalization beyond object identities. A closed-loop physics verifier further filters invalid generations using kinematic feasibility, collision constraints, and joint limits. We evaluate Pegasus across a range of egocentric manipulation benchmarks, including GTEA Gaze+ and EPIC-KITCHENS-100, and diverse robot embodiments, assessing Task Correctness, Executability, State Consistency, and Learnability. Results demonstrate reliable cross-embodiment translation and show that robot data generation can be reframed from a hardware collection problem into a scalable, low-resource knowledge transfer problem.

## TL;DR

The key bottleneck in embodied AI is not model architecture but data. Although billions of human manipulation videos exist online, robots cannot directly learn from them due to the embodiment gap between human morphology and robot hardware.

## Related
<!-- [[other-paper-citekey]] -->
