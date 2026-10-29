---
citekey: "memmesheimerSampleSimulateSelectPhysicsLoopTextMotionHumanoids2026"
title: "Sample, Simulate, Select: Physics-in-the-Loop Text-to-Motion for Humanoids Without Training"
authors: ["Raphael Memmesheimer", "Sven Behnke"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.26420"
doi: "10.48550/arXiv.2609.26420"
tags: [paper, embodied-ai, "cs.CV", "cs.RO"]
status: unread
rating:
created: 2026-09-24
---

# Sample, Simulate, Select: Physics-in-the-Loop Text-to-Motion for Humanoids Without Training

> Raphael Memmesheimer, Sven Behnke · 2026
> [arXiv](https://arxiv.org/abs/2609.26420) · [PDF](https://arxiv.org/pdf/2609.26420)

## Abstract

Text-to-motion models generate plausible human motion but do not model a robot's dynamics; whole-body tracking controllers execute robot references reliably but cannot replan an infeasible one. Recent language-to-humanoid systems bridge this gap by training. We measure how much of the gap closes with no training at all, by putting the deployment controller itself in the loop. Sample-simulate-select (S$^3$) draws $N$ motions per prompt from a frozen text-to-motion model, retargets each to a Unitree G1 by direction-matching inverse kinematics, rolls all of them out under full rigid-body dynamics with the pretrained SONIC tracking policy, and keeps the candidate the policy executed best. Because the verifier is the deterministic simulator itself, S$^3$ attains the any-of-$N$ ceiling by construction; what we measure is where that ceiling lies and what falls short of it. On 200 stratified HumanML3D test prompts with $N=8$, upright execution rises from 83.5% to 89.5% and hardware-gate passes from 33 to 85; on the complete test split (4,184 prompts) it rises from 80.5% to 89.5%. A kinematic verifier that predicts falls well (AUROC 0.90) recovers only a quarter of this gain: ranking a prompt's own candidates is harder than classifying the population. What selection cannot fix is one class, prompts that lower the pelvis, which a generator trained on retargeted robot data does execute. We further score the semantic fidelity of the executed motion with the standard text-motion evaluator, with a real-mocap control that attributes the loss to the robot projection, ablate the retargeter against GMR (complementary failures: the any-of-8 ceiling rises to 95.0% over both), and execute all 177 gate-selected clips on the real G1: every one completes standing, with hardware tracking error matching simulation ($r=0.94$).

## TL;DR

Text-to-motion models generate plausible human motion but do not model a robot's dynamics; whole-body tracking controllers execute robot references reliably but cannot replan an infeasible one. Recent language-to-humanoid systems bridge this gap by training.

## Related
<!-- [[other-paper-citekey]] -->
