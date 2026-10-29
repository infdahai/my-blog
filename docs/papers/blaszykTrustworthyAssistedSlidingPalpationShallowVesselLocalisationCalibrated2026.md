---
citekey: "blaszykTrustworthyAssistedSlidingPalpationShallowVesselLocalisationCalibrated2026"
title: "Toward Trustworthy Robot-Assisted Sliding Palpation for Shallow Vessel Localisation with a Calibrated Digital Twin"
authors: ["Piotr Blaszyk", "Wen Fan", "Kaizhong Deng", "Daniel Elson", "Dandan Zhang"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2608.29396"
doi: "10.48550/arXiv.2608.29396"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-02
---

# Toward Trustworthy Robot-Assisted Sliding Palpation for Shallow Vessel Localisation with a Calibrated Digital Twin

> Piotr Blaszyk, Wen Fan, Kaizhong Deng, Daniel Elson, Dandan Zhang · 2026
> [arXiv](https://arxiv.org/abs/2608.29396) · [PDF](https://arxiv.org/pdf/2608.29396)

## Abstract

Reliable localisation of shallow subsurface vessels is important for safe robot-assisted venous access and vessel-aware manipulation, but collecting diverse tactile data on physical hardware is costly, time-consuming, and can degrade soft vision-based tactile sensors. We present a robot-assisted sliding-palpation framework in which a calibrated digital twin generates labelled tactile sequences, reducing reliance on real-world data. The twin models sensor-vessel contact, is calibrated against real palpation trajectories using Bayesian-optimisation-based domain adaptation, and is randomised over sliding direction and contact conditions. A spatio-temporal graph neural network trained on simulated marker trajectories performs per-node vessel classification and produces a human-verifiable top-view localisation map through 2D-to-3D-to-2D geometric projection. We evaluate three datasets: Sim, Silicone, and Meat, the latter a raw-meat phantom with vessel models at nominal depths of 0 to 30 mm, using four train-to-test configurations: Sim to Sim, Sim to Silicone, Sim to Meat, and Meat to Silicone. The calibrated twin achieves a simulated-to-real marker-alignment mean absolute error of 0.50 mm at deepest contact across four canonical interactions. After reprojection onto a 1 mm top-view grid, predicted vessel pixels lie on average 1.05 to 5.49 mm from the nearest true vessel pixel across the four models, with 1.05 to 1.31 mm for all except Sim to Meat. The larger error for Sim to Meat reflects the greater domain shift and current limit of simulation transfer. These results demonstrate progress toward trustworthy tactile palpation through calibrated simulation, interpretable localisation, and transparent cross-domain evaluation. Code, model weights, and data are publicly available on GitHub and Zenodo.

## TL;DR

Reliable localisation of shallow subsurface vessels is important for safe robot-assisted venous access and vessel-aware manipulation, but collecting diverse tactile data on physical hardware is costly, time-consuming, and can degrade soft vision-based tactile sensors. We present a robot-assisted sliding-palpation framework in which a calibrated digital twin generates labelled tactile sequences, reducing reliance on real-world data.

## Related
<!-- [[other-paper-citekey]] -->
