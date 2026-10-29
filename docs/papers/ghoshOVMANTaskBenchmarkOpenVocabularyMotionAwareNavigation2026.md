---
citekey: "ghoshOVMANTaskBenchmarkOpenVocabularyMotionAwareNavigation2026"
title: "OVMAN: A Task and Benchmark for Open-Vocabulary Motion-Aware Navigation"
authors: ["Dibyendu Ghosh"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.06424"
doi: "10.48550/arXiv.2609.06424"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-11
---

# OVMAN: A Task and Benchmark for Open-Vocabulary Motion-Aware Navigation

> Dibyendu Ghosh · 2026
> [arXiv](https://arxiv.org/abs/2609.06424) · [PDF](https://arxiv.org/pdf/2609.06424)

## Abstract

Homes change between a robot's visits. Navigation benchmarks pose their goals in the world the agent currently sees, and the two-visit benchmarks that exist score recall or rearrangement rather than navigation. None of them can express go to the chair that was moved or go to where the vase used to be. OVMAN is a task in which an agent tours a scene, returns after a scripted change, and must navigate to a goal specified by the change itself. Two of its six change relations answer with a place an object has left, where nothing remains to be detected. We release 219 two-visit episodes, each certified solvable by an oracle agent that completes it three times. Two released systems fail as predicted. A zero-shot object-goal navigator reaches the change-defined target in 11.4% of episodes and essentially fails at vacated locations, 0.000 on former and 0.025 on removed. A self-maintaining open-vocabulary map answers past-tense queries at about a third of the rate of the same maps read as two visits, even when grounding is supplied. A simple two-visit reference agent reaches 45.2% when navigating, against an embodied oracle of 99.5%. An error decomposition places the remaining difficulty in open-vocabulary instance grounding rather than in geometry or in selecting the answer once positions are known.

## TL;DR

Homes change between a robot's visits. Navigation benchmarks pose their goals in the world the agent currently sees, and the two-visit benchmarks that exist score recall or rearrangement rather than navigation.

## Related
<!-- [[other-paper-citekey]] -->
