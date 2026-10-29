---
citekey: "liJoyInsideVLMAgentProductConditionedMultimodalPolicyLearning2026"
title: "JoyInside-VLM-Agent: Product-Conditioned Multimodal Policy Learning for Embodied Agents"
authors: ["Gangyi Li", "LuYao Wang", "Jingfu Sun", "Jingyi Yuan", "Hang Liu", "Hao Zong", "Yujia Hu", "Tingting Gao", "Jianyong Wang", "Xu Yang"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.12957"
doi: "10.48550/arXiv.2610.12957"
tags: [paper, embodied-ai, "cs.AI", "cs.LG", "cs.RO"]
status: unread
rating:
created: 2026-10-13
---

# JoyInside-VLM-Agent: Product-Conditioned Multimodal Policy Learning for Embodied Agents

> Gangyi Li, LuYao Wang, Jingfu Sun, Jingyi Yuan, Hang Liu, Hao Zong, Yujia Hu, Tingting Gao, Jianyong Wang, Xu Yang · 2026
> [arXiv](https://arxiv.org/abs/2610.12957) · [PDF](https://arxiv.org/pdf/2610.12957)

## Abstract

Embodied agents must translate multimodal observations and user requests into executable actions while adapting to product constraints, changing goals, and execution feedback. We present JoyInside-VLM-Agent, a ReAct-style multimodal agent developed through product-conditioned trajectory construction and staged policy learning for robotic platforms and smart hardware. A closed-loop sandbox generates multimodal interaction trajectories covering goal revisions and failure recovery, which are checked against execution outcomes and semantic criteria. Supervised fine-tuning and multi-teacher on-policy distillation precede reinforcement learning with DPER (Dual-Source Privileged On-Policy Self-Distillation with Token-Level Evidence Routing). DPER routes token-level evidence between a frozen privileged teacher and a privileged student sharing the rollout policy's parameters, modulating reward-derived token advantages while preserving their signs. Training rewards combine generative process evaluation, multi-judge rankings, and task-queue consistency. JoyInside-VLM-Agent achieves a BFCL v4 overall score of 77.44, exceeding the evaluated baselines; results on the other public benchmarks are mixed. On JoyInside-Devices and JoyInside-Robotics, the evaluated system, which includes domain-specific skill refinement, leads the baselines on all reported metrics. Two real-world quadruped case studies illustrate visually grounded search, replanning after execution failure, and explicit failure reporting.

## TL;DR

Embodied agents must translate multimodal observations and user requests into executable actions while adapting to product constraints, changing goals, and execution feedback. We present JoyInside-VLM-Agent, a ReAct-style multimodal agent developed through product-conditioned trajectory construction and staged policy learning for robotic platforms and smart hardware.

## Related
<!-- [[other-paper-citekey]] -->
