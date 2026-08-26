---
citekey: "zhangGripperAwareVisionLanguageActionModels2026"
title: "Gripper-aware Vision Language Action Models"
authors: ["Hanyi Zhang", "Zihong Luo", "Tianyu Li", "Khang Nguyen", "Basu Hela", "Shreyas Kumar", "Ngoc Duy Tran", "Feng Dai", "Charith Munasinghe", "Jorge Peña Queralta", "Giovanni Toffetti", "Khoa Vo", "Ngan Le", "Ravi Prakash", "Quan Vuong", "Tung D. Ta", "Long Hu", "Anh Nguyen", "Baoru Huang"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2608.24603"
doi: "10.48550/arXiv.2608.24603"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-08-26
---

# Gripper-aware Vision Language Action Models

> Hanyi Zhang, Zihong Luo, Tianyu Li, Khang Nguyen, Basu Hela, Shreyas Kumar, Ngoc Duy Tran, Feng Dai, Charith Munasinghe, Jorge Peña Queralta, Giovanni Toffetti, Khoa Vo, Ngan Le, Ravi Prakash, Quan Vuong, Tung D. Ta, Long Hu, Anh Nguyen, Baoru Huang · 2026
> [arXiv](https://arxiv.org/abs/2608.24603) · [PDF](https://arxiv.org/pdf/2608.24603)

## Abstract

Vision language action models (VLAs) have advanced general purpose robotic grasping and manipulation by enabling robots to interpret visual observations and natural language instructions to generate executable action sequences. However, existing VLAs often implicitly assume gripper invariance, despite grasping strategies being inherently embodiment-dependent. Different gripper types, such as parallel-jaw and suction, usually require distinct interaction strategies to achieve the same grasping objective. Moreover, current datasets for VLAs predominantly rely on parallel-jaw grippers, limiting gripper-aware learning. To address this gap, we introduce MiGA, a multi-gripper-aware dataset spanning five distinct gripper types across multiple robots with 103,000 demonstrations, explicitly capturing strategy divergence under shared task objectives. We further propose GVLA, which combines a new multi-gripper tokenizer with adapter-based policy routing. Our new gripper encoding induces structured embedding information that balances parameter sharing and strategy differentiation, while layer-wise probing confirms meaningful gripper-conditioned representations for VLAs. Intensive experiments in both simulation and real-world robots show that our GVLA outperforms the current baselines across evaluated settings. Our method also improves zero-shot generalization or few-shot adaptation to new objects or unseen tasks, and enable more efficient gripper adaptation.

## TL;DR

Vision language action models (VLAs) have advanced general purpose robotic grasping and manipulation by enabling robots to interpret visual observations and natural language instructions to generate executable action sequences. However, existing VLAs often implicitly assume gripper invariance, despite grasping strategies being inherently embodiment-dependent.

## Related
<!-- [[other-paper-citekey]] -->
