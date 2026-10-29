---
citekey: "huangRoboRenderOrientedVideoGenerationVisualSimRealTransfer2026"
title: "RoboRender: Robot-Oriented Video Generation for Visual Sim-to-Real Transfer"
authors: ["Huang Huang", "Wensi Ai", "Ziyu Chen", "Youhui Wang", "Zijian Du", "Yang Liu", "Jiaolong Yang", "Li Fei-Fei", "Jiajun Wu"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.09254"
doi: "10.48550/arXiv.2610.09254"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-08
---

# RoboRender: Robot-Oriented Video Generation for Visual Sim-to-Real Transfer

> Huang Huang, Wensi Ai, Ziyu Chen, Youhui Wang, Zijian Du, Yang Liu, Jiaolong Yang, Li Fei-Fei, Jiajun Wu · 2026
> [arXiv](https://arxiv.org/abs/2610.09254) · [PDF](https://arxiv.org/pdf/2610.09254)

## Abstract

Simulation enables large-scale, low-cost robot data generation, but policies trained in simulation often fail to transfer to the real world due to the sim-to-real visual discrepancies. Existing approaches often rely on intermediate representations, which can discard rich semantic information or require additional perception modules at deployment. We address this visual sim-to-real gap with RoboRender, a framework that converts simulated trajectories into photorealistic RGB videos for policy learning. RoboRender trains a robot-oriented video generation model conditioned on simulated depth videos, language instructions, and robot RGB mask videos, preserving simulator geometry, robot motion, and action labels while synthesizing realistic textures, backgrounds, and distractors. The generated RGB videos are paired with simulator-provided states and actions to train policies for zero-shot real-world deployment. On robot video test sets, our video model outperforms depth-conditioned video generation baselines in generation quality. In real-world experiments across pick-and-place, articulated-object manipulation, and mobile manipulation tasks, policies trained on RoboRender-generated data achieve a 71% average success rate, outperforming raw simulation renderings and conventional visual domain randomization by approximately 7.1x and 3.6x, respectively. We further show that policy performance improves with more generated videos per simulation trajectory, increasing opening-task success by 65 percentage points. These results demonstrate that generative video rendering mitigates the visual sim-to-real gap for zero-shot policy transfer. Project website: https://robo-render.github.io/.

## TL;DR

Simulation enables large-scale, low-cost robot data generation, but policies trained in simulation often fail to transfer to the real world due to the sim-to-real visual discrepancies. Existing approaches often rely on intermediate representations, which can discard rich semantic information or require additional perception modules at deployment.

## Related
<!-- [[other-paper-citekey]] -->
