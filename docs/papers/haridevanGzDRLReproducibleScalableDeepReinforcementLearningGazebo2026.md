---
citekey: "haridevanGzDRLReproducibleScalableDeepReinforcementLearningGazebo2026"
title: "GzDRL: Reproducible and Scalable Deep Reinforcement Learning with Gazebo"
authors: ["Amal Dev Haridevan", "Junjie Kang", "Jinjun Shan"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.13243"
doi: "10.48550/arXiv.2609.13243"
tags: [paper, embodied-ai, "cs.LG", "cs.RO"]
status: unread
rating:
created: 2026-09-16
---

# GzDRL: Reproducible and Scalable Deep Reinforcement Learning with Gazebo

> Amal Dev Haridevan, Junjie Kang, Jinjun Shan · 2026
> [arXiv](https://arxiv.org/abs/2609.13243) · [PDF](https://arxiv.org/pdf/2609.13243)

## Abstract

We present GzDRL, a novel single-process reinforcement learning (RL) framework for Gazebo that overcomes longstanding bottlenecks in scalable, reproducible robotics experimentation. Unlike conventional middleware-based RL-Gazebo integrations that suffer from nondeterminism and irreproducibility, GzDRL introduces a systematic, middleware-free environment-stepping mechanism that directly synchronizes agent actions and physics updates. This design enables deterministic, high-throughput data collection, efficient vectorization, and reproducible RL training and evaluation. Comprehensive benchmarks demonstrate that GzDRL achieves the highest workstation throughput among the evaluated frameworks while remaining competitive with GPU-accelerated simulators on laptop hardware, and maintains precise agent-environment synchronization, multi-agent scalability, and experiment-level reproducibility. We further validate sim-to-real transfer by deploying learned policies directly onto a physical quadrotor, without fine-tuning. Our results establish GzDRL as an accessible and reproducible platform for advancing RL in robotics and automation.

## TL;DR

We present GzDRL, a novel single-process reinforcement learning (RL) framework for Gazebo that overcomes longstanding bottlenecks in scalable, reproducible robotics experimentation. Unlike conventional middleware-based RL-Gazebo integrations that suffer from nondeterminism and irreproducibility, GzDRL introduces a systematic, middleware-free environment-stepping mechanism that directly synchronizes agent actions and physics updates.

## Related
<!-- [[other-paper-citekey]] -->
