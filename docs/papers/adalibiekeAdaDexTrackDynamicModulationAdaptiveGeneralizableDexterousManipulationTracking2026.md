---
citekey: "adalibiekeAdaDexTrackDynamicModulationAdaptiveGeneralizableDexterousManipulationTracking2026"
title: "AdaDexTrack: Dynamic Modulation for Adaptive and Generalizable Dexterous Manipulation Tracking"
authors: ["Jianibieke Adalibieke", "Qianwei Han", "Xueyi Liu", "Yuzhe Qin", "Li Yi"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.33852"
doi: "10.48550/arXiv.2610.33852"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-27
---

# AdaDexTrack: Dynamic Modulation for Adaptive and Generalizable Dexterous Manipulation Tracking

> Jianibieke Adalibieke, Qianwei Han, Xueyi Liu, Yuzhe Qin, Li Yi · 2026
> [arXiv](https://arxiv.org/abs/2610.33852) · [PDF](https://arxiv.org/pdf/2610.33852)

## Abstract

Language is a natural way to command robots, but converting a single instruction into a long-horizon, contact-rich hand-object interaction remains challenging: synthesized references are noisy, human-to-robot retargeting introduces embodiment bias, and fixed-reference tracking lets small errors snowball. We address this with AdaDexTrack, a modulator-in-the-loop framework for language-conditioned manipulation tracking. A distilled generalist tracker serves as the skill carrier, while a tightly aligned modulator performs three feedback corrections: reference modulation (continual adjustment of what to track), object-latent modulation (online adaptation of the object representation to recruit suitable skills), and positional-target modulation (small state-dependent refinements for execution). The tracker is learned via large-scale specialist to generalist distillation on a corpus of language-conditioned hand-object trajectories; the modulator is trained with RL under the same task objective, ensuring tight coupling. Across large-scale evaluations, AdaDexTrack consistently outperforms prior SOTA on unseen-trajectory and unseen-object sets in both average tracking error and success rate, demonstrating robustness and generalization. We further show zero-shot sim-to-real transfer on real hardware, where adding the modulator yields substantial gains over a tracker-only variant. AdaDexTrack reframes language-conditioned dexterous manipulation as modulated tracking, replacing the open-loop, fixed-reference tracking with in-loop modulation that adjusts the reference, object latent, and positional target, yielding drift-resistant execution from noisy text references.

## TL;DR

Language is a natural way to command robots, but converting a single instruction into a long-horizon, contact-rich hand-object interaction remains challenging: synthesized references are noisy, human-to-robot retargeting introduces embodiment bias, and fixed-reference tracking lets small errors snowball. We address this with AdaDexTrack, a modulator-in-the-loop framework for language-conditioned manipulation tracking.

## Related
<!-- [[other-paper-citekey]] -->
