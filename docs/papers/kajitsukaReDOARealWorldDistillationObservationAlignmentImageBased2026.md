---
citekey: "kajitsukaReDOARealWorldDistillationObservationAlignmentImageBased2026"
title: "ReDOA: Real-World Distillation via Observation Alignment for Image-Based Manipulation Policy Learning"
authors: ["Kotaro Kajitsuka", "Masaki Murooka", "Fumio Kanehiro"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.25691"
doi: "10.48550/arXiv.2610.25691"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-22
---

# ReDOA: Real-World Distillation via Observation Alignment for Image-Based Manipulation Policy Learning

> Kotaro Kajitsuka, Masaki Murooka, Fumio Kanehiro · 2026
> [arXiv](https://arxiv.org/abs/2610.25691) · [PDF](https://arxiv.org/pdf/2610.25691)

## Abstract

Data-driven learning for general-purpose robotic manipulation presents a fundamental trade-off between data-collection cost and adaptability to real-world environments. Imitation learning (IL) requires costly human demonstrations, whereas simulation-based learning is vulnerable to sim-to-real gaps in dynamics and sensor observations. We propose ReDOA (Real-World Distillation via Observation Alignment), a framework that decouples control learning from perception learning to learn image-based policies in the real world. A state-based teacher policy trained in simulation is executed on a real robot, and its control knowledge is distilled into an image-based student policy using the collected trajectories. Observation Alignment resolves observation mismatches between data collection and deployment. This framework collects successful, efficiently executed trajectories paired with real-world visual observations, without requiring demonstrations from human experts. In real-robot experiments on three non-prehensile manipulation tasks, including bimanual manipulation, our method achieves better overall performance when jointly considering task success and execution efficiency than both IL based on human demonstrations and policy distillation in simulation. https://isri-aist.github.io/redoa-project-page/

## TL;DR

Data-driven learning for general-purpose robotic manipulation presents a fundamental trade-off between data-collection cost and adaptability to real-world environments. Imitation learning (IL) requires costly human demonstrations, whereas simulation-based learning is vulnerable to sim-to-real gaps in dynamics and sensor observations.

## Related
<!-- [[other-paper-citekey]] -->
