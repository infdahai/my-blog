---
citekey: "milijasParameterSensitivityAnalysisAerialLiDARInertialOdometriesLow2026"
title: "Parameter Sensitivity Analysis for Aerial LiDAR-Inertial Odometries in low-altitude flights"
authors: ["Robert Milijas", "Jose Ramiro Martinez-de Dios", "Stjepan Bogdan"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.12837"
doi: "10.48550/arXiv.2609.12837"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-15
---

# Parameter Sensitivity Analysis for Aerial LiDAR-Inertial Odometries in low-altitude flights

> Robert Milijas, Jose Ramiro Martinez-de Dios, Stjepan Bogdan · 2026
> [arXiv](https://arxiv.org/abs/2609.12837) · [PDF](https://arxiv.org/pdf/2609.12837)

## Abstract

LiDAR-based SLAM (Simultaneous Localization and Mapping) and LIO (LiDAR-inertial odometry) algorithms are often used for precise navigation of unmanned aerial vehicles, especially during interactions with the aerial robot's environment. However, the performance of these algorithms is greatly dependent on the scenario, LiDAR, and robot motion characteristics, often requiring an intensive tuning process to achieve the desired performance. To aid these tuning efforts, this paper analyzes the influence on performance of the parameters of an EKF-based LIO algorithm (FAST-LIO2) and the LIO module of a graph-based SLAM algorithm (Cartographer) on aerial LiDAR SLAM datasets recorded using different LiDARs in low-to-moderate-altitude flights in diverse environments. The analysis is conducted on the absolute trajectory error (ATE) resulting from processing the datasets with the LIO algorithms configured with each combination of parameters obtained in an exhaustive grid search. The relationship between individual parameters and the ATE results is assessed using Pearson's correlation, while the influence of each parameter is assessed using random forest permutation importance analyses with random forest models trained to predict the resulting ATE values based on the choice of parameters. The performed analysis obtains for Cartographer and FAST-LIO2: i) the identification of parameters with stronger influence in performance, ii) a simplified tuning procedure, and iii) tuning recommendations. Using the proposed tuning recommendations, both algorithms obtain on the analyzed datasets ATE values within 5 cm to the optimal performance found in the grid search procedure in 94% of the analyzed cases.

## TL;DR

LiDAR-based SLAM (Simultaneous Localization and Mapping) and LIO (LiDAR-inertial odometry) algorithms are often used for precise navigation of unmanned aerial vehicles, especially during interactions with the aerial robot's environment. However, the performance of these algorithms is greatly dependent on the scenario, LiDAR, and robot motion characteristics, often requiring an intensive tuning process to achieve the desired performance.

## Related
<!-- [[other-paper-citekey]] -->
