---
citekey: "karimWorldModelsAreNotInvariantHowActionsAre2026"
title: "Robot World Models Are Not Invariant to How the Actions Are Written"
authors: ["Ahmed Karim", "Leon Chlon"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.23252"
doi: "10.48550/arXiv.2609.23252"
tags: [paper, embodied-ai, "cs.LG", "cs.RO"]
status: unread
rating:
created: 2026-09-22
---

# Robot World Models Are Not Invariant to How the Actions Are Written

> Ahmed Karim, Leon Chlon · 2026
> [arXiv](https://arxiv.org/abs/2609.23252) · [PDF](https://arxiv.org/pdf/2609.23252)

## Abstract

A robot policy is trained with one of two action parameterizations: absolute joint targets, or deltas relative to the current state. The choice is a live engineering decision in robot learning, and a world model conditioned on actions inherits it silently. We show the inheritance is catastrophic. A latent dynamics model trained on one parameterization and handed the identical commanded trajectory written in the other collapses: retrieval degrades by 2.6-13.4x across three robot datasets and two morphologies, goal-conditioned action selection falls from 53% to 15%, and on PushT the two beliefs about the same future are near-orthogonal (cos = 0.067, worst case -0.377), so the predictor does not degrade gracefully, it answers a different question. This is not a distribution-shift artifact in the usual sense: the two encodings are mutually reconstructible at R^2 = 0.996 given the joint input, so no information is lost, and we give the test that separates a valid re-parameterization from a lossy summary or a sensor swap. The test rejected three of the four axes we proposed. The defect lives in the action channel, which the invariance literature for visual models does not examine: work there concerns crops, jitter and camera pose, while the parameterization of the commands goes unaudited. The repair is averaging over the two encodings, and where it goes matters. Averaging the objective restores task performance by itself; averaging the outputs, safe for probabilities by concavity, is not available for direction-valued prediction, where the normalized mean can score below every member of the orbit. What objective-averaging leaves behind is the tail: worst-case agreement stays at 0.78, a disagreement penalty closes it to 0.995, and over a latent rollout it is the difference between a worst case that erodes and one that holds. On PushT, averaging alone does not repair the axis.

## TL;DR

A robot policy is trained with one of two action parameterizations: absolute joint targets, or deltas relative to the current state. The choice is a live engineering decision in robot learning, and a world model conditioned on actions inherits it silently.

## Related
<!-- [[other-paper-citekey]] -->
