---
citekey: "takebayashiExperienceBasedFeasibilityAwareGenerativeAdversarialImitationObservation2026"
title: "Experience-Based Feasibility-Aware Generative Adversarial Imitation from Observation under Embodiment Mismatch"
authors: ["Yoshiki Takebayashi", "Giovanni Perantoni", "Hikaru Sasaki", "Matteo Saveriano", "Takamitsu Matsubara"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.01171"
doi: "10.48550/arXiv.2610.01171"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-03
---

# Experience-Based Feasibility-Aware Generative Adversarial Imitation from Observation under Embodiment Mismatch

> Yoshiki Takebayashi, Giovanni Perantoni, Hikaru Sasaki, Matteo Saveriano, Takamitsu Matsubara · 2026
> [arXiv](https://arxiv.org/abs/2610.01171) · [PDF](https://arxiv.org/pdf/2610.01171)

## Abstract

With the increasing use of robot-free demonstration interfaces that provide state trajectories without action labels, imitation from observation has become a promising approach for learning robot behaviors from human demonstrations. However, due to differences in embodiment and dynamics between humans and robots, demonstrated human motions may not be feasible for the robot, potentially degrading policy performance. In this study, we propose Experience-Based Feasibility-Aware Generative Adversarial Imitation from Observation (EF-GAIfO), which estimates the feasibility of state-only demonstrations from the robot's own experience rather than relying on explicit dynamics models or large prior exploration datasets. A key feature of EF-GAIfO is that the notion of feasibility evolves with policy learning: as the policy improves and the robot experiences a broader range of state transitions, the feasible region is progressively expanded, allowing additional demonstrations to be incorporated into learning. This enables feasibility-aware imitation that adapts to the current stage of policy learning, rather than relying on a pre-designed feasibility criterion. We validate the effectiveness of EF-GAIfO on a locomotion task in simulation and on a real quadruped robot performing a object-reaching-and-grasping task.

## TL;DR

With the increasing use of robot-free demonstration interfaces that provide state trajectories without action labels, imitation from observation has become a promising approach for learning robot behaviors from human demonstrations. However, due to differences in embodiment and dynamics between humans and robots, demonstrated human motions may not be feasible for the robot, potentially degrading policy performance.

## Related
<!-- [[other-paper-citekey]] -->
