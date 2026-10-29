---
citekey: "wenMachEmbodiedU0UnifiedUnderstandingGenerationModelEmbodiedIntelligence2026"
title: "MachEmbodied-U0: Unified Understanding and Generation Model for Embodied Intelligence"
authors: ["Haoran Wen", "Wenfu Wang", "Kunsong Shi", "Jingke Wang", "Wancheng Feng", "Yiren Zhang", "Yueran Zhao", "Xuancheng Zhang", "Nanfei Ye", "Xingru Chen", "Zhaohong Sun", "Chengmin Yang", "Zikang Yu", "Penghao Bi", "Jia Shi", "Yu Liu", "Kun Zhan", "Yan Xie"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.25627"
doi: "10.48550/arXiv.2609.25627"
tags: [paper, embodied-ai, "cs.CV", "cs.RO"]
status: unread
rating:
created: 2026-09-23
---

# MachEmbodied-U0: Unified Understanding and Generation Model for Embodied Intelligence

> Haoran Wen, Wenfu Wang, Kunsong Shi, Jingke Wang, Wancheng Feng, Yiren Zhang, Yueran Zhao, Xuancheng Zhang, Nanfei Ye, Xingru Chen, Zhaohong Sun, Chengmin Yang, Zikang Yu, Penghao Bi, Jia Shi, Yu Liu, Kun Zhan, Yan Xie · 2026
> [arXiv](https://arxiv.org/abs/2609.25627) · [PDF](https://arxiv.org/pdf/2609.25627)

## Abstract

General-purpose robot control requires models to understand task intent, identify where to interact, capture how the scene evolves, and generate precise actions. Vision-language-action models provide strong semantic priors but typically do not explicitly model scene dynamics, while world-action models couple visual prediction with control without necessarily exposing the task-relevant semantic and spatial structure needed for fine-grained manipulation. We present MachEmbodied-U0 (ME-U0), a unified embodied foundation model connecting understanding and generation experts through a Mixture-of-Transformers architecture. Subtask prediction and affordance grounding guide joint visual-dynamics and action generation via flow matching. Visual dynamics encompass future RGB, depth, surface normals, and optical flow, providing complementary supervision for appearance, geometry, and motion. Multi-rate Rotary Position Encoding (MRPE) aligns visual dynamics with fine-grained control. We pretrain ME-U0 on approximately 4,200 hours of curated demonstrations from robotic datasets and egocentric datasets. Using only the supervision natively available in each downstream benchmark, ME-U0 achieves an average score of 17.66 on the RoboDojo simulation benchmark and average success rates of 99.0\% and 82.5\% on LIBERO and LIBERO-Plus, respectively. We additionally validate ME-U0 on real-world robotic manipulation tasks, demonstrating its effectiveness beyond simulation. Without corresponding downstream supervision, ME-U0 further demonstrates zero-shot subtask prediction, affordance grounding, and visual dynamics on simulated and real-world observations. Overall, ME-U0 combines competitive downstream control performance with transferable task-grounding and visual-dynamics capabilities across simulation and the real world.

## TL;DR

General-purpose robot control requires models to understand task intent, identify where to interact, capture how the scene evolves, and generate precise actions. Vision-language-action models provide strong semantic priors but typically do not explicitly model scene dynamics, while world-action models couple visual prediction with control without necessarily exposing the task-relevant semantic and spatial structure needed for fine-grained manipulation.

## Related
<!-- [[other-paper-citekey]] -->
