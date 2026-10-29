---
citekey: "cohensalmonBenchmarkingEMlogCalibrationAutonomousSurfaceVehicles2026"
title: "Benchmarking EMlog Calibration for Autonomous Surface Vehicles"
authors: ["Samuel Cohen-Salmon", "Itzik Klein"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.39203"
doi: "10.48550/arXiv.2609.39203"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-04
---

# Benchmarking EMlog Calibration for Autonomous Surface Vehicles

> Samuel Cohen-Salmon, Itzik Klein · 2026
> [arXiv](https://arxiv.org/abs/2609.39203) · [PDF](https://arxiv.org/pdf/2609.39203)

## Abstract

Accurate velocity measurement is a fundamental requirement for autonomous surface and underwater vehicles. Commonly, velocity is provided by a Doppler velocity log (DVL) sensor, yet it becomes unavailable due to operational altitude constraints. In such situations, electromagnetic logs (EMLogs) provide a critically robust alternative for continuous velocity estimation. However, raw EMLog measurements are inherently corrupted by systematic errors, which need to be calibrated prior mission begins. Currently, a benchmarking comparative evaluation of how different calibration models perform under rapidly changing dynamic sea conditions is missing in the literature. To bridge this gap, this paper presents a comparative model-based calibration methodology that evaluates four distinct calibration models using two different estimation pipelines. The proposed framework is rigorously validated on a unique 221 minutes of continuous real-world telemetry collected from the MARVEL surface vehicle during dynamic sea trials. The dataset contains two different EMLogs and DVL recordings. Experimental results demonstrate that the bias and scale error model implemented with the Kalman filter improves the speed estimation by 71%. We also demonstrate that dynamical manoeuvres further improve the accuracy compared to standard straight-line paths, ultimately delivering a validated, real-time online calibration EMLog approach for autonomous surface vehicles.

## TL;DR

Accurate velocity measurement is a fundamental requirement for autonomous surface and underwater vehicles. Commonly, velocity is provided by a Doppler velocity log (DVL) sensor, yet it becomes unavailable due to operational altitude constraints.

## Related
<!-- [[other-paper-citekey]] -->
