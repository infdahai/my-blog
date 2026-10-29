---
citekey: "srinivasScalableLEOConjunctionScreeningAdaptiveSyntheticCovarianceThresholds2026"
title: "Scalable LEO Conjunction Screening using Adaptive Synthetic-Covariance Thresholds"
authors: ["Vedant Srinivas", "Grace Ra Kim", "Duncan Eddy", "Mykel J. Kochenderfer"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.11645"
doi: "10.48550/arXiv.2610.11645"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-10
---

# Scalable LEO Conjunction Screening using Adaptive Synthetic-Covariance Thresholds

> Vedant Srinivas, Grace Ra Kim, Duncan Eddy, Mykel J. Kochenderfer · 2026
> [arXiv](https://arxiv.org/abs/2610.11645) · [PDF](https://arxiv.org/pdf/2610.11645)

## Abstract

As orbital populations grow, conjunction screening must search more object pairs for potential collision risks. Existing pipelines use early-stage filters, such as an apsis filter, to eliminate pairs whose orbital altitude ranges cannot produce a close approach. However, these filters apply the same fixed threshold to every object, making the screening unnecessarily conservative for well-constrained objects while potentially insufficient for objects with greater orbit-prediction uncertainty. In this work, we present an uncertainty-aware conjunction screening method that replaces a single fixed apsis threshold with object-specific thresholds derived from propagated radial uncertainty. The resulting thresholds vary across both objects and prediction time, becoming narrower when propagated uncertainty is small and wider when uncertainty grows. We pair this adaptive screening rule with a binary-search altitude sweep that makes resulting heterogeneous intervals efficient to evaluate at catalog scale with log-linear search complexity. We evaluate the method on 33,791 objects from the Space-Track General Perturbations (GP) catalog using the preceding eight public ephemeris snapshots and a seven-day prediction horizon. The adaptive sieve retains 162.8 million candidate pairs, reducing the candidate set by 28.78% relative to a fixed 50 km apsis threshold and by 71.48% relative to brute-force all-pairs screening. It retains all close approaches identified in two independently propagated reference sets. At the largest tested catalog size, the binary-search sweep is 27 times faster than exhaustive interval evaluation while returning the same candidate set. These results demonstrate that uncertainty-aware screening can substantially reduce the candidate burden passed to downstream conjunction analysis, providing a scalable path toward managing increasingly large and heterogeneous orbital populations.

## TL;DR

As orbital populations grow, conjunction screening must search more object pairs for potential collision risks. Existing pipelines use early-stage filters, such as an apsis filter, to eliminate pairs whose orbital altitude ranges cannot produce a close approach.

## Related
<!-- [[other-paper-citekey]] -->
