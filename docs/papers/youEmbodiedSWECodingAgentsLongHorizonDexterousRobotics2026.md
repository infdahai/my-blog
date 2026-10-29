---
citekey: "youEmbodiedSWECodingAgentsLongHorizonDexterousRobotics2026"
title: "EmbodiedSWE: Coding Agents for Long Horizon Dexterous Robotics"
authors: ["Haoxiang You", "Zeyu Shen", "Yilang Liu", "Zhicheng Zheng", "Lihan Zha", "Kashu Yamazaki", "Mingtong Zhang", "Suning Huang", "Jiankai Sun", "Qianzhong Chen", "Lucy He", "Kaiyuan Liu", "Haoran Chang", "Katerina Fragkiadaki", "Dhruv Shah", "Mac Schwager", "Peter Henderson", "Ian Abraham", "Canwen Xu"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.27308"
doi: "10.48550/arXiv.2609.27308"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-25
---

# EmbodiedSWE: Coding Agents for Long Horizon Dexterous Robotics

> Haoxiang You, Zeyu Shen, Yilang Liu, Zhicheng Zheng, Lihan Zha, Kashu Yamazaki, Mingtong Zhang, Suning Huang, Jiankai Sun, Qianzhong Chen, Lucy He, Kaiyuan Liu, Haoran Chang, Katerina Fragkiadaki, Dhruv Shah, Mac Schwager, Peter Henderson, Ian Abraham, Canwen Xu · 2026
> [arXiv](https://arxiv.org/abs/2609.27308) · [PDF](https://arxiv.org/pdf/2609.27308)

## Abstract

We study coding agents for long-horizon, dexterous robotics and ask whether their solutions can provide scalable supervision for learning general robot policies. To test this, we develop EMBODIEDSWE-BENCH, a simulation benchmark for coding agents spanning contact-rich manipulation, deformable objects, and long-horizon tasks requiring up to half an hour of continuous interaction. We find that frontier coding agents can solve complex long-horizon tasks and transfer prior solutions across both tasks and embodiments. We also design supporting tools that help agents more effectively solve these tasks. However, the resulting solutions require substantial iterative interaction and are typically specialized to individual task instances. We therefore introduce EMBODIEDSWE-GEN, which expands a single solution from coding agent into large diverse trajectories for training a VLA. VLA performance improves with more generated demonstrations, and agent-aided diversification improves generalization to held-out task variations. We also show that a VLA finetuned solely on coding-agent-generated simulation demonstrations completes a long-horizon task on real robot. Together, our framework uses coding agents to solve complex robotics tasks and turn verified solutions into scalable supervision for robot policies.

## TL;DR

We study coding agents for long-horizon, dexterous robotics and ask whether their solutions can provide scalable supervision for learning general robot policies. To test this, we develop EMBODIEDSWE-BENCH, a simulation benchmark for coding agents spanning contact-rich manipulation, deformable objects, and long-horizon tasks requiring up to half an hour of continuous interaction.

## Related
<!-- [[other-paper-citekey]] -->
