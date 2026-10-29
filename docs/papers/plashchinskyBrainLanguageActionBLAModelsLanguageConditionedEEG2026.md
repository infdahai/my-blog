---
citekey: "plashchinskyBrainLanguageActionBLAModelsLanguageConditionedEEG2026"
title: "Brain-Language-Action (BLA) Models: Language-Conditioned EEG for Robotics Control"
authors: ["Alexandr Plashchinsky"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2608.28967"
doi: "10.48550/arXiv.2608.28967"
tags: [paper, embodied-ai, "cs.LG", "cs.RO"]
status: unread
rating:
created: 2026-09-02
---

# Brain-Language-Action (BLA) Models: Language-Conditioned EEG for Robotics Control

> Alexandr Plashchinsky · 2026
> [arXiv](https://arxiv.org/abs/2608.28967) · [PDF](https://arxiv.org/pdf/2608.28967)

## Abstract

Electroencephalography (EEG)-based robotic control is commonly formulated as a direct classification problem, in which electrical neural signals are mapped to a fixed set of discrete actions. However, the limited separability and high noise of EEG signals make it difficult to scale this approach to fine-grained robotic control spaces. We introduce Brain-Language-Action (BLA) models, a framework in which language conditions the interpretation of neural representations for robotic action generation. In a BLA, a small set of reliably distinguishable brain states can be dynamically associated with different actions through a language-defined control mapping, allowing a small number of neural classes to apply to a larger global action space. We develop a proof-of-concept BLA for drone control using motor-imagery EEG from the BCI Competition IV 2a dataset. The system is trained in two stages. First, we evaluate multiple candidate EEG encoder architectures using subject-specific four-class motor-imagery classification, converting 250Hz, 3.5-second, 22-channel EEG samples into five 128-dimensional brain-token embeddings. Second, these embeddings are projected into the embedding space of a pretrained large language model (LLM) and jointly fine-tuned with language instructions to autoregressively generate structured three-token drone actions. Across 840 possible language-defined mappings between four neural states and seven flight action combinations, the resulting BLA achieves 90% per-token accuracy during evaluation. These results provide an initial demonstration that language conditioning can expand the effective control range of EEG-based robotic interfaces without requiring a corresponding increase in the number of directly distinguishable neural states.

## TL;DR

Electroencephalography (EEG)-based robotic control is commonly formulated as a direct classification problem, in which electrical neural signals are mapped to a fixed set of discrete actions. However, the limited separability and high noise of EEG signals make it difficult to scale this approach to fine-grained robotic control spaces.

## Related
<!-- [[other-paper-citekey]] -->
