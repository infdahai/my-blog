---
citekey: "luGeoWAMVisualGeometryWorldActionModelsAutonomousDriving2026"
title: "GeoWAM: Visual Geometry World Action Models for Autonomous Driving"
authors: ["Yiren Lu", "Xin Ye", "Jiaming Liu", "Philip Jacobson", "Jin Yao", "Yi-chung Chen", "Liam Merino", "Dhruva Dixith Kurra", "Min Cai", "Tom Lampo", "Yu Yin", "Danhua Guo", "Burhan Yaman"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2608.23486"
doi: "10.48550/arXiv.2608.23486"
tags: [paper, embodied-ai, "cs.CV", "cs.RO"]
status: unread
rating:
created: 2026-08-26
---

# GeoWAM: Visual Geometry World Action Models for Autonomous Driving

> Yiren Lu, Xin Ye, Jiaming Liu, Philip Jacobson, Jin Yao, Yi-chung Chen, Liam Merino, Dhruva Dixith Kurra, Min Cai, Tom Lampo, Yu Yin, Danhua Guo, Burhan Yaman · 2026
> [arXiv](https://arxiv.org/abs/2608.23486) · [PDF](https://arxiv.org/pdf/2608.23486)

## Abstract

World action models (WAMs) have recently gained increasing attention as a framework for jointly modeling scene evolution and ego actions in autonomous driving. Most existing WAMs learn scene dynamics in pixel space by combining a video-generation backbone for future-observation prediction with an action head for ego-trajectory prediction. Pixels, however, provide only an indirect representation of these dynamics: they entangle geometry and motion with appearance, texture, and illumination, forcing the model to infer three-dimensional transformations from two-dimensional observations. We argue that geometry, represented by point clouds, offers a more natural state space for driving because it explicitly captures spatial structure and the rigid and non-rigid transformations that govern scene evolution while directly aligning with the space in which driving actions are executed. Building on this insight, we introduce \textbf{GeoWAM}, a visual geometry world action model for autonomous driving. Rather than predicting future images, GeoWAM is pretrained to forecast future scene geometry, yielding representations that jointly encode spatial structure and temporal evolution. A geometry-conditioned action head then leverages these learned geometric dynamics to predict future ego trajectories. Extensive open-loop and closed-loop evaluations show that visual geometry world modeling yields substantially stronger driving policies than image-based alternatives, establishing future-geometry prediction as an effective pretraining objective for autonomous driving.

## TL;DR

World action models (WAMs) have recently gained increasing attention as a framework for jointly modeling scene evolution and ego actions in autonomous driving. Most existing WAMs learn scene dynamics in pixel space by combining a video-generation backbone for future-observation prediction with an action head for ego-trajectory prediction.

## Related
<!-- [[other-paper-citekey]] -->
