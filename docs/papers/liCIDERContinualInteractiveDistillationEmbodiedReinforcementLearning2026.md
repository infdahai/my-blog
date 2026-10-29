---
citekey: "liCIDERContinualInteractiveDistillationEmbodiedReinforcementLearning2026"
title: "CIDER: Continual Interactive Distillation for Embodied Reinforcement Learning"
authors: ["Houlin Li", "Minghui Xu", "Guo Xu", "Xuan Du", "Xiaohan Yan", "Chun Wang", "Yuxiang Yan", "Shukai Yang", "Yongcheng Liu", "Wei Shan", "Maoqing Yao"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2608.21899"
doi: "10.48550/arXiv.2608.21899"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-07
---

# CIDER: Continual Interactive Distillation for Embodied Reinforcement Learning

> Houlin Li, Minghui Xu, Guo Xu, Xuan Du, Xiaohan Yan, Chun Wang, Yuxiang Yan, Shukai Yang, Yongcheng Liu, Wei Shan, Maoqing Yao · 2026
> [arXiv](https://arxiv.org/abs/2608.21899) · [PDF](https://arxiv.org/pdf/2608.21899)

## Abstract

Human-in-the-loop real-world reinforcement learning enables rapid acquisition of effective robotic manipulation policies for individual tasks, often within tens of minutes. Yet it remains unclear how to extend this paradigm to continual learning, where a single policy must acquire new skills without losing previously learned behaviors. Existing real-world continual learning methods do not explicitly constrain prior behaviors, leading to severe catastrophic forgetting. We introduce Continual Interactive Distillation for Embodied Reinforcement Learning (CIDER), a continual reinforcement learning framework that freezes the accumulated historical policy as a teacher before learning each new task and interleaves task learning with distillation-based retention. We further introduce gradient routing to separate the gradients used for acquiring new tasks from those used for preserving prior behaviors. We evaluate our method with a single shared actor on six real-world household and industrial manipulation tasks. Interactive Distillation maintains high measured success on previously learned tasks across our six-task real-robot sequence while acquiring each new task in 10 to 20 minutes, whereas every baseline forgets at least one previous task. Additional ablations reveal the key design choices that govern the tradeoff between stability and plasticity in real-world continual reinforcement learning.

## TL;DR

Human-in-the-loop real-world reinforcement learning enables rapid acquisition of effective robotic manipulation policies for individual tasks, often within tens of minutes. Yet it remains unclear how to extend this paradigm to continual learning, where a single policy must acquire new skills without losing previously learned behaviors.

## Related
<!-- [[other-paper-citekey]] -->
