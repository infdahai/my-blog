---
citekey: "iwakataImprovingImitationLearningEfficiencyManipulationThroughGeometricPrior2026"
title: "Improving Imitation Learning Efficiency for Manipulation through Geometric Prior Pretraining"
authors: ["Shogo Iwakata", "Tomohiro Motoda", "Ryosuke Yamada", "Koshi Makihara", "Ryoichi Nakajo", "Keitaro Tanaka", "Masaki Murooka", "Roman Mykhailyshyn", "Hirokatsu Kataoka", "Shigeo Morishima", "Yukiyasu Domae"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.12721"
doi: "10.48550/arXiv.2609.12721"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-15
---

# Improving Imitation Learning Efficiency for Manipulation through Geometric Prior Pretraining

> Shogo Iwakata, Tomohiro Motoda, Ryosuke Yamada, Koshi Makihara, Ryoichi Nakajo, Keitaro Tanaka, Masaki Murooka, Roman Mykhailyshyn, Hirokatsu Kataoka, Shigeo Morishima, Yukiyasu Domae · 2026
> [arXiv](https://arxiv.org/abs/2609.12721) · [PDF](https://arxiv.org/pdf/2609.12721)

## Abstract

Applying an imitation learning policy to a new manipulation task usually requires collecting new demonstrations and retraining the model, which makes sample efficiency a practical concern. Pretraining on large-scale robot datasets is effective in this respect, but such datasets are costly to collect and train on, while data augmentation techniques typically require a new round of data generation and retraining for each task. A complementary question is what useful prior can be provided to a policy at negligible cost before any task-specific data are collected. In this study, we construct a geometric visual pretraining dataset in which each scene contains only a plane, an object, and a hand, and trajectories are generated automatically. The scenes contain neither textures nor backgrounds; pretraining primarily exposes the policy to the geometric relationship between the hand and the object. Furthermore, representing the hand as a cube avoids tailoring the dataset to a specific robot morphology. We evaluate this geometric prior using ACT on three simulated robots across five manipulation tasks each, as well as on three real-world robot tasks. Across many of these robot--task combinations, fine-tuning from the geometric prior achieves higher success rates in the early stages of training than training from scratch while using only a small number of task demonstrations. These results suggest that even highly simplified geometric scenes can provide a useful initialization that transfers across robots and to real-world tasks when task data are limited.

## TL;DR

Applying an imitation learning policy to a new manipulation task usually requires collecting new demonstrations and retraining the model, which makes sample efficiency a practical concern. Pretraining on large-scale robot datasets is effective in this respect, but such datasets are costly to collect and train on, while data augmentation techniques typically require a new round of data generation and retraining for each task.

## Related
<!-- [[other-paper-citekey]] -->
