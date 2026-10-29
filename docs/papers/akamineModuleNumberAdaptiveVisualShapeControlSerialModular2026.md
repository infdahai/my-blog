---
citekey: "akamineModuleNumberAdaptiveVisualShapeControlSerialModular2026"
title: "Module Number Adaptive Visual Shape Control for Serial Modular Soft Robots"
authors: ["Kyohei Akamine", "Takato Horii", "Yusuke Sakaue", "Hiroki Ishizuka"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2608.29547"
doi: "10.48550/arXiv.2608.29547"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-02
---

# Module Number Adaptive Visual Shape Control for Serial Modular Soft Robots

> Kyohei Akamine, Takato Horii, Yusuke Sakaue, Hiroki Ishizuka · 2026
> [arXiv](https://arxiv.org/abs/2608.29547) · [PDF](https://arxiv.org/pdf/2608.29547)

## Abstract

Image based shape control provides a simple means of controlling the whole body configuration of soft robots. However, existing data driven approaches are typically developed for fixed robot structures and require new control data when the number of modules changes. This paper presents a module number adaptive visual shape control method for serial modular soft pneumatic robots. A controller trained only on single module actuation shape data is reused for robots with one to five modules by decomposing whole body camera images into local module patches. A single common module segmenter localizes individual modules across all tested configurations, while the same local controller is applied to every extracted patch. Geometric data augmentation improves transferability to downstream modules, and a lightweight mask reconstruction network reconstructs a synthetically removed actuator mask channel. Experiments on physical robots demonstrate shape control across varying numbers of modules and under environmental changes and payload loading. The results show that single module control learning enables scalable whole body control without configuration specific control data collection.

## TL;DR

Image based shape control provides a simple means of controlling the whole body configuration of soft robots. However, existing data driven approaches are typically developed for fixed robot structures and require new control data when the number of modules changes.

## Related
<!-- [[other-paper-citekey]] -->
