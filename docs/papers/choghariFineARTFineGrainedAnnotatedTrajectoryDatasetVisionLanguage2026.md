---
citekey: "choghariFineARTFineGrainedAnnotatedTrajectoryDatasetVisionLanguage2026"
title: "FineART: Fine-grained Annotated Robotic Trajectory Dataset and Vision-Language-Action Model for Bimanual Manipulation"
authors: ["Jade Choghari", "Pepijn Kooijmans", "Mansi Agarwal", "Yusuf Umut Ciftci", "Aseem Doriwala", "Catherine Weaver", "Mouli Sivapurapu", "Kai Yang", "Jackson Lee", "Thomas Wolf", "Pragna Mannam"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.36416"
doi: "10.48550/arXiv.2609.36416"
tags: [paper, embodied-ai, "cs.AI", "cs.CV", "cs.LG", "cs.RO"]
status: unread
rating:
created: 2026-09-30
---

# FineART: Fine-grained Annotated Robotic Trajectory Dataset and Vision-Language-Action Model for Bimanual Manipulation

> Jade Choghari, Pepijn Kooijmans, Mansi Agarwal, Yusuf Umut Ciftci, Aseem Doriwala, Catherine Weaver, Mouli Sivapurapu, Kai Yang, Jackson Lee, Thomas Wolf, Pragna Mannam · 2026
> [arXiv](https://arxiv.org/abs/2609.36416) · [PDF](https://arxiv.org/pdf/2609.36416)

## Abstract

Robots operating in real-world environments must execute complex, multi-step bimanual tasks over long horizons rather than single, isolated actions. Current manipulation datasets struggle to support this capability: although single-arm datasets reach hundreds of thousands of trajectories, they typically provide only one high-level instruction per episode while the rare bimanual effort that does label subtasks annotates only a fraction of its hours. We present FineART, a densely annotated bimanual manipulation dataset of 40,543 episodes, 1,718 hours, and 533,913 subtasks across 151 tasks. We also introduce FineART-VLA, a vision-language-action policy that predicts its own next subtask, and show that mid-training it this way yields substantial gains. Specifically, success on a spatial disambiguation task increases from 32.0% to 100.0%, and step-by-step human subtask guidance lifts success on an unseen long-horizon task from 16.0% to 76.0%. Furthermore, after minimal fine-tuning on a new robot, the policy requires one-tenth the data of baselines without mid-training and generalizes zero-shot to completely unseen tasks on the new hardware. We open-source the full dataset, model weights, and training code.

## TL;DR

Robots operating in real-world environments must execute complex, multi-step bimanual tasks over long horizons rather than single, isolated actions. Current manipulation datasets struggle to support this capability: although single-arm datasets reach hundreds of thousands of trajectories, they typically provide only one high-level instruction per episode while the rare bimanual effort that does label subtasks annotates only a fraction of its hours.

## Related
<!-- [[other-paper-citekey]] -->
