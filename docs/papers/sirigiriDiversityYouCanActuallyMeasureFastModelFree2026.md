---
citekey: "sirigiriDiversityYouCanActuallyMeasureFastModelFree2026"
title: "Diversity You Can Actually Measure: A Fast, Model-Free Diversity Metric for Robotics Datasets"
authors: ["Sreevardhan Sirigiri", "Nathan Samuel de Lara", "Christopher Agia", "Florian Shkurti", "Fabio Ramos"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2603.11634"
doi: "10.48550/arXiv.2603.11634"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-08-27
---

# Diversity You Can Actually Measure: A Fast, Model-Free Diversity Metric for Robotics Datasets

> Sreevardhan Sirigiri, Nathan Samuel de Lara, Christopher Agia, Florian Shkurti, Fabio Ramos · 2026
> [arXiv](https://arxiv.org/abs/2603.11634) · [PDF](https://arxiv.org/pdf/2603.11634)

## Abstract

Robotics datasets for imitation learning typically consist of long-horizon trajectories of different lengths over states, actions, and high-dimensional observations (e.g., RGB video), making it non-trivial to quantify diversity in a way that respects the underlying trajectory structure and geometry. We extend Shannon and von Neumann entropy to this setting by defining signature transform-based entropy on the Gram matrix of a signature kernel over demonstrations, yielding entropy and diversity metrics that operate directly on the demonstration dataset. Building on these metrics, we study how dataset diversity affects generalization performance in robot imitation learning and propose a simple, model-free way to curate diverse demonstrations. We introduce FAKTUAL (FAst trajectory Kernel enTropy cUration for imitation Learning), a data curation algorithm that selects a subset of demonstrations maximizing entropy given a subset-size budget. FAKTUAL is fully model-free, requires no access to the imitation policy or rollouts, and adds negligible overhead relative to policy training. We evaluate our approach on image and state-based RoboMimic and MetaWorld benchmarks, as well as four real-world manipulation tasks. Across tasks and architectures, diversity-aware curation with FAKTUAL consistently improves downstream success rates over random selection, while being substantially more computationally efficient compared to recent robot data curation methods. Our results suggest that the entropy of demonstration datasets is a practical tool for understanding and improving dataset diversity in robot imitation learning.

## TL;DR

Robotics datasets for imitation learning typically consist of long-horizon trajectories of different lengths over states, actions, and high-dimensional observations (e.g., RGB video), making it non-trivial to quantify diversity in a way that respects the underlying trajectory structure and geometry. We extend Shannon and von Neumann entropy to this setting by defining signature transform-based entropy on the Gram matrix of a signature kernel over demonstrations, yielding entropy and diversity metrics that operate directly on the demonstration dataset.

## Related
<!-- [[other-paper-citekey]] -->
