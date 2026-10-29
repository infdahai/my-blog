---
citekey: "tiensmithSpaBenchRealBenchmarkSpatialGroundingVisionLanguage2026"
title: "Spa-Bench: A Real-Robot Benchmark for Spatial Grounding in Vision-Language-Action Models"
authors: ["Justin Tien-Smith", "Matthew Pidden", "Rolandos Alexandros Potamias"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.12696"
doi: "10.48550/arXiv.2610.12696"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-13
---

# Spa-Bench: A Real-Robot Benchmark for Spatial Grounding in Vision-Language-Action Models

> Justin Tien-Smith, Matthew Pidden, Rolandos Alexandros Potamias · 2026
> [arXiv](https://arxiv.org/abs/2610.12696) · [PDF](https://arxiv.org/pdf/2610.12696)

## Abstract

Vision-language-action models (VLAs) offer a promising route toward general-purpose robotics by transferring semantic knowledge from large-scale vision-language pretraining into language-conditioned control. However, most VLA evaluations emphasize aggregate manipulation success under changes in objects, instructions, or environments, leaving unclear how reliably these policies ground spatial descriptions in the physical scenes where they act. We therefore ask a sharper question: how reliably can current VLAs translate spatial descriptions into appropriate real-robot behavior? To investigate this, we introduce Spa-Bench, a real-robot benchmark that evaluates spatial grounding across six tabletop tasks covering Object State, Relative Size, Referential Description, Relational Placement, Ordinal Position, and Counting. Our primary evaluation compares in-distribution (ID) and out-of-distribution (OOD) spatial configurations while retaining training support for the relevant objects, concepts, and actions, reducing object and motor unfamiliarity as alternative explanations for failure. Four diagnostic conditions further probe physical execution, sensitivity to wording, object-task associations, and recognition that no action is required. We release 4,092 episodes collected on the SO-101 robot arm: 1,200 human-teleoperated demonstrations and 2,892 real-robot evaluation rollouts from five state-of-the-art VLA policies. Across the three fully evaluated policies, success falls from 67.5-73.3% on ID spatial configurations to 40.7-52.0% on OOD spatial configurations, while matched direct instructions improve success by 28.3-40.0 percentage points. These results show that the evaluated VLAs can often execute the required manipulations but lack robust spatial grounding. Project materials, including videos, code, and benchmark data, are available at https://justintiensmith.github.io/Spa-Bench/.

## TL;DR

Vision-language-action models (VLAs) offer a promising route toward general-purpose robotics by transferring semantic knowledge from large-scale vision-language pretraining into language-conditioned control. However, most VLA evaluations emphasize aggregate manipulation success under changes in objects, instructions, or environments, leaving unclear how reliably these policies ground spatial descriptions in the physical scenes where they act.

## Related
<!-- [[other-paper-citekey]] -->
