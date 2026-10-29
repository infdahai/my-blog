---
citekey: "hulchukLiLiLieTheoryBased3DLiDARScanAlignment2026"
title: "LiLi: Lie Theory Based 3D LiDAR Scan Alignment Degeneracy Detection"
authors: ["Vsevolod Hulchuk", "Jan Bayer", "Jan Faigl"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.17145"
doi: "10.48550/arXiv.2609.17145"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-17
---

# LiLi: Lie Theory Based 3D LiDAR Scan Alignment Degeneracy Detection

> Vsevolod Hulchuk, Jan Bayer, Jan Faigl · 2026
> [arXiv](https://arxiv.org/abs/2609.17145) · [PDF](https://arxiv.org/pdf/2609.17145)

## Abstract

In this paper, we study 3D LiDAR scan alignment in challenging scenarios with degeneracies, such as straight corridors or flat fields, where the alignment solution is not unique and compromises localization and mapping accuracy. Existing degeneracy detection methods that neglect the potential for reassociating data points are prone to being sensitive to noise and complex degeneracies. Therefore, we propose LiLi - a novel method that leverages Lie theory to identify the full set of degenerate transformations within the SE(3) Lie group of rigid transformations. The method employs perturbations of the optimized solution and compares the resulting optimized poses to ensure robust detection of degeneracies. By leveraging generators from the Lie algebra se(3), the method provides a systematic approach to describing the set of degenerate transformations. Quantitative evaluations on synthetic data show significant improvement over the state-of-the-art Hessian-based method, reducing alignment error by 50%, with more significant improvements for datasets featuring noise. In the real-world degenerate datasets, the proposed method integrated into LiDAR-based odometry yields superior localization performance compared to the reference solution based on the Hessian-based degeneracy detector on a 260 m long trajectory, and succeeds on a 430 m long round-trip tunnel trajectory where the reference fails.

## TL;DR

In this paper, we study 3D LiDAR scan alignment in challenging scenarios with degeneracies, such as straight corridors or flat fields, where the alignment solution is not unique and compromises localization and mapping accuracy. Existing degeneracy detection methods that neglect the potential for reassociating data points are prone to being sensitive to noise and complex degeneracies.

## Related
<!-- [[other-paper-citekey]] -->
