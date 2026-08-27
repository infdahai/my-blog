---
citekey: "liRethinkingDemonstrationUnlearningImitationLearningRobotics2026"
title: "Rethinking Demonstration Unlearning in Imitation Learning for Robotics"
authors: ["Jiazhuo Li", "Yu Zhang", "Yiming Fei", "Kangkang Dong", "Xiaojun Zhu", "Houde Liu", "Jinze Tao"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2608.20784"
doi: "10.48550/arXiv.2608.20784"
tags: [paper, embodied-ai, "cs.LG", "cs.RO"]
status: unread
rating:
created: 2026-08-27
---

# Rethinking Demonstration Unlearning in Imitation Learning for Robotics

> Jiazhuo Li, Yu Zhang, Yiming Fei, Kangkang Dong, Xiaojun Zhu, Houde Liu, Jinze Tao · 2026
> [arXiv](https://arxiv.org/abs/2608.20784) · [PDF](https://arxiv.org/pdf/2608.20784)

## Abstract

Imitation learning for robotics depends on human demonstrations, some of which people may later ask to remove. Retraining without them is the natural reference, but its cost grows with policy and dataset scale, motivating cheaper operators that edit a trained policy. Metrics inherited from machine unlearning, such as forgetting loss or a single membership attack, do not establish what an edit removed from a policy acting in closed loop. We therefore introduce a retrain-calibrated audit that reads demonstration unlearning along two axes: behavior, whether the edited policy acts like one retrained without the removed demonstrations, and evidence, whether an auditor can still detect it was trained on them. The behavior axis measures action divergence to that retrain at matched states, calibrated by a floor built from independent retrains, so a policy at the floor is as close to a retrain as retrains are to each other. The evidence axis applies a per-demonstration membership attack against a retrain null, reporting both its rank and its absolute member-loss level, since rank alone accepts operators that inflate member losses past the null. A conformal test then combines both axes into one hypothesis of joint retrain consistency, against a fleet of independent retrains large enough to reject at conventional significance. Across five preregistered conditions on three real-robot policy classes and two simulation suites, the axes dissociate in both directions on one checkpoint, as an edit may repair task behavior while leaving evidence unchanged, or reduce evidence while moving behavior away from retraining. On the ACT arm, a redirect edit restores blind-scored robot success to 18 of 20 trials.

## TL;DR

Imitation learning for robotics depends on human demonstrations, some of which people may later ask to remove. Retraining without them is the natural reference, but its cost grows with policy and dataset scale, motivating cheaper operators that edit a trained policy.

## Related
<!-- [[other-paper-citekey]] -->
