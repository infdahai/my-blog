---
citekey: "leReplayConstrainedSimulationFrameworkPersonalizationPoweredKneeAnkle2026"
title: "A Replay-Constrained Simulation Framework for Personalization of Powered Knee--Ankle Prosthesis Controllers"
authors: ["Duong Le", "Ryan Posh", "Shihao Cheng", "Maani Ghaffari", "Robert D. Gregg"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2607.22858"
doi: "10.48550/arXiv.2607.22858"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-07
---

# A Replay-Constrained Simulation Framework for Personalization of Powered Knee--Ankle Prosthesis Controllers

> Duong Le, Ryan Posh, Shihao Cheng, Maani Ghaffari, Robert D. Gregg · 2026
> [arXiv](https://arxiv.org/abs/2607.22858) · [PDF](https://arxiv.org/pdf/2607.22858)

## Abstract

Personalization of impedance controllers for powered prosthetic legs is critical to accommodating individual gait biomechanics but remains challenging. Existing methods rely on time-intensive human-in-the-loop exploration and/or constrain optimization to low-dimensional, single-joint parameter subspaces. Sim-to-real transfer has enabled high-dimensional locomotion control for legged robots, but in assistive device control the human partner remains un-modelable. We present a replay-constrained simulation framework: a MuJoCo-based simulator reproduces prosthetic knee-ankle dynamics while replaying recorded hip kinematics and feedback-based ground reaction forces from individual walking data, bypassing the need to model complex human neuromuscular control mechanisms. We demonstrate the framework with a deep reinforcement learning policy that personalizes phase-dependent stiffness, damping, and equilibrium angle at both joints simultaneously, maximizing a biomimicry-based reward computed solely from onboard prosthesis measurements. Experiments with three participants with transfemoral amputation during level-ground walking at 0.8~m/s demonstrate strong simulation-to-hardware predictive validity (Pearson $r=0.96$--$0.997$). The best-performing policy on hardware was consistently predicted within the top five simulation policies for all participants. The learned controllers improved overall biomimicry rewards by 42--59\% relative to the unpersonalized baseline. The framework supports scalable high-dimensional personalization of powered prosthetic legs and is amenable to extension to higher-dimensional controller parameterizations such as neural-network controllers.

## TL;DR

Personalization of impedance controllers for powered prosthetic legs is critical to accommodating individual gait biomechanics but remains challenging. Existing methods rely on time-intensive human-in-the-loop exploration and/or constrain optimization to low-dimensional, single-joint parameter subspaces.

## Related
<!-- [[other-paper-citekey]] -->
