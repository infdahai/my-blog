---
citekey: "liRoboBridgeSelfEvolvingEmbodiedAgentFrameworkSimReal2026"
title: "RoboBridge: A Self-Evolving Embodied Agent Framework for Sim-to-Real Transfer"
authors: ["Chenxi Li", "Zhangrui Zhao", "Rui Li", "Yuan Gao", "Kehui Liu", "Jiarui Li", "Dong Wang", "Tong Si", "Minting Pan", "Wanli Ouyang", "Dongzhan Zhou"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.02717"
doi: "10.48550/arXiv.2610.02717"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-05
---

# RoboBridge: A Self-Evolving Embodied Agent Framework for Sim-to-Real Transfer

> Chenxi Li, Zhangrui Zhao, Rui Li, Yuan Gao, Kehui Liu, Jiarui Li, Dong Wang, Tong Si, Minting Pan, Wanli Ouyang, Dongzhan Zhou · 2026
> [arXiv](https://arxiv.org/abs/2610.02717) · [PDF](https://arxiv.org/pdf/2610.02717)

## Abstract

A key challenge in bringing embodied intelligence into the real world is transferring capabilities from simulation to reality and enabling agents to continually adapt after deployment. End-to-end vision-language-action policies provide strong manipulation capabilities, but their transfer to physical environments typically relies on calibrating simulated visual and dynamical conditions, collecting additional target-domain demonstrations, and optimizing the policy through further training. Tool-using embodied agents offer flexible task orchestration, yet existing systems primarily emphasize task execution and experience reuse within a given environment, with limited support for transferring procedural knowledge and continuously adapting it across simulation and reality. We propose RoboBridge, a framework that treats sim-to-real transfer as the continued adaptation of executable task skills. The agent represents task knowledge as procedures connecting task intent, observations, tool operations, and outcome verification. Interaction feedback is used to generate candidate skill revisions, which are evaluated before being persisted or rejected. A pretrained vision-language-action policy is exposed as a reusable action tool and enhanced with inference-time guidance, enabling fine-grained execution without retraining the underlying policy. RoboBridge grounds transferable skills in task semantics and interaction interfaces shared across simulation and reality. This representation preserves reusable task structure while allowing environment-dependent operations to be selectively revised through real-world execution feedback. We evaluate the framework on LIBERO-PRO and corresponding physical tasks, studying both skill evolution and post-transfer adaptation. Our framework provides a route from one-shot policy deployment to continual procedural learning across environments.

## TL;DR

A key challenge in bringing embodied intelligence into the real world is transferring capabilities from simulation to reality and enabling agents to continually adapt after deployment. End-to-end vision-language-action policies provide strong manipulation capabilities, but their transfer to physical environments typically relies on calibrating simulated visual and dynamical conditions, collecting additional target-domain demonstrations, and optimizing the policy through further training.

## Related
<!-- [[other-paper-citekey]] -->
