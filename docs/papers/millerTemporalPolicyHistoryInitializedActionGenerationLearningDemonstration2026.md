---
citekey: "millerTemporalPolicyHistoryInitializedActionGenerationLearningDemonstration2026"
title: "Temporal Policy: History-Initialized Action Generation for Robotic Learning from Demonstration"
authors: ["Dylan Miller", "Martin Jagersand"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2607.29482"
doi: "10.48550/arXiv.2607.29482"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-07
---

# Temporal Policy: History-Initialized Action Generation for Robotic Learning from Demonstration

> Dylan Miller, Martin Jagersand · 2026
> [arXiv](https://arxiv.org/abs/2607.29482) · [PDF](https://arxiv.org/pdf/2607.29482)

## Abstract

By relying on independent couplings from uninformative Gaussian priors, standard diffusion and flow matching models are forced to learn complex, high-cost vector fields to reach the physical action space. Generative models excel at capturing multimodal behaviors for robotic Learning from Demonstration (LfD), but often suffer from high inference cost. This paper introduces Temporal Policy, a generative framework based on stochastic interpolants that formulates action generation as a temporally coupled transport problem. By initializing the generative flow at the robot's recent history, we explicitly couple past states to future action sequences. This data-dependent coupling reduces transport cost and produces straight vector fields. We validate Temporal Policy across visuomotor simulation benchmarks and on a physical Barrett WAM 2x 7DoF teleoperation platform. Our approach reduces transport costs by nearly an order of magnitude compared to noise-initialized baselines, achieving a 19.1 ms inference latency on a single NVIDIA RTX 4080. Crucially, these geometric and computational efficiencies are achieved while matching the success rates of state-of-the-art baselines. This simplified transport geometry bypasses the computational bottleneck of independent Gaussian priors, helping enable high-frequency, closed-loop control. The code is publicly available at https://github.com/dmiller12/TemporalPolicy.

## TL;DR

By relying on independent couplings from uninformative Gaussian priors, standard diffusion and flow matching models are forced to learn complex, high-cost vector fields to reach the physical action space. Generative models excel at capturing multimodal behaviors for robotic Learning from Demonstration (LfD), but often suffer from high inference cost.

## Related
<!-- [[other-paper-citekey]] -->
