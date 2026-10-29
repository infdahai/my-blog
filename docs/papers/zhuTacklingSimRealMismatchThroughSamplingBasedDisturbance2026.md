---
citekey: "zhuTacklingSimRealMismatchThroughSamplingBasedDisturbance2026"
title: "Tackling Sim-to-Real Mismatch Through Sampling-Based Disturbance Observers: From Analytical Models to Learned World Models"
authors: ["Tianqi Zhu", "Jun Yang", "Jianliang Mao", "Cong Li", "Shihua Li"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.04896"
doi: "10.48550/arXiv.2610.04896"
tags: [paper, embodied-ai, "cs.RO", "eess.SY"]
status: unread
rating:
created: 2026-10-08
---

# Tackling Sim-to-Real Mismatch Through Sampling-Based Disturbance Observers: From Analytical Models to Learned World Models

> Tianqi Zhu, Jun Yang, Jianliang Mao, Cong Li, Shihua Li · 2026
> [arXiv](https://arxiv.org/abs/2610.04896) · [PDF](https://arxiv.org/pdf/2610.04896)

## Abstract

Robotic controllers increasingly rely on analytical models, simulators, cost-query interfaces, and learned world models. However, physical deployment can deviate from nominal assumptions, and additional disturbances may arise even when the model itself is accurate. In control systems, disturbance observers (DOB) are widely used to estimate such unmeasured effects from nominal models and measured feedback. Classical DOB formulations are generally built around explicit plant models. This paper develops the sampling-based disturbance observer (SDOB), extending the DOB principle to a broader range of models, including simulators and learned world models, through state-rollout or cost-query interfaces. SDOB separates two observable channels: state-effect disturbances, for which the feedback state differs from its prediction, and cost disturbances, for which the same query state receives different costs as the perceived environment changes. Diverse simulation and real-robot experiments across traditional and learned models demonstrate the effectiveness of SDOB in compensating for sim-to-real mismatch and improving control performance.

## TL;DR

Robotic controllers increasingly rely on analytical models, simulators, cost-query interfaces, and learned world models. However, physical deployment can deviate from nominal assumptions, and additional disturbances may arise even when the model itself is accurate.

## Related
<!-- [[other-paper-citekey]] -->
