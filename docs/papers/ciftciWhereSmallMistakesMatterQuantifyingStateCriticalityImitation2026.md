---
citekey: "ciftciWhereSmallMistakesMatterQuantifyingStateCriticalityImitation2026"
title: "Where Small Mistakes Matter: Quantifying State Criticality for Imitation Learning"
authors: ["Yusuf Umut Ciftci", "Joonwon Kang", "Ajay Suresha Sathya", "Somil Bansal"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.17709"
doi: "10.48550/arXiv.2610.17709"
tags: [paper, embodied-ai, "cs.AI", "cs.LG", "cs.RO"]
status: unread
rating:
created: 2026-10-18
---

# Where Small Mistakes Matter: Quantifying State Criticality for Imitation Learning

> Yusuf Umut Ciftci, Joonwon Kang, Ajay Suresha Sathya, Somil Bansal · 2026
> [arXiv](https://arxiv.org/abs/2610.17709) · [PDF](https://arxiv.org/pdf/2610.17709)

## Abstract

Imitation learning typically treats every demonstration state as equally important, optimizing a behavior-cloning objective uniformly across the dataset. Yet not all states are created equal: in a small number of critical states, even a slight deviation from the expert action can lead to a failure, while in many other states such errors are recoverable and inconsequential. We formalize state criticality in imitation learning as the worst-case degradation in downstream value induced by a bounded perturbation of the expert action at a given state. We then propose SCRIM, a practical State CRIticality Measure that estimates this quantity by training an adversarial disturbance policy and a value critic around a fixed imitation policy. SCRIM assigns each demonstration state a score reflecting how vulnerable the task outcome is to small, policy-relevant action errors. We show that these scores can be used to reweight behavior-cloning losses, improving imitation at consequential states and increasing overall task performance. We further show that SCRIM enables data curation by selecting compact, high-value subsets of demonstrations that preserve performance while substantially reducing the amount of training data. We evaluate SCRIM across various simulated and real-world robotic manipulation tasks, and demonstrate that SCRIM improves policy training, enables efficient data selection, and provides interpretable insights into which moments in a demonstration are most critical for task success. Project website: https://sia-lab-git.github.io/SCRIM/

## TL;DR

Imitation learning typically treats every demonstration state as equally important, optimizing a behavior-cloning objective uniformly across the dataset. Yet not all states are created equal: in a small number of critical states, even a slight deviation from the expert action can lead to a failure, while in many other states such errors are recoverable and inconsequential.

## Related
<!-- [[other-paper-citekey]] -->
