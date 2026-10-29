---
citekey: "stewartRapidLearningDexterousHandPenWritingThroughReal2026"
title: "Rapid Learning of Dexterous In-Hand Pen Writing through Real-Time Jacobian Estimation"
authors: ["Kai Stewart", "Yasunori Toshimitsu", "Robert K. Katzschmann"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.11775"
doi: "10.48550/arXiv.2609.11775"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-12
---

# Rapid Learning of Dexterous In-Hand Pen Writing through Real-Time Jacobian Estimation

> Kai Stewart, Yasunori Toshimitsu, Robert K. Katzschmann · 2026
> [arXiv](https://arxiv.org/abs/2609.11775) · [PDF](https://arxiv.org/pdf/2609.11775)

## Abstract

Dexterous in-hand manipulation of a grasped object with an anthropomorphic hand is an unsolved frontier for robot dexterity. The contact-richness and highly dynamic nature of object-hand interactions tend to require extensive modeling or data-collection efforts for learning-based approaches. Modern simulators used for reinforcement learning (RL) cannot fully replicate the required contact complexity, while collecting dexterous demonstrations for imitation learning (IL) remains an open problem. In this research, we present an embodied control approach based on real-time task Jacobian estimation of the combined hand and object system on the physical robot. Using only the CPU on a laptop, the proposed controller begins in-hand pen writing after approximately 18 s of initialization and continues to adapt online, without an analytic hand--object kinematic/contact model, simulation training, or precollected task demonstrations. We demonstrate that the same estimator/controller formulation works on three anthropomorphic robotic hand systems (one physical, two simulated) to show human-like, in-hand articulation of a grasped pen by an embodiment-independent formulation. Sub-millimeter in-plane precision (mean 0.6 mm across runs) is achieved across letters and shapes written in the air and on paper on a physical robot. To our knowledge, this is the first demonstration of an anthropomorphic hand writing arbitrary single-stroke trajectories with a grasped pen through purely in-hand motion, and it showcases an alternative to compute- and data-heavy approaches such as RL and IL for achieving dexterous manipulation through computationally simple and data-efficient algorithms.

## TL;DR

Dexterous in-hand manipulation of a grasped object with an anthropomorphic hand is an unsolved frontier for robot dexterity. The contact-richness and highly dynamic nature of object-hand interactions tend to require extensive modeling or data-collection efforts for learning-based approaches.

## Related
<!-- [[other-paper-citekey]] -->
