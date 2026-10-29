---
citekey: "thienRoboWorMEvaluatingMovementRealismConsistencyAccelerationAffectsEmbodied2026"
title: "RoboWorM: Evaluating Movement Realism, Consistency and Acceleration Affects in Embodied Video World Models"
authors: ["Doanh Le Thien", "Viet-Thanh Nguyen", "Pham Tri Quang", "Nhi Pham", "Christopher Wewer", "Minh-Loi Nguyen", "Hoang H. Tran", "Tho Le", "Tung M. Luu", "Dung D. Le", "Vu N. Duong", "Jonas Fischer", "Ngan Le", "An Thai Le", "Daniel Sonntag", "Gim Hee Lee", "James Zou", "Mathias Niepert", "Jan Peters", "Duy M. H. Nguyen", "Ngo Anh Vien"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.33807"
doi: "10.48550/arXiv.2610.33807"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-27
---

# RoboWorM: Evaluating Movement Realism, Consistency and Acceleration Affects in Embodied Video World Models

> Doanh Le Thien, Viet-Thanh Nguyen, Pham Tri Quang, Nhi Pham, Christopher Wewer, Minh-Loi Nguyen, Hoang H. Tran, Tho Le, Tung M. Luu, Dung D. Le, Vu N. Duong, Jonas Fischer, Ngan Le, An Thai Le, Daniel Sonntag, Gim Hee Lee, James Zou, Mathias Niepert, Jan Peters, Duy M. H. Nguyen, Ngo Anh Vien · 2026
> [arXiv](https://arxiv.org/abs/2610.33807) · [PDF](https://arxiv.org/pdf/2610.33807)

## Abstract

Video world models (VWMs) are rapidly emerging as scalable neural simulators for robotic manipulation. However, most benchmarks only evaluate them as open-world video generators, using Vision-Language Models (VLMs) that lack strict 3D spatial and kinematic reasoning. To bridge this gap, we introduce RoboWorM, a comprehensive, deployment-aware benchmark that leverages known hardware priors such as robot kinematic trees and fixed camera configurations, to systematically examine structural and spatiotemporal fidelity. RoboWorM curates 1,605 episodes across single-arm, bimanual, and humanoid morphologies, spanning both Markovian and long-horizon non-Markovian tasks under single- and multi-view setups. To explicitly measure physical consistency, we propose two deterministic, VLM-free metrics: KIVA for intra-view kinematic stability, and RIGIS for multi-view geometric consistency. By exploiting intrinsic robotic invariants, KIVA improves hallucination detection alignment with human annotations by 25.8% relative to the strongest frontier VLMs, while RIGIS achieves a 130% higher Spearman correlation with human preferences. Furthermore, since real-world deployment requires low inference latency, we utilize RoboWorM to conduct the first large-scale audit of the quality-efficiency trade-off. Evaluating 9 state-of-the-art acceleration techniques across 3 leading world models (over 29,000 generated rollouts), we demonstrate how these acceleration methods can retain superficial visual quality while silently compromising deployment-critical physical constraints. Using our metrics, we achieve 2.3$\times$ maximum inference speed-up with minimal quality loss.

## TL;DR

Video world models (VWMs) are rapidly emerging as scalable neural simulators for robotic manipulation. However, most benchmarks only evaluate them as open-world video generators, using Vision-Language Models (VLMs) that lack strict 3D spatial and kinematic reasoning.

## Related
<!-- [[other-paper-citekey]] -->
