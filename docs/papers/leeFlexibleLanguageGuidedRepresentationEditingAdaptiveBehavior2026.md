---
citekey: "leeFlexibleLanguageGuidedRepresentationEditingAdaptiveBehavior2026"
title: "Flexible Language-Guided Representation Editing for Adaptive Robot Behavior"
authors: ["Audrey Lee", "Nathaniel Dennler", "Ilia Sucholutsky", "Andreea Bobu"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.28893"
doi: "10.48550/arXiv.2610.28893"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-23
---

# Flexible Language-Guided Representation Editing for Adaptive Robot Behavior

> Audrey Lee, Nathaniel Dennler, Ilia Sucholutsky, Andreea Bobu · 2026
> [arXiv](https://arxiv.org/abs/2610.28893) · [PDF](https://arxiv.org/pdf/2610.28893)

## Abstract

Trajectory demonstrations show robots how to behave but not why, leaving them to guess which features of the task actually matter. Incorrect guesses produce misaligned internal representations and lead to incorrect robot behaviors. Because task features are often semantically defined, we argue that natural language is better suited for specifying features rather than relying on demonstrations. Although existing representation editing methods have proposed using language to specify new features, only allowing additive edits produces feature sets that are often over-specified or too narrowly scoped, especially in sequential editing tasks. We propose the Flexible Feature Editing Pipeline (FLEX), which uses language models to iteratively refine a robot's internal representation of task features from natural language corrections via three complementary operations: Add missing features, Generalize existing specific features, and Mask irrelevant features. We evaluate FLEX on 2D navigation scenarios, 7DoF Franka tabletop manipulation tasks, and a real-world study using naturalistic human language corrections and real-robot demonstrations. Comparisons against single-operation and unscaffolded baselines show that all three operations are necessary in interactive scenarios, and that FLEX achieves consistently higher normalized reward compared to other feature editing approaches while maintaining compact, transferable representations. Project available at https://mit-clear-lab.github.io/FLEX/

## TL;DR

Trajectory demonstrations show robots how to behave but not why, leaving them to guess which features of the task actually matter. Incorrect guesses produce misaligned internal representations and lead to incorrect robot behaviors.

## Related
<!-- [[other-paper-citekey]] -->
