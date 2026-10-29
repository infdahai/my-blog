---
citekey: "maActiveGenerativeSimulationMetaLearningWhatSimulateSim2026"
title: "Active Generative Simulation: Meta-Learning What to Simulate for Sim-and-Real Policy Co-Training"
authors: ["Liqian Ma", "Vaibhav Saxena", "Utkarsh Aashu Mishra", "Shuo Cheng", "Yongxin Chen", "Danfei Xu"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.19479"
doi: "10.48550/arXiv.2610.19479"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-16
---

# Active Generative Simulation: Meta-Learning What to Simulate for Sim-and-Real Policy Co-Training

> Liqian Ma, Vaibhav Saxena, Utkarsh Aashu Mishra, Shuo Cheng, Yongxin Chen, Danfei Xu · 2026
> [arXiv](https://arxiv.org/abs/2610.19479) · [PDF](https://arxiv.org/pdf/2610.19479)

## Abstract

Sim-and-real co-training is an effective way to scale robot learning by augmenting limited real-world demonstrations with simulation data. However, existing approaches typically treat simulators as fixed data sources, relying on uniform generation, offline retrieval, or manual parameter alignment by domain experts. We formulate \textit{Active Generative Simulation}: optimizing a simulator's data-generation distribution to maximize downstream real-world performance. To solve this problem, we propose MetaGenSim, a meta-learning framework that trains an auxiliary rater network via meta-gradients to automatically discover high-utility data-generation distributions within a user-specified simulation parameter space, without manual parameter alignment. Across simulation and real-world manipulation tasks, MetaGenSim outperforms uniform generation and retrieval baselines, achieves a 150% relative improvement in real-world full-task success over uniform generation, and matches expert manual alignment. We further show that distributions curated with a lightweight proxy policy transfer to VLA fine-tuning, and that MetaGenSim can exploit partial alignment through atomic skill stitching and object-receptacle composition when exact sim-and-real task alignment is unavailable. Project website: https://meta-gensim.github.io

## TL;DR

Sim-and-real co-training is an effective way to scale robot learning by augmenting limited real-world demonstrations with simulation data. However, existing approaches typically treat simulators as fixed data sources, relying on uniform generation, offline retrieval, or manual parameter alignment by domain experts.

## Related
<!-- [[other-paper-citekey]] -->
