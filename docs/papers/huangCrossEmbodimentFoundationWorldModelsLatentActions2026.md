---
citekey: "huangCrossEmbodimentFoundationWorldModelsLatentActions2026"
title: "Cross-Embodiment Robot Foundation World Models with Latent Actions"
authors: ["Huang Huang", "Sriram Yenamandra", "Arjun Majumdar", "Elie Aljalbout", "Tushar Nagarajan", "Tsung-Yen Yang", "Akshara Rai", "Michael Rabbat", "Li Fei-Fei", "Jiajun Wu", "Tingfan Wu", "Franziska Meier"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.10846"
doi: "10.48550/arXiv.2610.10846"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-09
---

# Cross-Embodiment Robot Foundation World Models with Latent Actions

> Huang Huang, Sriram Yenamandra, Arjun Majumdar, Elie Aljalbout, Tushar Nagarajan, Tsung-Yen Yang, Akshara Rai, Michael Rabbat, Li Fei-Fei, Jiajun Wu, Tingfan Wu, Franziska Meier · 2026
> [arXiv](https://arxiv.org/abs/2610.10846) · [PDF](https://arxiv.org/pdf/2610.10846)

## Abstract

The diversity of robot embodiments and action spaces makes it challenging to build robot world models that generalize across different embodiments. We introduce the Latent Action-Conditioned Robot World Model (LAC-WM), which operates within a learned unified latent action space shared across diverse embodiments. This unified action space improves the world model's performance when adapted to previously unseen robot embodiments. We compare LAC-WM with an Explicit Action-Conditioned World Model (EAC-WM), which conditions on explicit motion labels. Our results show that explicit action conditioning leads to disjoint action representations across embodiments, limiting downstream performance when adapting to new robots. We evaluate both models on dexterous manipulation tasks and a modified LIBERO benchmark. LAC-WM improves downstream performance over EAC-WM by up to 46.7% on dexterous manipulation and 11.7% on LIBERO. Crucially, the unified latent action space allows LAC-WM's downstream performance to scale positively with the number of embodiments used during pretraining. In contrast, the disjoint action space in EAC-WM leads to decreased performance as the number of pretraining embodiments increases. These results highlight the importance of a unified action space for efficient cross-embodiment learning, addressing a key challenge in robotics. Project website: https://lacwm.github.io/

## TL;DR

The diversity of robot embodiments and action spaces makes it challenging to build robot world models that generalize across different embodiments. We introduce the Latent Action-Conditioned Robot World Model (LAC-WM), which operates within a learned unified latent action space shared across diverse embodiments.

## Related
<!-- [[other-paper-citekey]] -->
