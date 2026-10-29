---
citekey: "vuRealTimeConformalSeededHybridInverseKinematicsOffset2026"
title: "Real-Time Conformal-Seeded Hybrid Inverse Kinematics for Offset Redundant Manipulators"
authors: ["Duc Cuong Vu", "Van Tung Nguyen", "Duc Hai Nguyen", "Manh Cuong Nguyen", "Vu Trung Tran", "Minh Nhat Vu"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.04266"
doi: "10.48550/arXiv.2610.04266"
tags: [paper, embodied-ai, "cs.RO", "cs.SY", "eess.SY"]
status: unread
rating:
created: 2026-10-07
---

# Real-Time Conformal-Seeded Hybrid Inverse Kinematics for Offset Redundant Manipulators

> Duc Cuong Vu, Van Tung Nguyen, Duc Hai Nguyen, Manh Cuong Nguyen, Vu Trung Tran, Minh Nhat Vu · 2026
> [arXiv](https://arxiv.org/abs/2610.04266) · [PDF](https://arxiv.org/pdf/2610.04266)

## Abstract

This paper presents a conformal-seeded hybrid strategy for solving inverse kinematics of offset, redundant 7-DoF robot arms of the humanoid class. Analytical inverse kinematics (AIK) provides closed-form solutions with very low computational cost. However, for offset kinematic structures, the exact closed-form solution is generally unavailable, and practical AIK must rely on an approximate or simplified kinematic model. In contrast, numerical inverse kinematics (NIK) can achieve high-precision solutions on the full kinematic model. However, its convergence is highly sensitive to initialization. To overcome these limitations, we propose a two-stage hybrid inverse kinematics framework with conformal-calibrated seed selection. First, an approximate analytical model efficiently enumerates a finite set of candidate joint solutions. Second, we rank these candidates using a lightweight learned predictor of post-refinement difficulty, wrapped by split-conformal prediction into a calibrated upper bound that serves as the selection score. The best-ranked seed is then refined using a Levenberg-Marquardt solver on the full kinematic model. The proposed method combines fast candidate generation, learned seed ranking with a calibrated difficulty bound, and accurate numerical refinement, achieving real-time performance of less than 40us and a success rate of 100% in our evaluation on reachable targets. We validate the approach through large-scale stochastic simulation across the workspace and experimental demonstrations with motion planning on a humanoid robot arm. Demonstration videos are available at https://youtu.be/aeiBmw1XRbw.

## TL;DR

This paper presents a conformal-seeded hybrid strategy for solving inverse kinematics of offset, redundant 7-DoF robot arms of the humanoid class. Analytical inverse kinematics (AIK) provides closed-form solutions with very low computational cost.

## Related
<!-- [[other-paper-citekey]] -->
