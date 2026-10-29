---
citekey: "zhangLearningInferManipulateThroughDistributedWholeArmInteraction2026"
title: "Learning to infer and manipulate through distributed whole-arm interaction in a soft robot"
authors: ["Chuhan Zhang", "Ebrahim Shahabi", "Kseniia Khomenko", "Wei Pan", "Cosimo Della Santina"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2608.30773"
doi: "10.48550/arXiv.2608.30773"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-07
---

# Learning to infer and manipulate through distributed whole-arm interaction in a soft robot

> Chuhan Zhang, Ebrahim Shahabi, Kseniia Khomenko, Wei Pan, Cosimo Della Santina · 2026
> [arXiv](https://arxiv.org/abs/2608.30773) · [PDF](https://arxiv.org/pdf/2608.30773)

## Abstract

In animals such as elephants and octopuses, acquiring non-visual information about an object and physically engaging with it are inseparable processes mediated by rich, large-area interactions between compliant appendages and the environment. Soft robots provide a natural platform for translating this principle into engineered systems. Yet current robotic intelligence makes limited use of physical interaction, treating it primarily as a disturbance to be rejected or, at best, as a means of compensating for object misalignment. Here, we introduce a physical intelligence framework in which distributed compliant interactions jointly reveal task-relevant information and organize manipulation behavior. This results in an intrinsically partially observable problem: key task-relevant information is never measured directly, but must instead be inferred from the history of physical interactions. We propose a reinforcement-learning architecture that addresses this challenge by learning a memory-based control policy end-to-end. The key innovations making this possible are (i) a pretrained exploration policy that provides a reference for broad workspace exploration, (ii) joint optimization that integrates exploration and grasping objectives within a single recurrent policy, and (iii) a two-stage sim-to-real adaptation including observation mapping and policy fine-tuning. We demonstrate this principle through blind whole-arm grasping with a hybrid rigid-soft robotic arm that we equip with IMUs embedded directly within its compliant structure, providing its only source of proprioceptive sensing. The learned policy successfully identifies and grasps various objects by autonomously coordinating workspace exploration, object encounter and localization, inference of grasp-relevant properties, and stable whole-arm wrapping.

## TL;DR

In animals such as elephants and octopuses, acquiring non-visual information about an object and physically engaging with it are inseparable processes mediated by rich, large-area interactions between compliant appendages and the environment. Soft robots provide a natural platform for translating this principle into engineered systems.

## Related
<!-- [[other-paper-citekey]] -->
