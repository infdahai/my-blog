---
citekey: "xuGAFTGeoAnchoredFineTuningHazardIdentificationRare2026"
title: "GAFT: Geo-Anchored Fine-Tuning for Hazard Identification from Rare Failures"
authors: ["Yanran Xu", "Chuanhang Qiu", "Yue Wang", "Wenbo Wu", "Zhaoxing Li"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2608.30858"
doi: "10.48550/arXiv.2608.30858"
tags: [paper, embodied-ai, "cs.CV", "cs.RO"]
status: unread
rating:
created: 2026-09-02
---

# GAFT: Geo-Anchored Fine-Tuning for Hazard Identification from Rare Failures

> Yanran Xu, Chuanhang Qiu, Yue Wang, Wenbo Wu, Zhaoxing Li · 2026
> [arXiv](https://arxiv.org/abs/2608.30858) · [PDF](https://arxiv.org/pdf/2608.30858)

## Abstract

Off-road navigation can fail when physical structures induce irrecoverable states such as high-centering or entrapment, requiring human interventions. Identifying these structures is crucial, yet challenging. Such failure events are rare and costly to collect, resulting in limited training data. Moreover, the collected data associate frames with outcomes, but do not indicate the visual cues responsible for the failure. Learning directly from these data can therefore exploit scenario-specific visual cues, leading to poor generalization. We propose \textbf{Geo-Anchored Fine-Tuning (GAFT)}, a parameter-efficient method that adapts a vision foundation model with a geometry-derived prior. It guides LoRA adaptation by aligning a spatial attention-rollout map with the geometry prior, while preserving pretrained representations. On an intervention-verified forest hazard benchmark, across ten independently trained adaptations, GAFT consistently outperforms frozen DINOv2 and supervised PEFT baselines, improving the repeated leave-one-scenario-out mean $F_2$ from 0.0607 to 0.3757 with statistical significance under paired analysis. Within these independently trained models, the best-performing GAFT model achieves a repeated-LOSO $F_2$ of 0.570. Code and benchmark: https://github.com/Xu-Yanran/geo_anchored_fine_tuning

## TL;DR

Off-road navigation can fail when physical structures induce irrecoverable states such as high-centering or entrapment, requiring human interventions. Identifying these structures is crucial, yet challenging.

## Related
<!-- [[other-paper-citekey]] -->
