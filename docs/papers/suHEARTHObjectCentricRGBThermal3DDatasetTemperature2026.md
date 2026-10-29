---
citekey: "suHEARTHObjectCentricRGBThermal3DDatasetTemperature2026"
title: "HEARTH: An Object-Centric RGB-Thermal-3D Dataset for Temperature-Aware Robot Manipulation"
authors: ["Yuning Su", "Borui Li", "Yonghao Shi", "Bofei Liu", "Xing-Dong Yang"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.23418"
doi: "10.48550/arXiv.2609.23418"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-23
---

# HEARTH: An Object-Centric RGB-Thermal-3D Dataset for Temperature-Aware Robot Manipulation

> Yuning Su, Borui Li, Yonghao Shi, Bofei Liu, Xing-Dong Yang · 2026
> [arXiv](https://arxiv.org/abs/2609.23418) · [PDF](https://arxiv.org/pdf/2609.23418)

## Abstract

Language-guided manipulation can depend on physical properties that visible appearance does not reveal. Temperature is one such property, but object datasets for robot learning rarely associate measured temperatures with object appearance and geometry. We present HEARTH, an object-centric RGB-thermal-3D dataset of 90 physical objects from 18 everyday categories, comprising 145 captured object states. Our pipeline maps apparent surface temperatures onto reconstructed meshes through camera calibration and pose transfer. The dataset includes raw temperature measurements, camera parameters, RGB-textured meshes, and thermal textures for simulation. We use these assets to construct three LIBERO-derived tasks and collect 1,200 demonstrations for fine-tuning a pretrained vision-language-action (VLA) model, $π_{0.5}$. In an ablation study, adding thermal observations to the VLA increases success on temperature-dependent object-selection tasks from 35.0% for the RGB-only baseline to 75.0%. These results demonstrate the utility of HEARTH for training robot policies to follow temperature-related instructions.

## TL;DR

Language-guided manipulation can depend on physical properties that visible appearance does not reveal. Temperature is one such property, but object datasets for robot learning rarely associate measured temperatures with object appearance and geometry.

## Related
<!-- [[other-paper-citekey]] -->
