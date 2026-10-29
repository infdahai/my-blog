---
citekey: "kandoriaKalmanFilteringBasedFlightManagementSystemModelingAAM2026"
title: "Kalman Filtering Based Flight Management System Modeling for AAM Aircraft"
authors: ["Balram Kandoria", "Aryaman Singh Samyal"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2602.14948"
doi: "10.48550/arXiv.2602.14948"
tags: [paper, embodied-ai, "cs.RO", "cs.SY", "eess.SY"]
status: unread
rating:
created: 2026-09-12
---

# Kalman Filtering Based Flight Management System Modeling for AAM Aircraft

> Balram Kandoria, Aryaman Singh Samyal · 2026
> [arXiv](https://arxiv.org/abs/2602.14948) · [PDF](https://arxiv.org/pdf/2602.14948)

## Abstract

Advanced Air Mobility (AAM) operations are planned to utilize strategic flight planning services that predict temporal uncertainties to validate flight plans against hazards such as weather cells, restricted airspaces, and CNS disruption areas. This paper presents a Kalman Filter-based uncertainty propagation method that models Flight Management System (FMS) correction behavior through a sigmoid-blended measurement noise covariance. The sigmoid formulation generalizes existing discrete FMS activation thresholds into a continuous, tunable function that smoothly transitions the filter's measurement noise based on progress toward each waypoint. When the measurement noise is high, due to an inverse relationship, the Kalman gain is small and thus uncertainty grows; as the aircraft nears a waypoint, measurement noise decreases as a function of progress, the Kalman gain increases, and state covariance contracts which models the FMS progressively correcting toward the planned trajectory. The approach is computationally efficient (up to two orders of magnitude faster than Monte Carlo methods), scales with control inputs, and is parametrically tunable for different classes of aircraft. The measurement noise covariance is calibrated using real Automatic Dependent Surveillance-Broadcast (ADS-B) data from commercial Instrument Flight Rules (IFR) flights serving as surrogates for future AAM operations, achieving coverage probability conservative relative to theoretical Gaussian predictions at the 1-sigma confidence level on a hold out verification dataset (N = 36). Parameter sensitivity analysis across multiple flight routes demonstrates robust behavior, and comparative evaluation against Monte Carlo and Linear Propagation methods contextualizes the method's computational and accuracy trade-offs.

## TL;DR

Advanced Air Mobility (AAM) operations are planned to utilize strategic flight planning services that predict temporal uncertainties to validate flight plans against hazards such as weather cells, restricted airspaces, and CNS disruption areas. This paper presents a Kalman Filter-based uncertainty propagation method that models Flight Management System (FMS) correction behavior through a sigmoid-blended measurement noise covariance.

## Related
<!-- [[other-paper-citekey]] -->
