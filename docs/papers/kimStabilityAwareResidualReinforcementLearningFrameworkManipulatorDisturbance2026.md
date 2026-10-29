---
citekey: "kimStabilityAwareResidualReinforcementLearningFrameworkManipulatorDisturbance2026"
title: "Stability-aware Residual Reinforcement Learning Framework for Robotic Manipulator Disturbance Compensation"
authors: ["Jihong Kim", "Joonhyuk Kwon", "Hwa Soo Kim", "TaeWon Seo", "Hyung-Tae Seo"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.21307"
doi: "10.48550/arXiv.2609.21307"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-21
---

# Stability-aware Residual Reinforcement Learning Framework for Robotic Manipulator Disturbance Compensation

> Jihong Kim, Joonhyuk Kwon, Hwa Soo Kim, TaeWon Seo, Hyung-Tae Seo · 2026
> [arXiv](https://arxiv.org/abs/2609.21307) · [PDF](https://arxiv.org/pdf/2609.21307)

## Abstract

Although conventional controllers and disturbance observers (DOBs) are the standard for precision tracking in manipulators, they suffer from parameter uncertainty, nonlinear friction, and compound disturbances. This study proposes a residual reinforcement learning DOB framework that pairs an analytical observer with an RL policy. The deterministic baseline operates within a reliable region, whereas the RL policy explicitly targets the residuals that the model cannot capture. To make this compensation disturbance-aware, an estimator network aligns the observation history with a privileged disturbance context, organizing the latent space by disturbance regime and enabling rapid adaptation across disturbance transitions. To guarantee stability, we derived and enforced a state-dependent action bound on the RL policy from an input-to-state stability (ISS) analysis such that the closed loop provably confines the tracking error to a certified envelope for arbitrary policy outputs. Experiments on a 6-DOF manipulator demonstrated consistent improvements in disturbance estimation and tracking, including a 27.8% tracking-error reduction on real hardware under zero-shot sim-to-real transfer and a 38.0% reduction under a base-vibration disturbance that was not observed during training.

## TL;DR

Although conventional controllers and disturbance observers (DOBs) are the standard for precision tracking in manipulators, they suffer from parameter uncertainty, nonlinear friction, and compound disturbances. This study proposes a residual reinforcement learning DOB framework that pairs an analytical observer with an RL policy.

## Related
<!-- [[other-paper-citekey]] -->
