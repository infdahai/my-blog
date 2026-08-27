---
citekey: "kimSafetyCriticalBilateralTeleoperationOmnidirectionalAerialManipulationForce2026"
title: "Safety-Critical Bilateral Teleoperation for Omnidirectional Aerial Manipulation Using Force-Sensorless Haptic Feedback"
authors: ["Yubin Kim", "Jinwoo Lee", "Yongjun You", "H. Jin Kim", "Jeonghyun Byun"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2608.21735"
doi: "10.48550/arXiv.2608.21735"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-08-27
---

# Safety-Critical Bilateral Teleoperation for Omnidirectional Aerial Manipulation Using Force-Sensorless Haptic Feedback

> Yubin Kim, Jinwoo Lee, Yongjun You, H. Jin Kim, Jeonghyun Byun · 2026
> [arXiv](https://arxiv.org/abs/2608.21735) · [PDF](https://arxiv.org/pdf/2608.21735)

## Abstract

This paper presents a safety-critical bilateral teleoperation framework for omnidirectional aerial manipulators that integrates visual and force-sensorless haptic wrench feedback. Unlike existing approaches that either rely on onboard force/torque sensors or use model-dependent wrench estimates, which may become unreliable under model uncertainties or induce unintended feedback during free-flight, our method implements a hierarchical safety filter based on control barrier functions to avoid such limitations. The safety filter, being the key contribution, explicitly accounts for tracking errors arising from physical interaction between the aerial manipulator and its surroundings while enforcing thrust limits, a factor overlooked despite its critical importance for flight safety. This safety filter adjusts the command from the operator to ensure safe and stable aerial manipulation and avoid motor saturation. The adjustment made by the filter is mapped to haptic feedback, which is intuitive to the operator and conveys information on physical interaction and impending motor saturation. By actual experiments with a hexarotor-based omnidirectional aerial manipulator, we demonstrate that the proposed method avoids haptic feedback during free-flight, provides directionally consistent feedback under physical interaction, and can be operated for diverse manipulative tasks. Moreover, an ablation study further shows that the saturation filter improves interaction stability by explicitly preventing motor saturation and informing the operator of corrective actions.

## TL;DR

This paper presents a safety-critical bilateral teleoperation framework for omnidirectional aerial manipulators that integrates visual and force-sensorless haptic wrench feedback. Unlike existing approaches that either rely on onboard force/torque sensors or use model-dependent wrench estimates, which may become unreliable under model uncertainties or induce unintended feedback during free-flight, our method implements a hierarchical safety filter based on control barrier functions to avoid such limitations.

## Related
<!-- [[other-paper-citekey]] -->
