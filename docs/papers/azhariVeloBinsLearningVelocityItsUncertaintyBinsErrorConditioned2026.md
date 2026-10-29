---
citekey: "azhariVeloBinsLearningVelocityItsUncertaintyBinsErrorConditioned2026"
title: "VeloBins: Learning Velocity and Its Uncertainty via Bins and Error-Conditioned Gaussian Labels for Aerial Inertial Odometry"
authors: ["Maulana Bisyir Azhari", "Seungwook Lee", "Donghun Han", "Sung Jun Park", "David Hyunchul Shim"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2608.29720"
doi: "10.48550/arXiv.2608.29720"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-02
---

# VeloBins: Learning Velocity and Its Uncertainty via Bins and Error-Conditioned Gaussian Labels for Aerial Inertial Odometry

> Maulana Bisyir Azhari, Seungwook Lee, Donghun Han, Sung Jun Park, David Hyunchul Shim · 2026
> [arXiv](https://arxiv.org/abs/2608.29720) · [PDF](https://arxiv.org/pdf/2608.29720)

## Abstract

Inertial odometry (IO) is critical for aerial robots, where aggressive maneuvers and poor lighting degrade visual sensors. Recent learning-based IO methods improve traditional integration-based approaches by learning motion priors from IMU and platform-specific sensors, then fusing the predictions within an extended Kalman filter. However, learning velocity through regression is difficult, while jointly estimating uncertainty with a separate decoder and negative log-likelihood (NLL) loss further complicates training and can lead to over-confident estimates. We introduce VeloBins, which reformulates velocity regression as classification over discretized velocity bins. We decode both the velocity from the bin distribution's expectation and the uncertainty from its variance, removing the need for a separate uncertainty decoder. We further supervise the uncertainty explicitly using an error-conditioned Gaussian label centered at the ground-truth velocity, with a standard deviation set to the velocity error. We evaluate VeloBins on four aerial datasets, ranging from free-form aggressive flights and a 27 g nano-quadrotor to drone racing at over 21~m/s. VeloBins achieves the lowest average errors on all four datasets, reducing velocity, relative trajectory, and absolute trajectory errors by 3-27%, 8-40%, and 6-53%, respectively, compared with the strongest baseline. Notably, the proposed supervision achieves the lowest NLL and best filter consistency despite never optimizing an NLL loss. The code will be available upon acceptance.

## TL;DR

Inertial odometry (IO) is critical for aerial robots, where aggressive maneuvers and poor lighting degrade visual sensors. Recent learning-based IO methods improve traditional integration-based approaches by learning motion priors from IMU and platform-specific sensors, then fusing the predictions within an extended Kalman filter.

## Related
<!-- [[other-paper-citekey]] -->
