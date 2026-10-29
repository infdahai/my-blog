---
citekey: "odrowazsypniewskiLearningBehaviorPriorsNonSyntheticData2026"
title: "Learning Robot Behavior Priors from Non-Robotic Synthetic Data"
authors: ["Mateusz Odrowaz-Sypniewski", "Michael Amir", "Jasmine Bayrooti", "Ajay Shankar", "Amanda Prorok"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.31275"
doi: "10.48550/arXiv.2610.31275"
tags: [paper, embodied-ai, "cs.LG", "cs.RO"]
status: unread
rating:
created: 2026-10-24
---

# Learning Robot Behavior Priors from Non-Robotic Synthetic Data

> Mateusz Odrowaz-Sypniewski, Michael Amir, Jasmine Bayrooti, Ajay Shankar, Amanda Prorok · 2026
> [arXiv](https://arxiv.org/abs/2610.31275) · [PDF](https://arxiv.org/pdf/2610.31275)

## Abstract

Real robot data, rich across tasks and morphologies, is often treated as the bottleneck for training robot learning models, including embodied foundation models that aim for zero-shot physical transfer. In this paper, we investigate the degree to which such models can acquire necessary structure using data from systems without embodiment. To this end, we test if inexpensive, procedurally generated synthetic data can yield useful priors before a model observes any real-world behavior. We study this through robot action prediction, a natural pretraining objective and a direct test of whether structure learned from arbitrary synthetic tasks transfers to embodied settings. We introduce three data generation pipelines that model mathematical abstractions of robotic control, and use them as pretraining priors for a Transformer. We demonstrate that a model trained purely on this non-robotic data attains non-trivial zero-shot prediction performance on unseen physical robot tasks via an in-context learning mechanism, and that our specialized control priors notably improve upon generic causal priors. We also compare against a compute-matched baseline trained on real robot data, and find that it outperforms our model but only on the datasets it was trained on. These findings suggest that procedurally generated, mathematical abstractions can yield useful robotic priors, offering a potential complement to expensive embodied data collection.

## TL;DR

Real robot data, rich across tasks and morphologies, is often treated as the bottleneck for training robot learning models, including embodied foundation models that aim for zero-shot physical transfer. In this paper, we investigate the degree to which such models can acquire necessary structure using data from systems without embodiment.

## Related
<!-- [[other-paper-citekey]] -->
