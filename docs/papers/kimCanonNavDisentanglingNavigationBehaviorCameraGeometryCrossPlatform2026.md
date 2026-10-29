---
citekey: "kimCanonNavDisentanglingNavigationBehaviorCameraGeometryCrossPlatform2026"
title: "CanonNav: Disentangling Navigation Behavior from Camera Geometry in Cross-Platform Visual Navigation"
authors: ["Dong-Wook Kim", "Ji-Hoon Hwang", "E-In Son", "Mintaek Oh", "Seung-Woo Seo"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2608.30242"
doi: "10.48550/arXiv.2608.30242"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-02
---

# CanonNav: Disentangling Navigation Behavior from Camera Geometry in Cross-Platform Visual Navigation

> Dong-Wook Kim, Ji-Hoon Hwang, E-In Son, Mintaek Oh, Seung-Woo Seo · 2026
> [arXiv](https://arxiv.org/abs/2608.30242) · [PDF](https://arxiv.org/pdf/2608.30242)

## Abstract

While visual navigation has advanced through imitation learning from cross-platform demonstrations, fully leveraging such data remains challenging. First, directly learning from image-trajectory pairs entangles navigation behavior with platform-dependent camera geometry. This hinders consistent learning by forcing the policy to implicitly infer camera geometry from visual observations, an inherently ill-posed problem. Second, imitation learning from demonstrated trajectories captures the expert's chosen motion but leaves the intermediate decisions underlying that motion implicit. To address these issues, we propose CanonNav, a visual navigation framework that disentangles navigation behavior from camera geometry and incorporates complementary planning supervision into learning from cross-platform demonstrations. CanonNav introduces camera geometry canonicalization, which transforms visual observations and trajectories into a camera-consistent representation space. Building on this representation, we derive safety and local-progress supervision using pseudo-labels from an offline traversability estimator. Safety supervision penalizes unsafe trajectories, while local-progress supervision guides where the robot should advance. Experiments across diverse camera configurations and environments show that, despite using only RGB at inference, CanonNav consistently outperforms RGB-based baselines and even surpasses RGB-D-based methods in challenging scenarios.

## TL;DR

While visual navigation has advanced through imitation learning from cross-platform demonstrations, fully leveraging such data remains challenging. First, directly learning from image-trajectory pairs entangles navigation behavior with platform-dependent camera geometry.

## Related
<!-- [[other-paper-citekey]] -->
