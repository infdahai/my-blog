---
citekey: "zhouImitatorGameBenchmarkingImitativeAbilityBeyondActionPrediction2026"
title: "The Imitator Game: Benchmarking Robot Imitative Ability Beyond Action Prediction"
authors: ["Xunzhe Zhou", "Yiyang Cai", "Fengyi Wang", "Ran Ju", "Hanxiang Ren", "Ruizhe Liu", "Yu Zhang", "Qian Luo", "Feng Chen", "Pei Zhou", "Yi Ma", "Yanchao Yang"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2608.22301"
doi: "10.48550/arXiv.2608.22301"
tags: [paper, embodied-ai, "cs.AI", "cs.RO"]
status: unread
rating:
created: 2026-08-27
---

# The Imitator Game: Benchmarking Robot Imitative Ability Beyond Action Prediction

> Xunzhe Zhou, Yiyang Cai, Fengyi Wang, Ran Ju, Hanxiang Ren, Ruizhe Liu, Yu Zhang, Qian Luo, Feng Chen, Pei Zhou, Yi Ma, Yanchao Yang · 2026
> [arXiv](https://arxiv.org/abs/2608.22301) · [PDF](https://arxiv.org/pdf/2608.22301)

## Abstract

Humans imitate at the level of intent: given a demonstration, we infer its goal and carry it out with whatever tools, objects, and layouts are at hand. Current robot policies instead learn observation-to-action mappings from visual inputs and language instructions, without explicitly inferring the demonstrated task. Learning from human video thus remains largely trajectory-level: models can replay motions in near-identical scenes, but still struggle to imitate what the demonstrator intends rather than merely what they do. We introduce The Imitator Game, a four-level benchmark (L0-L3) that progressively widens the gap between the human demonstration and the robot's own scene, isolating where trajectory replay ceases to suffice and task understanding becomes necessary. We pair it with IG-10K, the largest environment-aligned paired human-robot dataset to date and the only one instantiated across all four levels in both real and simulated settings (20,000+ paired episodes, 50+ tasks, 6 domains), and Imitator Arena, an open platform for blind A/B human evaluation. Across nine state-of-the-art models, performance is stable from L0 to L2 but collapses at L3, identifying functional substitution - achieving the same intent through a different object affordance - as the decisive barrier to intent-level imitation. Human-video-conditioned models outperform caption-conditioned ones, yet every model falls below 13% zero-shot success on unseen tasks; fine-tuning IG-10K-pretrained models with only $10$ paired human-robot demonstrations yields large gains that grow with pretraining scale. The project website and access to Imitator Arena are available at https://imitator-game.github.io.

## TL;DR

Humans imitate at the level of intent: given a demonstration, we infer its goal and carry it out with whatever tools, objects, and layouts are at hand. Current robot policies instead learn observation-to-action mappings from visual inputs and language instructions, without explicitly inferring the demonstrated task.

## Related
<!-- [[other-paper-citekey]] -->
