---
citekey: "ahmadBeyondKinematicsBenchmarkingSimulationFidelityMuscleDrivenImitation2026"
title: "Beyond Kinematics: Benchmarking Simulation Fidelity for Muscle-Driven Imitation Learning"
authors: ["Ayah G. Ahmad", "Claire E. Borden", "Maegan Tucker"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.21909"
doi: "10.48550/arXiv.2609.21909"
tags: [paper, embodied-ai, "cs.LG", "cs.RO"]
status: unread
rating:
created: 2026-09-22
---

# Beyond Kinematics: Benchmarking Simulation Fidelity for Muscle-Driven Imitation Learning

> Ayah G. Ahmad, Claire E. Borden, Maegan Tucker · 2026
> [arXiv](https://arxiv.org/abs/2609.21909) · [PDF](https://arxiv.org/pdf/2609.21909)

## Abstract

In this work, we conduct a systematic comparison of two state-of-the-art motion-imitation reinforcement learning (MIRL) pipelines, one built on SCONE/HyFyDy and one built on MuJoCo/MyoSim. HyFyDy emphasizes physiological realism through detailed musculotendon modeling, while MuJoCo prioritizes computational efficiency and scalable policy learning. While recent work has demonstrated that both pipelines reproduce human kinematics with high fidelity, it remains unclear if they accurately capture the underlying neuromuscular behavior that produced the movement. This limitation is particularly important for robotic assistive-device design and control, where outcome measures such as muscle activation patterns and metabolic cost are often used as optimization targets. To conduct a systematic comparison, our work compares both pipelines using a common set of human motion-capture and electromyography (EMG) measurements. The results find that while both pipelines produce similar kinematics with relative accuracy, the muscle activations from HyFyDy are more aligned with the experimental EMG, as supported by the average pooled (RMSE, r) values for muscle activations from HyFyDy and MuJoCo: (0.164, 0.4) and (0.344, 0.11), respectively. While we conclude that the more advanced physiological realism of HyFyDy currently makes it more suitable for musculoskeletal modeling, both require further development to bring physiological realism to GPU-parallelizable simulation environments and advance robotic assistive device design.

## TL;DR

In this work, we conduct a systematic comparison of two state-of-the-art motion-imitation reinforcement learning (MIRL) pipelines, one built on SCONE/HyFyDy and one built on MuJoCo/MyoSim. HyFyDy emphasizes physiological realism through detailed musculotendon modeling, while MuJoCo prioritizes computational efficiency and scalable policy learning.

## Related
<!-- [[other-paper-citekey]] -->
