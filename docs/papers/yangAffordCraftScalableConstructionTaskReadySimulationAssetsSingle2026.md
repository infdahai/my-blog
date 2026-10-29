---
citekey: "yangAffordCraftScalableConstructionTaskReadySimulationAssetsSingle2026"
title: "AffordCraft: Scalable Construction of Task-Ready Simulation Assets from Single Images"
authors: ["Haoyun Yang", "Xueyang Zhou", "Ziyi Xie", "Yongchao Chen"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.06643"
doi: "10.48550/arXiv.2610.06643"
tags: [paper, embodied-ai, "cs.AI", "cs.CV", "cs.RO"]
status: unread
rating:
created: 2026-10-07
---

# AffordCraft: Scalable Construction of Task-Ready Simulation Assets from Single Images

> Haoyun Yang, Xueyang Zhou, Ziyi Xie, Yongchao Chen · 2026
> [arXiv](https://arxiv.org/abs/2610.06643) · [PDF](https://arxiv.org/pdf/2610.06643)

## Abstract

Robot learning in simulation depends on the objects the simulator offers. Many tasks need objects with separate parts, joints that allow the required motion, and physical properties that remain valid under contact. Existing methods recover this structure anew for every image: generative models predict parts and joints that mostly fail to settle or move in simulation, and general-purpose agents need a long session of model calls for each photograph. AffordCraft builds such an asset from a single RGB image and a task instruction by retrieval instead of generation: it locates the object and the part to operate, selects a matching entry from a library of articulated assets, and fits it to the image while keeping its parts and joints intact. Without any box or mask marking the object, AffordCraft produces a physically valid asset for 1,703 of 2,000 photographs from 31 categories. Five generative methods pass on at most 45% of the same photographs and, at the median, need 10 to 78 times our GPU time per valid asset. On 50 cluttered images, 162 of 237 annotated objects pass the same physical test after automatic detection. Growing the library from 141 to 11,372 entries needs no change to the method and raises category coverage from 46% to 100% and the share of selections with the requested label from 18% to 51%. We also build manipulation tasks from the constructed assets, both with single objects and in composed scenes; policies trained on scripted demonstrations complete both kinds of tasks from initial states unseen in training.

## TL;DR

Robot learning in simulation depends on the objects the simulator offers. Many tasks need objects with separate parts, joints that allow the required motion, and physical properties that remain valid under contact.

## Related
<!-- [[other-paper-citekey]] -->
