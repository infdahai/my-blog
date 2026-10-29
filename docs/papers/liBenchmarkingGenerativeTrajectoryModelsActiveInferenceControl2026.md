---
citekey: "liBenchmarkingGenerativeTrajectoryModelsActiveInferenceControl2026"
title: "Benchmarking Generative Trajectory Models for Active-Inference Control"
authors: ["Yulin Li", "Mohsen A. Jafari", "Andrea Matta"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.05692"
doi: "10.48550/arXiv.2610.05692"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-07
---

# Benchmarking Generative Trajectory Models for Active-Inference Control

> Yulin Li, Mohsen A. Jafari, Andrea Matta · 2026
> [arXiv](https://arxiv.org/abs/2610.05692) · [PDF](https://arxiv.org/pdf/2610.05692)

## Abstract

Learning from trajectory demonstrations offers a route to active-inference control of complex systems whose dynamics are difficult to model explicitly. We introduce generative active-inference control (GenAIF), in which one generative trajectory model learns from demonstrations and measured action interventions to supply a goal-conditioned policy distribution and a state-to-observation likelihood mapping. From this control design, we derive three model requirements: (i) useful action proposals, (ii) accurate prediction under imposed actions, and (iii) probabilistic observation evidence for belief updating and expected information gain. We benchmark diffusion, autoregressive Transformers, conditional variational autoencoders (CVAEs), and flow matching in a MuJoCo manipulation task with multiple physical conditions. Diffusion delivers the strongest control across the tested dynamics, while CVAE combines comparable short-horizon prediction with much faster inference. Correct conditioning is decisive, and trajectory reuse offers further computational savings. With the same frozen models, a hidden-dynamics experiment demonstrates prompt belief adaptation after an unannounced tilt change; subsequent instability identifies sustained inference as a remaining challenge. These findings support the use of shared generative trajectory models to connect action proposal, controlled prediction, and observation evidence within GenAIF.

## TL;DR

Learning from trajectory demonstrations offers a route to active-inference control of complex systems whose dynamics are difficult to model explicitly. We introduce generative active-inference control (GenAIF), in which one generative trajectory model learns from demonstrations and measured action interventions to supply a goal-conditioned policy distribution and a state-to-observation likelihood mapping.

## Related
<!-- [[other-paper-citekey]] -->
