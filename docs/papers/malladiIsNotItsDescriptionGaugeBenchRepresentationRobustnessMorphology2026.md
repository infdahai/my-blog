---
citekey: "malladiIsNotItsDescriptionGaugeBenchRepresentationRobustnessMorphology2026"
title: "The Robot Is Not Its Description: GaugeBench for Representation Robustness in Morphology-Aware Policies"
authors: ["Rahath Malladi", "Arshia Sangwan", "Rajesh K. Gupta", "Tauhidur Rahman"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.07597"
doi: "10.48550/arXiv.2610.07597"
tags: [paper, embodied-ai, "cs.LG", "cs.RO"]
status: unread
rating:
created: 2026-10-08
---

# The Robot Is Not Its Description: GaugeBench for Representation Robustness in Morphology-Aware Policies

> Rahath Malladi, Arshia Sangwan, Rajesh K. Gupta, Tauhidur Rahman · 2026
> [arXiv](https://arxiv.org/abs/2610.07597) · [PDF](https://arxiv.org/pdf/2610.07597)

## Abstract

A robot description does more than specify a physical mechanism: it also encodes arbitrary conventions, such as joint-axis direction, joint-angle zero, and the order and names of links and joints. Morphology-aware policies consume interfaces built from these descriptions, yet cross-embodiment evaluation typically changes the robot while keeping those conventions fixed. This leaves a simple question unanswered: does behavior survive when the robot stays fixed but its description changes? GaugeBench isolates this case by rewriting a fixed mechanism under physically equivalent conventions, verifying that its physics and policy interface are preserved, and then evaluating the same policy weights. The result is stark: three MetaMorph policies score 4030.6 on 80 familiar robots, but only 51.6 when those same robots are equivalently re-described, while 98 genuinely held-out robots score 1489.6. A new description can therefore be more damaging than a new robot. Tracing the failure reveals that axis reversal alone reproduces the collapse, joint-angle zero changes are nearly harmless, and reordering lies between them; moreover, changing joint-state and torque coordinates alone is sufficient to cause the failure, while changing description-derived features alone is not. The same phenomenon appears in ModuMorph and an unrelated PyBullet framework. Yet it is not irreversible: exact two-description transport restores the original controller, and training across equivalent axis conventions raises retained return under axis reversal from 3.6% to 80.6%. Together, these results separate mechanism robustness from representation robustness and show that cross-embodiment evaluation should test both.

## TL;DR

A robot description does more than specify a physical mechanism: it also encodes arbitrary conventions, such as joint-axis direction, joint-angle zero, and the order and names of links and joints. Morphology-aware policies consume interfaces built from these descriptions, yet cross-embodiment evaluation typically changes the robot while keeping those conventions fixed.

## Related
<!-- [[other-paper-citekey]] -->
