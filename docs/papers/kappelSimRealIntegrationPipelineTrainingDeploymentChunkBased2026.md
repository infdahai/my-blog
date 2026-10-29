---
citekey: "kappelSimRealIntegrationPipelineTrainingDeploymentChunkBased2026"
title: "A Sim-to-Real Integration Pipeline for Training and Deployment of Chunk-Based VLA Manipulation Policies"
authors: ["Mathilde Kappel", "Clémence Grislain", "Mohamed Chetouani", "Olivier Sigaud", "Louis Annabi", "Faïz Ben Amar", "Stéphane Doncieux", "Mahdi Khoramshahi"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.21817"
doi: "10.48550/arXiv.2609.21817"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-21
---

# A Sim-to-Real Integration Pipeline for Training and Deployment of Chunk-Based VLA Manipulation Policies

> Mathilde Kappel, Clémence Grislain, Mohamed Chetouani, Olivier Sigaud, Louis Annabi, Faïz Ben Amar, Stéphane Doncieux, Mahdi Khoramshahi · 2026
> [arXiv](https://arxiv.org/abs/2609.21817) · [PDF](https://arxiv.org/pdf/2609.21817)

## Abstract

Vision-Language-Action (VLA) models have become a prominent paradigm for mapping multimodal inputs, including semantic instructions, visual observations of the scene, and proprioceptive observations, to robot actions. Most state-of-the-art models predict actions in the end-effector pose space as sequences of action chunks. Training and evaluating these models requires large-scale collections of real-world demonstrations, pairing robot actions with the corresponding visual and proprioceptive observations. Collecting such data on real hardware typically relies on human teleoperation, making the process costly, time-consuming, and difficult to scale. We present an open-source sim-to-real experimental protocol that addresses this bottleneck: expert trajectories generated in simulation are replayed open-loop on a real Franka FR3 setup, where the corresponding real visual and proprioceptive observations are recorded and converted into a format compatible with VLA training. The same deployment stack is then reused, in closed-loop, to evaluate a trained policy on that setup, so that data collection and evaluation share an identical hardware configuration. Because each real recording is paired with the simulated trajectory that produced it, the protocol also yields a direct measurement of the sim-to-real gap. We release the collected datasets on Hugging Face together with the pipeline source code https://gitlab.isir.upmc.fr/kappel/sim2real_public_chunk_control.

## TL;DR

Vision-Language-Action (VLA) models have become a prominent paradigm for mapping multimodal inputs, including semantic instructions, visual observations of the scene, and proprioceptive observations, to robot actions. Most state-of-the-art models predict actions in the end-effector pose space as sequences of action chunks.

## Related
<!-- [[other-paper-citekey]] -->
