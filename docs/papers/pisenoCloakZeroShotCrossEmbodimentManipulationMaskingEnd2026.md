---
citekey: "pisenoCloakZeroShotCrossEmbodimentManipulationMaskingEnd2026"
title: "Cloak: Zero-Shot Cross-Embodiment Manipulation by Masking the End-Effector from the VLA"
authors: ["Michael Piseno", "Guy Tevet", "C. Karen Liu"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2606.22836"
doi: "10.48550/arXiv.2606.22836"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-08-27
---

# Cloak: Zero-Shot Cross-Embodiment Manipulation by Masking the End-Effector from the VLA

> Michael Piseno, Guy Tevet, C. Karen Liu · 2026
> [arXiv](https://arxiv.org/abs/2606.22836) · [PDF](https://arxiv.org/pdf/2606.22836)

## Abstract

We present Cloak, a training recipe that endows a Vision-Language-Action (VLA) model with zero-shot cross-embodiment transfer by cloaking the end-effector from its own wrist camera. The end-effector occupies a large and consistent region of the wrist view and masking it allows for embodiment-agnostic visual reasoning. Cloak renders a mask in simulation from the robot's known geometry, accurately and in real time, with no segmentation or generative models. During training, we augment the mask so the model generalizes to embodiments unseen at training time. We demonstrate the recipe with Cloak-VLA, a VLA trained with Cloak on a single parallel-jaw gripper dataset. No data of new embodiments is ever collected. Cloak-VLA transfers zero-shot to various unseen embodiments, including another gripper, another arm, and a five-fingered hand, while preserving the source embodiment's performance. By decoupling the wrist view from its own embodiment, Cloak allows data to outlive the hardware it was collected on.

## TL;DR

We present Cloak, a training recipe that endows a Vision-Language-Action (VLA) model with zero-shot cross-embodiment transfer by cloaking the end-effector from its own wrist camera. The end-effector occupies a large and consistent region of the wrist view and masking it allows for embodiment-agnostic visual reasoning.

## Related
<!-- [[other-paper-citekey]] -->
