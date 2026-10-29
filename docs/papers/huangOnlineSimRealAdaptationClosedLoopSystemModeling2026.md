---
citekey: "huangOnlineSimRealAdaptationClosedLoopSystemModeling2026"
title: "Online Sim-to-Real Adaptation via Closed-Loop System Modeling"
authors: ["Yuhao Huang", "Samuel A. Moore", "Boyuan Chen"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.28878"
doi: "10.48550/arXiv.2609.28878"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-26
---

# Online Sim-to-Real Adaptation via Closed-Loop System Modeling

> Yuhao Huang, Samuel A. Moore, Boyuan Chen · 2026
> [arXiv](https://arxiv.org/abs/2609.28878) · [PDF](https://arxiv.org/pdf/2609.28878)

## Abstract

Sim-to-real transfer has made substantial progress, but can still produce controllers that remain stable and functional on hardware while suffering from degraded tracking accuracy due to residual dynamics mismatch. Correcting these errors typically requires identifying the underlying system dynamics, adapting the control policy, or returning to simulation for additional training and finetuning, all of which can require substantial data and computation. We propose OSRAM (Online Sim-to-Real Adaptation via Closed-Loop System Modeling), a framework that instead adapts the reference commands provided to an existing controller. OSRAM treats the deployed robot and its policy as a unified closed-loop dynamical system and learns its task-level command-response behavior directly from tracking observations. A closed-loop dynamics model is meta-trained across randomized dynamics in simulation and rapidly finetuned after deployment using limited real-world interaction. The adapted model is then used to optimize future reference commands while leaving the underlying control policy unchanged. We evaluate OSRAM on bipedal velocity tracking and loco-manipulation in simulation and on hardware. Results show that closed-loop modeling improves prediction and tracking accuracy under unseen dynamics, while online reference adaptation reduces residual sim-to-real tracking errors across different control objectives and hardware configurations. These results demonstrate that adapting the behavior of the robot-policy closed loop provides a practical alternative to finetuning the policy or identifying the full physical dynamics for sim-to-real transfer. More information can be found at http://generalroboticslab.com/OSRAM.

## TL;DR

Sim-to-real transfer has made substantial progress, but can still produce controllers that remain stable and functional on hardware while suffering from degraded tracking accuracy due to residual dynamics mismatch. Correcting these errors typically requires identifying the underlying system dynamics, adapting the control policy, or returning to simulation for additional training and finetuning, all of which can require substantial data and computation.

## Related
<!-- [[other-paper-citekey]] -->
