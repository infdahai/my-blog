---
citekey: "liFetchMyBeerSyntheticRealHierarchicalPolicySmooth2026"
title: "Fetch My Beer: Synthetic-to-real Hierarchical Policy for Smooth Pick-and-place"
authors: ["Yingyue Li", "Chenyangguang Zhang", "Ruida Zhang", "Bowen Fu", "Guangyao Zhai", "Xiangyang Ji"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.18119"
doi: "10.48550/arXiv.2609.18119"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-17
---

# Fetch My Beer: Synthetic-to-real Hierarchical Policy for Smooth Pick-and-place

> Yingyue Li, Chenyangguang Zhang, Ruida Zhang, Bowen Fu, Guangyao Zhai, Xiangyang Ji · 2026
> [arXiv](https://arxiv.org/abs/2609.18119) · [PDF](https://arxiv.org/pdf/2609.18119)

## Abstract

Many real-world robotic applications require dynamically sensitive manipulation, where success depends not only on reaching a target state but on maintaining stable object dynamics throughout execution. We study the stable transport of liquid-filled containers, where a robot must move objects to target locations while suppressing sloshing and preventing spillage. Unlike conventional pick-and-place, this task imposes stringent requirements on motion smoothness and trajectory-level stability, exposing clear limitations in existing systems. Specifically, fluid simulation remains too costly for online reinforcement learning; human teleoperation introduces unintended accelerations that induce sloshing during imitation learning; and current policy pipelines optimize for task completion rather than dynamic stability. We propose a synthetic-to-real framework coupling physically validated data generation with a hierarchical, diffusion-based controller. The scalable data pipeline synthesizes grasps, filters unstable poses via a vision-language model, and validates transport trajectories through fluid simulation. The policy is organized with a high-level module that translates language and visual observations into SE(3) control targets, and a latent diffusion controller that first plans efficiently in a compact latent space and then decodes dense action chunks, enabling the high control frequency needed for smooth and stable motion. Extensive experiments show our system outperforms state-of-the-art manipulation policies in transport smoothness and dynamic stability. Our project page: https://fetch-my-beer.github.io/

## TL;DR

Many real-world robotic applications require dynamically sensitive manipulation, where success depends not only on reaching a target state but on maintaining stable object dynamics throughout execution. We study the stable transport of liquid-filled containers, where a robot must move objects to target locations while suppressing sloshing and preventing spillage.

## Related
<!-- [[other-paper-citekey]] -->
