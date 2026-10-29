---
citekey: "jungLLAMPPIRapidlyAdaptiveWholeBodyControlLegged2026"
title: "LLA-MPPI: Rapidly Adaptive Whole-body Control of Legged Robots with GPU-Accelerated Parallel Simulations"
authors: ["Sebin Jung", "Maitham F. AL-Sunni", "Juan Alvarez-Padilla", "Zachary Manchester", "Changliu Liu", "John M. Dolan"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.10465"
doi: "10.48550/arXiv.2610.10465"
tags: [paper, embodied-ai, "cs.RO", "eess.SY"]
status: unread
rating:
created: 2026-10-10
---

# LLA-MPPI: Rapidly Adaptive Whole-body Control of Legged Robots with GPU-Accelerated Parallel Simulations

> Sebin Jung, Maitham F. AL-Sunni, Juan Alvarez-Padilla, Zachary Manchester, Changliu Liu, John M. Dolan · 2026
> [arXiv](https://arxiv.org/abs/2610.10465) · [PDF](https://arxiv.org/pdf/2610.10465)

## Abstract

Real-time whole-body controllers for legged robots typically plan through a fixed nominal model and degrade when the deployed dynamics change. Adaptive methods typically require a model structure that contact dynamics do not provide, or they need offline training for each anticipated condition. We present Look-back and Look-ahead Adaptive Model Predictive Path Integral control (LLA-MPPI). The method converts whole-body adaptation into selection over a bank of GPU-batched contact simulators with different physical or structural parameters. Windowed prediction errors select the simulator that best explains recent motion. A whole-body MPPI planner optimizes controls through the selected model. The framework requires no offline training, and its selected hypotheses are physically interpretable. Across four simulated tasks, it achieves 97.5% success while the strongest baseline reaches 74% and an oracle with the true model reaches 98.5%. Hardware validation on a Unitree Go2 shows the robot walking under a payload added mid-run, walking after one leg is disabled, and pushing a box to its goal while increasing its mass on the fly. Code, videos, and project details are available at: https://lla-control.github.io

## TL;DR

Real-time whole-body controllers for legged robots typically plan through a fixed nominal model and degrade when the deployed dynamics change. Adaptive methods typically require a model structure that contact dynamics do not provide, or they need offline training for each anticipated condition.

## Related
<!-- [[other-paper-citekey]] -->
