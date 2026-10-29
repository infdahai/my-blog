---
citekey: "yanagidaDeicticVLAUnifyingInstructionModesBasedLanguageDeicticGestures2026"
title: "DeicticVLA: Unifying Instruction Modes Based on Language and Deictic Gestures in a Single VLA"
authors: ["Kango Yanagida", "Tatsuya Aoki", "Yuichiro Yoshikawa", "Takato Horii"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2608.28108"
doi: "10.48550/arXiv.2608.28108"
tags: [paper, embodied-ai, "cs.CV", "cs.RO"]
status: unread
rating:
created: 2026-09-01
---

# DeicticVLA: Unifying Instruction Modes Based on Language and Deictic Gestures in a Single VLA

> Kango Yanagida, Tatsuya Aoki, Yuichiro Yoshikawa, Takato Horii · 2026
> [arXiv](https://arxiv.org/abs/2608.28108) · [PDF](https://arxiv.org/pdf/2608.28108)

## Abstract

Vision-Language-Action models (VLAs) allow users to specify manipulation tasks in natural language, but distinguishing a target or placement goal among objects of the same category or similar appearance requires detailed expressions that VLAs may not use reliably. We propose DeicticVLA, which canonicalizes Language Instruction (LI), Vision-Language Instruction (VLI), and Visual Instruction (VI) into a text prompt and deictic masks through text-prompt completion and deictic gesture grounding, enabling a single pretrained VLA to handle all three instruction modes. With a shared backbone, demonstrations, and matched training steps, we compare two RGB visual prompting methods, two separate-channel mask prompting methods, and three training strategies in simulation. Under two-stage training, the four prompting methods achieve high in-distribution success but differ in their ability to use deictic masks in unseen layouts. Across methods, training-strategy ablations show that two-stage training improves such use, while retaining second-stage LI data mitigates forgetting without reducing VLI and VI performance. In three real-world tasks, one policy supports all modes. VLI and VI outperform LI under unseen expressions, appearance changes, and novel objects. For unseen categories, both achieve 100% success, compared with 16.7% for jointly trained LI. These results demonstrate the unified three-mode interface and guide DeicticVLA design.

## TL;DR

Vision-Language-Action models (VLAs) allow users to specify manipulation tasks in natural language, but distinguishing a target or placement goal among objects of the same category or similar appearance requires detailed expressions that VLAs may not use reliably. We propose DeicticVLA, which canonicalizes Language Instruction (LI), Vision-Language Instruction (VLI), and Visual Instruction (VI) into a text prompt and deictic masks through text-prompt completion and deictic gesture grounding, enabling a single pretrained VLA to handle all three instruction modes.

## Related
<!-- [[other-paper-citekey]] -->
