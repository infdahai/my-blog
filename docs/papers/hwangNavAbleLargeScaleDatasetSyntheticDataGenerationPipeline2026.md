---
citekey: "hwangNavAbleLargeScaleDatasetSyntheticDataGenerationPipeline2026"
title: "NavAble: A Large-Scale Dataset and Synthetic Data Generation Pipeline for Blind Navigation"
authors: ["Hochul Hwang", "Jahir Sadik Monon", "Soowan Yang", "Shiven Umeshbhai Patel", "Anh Nhat Hong Nguyen", "Kien Nguyen", "Keshav Garg", "Dylan Gage", "Duretti Hordofaa", "Anshu Anjna", "Eshed Ohn-Bar", "Donghyun Kim"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.19330"
doi: "10.48550/arXiv.2610.19330"
tags: [paper, embodied-ai, "cs.CV", "cs.RO"]
status: unread
rating:
created: 2026-10-18
---

# NavAble: A Large-Scale Dataset and Synthetic Data Generation Pipeline for Blind Navigation

> Hochul Hwang, Jahir Sadik Monon, Soowan Yang, Shiven Umeshbhai Patel, Anh Nhat Hong Nguyen, Kien Nguyen, Keshav Garg, Dylan Gage, Duretti Hordofaa, Anshu Anjna, Eshed Ohn-Bar, Donghyun Kim · 2026
> [arXiv](https://arxiv.org/abs/2610.19330) · [PDF](https://arxiv.org/pdf/2610.19330)

## Abstract

Reliable recognition of accessibility-critical objects (e.g., audible pedestrian signals, door-activation buttons, and handrails) is essential for assistive navigation technologies that support safe, independent mobility for blind and low-vision (BLV) users. Yet these categories are underrepresented in existing large-scale vision datasets, and the few datasets that include them suffer from limited class coverage, inconsistent annotations, and poor diversity. We introduce NavAble, a large-scale dataset spanning 11 accessibility-critical object classes, combining 41K curated open-source images with 8K newly collected, densely annotated real-world images. To extend scale and diversity, we develop a synthetic data generation pipeline that renders high-fidelity 3D assets across 37 environments under diverse styles and viewpoints, yielding 452K frames with rich ground-truth annotations from 565 assets. The pipeline minimizes manual effort by combining automated web image crawling, VLM-based filtering, SAM 3D-based asset generation, and convenient camera trajectory configuration, enabling large-scale data generation at a diversity unattainable through manual collection. Experiments show that fine-tuning existing segmentation models on the NavAble Dataset achieves reliable accessibility-object segmentation (>80% mIoU on our held-out test set). We also demonstrate the effectiveness of synthetic data augmentation, which yields up to +3.5 mIoU over real-world-only fine-tuning. Beyond benchmark evaluation, validation on egocentric data from two mobility-assistive robots demonstrates improved perception reliability in real-world navigation scenarios. Together, NavAble establishes a scalable foundation for BLV navigation perception, directly addressing the data scarcity and embodiment gaps. The dataset and pipeline are publicly available at https://huggingface.co/datasets/NavAble/NeurIPS_2026_BLV.

## TL;DR

Reliable recognition of accessibility-critical objects (e.g., audible pedestrian signals, door-activation buttons, and handrails) is essential for assistive navigation technologies that support safe, independent mobility for blind and low-vision (BLV) users. Yet these categories are underrepresented in existing large-scale vision datasets, and the few datasets that include them suffer from limited class coverage, inconsistent annotations, and poor diversity.

## Related
<!-- [[other-paper-citekey]] -->
