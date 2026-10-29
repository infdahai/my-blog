---
citekey: "caoFACTMultimodalForceActionTrackFoundationModelHuman2026"
title: "FACT: A Multimodal Force-Action-Track Foundation Model for Human-to-Robot Dexterity"
authors: ["Zhi Cao", "Yining Hong", "Jiaolong Yang", "Yejin Choi", "Li Fei-Fei", "Jiajun Wu", "Huang Huang"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.19155"
doi: "10.48550/arXiv.2610.19155"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-16
---

# FACT: A Multimodal Force-Action-Track Foundation Model for Human-to-Robot Dexterity

> Zhi Cao, Yining Hong, Jiaolong Yang, Yejin Choi, Li Fei-Fei, Jiajun Wu, Huang Huang · 2026
> [arXiv](https://arxiv.org/abs/2610.19155) · [PDF](https://arxiv.org/pdf/2610.19155)

## Abstract

Human demonstrations offer a scalable alternative to costly robot data collection for dexterous manipulation, but most human datasets lack force measurements. Dexterous manipulation requires not only visual and proprioceptive understanding but also the ability to anticipate and regulate interaction forces. To scale force-aware human-robot co-training, we introduce EgoForce, a large-scale human tactile dataset capturing force-rich manipulation experience, and combine it with robot demonstrations for pretraining. We present FACT, a robot foundation model that cascades from prospective visual planning to force-aware refinement for dexterous manipulation. FACT comprises two jointly trained components. A Track-Guided Coarse Planner jointly predicts actions, future video, and visual tracks. Future video and visual tracks also provide a shared task representation that facilitates cross-embodiment knowledge transfer and coarse action generation. Building on this coarse plan, a Force-Action Joint Refiner jointly predicts future force and refines the coarse action, allowing anticipated force and action to shape each other during refinement. We evaluate the model on ten tasks requiring fine-grained coordination and force feedback, including tool use, musical instruments, and precision laboratory procedures. Using as few as 10 robot trajectories with 90 human trajectories for fine-tuning, FACT outperforms both baselines, with success-rate gains of up to 60 percentage points over T-Rex. Ablations show that force supervision in human pretraining data is crucial for downstream robot performance after fine-tuning, while visual track prediction and training with future-force prediction improve dexterous execution. Experiments varying the human-robot data ratio during fine-tuning further suggest that FACT learns from human demonstrations nearly as effectively as from robot demonstrations.

## TL;DR

Human demonstrations offer a scalable alternative to costly robot data collection for dexterous manipulation, but most human datasets lack force measurements. Dexterous manipulation requires not only visual and proprioceptive understanding but also the ability to anticipate and regulate interaction forces.

## Related
<!-- [[other-paper-citekey]] -->
