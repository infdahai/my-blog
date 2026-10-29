---
citekey: "vermaMeasuringAssetSceneReconstructionEffectsRealSimEvaluation2026"
title: "Measuring Asset and Scene Reconstruction Effects in Real-to-Sim Robot Evaluation"
authors: ["Sanya Verma", "Luca Cilio", "Velissarios Christodoulou"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.00731"
doi: "10.48550/arXiv.2610.00731"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-03
---

# Measuring Asset and Scene Reconstruction Effects in Real-to-Sim Robot Evaluation

> Sanya Verma, Luca Cilio, Velissarios Christodoulou · 2026
> [arXiv](https://arxiv.org/abs/2610.00731) · [PDF](https://arxiv.org/pdf/2610.00731)

## Abstract

Simulated evaluation is increasingly used alongside real-world evaluation of robot policies because it is cheaper and easier to repeat; however, its value depends on how closely its outcomes track the real robot's. We test whether our reconstruction pipeline, combining metrically scaled object geometry, authored physical parameters and scene reconstruction, reduces disagreement between simulated and real robot scores relative to a default open-source recipe. We constructed two simulated versions of one bimanual robot cell: an authored reconstruction, using object geometry at estimated metric scale, projected textures, authored physics and our own scene splat; and a baseline, referred to as the default reconstruction, using the open-source recipe of a generative single-image mesh, engine-default physics and a Gaussian-splat scene. Both reconstructions use the same object photographs and scene video. Two policies ran five tasks each, giving ten task-policy pairs, which we call cells; each cell was run twenty times in each reconstruction with all other settings held fixed. Both reconstructions were scored against the same real trials, graded by a third-party evaluator. Pearson correlation between the ten simulated and real cell means is r = 0.90 for the authored reconstruction and 0.51 for the default. Mean score error is 6.97 percentage points for the authored reconstruction and 17.54 for the default, a reduction of 10.56 percentage points. These results show that improving the quality of the environment reconstruction through higher visual fidelity, authored physics and metric scale makes the simulation more faithful to the real world and narrows the sim-to-real gap. We release the harness, the per-trial scores, every reported run's configuration, and the assets and scenes of both reconstructions.

## TL;DR

Simulated evaluation is increasingly used alongside real-world evaluation of robot policies because it is cheaper and easier to repeat; however, its value depends on how closely its outcomes track the real robot's. We test whether our reconstruction pipeline, combining metrically scaled object geometry, authored physical parameters and scene reconstruction, reduces disagreement between simulated and real robot scores relative to a default open-source recipe.

## Related
<!-- [[other-paper-citekey]] -->
