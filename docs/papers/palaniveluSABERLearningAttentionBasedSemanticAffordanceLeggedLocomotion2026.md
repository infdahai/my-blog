---
citekey: "palaniveluSABERLearningAttentionBasedSemanticAffordanceLeggedLocomotion2026"
title: "SABER: Learning Attention-based Semantic Affordance for Legged Locomotion"
authors: ["Hari Prasanth Palanivelu", "Samuel Sze", "Kennard Garrison Johannes", "Albertus Hendrawan Adiwahono", "Meng Yee", " Chuah"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.21572"
doi: "10.48550/arXiv.2609.21572"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-21
---

# SABER: Learning Attention-based Semantic Affordance for Legged Locomotion

> Hari Prasanth Palanivelu, Samuel Sze, Kennard Garrison Johannes, Albertus Hendrawan Adiwahono, Meng Yee,  Chuah · 2026
> [arXiv](https://arxiv.org/abs/2609.21572) · [PDF](https://arxiv.org/pdf/2609.21572)

## Abstract

Perceptive legged locomotion has advanced rapidly by integrating terrain geometry into learned policies, yet the integration of terrain meaning remains sparse: a pipe, a patch of grass, or a fragile box may be geometrically traversable while being inappropriate for contact. In industrial environments, where legged robots increasingly operate, a single misplaced step can damage fragile equipment, destabilize the robot, or endanger the site. To address this, we introduce SABER, a planner-free reinforcement-learning policy that jointly reasons about terrain geometry and semantic contact permission. The policy consumes a unified terrain-affordance map, where each cell encodes local 3D geometry and a semantic contact cost. We augment cross-attention with a learned, signed semantic bias: an additive term on the attention logits, gated by the contact cost, that reweights flagged cells by their distance from the nearest foot. A hazard therefore reshapes attention where it can still affect the next foothold, and its influence fades where it cannot. The resulting policy selects footholds on permitted support and keeps the leg clear of forbidden regions throughout the swing phase. We perform a systematic ablation that isolates the contribution of each architectural component; removing the semantic bias alone increases forbidden contacts by 55% while velocity tracking is unchanged. We validate the policy on a Unitree B2, demonstrating sim-to-real semantic contact selection across indoor and outdoor environments and four semantic obstacle classes.

## TL;DR

Perceptive legged locomotion has advanced rapidly by integrating terrain geometry into learned policies, yet the integration of terrain meaning remains sparse: a pipe, a patch of grass, or a fragile box may be geometrically traversable while being inappropriate for contact. In industrial environments, where legged robots increasingly operate, a single misplaced step can damage fragile equipment, destabilize the robot, or endanger the site.

## Related
<!-- [[other-paper-citekey]] -->
