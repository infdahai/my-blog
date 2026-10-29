---
citekey: "sunVisualSimRealLearningInsertionGeometricVariationsApplication2026"
title: "Visual Sim-to-Real Learning for Robotic Insertion under Geometric Variations: Application to Rebar Installation"
authors: ["Tao Sun", "Beining Han", "Patrick Yin", "Rui Xu", "Harry He", "Abhishek Gupta", "Szymon Rusinkiewicz", "Yi Shao"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.20477"
doi: "10.48550/arXiv.2609.20477"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-19
---

# Visual Sim-to-Real Learning for Robotic Insertion under Geometric Variations: Application to Rebar Installation

> Tao Sun, Beining Han, Patrick Yin, Rui Xu, Harry He, Abhishek Gupta, Szymon Rusinkiewicz, Yi Shao · 2026
> [arXiv](https://arxiv.org/abs/2609.20477) · [PDF](https://arxiv.org/pdf/2609.20477)

## Abstract

Rebar insertion is among the most repetitive and physically demanding tasks on construction sites, and a contact-rich problem at 1.4 mm clearance. The parts, however, vary at two levels: a nominal design per structural member, and fabrication tolerance around each nominal design. Real-world data therefore has to be re-collected as designs and batches change. We present RebarSim, a visual sim-to-real system trained entirely in simulation. A privileged state-based teacher is trained with reinforcement learning over procedurally generated rebar geometries, then distilled into a multi-view student that maps raw RGB and proprioception directly to actions under extensive domain randomization. The student transfers to the real world zero-shot, seating rebars taken from a real factory production run in 91.3% of real-robot rollouts. Underlying that result, geometry diversity and pretraining both bring benefits. Training across a diverse set of nominal designs rather than one lifts the zero-shot success of both the teacher and the student on unseen designs, and the student policy outperforms a single-design specialist on that specialist's own design. A pretrained student then adapts to a new design with 4--6x fewer distillation samples than one trained from scratch. Visual sim-to-real transfer depends on appearance randomization and the DAgger mixture: removing either one sharply lowers success. Videos, code, and task assets are available at https://rebarsim.github.io.

## TL;DR

Rebar insertion is among the most repetitive and physically demanding tasks on construction sites, and a contact-rich problem at 1.4 mm clearance. The parts, however, vary at two levels: a nominal design per structural member, and fabrication tolerance around each nominal design.

## Related
<!-- [[other-paper-citekey]] -->
