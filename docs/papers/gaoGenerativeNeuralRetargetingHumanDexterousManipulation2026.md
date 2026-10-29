---
citekey: "gaoGenerativeNeuralRetargetingHumanDexterousManipulation2026"
title: "Generative Neural Retargeting for Human-to-Robot Dexterous Manipulation"
authors: ["Dechen Gao", "Yue Yang", "Ben Abbatematteo", "Nathan Godwin", "Pengcheng Wang", "Roger Boldu", "Steven Man", "Zhiyang Dou", "Chuan Qin", "Sho Nakagome", "Eric Whitmire"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.12440"
doi: "10.48550/arXiv.2610.12440"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-10
---

# Generative Neural Retargeting for Human-to-Robot Dexterous Manipulation

> Dechen Gao, Yue Yang, Ben Abbatematteo, Nathan Godwin, Pengcheng Wang, Roger Boldu, Steven Man, Zhiyang Dou, Chuan Qin, Sho Nakagome, Eric Whitmire · 2026
> [arXiv](https://arxiv.org/abs/2610.12440) · [PDF](https://arxiv.org/pdf/2610.12440)

## Abstract

Human demonstrations are a scalable data source for learning dexterous manipulation, but the embodiment gap prevents human motion from being executed directly on robots. Inverse kinematics (IK) retargets human motion to robots efficiently but ignores dynamics, often producing infeasible motions. Reinforcement learning (RL) and sampling-based model predictive control (MPC) are commonly employed to yield dynamically feasible motions, but both are sample-inefficient and sensitive to hyperparameters. RL suffers from costly and unstable training and tedious reward engineering; MPC avoids policy optimization, yet retargets each trajectory in isolation, and solving one does not make the next easier. Sampling cost grows rapidly with dataset size and task difficulty. We hypothesize that dynamically feasible trajectories concentrate near a low-dimensional manifold shared across demonstrations, so that retargeting can be reduced to sampling from that manifold, conditioned on human motion, rather than solving a fresh optimization problem for every demonstration. We propose \textbf{Generative Neural Retargeting} (GNR), which uses a flow matching model to sample feasible trajectories. GNR outperforms MPC with only $8.5\%$ of the samples required by MPC, achieving a success rate of $56.20\%$ compared to $27.20\%$ for MPC. GNR can be used for scalable and efficient retargeting of large-scale, long-horizon, and millimeter precision human demonstrations: by applying GNR within a real-to-sim data engine, we produce a dexterous manipulation dataset with dense contact-force labels, spanning $223$k demonstrations and $3.3$k object geometries.

## TL;DR

Human demonstrations are a scalable data source for learning dexterous manipulation, but the embodiment gap prevents human motion from being executed directly on robots. Inverse kinematics (IK) retargets human motion to robots efficiently but ignores dynamics, often producing infeasible motions.

## Related
<!-- [[other-paper-citekey]] -->
