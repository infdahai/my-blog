---
citekey: "universityIMLEVLAFastSingleStepActionGenerationVision2026"
title: "IMLE-VLA: Fast Single-Step Action Generation for Vision-Language-Action Policies"
authors: ["Kian Hosseinkhani (Simon Fraser University)", "Qinhe Peng (University of Pennsylvania)", "George Shramko (Simon Fraser University)", "Mehran Aghabozorgi (Simon Fraser University)", "Jianing Qian (University of Pennsylvania)", "Tristan Engst (Simon Fraser University)", "Alireza Moazeni (Simon Fraser University)", "Dinesh Jayaraman (University of Pennsylvania)", "Ke Li (Simon Fraser University", "Canada CIFAR AI Chair)"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.10915"
doi: "10.48550/arXiv.2609.10915"
tags: [paper, embodied-ai, "cs.CV", "cs.RO"]
status: unread
rating:
created: 2026-09-12
---

# IMLE-VLA: Fast Single-Step Action Generation for Vision-Language-Action Policies

> Kian Hosseinkhani (Simon Fraser University), Qinhe Peng (University of Pennsylvania), George Shramko (Simon Fraser University), Mehran Aghabozorgi (Simon Fraser University), Jianing Qian (University of Pennsylvania), Tristan Engst (Simon Fraser University), Alireza Moazeni (Simon Fraser University), Dinesh Jayaraman (University of Pennsylvania), Ke Li (Simon Fraser University, Canada CIFAR AI Chair) · 2026
> [arXiv](https://arxiv.org/abs/2609.10915) · [PDF](https://arxiv.org/pdf/2609.10915)

## Abstract

Vision-language-action (VLA) policies leverage pretrained vision-language backbones to achieve strong cross-task generalization. A leading design couples this backbone with a dedicated continuous action head trained via diffusion or flow matching. However, such heads rely on iterative multi-step sampling, for example 10 Euler steps in $\pi_{0.5}$. This creates an inference bottleneck that produces stop-and-go movement in the robot and slower task completion. We introduce IMLE-VLA, which replaces the iterative action head with a single-step conditional generator trained via conditional Implicit Maximum Likelihood Estimation (cIMLE). The cIMLE objective promotes multimodal action coverage, avoiding the mode collapse of naive regression heads while eliminating multi-step sampling entirely. When IMLE-VLA is applied to $\pi_{0.5}$, it increases inference frequency 3.67x (55 Hz vs. 15 Hz), enabling up to 11x higher action throughput. On the 40-task LIBERO benchmark, IMLE-VLA achieves the highest average success rate (98.0%) among all baselines while leading in inference frequency. Under the test-time perturbations of LIBERO-plus, IMLE-VLA retains $\pi_{0.5}$'s robustness while other baselines degrade sharply, confirming that the cIMLE head preserves generalization. Real-world experiments on a Franka Emika Panda across four tasks demonstrate smoother motion (2.2x to 3.0x lower jerk) and faster task completion, with IMLE-VLA outperforming $\pi_{0.5}$ on every task and reducing average VLA inference time per episode by 3.9x to 6.6x. Videos and code are available at https://kianhk6.github.io/IMLE-VLA/

## TL;DR

Vision-language-action (VLA) policies leverage pretrained vision-language backbones to achieve strong cross-task generalization. A leading design couples this backbone with a dedicated continuous action head trained via diffusion or flow matching.

## Related
<!-- [[other-paper-citekey]] -->
