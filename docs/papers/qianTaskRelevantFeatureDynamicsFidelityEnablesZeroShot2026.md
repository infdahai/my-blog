---
citekey: "qianTaskRelevantFeatureDynamicsFidelityEnablesZeroShot2026"
title: "Task-Relevant Feature-Dynamics Fidelity Enables Zero-Shot Sim-to-Real Transfer for Robotic Ultrasound Scanning"
authors: ["Yizhao Qian", "Jiayuan Luo", "Wanyi Zhu", "Yameng Zhang", "Max Q. -H. Meng", "Yixuan Yuan", "Li Liu"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2608.29516"
doi: "10.48550/arXiv.2608.29516"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-02
---

# Task-Relevant Feature-Dynamics Fidelity Enables Zero-Shot Sim-to-Real Transfer for Robotic Ultrasound Scanning

> Yizhao Qian, Jiayuan Luo, Wanyi Zhu, Yameng Zhang, Max Q. -H. Meng, Yixuan Yuan, Li Liu · 2026
> [arXiv](https://arxiv.org/abs/2608.29516) · [PDF](https://arxiv.org/pdf/2608.29516)

## Abstract

Robotic ultrasound policies operating directly on B-mode images require extensive interaction data, whereas real-robot data collection is costly and safety-constrained. Simulation provides a scalable alternative, but zero-shot transfer depends not only on single-frame realism but also on whether simulated observations reproduce task-relevant feature changes induced by probe motion. We term this cross-domain consistency task-relevant feature-dynamics fidelity (TR-FDF). Under local regularity assumptions, our contraction analysis shows that greater sensitivity of TR-FDF mismatch to probe motion reduces the effective closed-loop contraction margin, whereas motion-independent errors primarily enlarge the residual error bound. Guided by this analysis, we develop a TR-FDF-oriented ultrasound simulator that combines a shared structural intermediate domain, trajectory-level fixed noise, and few-step conditional flow generation. In phantom experiments, a policy trained exclusively in simulation succeeded in 390 of 400 zero-shot deployments across four target planes. The simulator achieved an FID of 29.66 and generated observations at 67.1 Hz. Controlled interventions, ablations, and baseline comparisons showed that TR-FDF sensitivity complements single-frame realism in predicting zero-shot transfer performance.

## TL;DR

Robotic ultrasound policies operating directly on B-mode images require extensive interaction data, whereas real-robot data collection is costly and safety-constrained. Simulation provides a scalable alternative, but zero-shot transfer depends not only on single-frame realism but also on whether simulated observations reproduce task-relevant feature changes induced by probe motion.

## Related
<!-- [[other-paper-citekey]] -->
