---
citekey: "mhlbauerLearningGeometryAwareVirtualFixturesSparseDemonstrations2026"
title: "Learning Geometry-Aware Virtual Fixtures From Sparse Demonstrations"
authors: ["Maximilian Mühlbauer", "Marcella Piacentino", "Raffaella Mancino", "Paolino De Risi", "Bernhard Weber", "Margarida Campos", "Thomas Hulin", "Sylvain Calinon", "Freek Stulp", "Alin Albu-Schäffer", "Julian Klodmann", "Fanny Ficuciello", "João Silvério"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.32958"
doi: "10.48550/arXiv.2609.32958"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-30
---

# Learning Geometry-Aware Virtual Fixtures From Sparse Demonstrations

> Maximilian Mühlbauer, Marcella Piacentino, Raffaella Mancino, Paolino De Risi, Bernhard Weber, Margarida Campos, Thomas Hulin, Sylvain Calinon, Freek Stulp, Alin Albu-Schäffer, Julian Klodmann, Fanny Ficuciello, João Silvério · 2026
> [arXiv](https://arxiv.org/abs/2609.32958) · [PDF](https://arxiv.org/pdf/2609.32958)

## Abstract

In many teleoperation applications, collecting a large number of demonstrations as required for traditional probabilistic learning from demonstration (LfD) approaches may not be feasible. To still give operators the ability to intuitively create trajectories as Virtual Fixtures (VFs), we propose to leverage a motion prior in the learning process. Particularly, by using Linear Quadratic Tracking (LQT), users are able to define guiding trajectories from the demonstration of just a few via points. To account for orientation guidance, we further reformulate classical LQT on Riemannian manifolds, introducing an additional geometric prior. Through a probabilistic interpretation of the LQT solution, we derive a covariance estimate at each trajectory point which we use to modulate the stiffness of the resulting fixture, resulting in strong guidance around the via points and softer guidance when far away. The covariance information is also used to define a validity region of the fixture, allowing the operator to leave its influence area and conduct unmodeled tasks. We evaluate the proposed Riemannian LQT formulation in a set of toy examples and the full framework on a cutting task requiring high precision in a minimally invasive surgery setting on the da Vinci Research Kit (dVRK).

## TL;DR

In many teleoperation applications, collecting a large number of demonstrations as required for traditional probabilistic learning from demonstration (LfD) approaches may not be feasible. To still give operators the ability to intuitively create trajectories as Virtual Fixtures (VFs), we propose to leverage a motion prior in the learning process.

## Related
<!-- [[other-paper-citekey]] -->
