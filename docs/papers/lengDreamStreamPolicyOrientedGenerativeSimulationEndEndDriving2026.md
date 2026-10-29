---
citekey: "lengDreamStreamPolicyOrientedGenerativeSimulationEndEndDriving2026"
title: "DreamStream: Towards Policy-Oriented Generative Simulation for End-to-End Driving"
authors: ["Ziyang Leng", "Sicheng Mo", "Seth Z. Zhao", "Haoyuan Cai", "Yu Zeng", "Rowan McAllister", "Bolei Zhou"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.26792"
doi: "10.48550/arXiv.2609.26792"
tags: [paper, embodied-ai, "cs.CV", "cs.RO"]
status: unread
rating:
created: 2026-09-24
---

# DreamStream: Towards Policy-Oriented Generative Simulation for End-to-End Driving

> Ziyang Leng, Sicheng Mo, Seth Z. Zhao, Haoyuan Cai, Yu Zeng, Rowan McAllister, Bolei Zhou · 2026
> [arXiv](https://arxiv.org/abs/2609.26792) · [PDF](https://arxiv.org/pdf/2609.26792)

## Abstract

Faithfully evaluating end-to-end driving policies in simulation requires observations that are not merely photo-realistic, but preserve the scene features a policy relies on to make decisions. Existing platforms, however, exhibit a sim-to-real visual gap that corrupts policy perception, undermining their ability to assess a policy's closed-loop decision-making. To this end, we propose DreamStream, a generative, closed-loop simulator that achieves policy-oriented fidelity using a simulator-grounded autoregressive video model. Our video model is distilled from a large pretrained video model via traffic layout guidance, varying visual appearance while preserving policy-relevant features such as scenario layout and the temporal consistency of dynamic objects. We further observe that perceptual metrics like FID misrank how well these features are preserved. To tackle this, we introduce FD$π$, a new multi-representation metric that measures the sim-to-real gap as the Fréchet distance over scene-context features from public E2E policies. Under FD$π$, DreamStream improves over the strongest prior closed-loop simulator by $1.6\times$ on nuScenes and $4.7\times$ on NAVSIM, and induces the least perturbation to policy's perceptual observability. Based on DreamStream, we construct Navhard-CL benchmark, which turns non-reactive real-world benchmark NAVSIM into interactive testing environments with adversarial driving behaviors and weather variations. This benchmark exposes many failure modes of driving policies, such as scorer bias and lack of recovery behaviors, that prior closed-loop benchmarks overlook. Code and data are available at https://github.com/VAIL-UCLA/DreamStream.

## TL;DR

Faithfully evaluating end-to-end driving policies in simulation requires observations that are not merely photo-realistic, but preserve the scene features a policy relies on to make decisions. Existing platforms, however, exhibit a sim-to-real visual gap that corrupts policy perception, undermining their ability to assess a policy's closed-loop decision-making.

## Related
<!-- [[other-paper-citekey]] -->
