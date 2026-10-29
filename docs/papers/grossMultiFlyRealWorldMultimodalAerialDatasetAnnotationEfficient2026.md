---
citekey: "grossMultiFlyRealWorldMultimodalAerialDatasetAnnotationEfficient2026"
title: "MultiFly: A Real-World Multimodal Aerial Dataset with Annotation-Efficient Label Transfer and Cross-Modal Semantic Consistency"
authors: ["Markus Gross", "Andreas Greiner", "Taehyoung Kim", "Sivasubiramaniam Subbiah", "Tomaž Cotič", "Sai Bharadwaj Matha", "Conrad Christoph", "Oussema Dhaouadi", "Simon Zieher", "Surya Vijaya Kumar", "Gordon Elger", "Henri Meeß", "Olaf Wysocki", "Paul Spannaus", "Daniel Cremers"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.10359"
doi: "10.48550/arXiv.2610.10359"
tags: [paper, embodied-ai, "cs.CV", "cs.RO"]
status: unread
rating:
created: 2026-10-10
---

# MultiFly: A Real-World Multimodal Aerial Dataset with Annotation-Efficient Label Transfer and Cross-Modal Semantic Consistency

> Markus Gross, Andreas Greiner, Taehyoung Kim, Sivasubiramaniam Subbiah, Tomaž Cotič, Sai Bharadwaj Matha, Conrad Christoph, Oussema Dhaouadi, Simon Zieher, Surya Vijaya Kumar, Gordon Elger, Henri Meeß, Olaf Wysocki, Paul Spannaus, Daniel Cremers · 2026
> [arXiv](https://arxiv.org/abs/2610.10359) · [PDF](https://arxiv.org/pdf/2610.10359)

## Abstract

We introduce MultiFly, a real-world, low-altitude UAV dataset for semantic perception across RGB, thermal, LiDAR, and radar modalities. MultiFly provides 17,272 synchronized samples from four suburban scenes with frame-wise annotations for 15 semantic classes, together with calibration and GNSS-RTK/IMU measurements. To avoid costly and inconsistent modality-specific annotation, we propagate labels from only 115 manually annotated RGB images through shared geometric representations to all four modalities. This approach generates semantic labels for 17,157 additional RGB images, 17,272 thermal images, 840M LiDAR points, and 3.4M radar points. Transferred annotations achieve 89.93% average agreement with held-out manual annotations, and 90.94% average semantic consistency across all six modality pairs. We further establish semantic segmentation benchmarks for all four modalities, revealing distinct architectural behavior for dense LiDAR and sparse radar data. Taken together, MultiFly provides a scalable foundation for multimodal aerial perception and, to the best of our knowledge, the first public real-world low-altitude aerial benchmark that combines consistent frame-wise semantic annotations for RGB, thermal, LiDAR, and radar. Data at https://github.com/markus-42/multifly.

## TL;DR

We introduce MultiFly, a real-world, low-altitude UAV dataset for semantic perception across RGB, thermal, LiDAR, and radar modalities. MultiFly provides 17,272 synchronized samples from four suburban scenes with frame-wise annotations for 15 semantic classes, together with calibration and GNSS-RTK/IMU measurements.

## Related
<!-- [[other-paper-citekey]] -->
