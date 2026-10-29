---
citekey: "huangEndEndVisionLanguageActionPoliciesAutonomousLunar2026"
title: "End-to-End Vision-Language-Action Policies for Autonomous Lunar Rover Docking"
authors: ["Sitan Huang", "Grace Gao"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.19224"
doi: "10.48550/arXiv.2610.19224"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-16
---

# End-to-End Vision-Language-Action Policies for Autonomous Lunar Rover Docking

> Sitan Huang, Grace Gao · 2026
> [arXiv](https://arxiv.org/abs/2610.19224) · [PDF](https://arxiv.org/pdf/2610.19224)

## Abstract

Surface navigation on the Moon is subject to extreme illumination contrast and deployment-time perceptual disturbances. While modular navigation pipelines have long supported planetary rover navigation, robustness is compromised by measurement errors that propagate through hand-engineered components. End-to-end learned policies are an alternative approach to navigation, which maps observations directly to control actions without intermediate components. Vision-language-action models, in particular, have driven significant breakthroughs in robotics and autonomous vehicle research. By leveraging internet-scale vision-language pretraining, these models can be exploited for their commonsense reasoning and visual understanding to provide robust generalization with limited task-specific data. However, their applicability and performance have yet to be characterized for lunar surface operations. In this study, we design a vision-language-action policy for autonomous lunar rover docking and characterize its performance relative to a modular navigation pipeline. We develop a scalable training framework that generates safety-aware expert demonstrations in a high-fidelity lunar simulation environment. In closed-loop evaluations, our policy performs competitively relative to the modular baseline under perceptual disturbances unseen during training. To address the tradeoff between compute consumption and closed-loop safety, the policy adapts its execution horizon by determining how far the rover may safely travel in open loop. Adaptive-horizon execution reduces inference frequency while limiting hazard-contact rates relative to fixed horizons in the evaluated scenarios.

## TL;DR

Surface navigation on the Moon is subject to extreme illumination contrast and deployment-time perceptual disturbances. While modular navigation pipelines have long supported planetary rover navigation, robustness is compromised by measurement errors that propagate through hand-engineered components.

## Related
<!-- [[other-paper-citekey]] -->
