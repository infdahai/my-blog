---
citekey: "wangKITEDecouplingKinematicsInteractionZeroShotCrossEmbodiment2026"
title: "KITE: Decoupling Kinematics and Interaction for Zero-Shot Cross-Embodiment Manipulation"
authors: ["Qianxu Wang", "Kuan Fang"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2606.22113"
doi: "10.48550/arXiv.2606.22113"
tags: [paper, embodied-ai, "cs.AI", "cs.RO"]
status: unread
rating:
created: 2026-08-27
---

# KITE: Decoupling Kinematics and Interaction for Zero-Shot Cross-Embodiment Manipulation

> Qianxu Wang, Kuan Fang · 2026
> [arXiv](https://arxiv.org/abs/2606.22113) · [PDF](https://arxiv.org/pdf/2606.22113)

## Abstract

Generalizing manipulation policies across robot embodiments remains difficult because standard policies entangle task reasoning with embodiment-specific motor control. We study zero-shot cross-embodiment manipulation, where a policy trained on source embodiments must be deployed on a structurally different target embodiment without additional task demonstrations. We introduce Kinematic Interaction Transfer across Embodiments (KITE), which decouples manipulation into embodiment-agnostic task reasoning and embodiment-specific motor control, connected through a learned latent representation of interaction intent based on contact patterns. Task reasoning is performed by a shared policy that predicts latent intents from source demonstrations, while motor control is performed by an intent-conditioned action decoder learned from each embodiment's kinematic model. With KITE, adaptation to a new embodiment requires only training a new action decoder using its kinematic model, without recollecting demonstration data. We evaluate KITE on three manipulation tasks spanning transfer between parallel grippers, dexterous hands, and composite embodiments. KITE consistently achieves zero-shot transfer to structurally different target embodiments, outperforming state-of-the-art baselines in transfer success and task-embodiment scope.

## TL;DR

Generalizing manipulation policies across robot embodiments remains difficult because standard policies entangle task reasoning with embodiment-specific motor control. We study zero-shot cross-embodiment manipulation, where a policy trained on source embodiments must be deployed on a structurally different target embodiment without additional task demonstrations.

## Related
<!-- [[other-paper-citekey]] -->
