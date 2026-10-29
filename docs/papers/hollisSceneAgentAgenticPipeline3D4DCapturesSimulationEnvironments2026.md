---
citekey: "hollisSceneAgentAgenticPipeline3D4DCapturesSimulationEnvironments2026"
title: "SceneAgent: An Agentic Pipeline from 3D and 4D Captures to Simulation Environments"
authors: ["Luke Hollis", "Tianxing Fan", "Heng Yang"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.34745"
doi: "10.48550/arXiv.2610.34745"
tags: [paper, embodied-ai, "cs.AI", "cs.CV", "cs.RO"]
status: unread
rating:
created: 2026-10-28
---

# SceneAgent: An Agentic Pipeline from 3D and 4D Captures to Simulation Environments

> Luke Hollis, Tianxing Fan, Heng Yang · 2026
> [arXiv](https://arxiv.org/abs/2610.34745) · [PDF](https://arxiv.org/pdf/2610.34745)

## Abstract

Visual captures provide detailed scene appearance, but converting them into interactive simulation environments requires object reconstruction, physical modeling, and correction of intermediate errors. We present SceneAgent, an agentic pipeline that coordinates these steps through simulator-based visual inspection and repair. The pipeline processes 3D Gaussian Splatting (3DGS), photogrammetry, LiDAR captures, AI-generated 3DGS scenes, and 4D videos of dynamic scenes, and combines object segmentation, physical parameter estimation, part decomposition, articulation, and deformable simulation. To support policy learning, SceneAgent generates diverse object variants ("digital sisters") and scripted demonstrations. On a cluttered bin scene from GraspClutter6D, SceneAgent raises F1 at 1 cm for every coding agent with scorable outputs both with and without its skills, and its reconstructions are better than SimFoundry: all agent configurations exceed SimFoundry's F1 score, with a best of 60.75% versus 6.9%. On three dynamic scenes from 4DCodeBench, SceneAgent raises the mean dynamic IoU of Gemini 4 Argon from 0.86% to 99.09%. We further demonstrate diverse simulated interactions and preliminary policy transfer to a real robot.

## TL;DR

Visual captures provide detailed scene appearance, but converting them into interactive simulation environments requires object reconstruction, physical modeling, and correction of intermediate errors. We present SceneAgent, an agentic pipeline that coordinates these steps through simulator-based visual inspection and repair.

## Related
<!-- [[other-paper-citekey]] -->
