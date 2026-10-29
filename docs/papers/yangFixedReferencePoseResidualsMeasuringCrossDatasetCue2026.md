---
citekey: "yangFixedReferencePoseResidualsMeasuringCrossDatasetCue2026"
title: "Fixed-Reference Pose Residuals for Measuring Cross-Dataset Cue Transfer in Human-Robot Interaction Anticipation"
authors: ["Bowen Yang", "Xinliang Xiao", "Wenjing Zhang", "Li Yang", "Wei Zhou"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.12245"
doi: "10.48550/arXiv.2610.12245"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-10
---

# Fixed-Reference Pose Residuals for Measuring Cross-Dataset Cue Transfer in Human-Robot Interaction Anticipation

> Bowen Yang, Xinliang Xiao, Wenjing Zhang, Li Yang, Wei Zhou · 2026
> [arXiv](https://arxiv.org/abs/2610.12245) · [PDF](https://arxiv.org/pdf/2610.12245)

## Abstract

Social and service robots in public spaces need to anticipate which nearby person is about to approach and touch them, so that a response can be prepared before contact. It is largely unknown which cues support this anticipation when a model trained with one robot is used on another robot at a different site. We study this question with a fixed-reference pose residual (FRPR) model: a geometry predictor built from the person's bounding box and mask is trained and frozen, and a temporal network then learns from body pose an additive correction to its logit, so that every prediction splits exactly into a geometry term and a pose term. Between two public egocentric datasets recorded by different robots, HUI360 and SSUP-A, with every choice made on source data, the pose correction raised average precision (AP) from 0.277 to 0.321 from SSUP-A to HUI360 and gave no measurable gain in the opposite direction; the same asymmetry held over a stronger, source-selected geometry reference. Freezing gave no AP advantage over joint training, and simple geometric baselines and tree ensembles remained competitive or better, so the construction serves measurement rather than prediction accuracy. A head-orientation residual added small gains in both directions. Post hoc, whether a person faces the camera kept its discriminative direction across datasets, whereas head pitch reversed. With thresholds chosen on source data, the neural models that use geometry detected at most 17% of target interactions. Code and processed data are available at https://github.com/WeiZhou96/FRPR-interaction-anticipation.

## TL;DR

Social and service robots in public spaces need to anticipate which nearby person is about to approach and touch them, so that a response can be prepared before contact. It is largely unknown which cues support this anticipation when a model trained with one robot is used on another robot at a different site.

## Related
<!-- [[other-paper-citekey]] -->
