---
citekey: "kolheRadGeoLocRadarGeolocalizationParticleFiltering2026"
title: "RadGeoLoc: Radar Geolocalization via Particle Filtering"
authors: ["Shaunak Kolhe", "Peng Jiang", "Kasi Viswanath", "Srikanth Saripalli"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.27310"
doi: "10.48550/arXiv.2610.27310"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-22
---

# RadGeoLoc: Radar Geolocalization via Particle Filtering

> Shaunak Kolhe, Peng Jiang, Kasi Viswanath, Srikanth Saripalli · 2026
> [arXiv](https://arxiv.org/abs/2610.27310) · [PDF](https://arxiv.org/pdf/2610.27310)

## Abstract

In real-time autonomous field applications, GNSS is often unreliable and inaccurate. A possible solution is localizing against a prebuilt map like a satellite image, as it is georeferenced and already surveyed. In this work, we localize a spinning radar measurement against overhead RGB imagery with a learned observation model. We use a radar representation pretrained by masked reconstruction and align it to features from a satellite image. A particle filter propagated by radar odometry proposes candidate poses, and our observation model provides a likelihood over these poses. We evaluate our method over 31 distinct routes, over 8 datasets spanning both urban and offroad conditions using only ground radar and a coarse local prior. We also examine the robustness over changing weather using repeated traversals over the same route over 13 months, in both urban and offroad conditions.

## TL;DR

In real-time autonomous field applications, GNSS is often unreliable and inaccurate. A possible solution is localizing against a prebuilt map like a satellite image, as it is georeferenced and already surveyed.

## Related
<!-- [[other-paper-citekey]] -->
