---
citekey: "zhouBenchmarkingWorldModelsContinualLearningCompositionalTasks2026"
title: "Benchmarking World Models for Continual Learning on Compositional Tasks"
authors: ["Haoyu Zhou", "Joe Watson", "Anson Lei", "Ingmar Posner"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.22055"
doi: "10.48550/arXiv.2609.22055"
tags: [paper, embodied-ai, "cs.LG", "cs.RO"]
status: unread
rating:
created: 2026-09-22
---

# Benchmarking World Models for Continual Learning on Compositional Tasks

> Haoyu Zhou, Joe Watson, Anson Lei, Ingmar Posner · 2026
> [arXiv](https://arxiv.org/abs/2609.22055) · [PDF](https://arxiv.org/pdf/2609.22055)

## Abstract

A desirable property of a world model is the ability to learn continually across tasks, adapting to new environments without forgetting what the agent has already learnt. In particular, the ability to retain and reuse knowledge obtained from prior experiences underpins an agent's ability to efficiently adapt to novel environments, as the dynamics of the physical world can often be described in recurring mechanisms. However, the world model's measure of adaptation entangles two abilities: the speed and capacity to learn unseen tasks, and the reuse of knowledge already acquired, since incoming tasks carry novel content alongside what recurs. In order to isolate knowledge reuse from prior experiences, we propose a compositional continual learning benchmark for world models in robot manipulation. Specifically, we design each task curriculum with compositional tasks that combine aspects of the tasks seen in the sequence. We further factorise this composition along the axes of action and perception to better understand how different input modalities bottleneck knowledge reuse. We evaluate state-of-the-art world models under canonical continual learning methods, alongside a modular world model whose dynamics backbone contains explicitly reusable components. Results show that modularity balances reuse against forgetting better than conventional methods, but none solve the problem fully, leaving clear room for continual world models built to reuse without forgetting. More details are available on our project website: https://object814.github.io/Compositional-Continual-Learning/.

## TL;DR

A desirable property of a world model is the ability to learn continually across tasks, adapting to new environments without forgetting what the agent has already learnt. In particular, the ability to retain and reuse knowledge obtained from prior experiences underpins an agent's ability to efficiently adapt to novel environments, as the dynamics of the physical world can often be described in recurring mechanisms.

## Related
<!-- [[other-paper-citekey]] -->
