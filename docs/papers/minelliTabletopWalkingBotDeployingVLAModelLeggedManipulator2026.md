---
citekey: "minelliTabletopWalkingBotDeployingVLAModelLeggedManipulator2026"
title: "From Tabletop to Walking Bot: Deploying a VLA Model on a Legged Manipulator Robot"
authors: ["Giovanni Minelli", "Antonio Langella", "Giovanni B. Dessy", "Lorenzo Amatucci", "Giulio Turrisi", "Victor Barasuol", "Claudio Semini"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.32271"
doi: "10.48550/arXiv.2610.32271"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-27
---

# From Tabletop to Walking Bot: Deploying a VLA Model on a Legged Manipulator Robot

> Giovanni Minelli, Antonio Langella, Giovanni B. Dessy, Lorenzo Amatucci, Giulio Turrisi, Victor Barasuol, Claudio Semini · 2026
> [arXiv](https://arxiv.org/abs/2610.32271) · [PDF](https://arxiv.org/pdf/2610.32271)

## Abstract

Vision-language-action (VLA) models are typically pretrained on broad, diverse datasets and subsequently fine-tuned on a comparatively small dataset tailored to a specific target robot. Such adaptation recipe is now widely established, achieving its most mature results on fixed-base arms due to their static base dynamics and consistent reference frame. Mounting the same arm on a quadruped extends the workspace to the entire floor, but fundamentally changes the embodiment: rather than controlling the arm in isolation, the policy must jointly coordinate base navigation, body posture, and end-effector motion. In this work, we study the practical demands of this embodiment change across data collection, model adaptation, and inference design to achieve closed-loop loco-manipulation on a Unitree Go2 with an AgileX Piper arm. We report the choices that made this real-robot deployment feasible, namely model variant, action horizon, and demonstration conventions, together with a study tailored to a pick-and-place task, separating data coverage from model capacity. We show that expanding demonstration coverage reduces held-out end-effector error by 30%, and incorporating secondary skills (such as pushing rather than grasping) introduces new behavioral modes without degrading baseline performance. Finally, closed-loop real-world experiments show how dataset composition shapes success and failure, validating the pipeline for more complex loco-manipulation.

## TL;DR

Vision-language-action (VLA) models are typically pretrained on broad, diverse datasets and subsequently fine-tuned on a comparatively small dataset tailored to a specific target robot. Such adaptation recipe is now widely established, achieving its most mature results on fixed-base arms due to their static base dynamics and consistent reference frame.

## Related
<!-- [[other-paper-citekey]] -->
