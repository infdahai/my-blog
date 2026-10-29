---
citekey: "zhaoWhatLimitsCrossTaskGeneralizationWorldActionModels2026"
title: "What Limits Cross-Task Generalization in World Action Models?"
authors: ["Chen Zhao", "Zipeng Ye", "Yihan Lin", "Yuchen Xie", "Jing Zhang"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.16641"
doi: "10.48550/arXiv.2610.16641"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-18
---

# What Limits Cross-Task Generalization in World Action Models?

> Chen Zhao, Zipeng Ye, Yihan Lin, Yuchen Xie, Jing Zhang · 2026
> [arXiv](https://arxiv.org/abs/2610.16641) · [PDF](https://arxiv.org/pdf/2610.16641)

## Abstract

Cross-task generalization remains difficult for world action models (WAMs), even when their predicted futures depict plausible manipulation. This gap can be attributed directly: we make this gap directly testable by decoupling a WAM into a world model and an inverse-dynamics model (IDM), then holding the IDM fixed while replacing the source of future images. We introduce Align Once, Evaluate Everywhere (AoE), a camera-space inverse-dynamics model pretrained on large-scale robot data, which provides this recovery interface for different future sources across tasks and environments. Through it, we find that actions recovered from recorded futures of unseen tasks execute almost as well as replayed demonstrations, whereas futures predicted by world models collapse across benchmarks. The failures are not generic: they concentrate on the gripper and interaction geometry while generation capacity is spent on task-irrelevant background. This diagnosis suggests that supervision should target exactly these regions. We therefore introduce the vision-to-action (VITA) loss, which passes generated futures through the frozen AoE and penalizes discrepancies in the recovered actions, redirecting generation toward action-relevant detail. Across two world models and three manipulation benchmarks, this simple change raises the execution success of generated futures from near zero to 47.0%. The same loss also transfers to WAMs and yields consistent gains in native control.

## TL;DR

Cross-task generalization remains difficult for world action models (WAMs), even when their predicted futures depict plausible manipulation. This gap can be attributed directly: we make this gap directly testable by decoupling a WAM into a world model and an inverse-dynamics model (IDM), then holding the IDM fixed while replacing the source of future images.

## Related
<!-- [[other-paper-citekey]] -->
