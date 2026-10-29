---
citekey: "khanzadaBranchDriveBranchStructuredDatasetActionConditionedDrivingPrediction2026"
title: "BranchDrive: A Branch-Structured Dataset for Action-Conditioned Driving Prediction"
authors: ["Feeza Khan Khanzada", "Sudarshan Sridhar", "Jaerock Kwon"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.27275"
doi: "10.48550/arXiv.2609.27275"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-25
---

# BranchDrive: A Branch-Structured Dataset for Action-Conditioned Driving Prediction

> Feeza Khan Khanzada, Sudarshan Sridhar, Jaerock Kwon · 2026
> [arXiv](https://arxiv.org/abs/2609.27275) · [PDF](https://arxiv.org/pdf/2609.27275)

## Abstract

Most autonomous-driving datasets record only the action executed by a behavior policy and the single future that followed, providing limited supervision for comparing alternative ego decisions. We introduce BranchDrive, a branch-structured CARLA dataset and benchmark that pairs one canonical pre-decision history with one nominal expert future and twelve physically executed intervention futures spanning acceleration, braking, and left- and right-steering policies at three magnitudes. Each intervention lasts 2.5 s and is followed by expert recovery. Following control-compliance, modality-completeness, replay-fidelity, and action-leakage audits, the frozen benchmark contains 606 independent branch groups and 7,878 associated trajectories. We evaluate prediction of six continuous short-horizon outcomes and a ten-step ego trajectory using action-only, history-only, structured, visual, multimodal, and privileged bird's-eye-view models. On the held-out test split, the structured history-and-action model achieves a macro normalized mean absolute error of 0.5036 and an average displacement error of 2.2042 m, significantly outperforming both restricted baselines. In full-information offline evaluation, its outcome-derived selector increases balanced policy value from 0.5364 to 0.5704 and reduces normalized regret from 0.2674 to 0.1495 relative to the frozen action prior. However, a validation-calibrated minimum-separation guard rejects every intervention, showing that conservative execution remains unresolved. BranchDrive therefore supports action-conditioned short-horizon prediction and fixed-bank offline decision evaluation, but does not establish exact causal effects, binary safety prediction, or closed-loop safety improvement.

## TL;DR

Most autonomous-driving datasets record only the action executed by a behavior policy and the single future that followed, providing limited supervision for comparing alternative ego decisions. We introduce BranchDrive, a branch-structured CARLA dataset and benchmark that pairs one canonical pre-decision history with one nominal expert future and twelve physically executed intervention futures spanning acceleration, braking, and left- and right-steering policies at three magnitudes.

## Related
<!-- [[other-paper-citekey]] -->
