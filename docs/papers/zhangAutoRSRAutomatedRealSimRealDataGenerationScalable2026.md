---
citekey: "zhangAutoRSRAutomatedRealSimRealDataGenerationScalable2026"
title: "AutoRSR: Automated Real-to-Sim-to-Real Data Generation for Scalable Robot Learning"
authors: ["Jiawei Zhang", "Chang Liu", "Litao Deng", "Tao Zhang", "Qin Jin"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.20336"
doi: "10.48550/arXiv.2610.20336"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-16
---

# AutoRSR: Automated Real-to-Sim-to-Real Data Generation for Scalable Robot Learning

> Jiawei Zhang, Chang Liu, Litao Deng, Tao Zhang, Qin Jin · 2026
> [arXiv](https://arxiv.org/abs/2610.20336) · [PDF](https://arxiv.org/pdf/2610.20336)

## Abstract

Scaling embodied robot learning requires large and diverse manipulation datasets, but collecting real-world demonstrations remains expensive in human effort and robot time. Simulation provides a scalable alternative, yet converting a real workspace into a robot-learning-ready environment still requires substantial manual effort for object extraction, asset processing, coordinate calibration, and trajectory specification. We present AutoRSR, a highly automated real-to-sim-to real framework that converts scanned real-world workspaces into reusable embodied simulation assets and scalable manipulation data. Given multi-view observations, robot states, and open-vocabulary semantic queries, AutoRSR reconstructs the workspace, extracts individual object assets, and automatically registers the reconstructed scene to the robot base frame at metric scale. Starting from a small number of reference motions, AutoRSR then generates executable manipulation trajectories and scales them through trajectory interpolation and domain randomization. After workspace scanning and semantic queries, the remaining pipeline requires no manual object annotation, scene-to-robot calibration, or robot teleoperation. Across three real-world manipulation tasks, policies trained on 1K automatically generated episodes per task achieve 73.3--86.7% real-world success rates, comparable to pi 0.5 trained from 150 human teleoperated demonstrations, while reducing the human time required for data generation by an order of magnitude. These results demonstrate that real-world observations can be converted into metrically aligned, executable, and scalable simulation data with substantially reduced human effort.

## TL;DR

Scaling embodied robot learning requires large and diverse manipulation datasets, but collecting real-world demonstrations remains expensive in human effort and robot time. Simulation provides a scalable alternative, yet converting a real workspace into a robot-learning-ready environment still requires substantial manual effort for object extraction, asset processing, coordinate calibration, and trajectory specification.

## Related
<!-- [[other-paper-citekey]] -->
