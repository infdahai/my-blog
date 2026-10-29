---
citekey: "saitoVLaRLAugmentingVisionLanguageActionModelsSimulationTrained2026"
title: "VLaRL: Augmenting Vision-Language-Action Models with Simulation-Trained Latent-Conditioned Residual RL"
authors: ["Namiko Saito", "Kinam Kim", "Heecheol Kim", "Katsushi Ikeuchi", "Yasuyuki Matsushita"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.30868"
doi: "10.48550/arXiv.2609.30868"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-29
---

# VLaRL: Augmenting Vision-Language-Action Models with Simulation-Trained Latent-Conditioned Residual RL

> Namiko Saito, Kinam Kim, Heecheol Kim, Katsushi Ikeuchi, Yasuyuki Matsushita · 2026
> [arXiv](https://arxiv.org/abs/2609.30868) · [PDF](https://arxiv.org/pdf/2609.30868)

## Abstract

Vision-language-action (VLA) models provide broad, instruction-conditioned manipulation behaviors, but their physical execution can remain imprecise during contact-rich interaction. Residual reinforcement learning (RL) can correct such errors while keeping the VLA frozen, but real-robot RL is costly and safety-critical. We propose VLA Latent-Conditioned RL (VLaRL), which enables residual RL for frozen VLAs to be trained in simulation and deployed on real robots without real-world RL or online adaptation. The key challenge is transferring the learned residual policy despite the visual gap between simulation and reality. Rather than requiring pixel-level visual correspondence, VLaRL uses the VLA's internal vision-language latent representation to condition residual control and as the sim-to-real transfer interface, and learns a lightweight mapper that transforms simulation-derived latents toward the real latent distribution. Across four contact-rich manipulation tasks and two VLA backbones, VLaRL improves real-world success in all task-backbone combinations, while controlled ablations demonstrate the importance of both latent conditioning and latent alignment for transferring simulation-trained residual control.

## TL;DR

Vision-language-action (VLA) models provide broad, instruction-conditioned manipulation behaviors, but their physical execution can remain imprecise during contact-rich interaction. Residual reinforcement learning (RL) can correct such errors while keeping the VLA frozen, but real-robot RL is costly and safety-critical.

## Related
<!-- [[other-paper-citekey]] -->
