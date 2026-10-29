---
citekey: "zhuraFlockDiffusionAssignmentConditionedDiffusionMultiDroneTaskAllocation2026"
title: "FlockDiffusion: Assignment-Conditioned Diffusion for Multi-Drone Task Allocation and Completion"
authors: ["Iana Zhura", "Satenik Akopyan", "Roohan Ahmed Khan", "Miguel Altamirano Cabrera", "Aleksey Fedoseev", "Dzmitry Tsetserukou"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.23745"
doi: "10.48550/arXiv.2609.23745"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-23
---

# FlockDiffusion: Assignment-Conditioned Diffusion for Multi-Drone Task Allocation and Completion

> Iana Zhura, Satenik Akopyan, Roohan Ahmed Khan, Miguel Altamirano Cabrera, Aleksey Fedoseev, Dzmitry Tsetserukou · 2026
> [arXiv](https://arxiv.org/abs/2609.23745) · [PDF](https://arxiv.org/pdf/2609.23745)

## Abstract

Autonomous multi-drone navigation requires fleets to service distributed objectives in cluttered environments under tight computational budgets. Efficient coordination depends on task bundling, where each drone visits multiple objectives along its route. Separate solvers for cost estimation, assignment, and execution incur redundant graph search and produce long, abrupt paths. We propose FlockDiffusion, a learned framework combining a scene graph encoder, an explicit allocation head, an assignment conditioned diffusion transformer, and a closed form trajectory decoder. An autoregressive teacher provides offline supervision for parallel fleet trajectory generation. PyBullet ablations show that bundling increases task completion from 50% to 100%, while our complete teacher further reduces route cost by 8.4% relative to MAGNNET with bundling. In the optimized scalability benchmark, evaluated on 100 scenes per density with ten drones, FlockDiffusion achieves 6.2 to 7.6 times faster inference and approximately 37% shorter routes than the classical pipeline. As nominal task counts increase from 20 to 40, latency rises from 7.8 to 11.1 ms, compared with 48.0 to 75.8 ms for the baseline. In a separate evaluation across five Gazebo environments, FlockDiffusion achieves 100% planner coverage and reduces planned route cost by 15.4% relative to the baseline with bundling. These results demonstrate efficient planning under increasing task density in configurations that are demanding to reproduce with physical drone fleets.

## TL;DR

Autonomous multi-drone navigation requires fleets to service distributed objectives in cluttered environments under tight computational budgets. Efficient coordination depends on task bundling, where each drone visits multiple objectives along its route.

## Related
<!-- [[other-paper-citekey]] -->
