---
citekey: "ejazSUFLECAScalingUpFeatureLearningCADImageAlignment2026"
title: "SUFLECA: Scaling Up Feature Learning for CAD-to-image Alignment"
authors: ["Saad Ejaz", "Miguel Fernandez-Cortizas", "Javier Civera", "Holger Voos", "Jose Luis Sanchez-Lopez"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2607.15058"
doi: "10.48550/arXiv.2607.15058"
tags: [paper, embodied-ai, "cs.CV", "cs.RO"]
status: unread
rating:
created: 2026-09-01
---

# SUFLECA: Scaling Up Feature Learning for CAD-to-image Alignment

> Saad Ejaz, Miguel Fernandez-Cortizas, Javier Civera, Holger Voos, Jose Luis Sanchez-Lopez · 2026
> [arXiv](https://arxiv.org/abs/2607.15058) · [PDF](https://arxiv.org/pdf/2607.15058)

## Abstract

CAD-to-image alignment aims to estimate an object's 9D pose (rotation, translation, and anisotropic scale) from a single RGB image, with applications in robotics and augmented reality. Recent zero-shot methods use vision foundation models to match image regions to CAD models; yet their correspondences are typically appearance-driven or unreliable under occlusion or synthetic-to-real domain shift. To address these limitations, we introduce SUFLECA (Scaling Up Feature LEarning for CAD-to-image Alignment), a weakly supervised framework for zero-shot CAD alignment with two key contributions. First, SUFLECA scales up geometry-grounded feature learning from pretrained visual representations through Normalized Object Coordinates (NOCs) supervision on images spanning up to 12 real and synthetic datasets, learning compact geometry-aware features that generalize across domains. Second, we propose a geometrically consistent matching algorithm that establishes reliable CAD-to-image correspondences. Together, these contributions enable accurate, sub-second alignment per object instance without iterative pose refinement. On ScanNet25k, SUFLECA achieves 32.8%/42.6% category/instance accuracy, outperforming the strongest zero-shot baseline by 9.7/12.5 percentage points with a smaller computational footprint, and for the first time on this benchmark, even surpassing existing pose-supervised methods. Code is available at: https://github.com/snt-arg/SUFLECA

## TL;DR

CAD-to-image alignment aims to estimate an object's 9D pose (rotation, translation, and anisotropic scale) from a single RGB image, with applications in robotics and augmented reality. Recent zero-shot methods use vision foundation models to match image regions to CAD models; yet their correspondences are typically appearance-driven or unreliable under occlusion or synthetic-to-real domain shift.

## Related
<!-- [[other-paper-citekey]] -->
