---
citekey: "loukovitisThreeWayOpenSetDetectionRobustAutonomousNavigation2026"
title: "Three-Way Open-Set Detection for Robust Autonomous Navigation"
authors: ["Spyridon Loukovitis", "Vasileios Karampinis", "Athanasios Voulodimos"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2511.15343"
doi: "10.48550/arXiv.2511.15343"
tags: [paper, embodied-ai, "cs.CV", "cs.LG", "cs.RO"]
status: unread
rating:
created: 2026-08-28
---

# Three-Way Open-Set Detection for Robust Autonomous Navigation

> Spyridon Loukovitis, Vasileios Karampinis, Athanasios Voulodimos · 2026
> [arXiv](https://arxiv.org/abs/2511.15343) · [PDF](https://arxiv.org/pdf/2511.15343)

## Abstract

Autonomous navigation in complex scenes requires reliable perception across scenarios that the model did not encounter during its training. Along its route, an autonomous framework encounters objects it was trained to recognize, obstacles it has never seen, and background structures that resemble objects. Each of the three must be handled differently. To tackle this, existing open-set and out-of-distribution detectors discard low-confidence detections with an objectness threshold and only then test the rest for novelty. By forcing a single threshold like this they introduce a trade-off where a low threshold adds background clutter to the detected objects, while a high one may discard needed novel objects. We instead formulate open-set detection as a three-way classification of each detection into known object, unknown object, or background, computed post hoc from the outputs of a pretrained detector. We develop methods for domain generalization and for domain adaptation, evaluated across different detector families and benchmarks up to a combined semantic and covariate domain shift. To test the framework in a navigation context, we conduct simulations parameterized by the measured detection performance. The results show that the three-way decision yields safer and more efficient missions than binary alternatives.

## TL;DR

Autonomous navigation in complex scenes requires reliable perception across scenarios that the model did not encounter during its training. Along its route, an autonomous framework encounters objects it was trained to recognize, obstacles it has never seen, and background structures that resemble objects.

## Related
<!-- [[other-paper-citekey]] -->
