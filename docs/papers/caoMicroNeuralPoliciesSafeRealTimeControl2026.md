---
citekey: "caoMicroNeuralPoliciesSafeRealTimeControl2026"
title: "Micro Neural Policies for Safe Real-Time Robotic Control"
authors: ["Hongpeng Cao", "Riccardo Curcio", "Daniele Ottaviano", "Marco Caccamo"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.08541"
doi: "10.48550/arXiv.2610.08541"
tags: [paper, embodied-ai, "cs.AI", "cs.RO"]
status: unread
rating:
created: 2026-10-08
---

# Micro Neural Policies for Safe Real-Time Robotic Control

> Hongpeng Cao, Riccardo Curcio, Daniele Ottaviano, Marco Caccamo · 2026
> [arXiv](https://arxiv.org/abs/2610.08541) · [PDF](https://arxiv.org/pdf/2610.08541)

## Abstract

In this paper, we investigate the synthesis of Micro Neural Policies (MNP) to enable safe and robust real-time robotic control on computationally constrained embedded devices. We demonstrate that integrating Evolution Strategy (ES) and Statistical Model Checking (SMC)-based verification for policy search can drastically reduce neural network size without compromising safety and robustness. We conduct a large-scale training and evaluation of MNP on Cartpole and Quadrotor control tasks, varying control frequencies and network architectures. After validating these policies in simulation, we evaluate their deployability through zero-shot transfer to physical systems. Our experiments show that MNP can successfully achieve safe sim-to-real transfer without sacrificing control performance. We then show that the policies' memory footprint, ranging from 0.5 to 7.5 kB, allows deployment on microcontrollers, where they achieve real-time inference latency with under 25 ns of jitter while leaving the chip idle for over 97% of the time for additional workloads. This makes them a highly practical solution for severely resource-constrained robotic systems.

## TL;DR

In this paper, we investigate the synthesis of Micro Neural Policies (MNP) to enable safe and robust real-time robotic control on computationally constrained embedded devices. We demonstrate that integrating Evolution Strategy (ES) and Statistical Model Checking (SMC)-based verification for policy search can drastically reduce neural network size without compromising safety and robustness.

## Related
<!-- [[other-paper-citekey]] -->
