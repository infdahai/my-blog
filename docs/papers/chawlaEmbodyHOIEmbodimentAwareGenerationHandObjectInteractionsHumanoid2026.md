---
citekey: "chawlaEmbodyHOIEmbodimentAwareGenerationHandObjectInteractionsHumanoid2026"
title: "EmbodyHOI: Embodiment-Aware Generation of Hand-Object Interactions for Humanoid Dexterous Manipulation"
authors: ["Chaitanya Chawla", "Kartik Sharma", "Ananya Bal", "Laszlo A. Jeni", "Guanya Shi"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.27242"
doi: "10.48550/arXiv.2610.27242"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-22
---

# EmbodyHOI: Embodiment-Aware Generation of Hand-Object Interactions for Humanoid Dexterous Manipulation

> Chaitanya Chawla, Kartik Sharma, Ananya Bal, Laszlo A. Jeni, Guanya Shi · 2026
> [arXiv](https://arxiv.org/abs/2610.27242) · [PDF](https://arxiv.org/pdf/2610.27242)

## Abstract

Humanoid dexterous manipulation needs reference motions that are both semantically rich and kinematically feasible for the target robot. Text-conditioned hand-object interaction (HOI) generators supply diverse, language-specified demonstrations, but they synthesize motion in human (MANO) space. The embodiment gap is therefore deferred to post-hoc retargeting, where trajectories deployed on the robot can fail to maintain contact with objects and also degrade policy learning. Our key idea is that robot reachability should constrain the interaction trajectories while they are being generated. We present EmbodyHOI, which runs a differentiable inverse-kinematics (IK) solver for a specific humanoid embodiment inside the sampling loop of a frozen flow-matching HOI trajectory generator. We feed back gradients from the embodiment-aware IK solver into the HOI sampler and jointly optimize the position of the humanoid with respect to the object. Because guidance acts only at inference, one HOI trajectory generator trained on human hand poses transfers across humanoid embodiments without retraining. On ARCTIC trajectories with two contrasting humanoids (Unitree G1 and H1-2), our proposed guidance-based method cuts the retargeted wrist error from 8.9 cm to 0.6 cm while leaving text-to-HOI generation quality intact, and raises task success from 68% to 79% on 50 random G1 tasks and from 62% to 76% on a four-task H1-2 suite. Critically, cheaper alternatives for bridging the embodiment gap fail to beat EmbodyHOI. Post-hoc wrist refinement and compute-matched best-of-N selection both reach lower IK energy than our guidance yet train worse policies. For simulation results, see our website: https://embodyhoi.github.io/

## TL;DR

Humanoid dexterous manipulation needs reference motions that are both semantically rich and kinematically feasible for the target robot. Text-conditioned hand-object interaction (HOI) generators supply diverse, language-specified demonstrations, but they synthesize motion in human (MANO) space.

## Related
<!-- [[other-paper-citekey]] -->
