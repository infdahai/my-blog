---
citekey: "nayakSimpleGripperInterfaceSimulatorAgnosticClothManipulation2026"
title: "A Simple Gripper Interface for Simulator-Agnostic Cloth Manipulation"
authors: ["Abhilash Nayak", "Franco Coltraro", "Maria Alberich-Carramiñana", "Carme Torras"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.29340"
doi: "10.48550/arXiv.2609.29340"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-25
---

# A Simple Gripper Interface for Simulator-Agnostic Cloth Manipulation

> Abhilash Nayak, Franco Coltraro, Maria Alberich-Carramiñana, Carme Torras · 2026
> [arXiv](https://arxiv.org/abs/2609.29340) · [PDF](https://arxiv.org/pdf/2609.29340)

## Abstract

This paper presents a grasping model for cloth manipulation specifically tailored to ease the deployment of robotic control methods. The model is robust, fast and easy to implement avoiding at the same time contact and friction considerations between the gripper and the cloth in favor of simple positional constraints. The gripper is described by its pose, jaw state, and an attached grasping volume. Two kinds of grasping volumes are considered: an axis-aligned box to simulate a pinch grasping and a square pyramidal volume to simulate point grasping. When the gripper closes, the discrete cloth positions lying inside this volume are selected, stored in the local gripper frame, and then transported with the gripper motion. A simple squeezing step is also included to progressively move the selected cloth positions toward the center of the grasping region, avoiding an instantaneous displacement at closure. The model can be used in any simulator as it only requires access to discrete cloth positions and a mechanism for imposing target positions as constraints. We implement our grasping model in conjunction with a constraint-based inextensible cloth simulator, where grasping is implemented as moving positional equality constraints coupled with stretch, shear, collision, and table contact projection steps. The same gripper trajectory is applied on a robot arm to fold a real piece of cloth, serving as a simple bridge between simulation and physical cloth manipulation and showcasing the realism and practicality of our idealized grasping model.

## TL;DR

This paper presents a grasping model for cloth manipulation specifically tailored to ease the deployment of robotic control methods. The model is robust, fast and easy to implement avoiding at the same time contact and friction considerations between the gripper and the cloth in favor of simple positional constraints.

## Related
<!-- [[other-paper-citekey]] -->
