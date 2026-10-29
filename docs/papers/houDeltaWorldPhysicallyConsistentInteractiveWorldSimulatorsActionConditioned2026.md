---
citekey: "houDeltaWorldPhysicallyConsistentInteractiveWorldSimulatorsActionConditioned2026"
title: "DeltaWorld: Physically Consistent Interactive World Simulators via Action-Conditioned Latent Increment Learning"
authors: ["Boyuan Hou", "Xiaoge Cao", "Chaofan Zhang", "Shuo Wang", "Shaowei Cui"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.02691"
doi: "10.48550/arXiv.2610.02691"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-06
---

# DeltaWorld: Physically Consistent Interactive World Simulators via Action-Conditioned Latent Increment Learning

> Boyuan Hou, Xiaoge Cao, Chaofan Zhang, Shuo Wang, Shaowei Cui · 2026
> [arXiv](https://arxiv.org/abs/2610.02691) · [PDF](https://arxiv.org/pdf/2610.02691)

## Abstract

Interactive world simulators can provide scalable environments for robot planning, policy training, and evaluation by predicting action consequences while reducing reliance on repeated physical rollouts. To serve these applications, they must generate future image sequences that respond faithfully to robot actions and preserve the dynamics of robot-object interactions over long horizons. However, existing world models typically predict the entire next latent state and often fail to capture subtle changes induced by robot actions. Such omissions can produce physically implausible outcomes, including object interpenetration and excessive deformation. To address this limitation, we propose DeltaWorld, a physically consistent interactive world simulator for robotic manipulation. Our method introduces the Delta Latent Transition Model (Delta-LTM), which predicts action-induced latent feature changes and adds them to the current latent state to obtain the next state, rather than predicting the next latent state directly. To mitigate object interpenetration and excessive deformation in predicted future frames, Interaction-aware Latent Alignment is introduced to construct counterfactual interaction regions and supervise interaction-related latent changes. DeltaWorld is evaluated on the IWS manipulation benchmark and a self-collected cross-robot dataset covering multiple robot embodiments and manipulation tasks. On the cross-robot dataset, DeltaWorld reduces FVD by 46.6% and LPIPS by 31.1% relative to the IWS baseline. These results highlight the potential of DeltaWorld for long-horizon action-conditioned video prediction in robotic manipulation.

## TL;DR

Interactive world simulators can provide scalable environments for robot planning, policy training, and evaluation by predicting action consequences while reducing reliance on repeated physical rollouts. To serve these applications, they must generate future image sequences that respond faithfully to robot actions and preserve the dynamics of robot-object interactions over long horizons.

## Related
<!-- [[other-paper-citekey]] -->
