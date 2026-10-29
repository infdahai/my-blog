---
citekey: "dongMIMICDMultiModalImitationMultIAgentCoordination2026"
title: "MIMIC-D: Multi-modal Imitation for MultI-agent Coordination with Decentralized Diffusion Policies"
authors: ["Dayi Dong", "Maulik Bhatt", "Seoyeon Choi", "Negar Mehr"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2509.14159"
doi: "10.48550/arXiv.2509.14159"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-12
---

# MIMIC-D: Multi-modal Imitation for MultI-agent Coordination with Decentralized Diffusion Policies

> Dayi Dong, Maulik Bhatt, Seoyeon Choi, Negar Mehr · 2026
> [arXiv](https://arxiv.org/abs/2509.14159) · [PDF](https://arxiv.org/pdf/2509.14159)

## Abstract

As robots become more integrated in society, their ability to coordinate with other robots and humans on multi-modal tasks (those with multiple valid solutions) is crucial. Such behaviors can be learned from expert demonstrations via imitation learning (IL), but when expert demonstrations are multi-modal, standard IL approaches usually average across modes or collapse to a single mode, preventing effective coordination. Being inspired by diffusion models' ability to capture complex multi-modal trajectory distributions in single-agent settings, we develop a diffusion-based framework for coordinated multi-modal behavior in multi-agent systems. However, existing multi-agent diffusion approaches typically require a centralized planner or explicit communication among agents. This assumption can fail in real-world scenarios where robots must operate independently or with agents like humans that they cannot directly communicate with. Therefore, we propose MIMIC-D, a joint training with decentralized execution paradigm for multi-modal multi-agent IL via diffusion. We jointly train all agents' policies with only local information to achieve implicit coordination. In simulation and hardware experiments, our method exhibits robust multi-modal coordination behavior in various tasks and environments, improving upon state-of-the-art baselines.

## TL;DR

As robots become more integrated in society, their ability to coordinate with other robots and humans on multi-modal tasks (those with multiple valid solutions) is crucial. Such behaviors can be learned from expert demonstrations via imitation learning (IL), but when expert demonstrations are multi-modal, standard IL approaches usually average across modes or collapse to a single mode, preventing effective coordination.

## Related
<!-- [[other-paper-citekey]] -->
