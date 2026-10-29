---
citekey: "siderisLearningGraspTargetingPointCloudsLogPileClearing2026"
title: "Learning Grasp Targeting from Point Clouds for Log Pile Clearing on a Hydraulic Crane"
authors: ["George Sideris", "Lucas Bessai", "Heshan Fernando", "Elie Ayoub", "Nicolas Lemieux", "Inna Sharf"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.07613"
doi: "10.48550/arXiv.2610.07613"
tags: [paper, embodied-ai, "cs.LG", "cs.RO"]
status: unread
rating:
created: 2026-10-08
---

# Learning Grasp Targeting from Point Clouds for Log Pile Clearing on a Hydraulic Crane

> George Sideris, Lucas Bessai, Heshan Fernando, Elie Ayoub, Nicolas Lemieux, Inna Sharf · 2026
> [arXiv](https://arxiv.org/abs/2610.07613) · [PDF](https://arxiv.org/pdf/2610.07613)

## Abstract

In mill yards, log loaders clear dense piles by a sequence of bundle grasps: hundreds of logs rest in contact, and each removal changes the pile available to the next grasp. A learned policy chooses where to place and orient the grapple from unsegmented point clouds and runs on a trailer-mounted hydraulic forestry crane. The policy classifies at which observed point to grasp and predicts depth and grapple orientation there. The same network outputs support behavior cloning (BC), reinforcement learning (RL), and deployment. BC learns from successful top-of-pile demonstrations; RL explores for improvements by fine-tuning the cloned policy (BC$\to$RL) or by training from scratch. In simulation, BC clears 98 of 100 piles of 200 logs, while BC$\to$RL improves load stability. Twelve field trials compare a geometric heuristic, RL from scratch, BC, and BC$\to$RL through complete grasp-transport-deposit cycles. BC and BC$\to$RL deposit 93.8% and 88.9% of pooled inventory, against 80.4% for the heuristic. BC$\to$RL deposits logs on 83.6% of its cycles, against 79.6% for the heuristic and 65.7% for BC, while its simulated stability gain does not carry over to the crane testbed. Trained entirely in simulation and run unchanged on the crane, the learned policies clear more than the hand-filtered heuristic while observing unfiltered clouds that still contain the storage rack's rails and poles.

## TL;DR

In mill yards, log loaders clear dense piles by a sequence of bundle grasps: hundreds of logs rest in contact, and each removal changes the pile available to the next grasp. A learned policy chooses where to place and orient the grapple from unsegmented point clouds and runs on a trailer-mounted hydraulic forestry crane.

## Related
<!-- [[other-paper-citekey]] -->
