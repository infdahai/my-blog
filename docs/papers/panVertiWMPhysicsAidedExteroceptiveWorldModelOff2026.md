---
citekey: "panVertiWMPhysicsAidedExteroceptiveWorldModelOff2026"
title: "Verti-WM: A Physics-Aided Exteroceptive World Model for Off-Road Reinforcement Learning"
authors: ["Chenhui Pan", "Tong Xu", "Xuesu Xiao"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.23118"
doi: "10.48550/arXiv.2609.23118"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-22
---

# Verti-WM: A Physics-Aided Exteroceptive World Model for Off-Road Reinforcement Learning

> Chenhui Pan, Tong Xu, Xuesu Xiao · 2026
> [arXiv](https://arxiv.org/abs/2609.23118) · [PDF](https://arxiv.org/pdf/2609.23118)

## Abstract

Reinforcement learning for off-road navigation requires extensive vehicle-terrain interaction data, which are costly to collect in high-fidelity simulation. World models offer a promising alternative by replacing simulator roll-outs during policy optimization. However, an off-road world model must condition state transitions on exteroceptive terrain information, which proprioception alone does not provide. This challenge is further amplified by the need to model both rigid and deformable terrain, where data-driven and physics-based approaches offer complementary strengths. We propose Verti-WM, a physics-aided exteroceptive world model that recurrently fuses a frozen Transformer for rigid terrain and a neuro-symbolic terramechanics model for deformable terrain. Elevation and semantic observations queried from a supplied map at each predicted pose condition fusion, enabling six-degree-of-freedom rollouts for policy optimization without further simulator access. Verti-WM reduces prediction error by 34.6% and 21.7% over data-driven and physics-based baselines, respectively. Policies trained entirely within Verti-WM achieve comparable task success rates while reducing computation time by 23.6X relative to direct training in the high-fidelity simulator. We further validate Verti-WM using real-world data, enabling policy optimization within learned real-world kinodynamics and achieving a 80% success rate on the Verti-4-Wheeler platform, compared with 40% for direct sim-to-real transfer.

## TL;DR

Reinforcement learning for off-road navigation requires extensive vehicle-terrain interaction data, which are costly to collect in high-fidelity simulation. World models offer a promising alternative by replacing simulator roll-outs during policy optimization.

## Related
<!-- [[other-paper-citekey]] -->
