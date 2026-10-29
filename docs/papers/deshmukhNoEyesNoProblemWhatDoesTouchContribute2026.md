---
citekey: "deshmukhNoEyesNoProblemWhatDoesTouchContribute2026"
title: "No Eyes, No Problem: What Does Touch Contribute to Blind Baoding Ball Manipulation?"
authors: ["Ayush Deshmukh", "Nalin Agarwal", "Elle Miller", "Sethu Vijayakumar"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.23438"
doi: "10.48550/arXiv.2610.23438"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-22
---

# No Eyes, No Problem: What Does Touch Contribute to Blind Baoding Ball Manipulation?

> Ayush Deshmukh, Nalin Agarwal, Elle Miller, Sethu Vijayakumar · 2026
> [arXiv](https://arxiv.org/abs/2610.23438) · [PDF](https://arxiv.org/pdf/2610.23438)

## Abstract

Humans manipulate objects within their hands through touch alone with remarkable ease, but for robots, achieving sustained real-world manipulation without vision remains an open challenge. Although reinforcement learning (RL) can generate sophisticated blind manipulation policies in simulation, transferring them to a real dexterous hand remains hindered by continuously changing contacts, motion-induced tactile information drift, and the gap between simulated and physical dynamics. We study this problem through Baoding ball rotation on the Shadow Dexterous Hand Lite, using only proprioception and binary tactile feedback as observations. We achieve successful zero-shot transfer through a combination of a sensor-aligned, coupling-aware embodiment in simulation, tactile calibration, and two novel episodic domain randomisations: slew-rate action limits and STuck-AT Taxels. On the physical hand, the policy achieves sustained blind Baoding rotation, completing 225 consecutive $\mathbf{180^\circ}$ rotations (112.5 full rotations) at $\sim0.36 \;\text{rot/s}$ in a single continuous trial without any vision or object-state information. Furthermore, we evaluate the contribution of tactile sensing relative to proprioception alone and identify the hand regions where tactile information is most important. This is the strongest reported hardware result for Baoding ball manipulation in both rotation count and speed, irrespective of the sensing modality used. By effectively bridging the sim-to-real gap, our framework sets a new benchmark for sustained tactile-driven dexterous manipulation on physical hardware.

## TL;DR

Humans manipulate objects within their hands through touch alone with remarkable ease, but for robots, achieving sustained real-world manipulation without vision remains an open challenge. Although reinforcement learning (RL) can generate sophisticated blind manipulation policies in simulation, transferring them to a real dexterous hand remains hindered by continuously changing contacts, motion-induced tactile information drift, and the gap between simulated and physical dynamics.

## Related
<!-- [[other-paper-citekey]] -->
