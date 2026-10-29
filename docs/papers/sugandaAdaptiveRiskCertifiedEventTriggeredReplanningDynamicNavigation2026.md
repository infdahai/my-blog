---
citekey: "sugandaAdaptiveRiskCertifiedEventTriggeredReplanningDynamicNavigation2026"
title: "Adaptive Risk-Certified Event-Triggered Replanning for Dynamic Navigation"
authors: ["Richie R. Suganda", "Bin Hu"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.09302"
doi: "10.48550/arXiv.2610.09302"
tags: [paper, embodied-ai, "cs.RO", "cs.SY", "eess.SY"]
status: unread
rating:
created: 2026-10-09
---

# Adaptive Risk-Certified Event-Triggered Replanning for Dynamic Navigation

> Richie R. Suganda, Bin Hu · 2026
> [arXiv](https://arxiv.org/abs/2610.09302) · [PDF](https://arxiv.org/pdf/2610.09302)

## Abstract

Safe navigation in dynamic environments requires robots to plan under obstacle predictions whose errors are uncertain, non-stationary, and can induce rare but safety-critical failures. Existing control-barrier-function safety filters can reject immediately unsafe controls, but they provide little guidance on when the current finite-horizon planning mode itself is becoming unsafe as prediction uncertainty evolves. We propose Conformal Event-Triggered Risk-Certified Replanning (\emph{CERT-Replan}), a framework that uses calibrated barrier risk as an early-warning signal for replanning. CERT-Replan calibrates horizon-indexed obstacle-prediction residuals online and uses the resulting uncertainty radii to evaluate dynamic-obstacle safety margins. A one-step safety filter protects the next applied control, while a horizon-level risk monitor evaluates the upper-tail CVaR of predicted barrier-violation losses along the current MPC rollout. When this risk exceeds an allocated budget, CERT-Replan rejects the current planning mode and selects a lower-risk alternative, such as a different speed profile, corridor, or homotopy class, rather than repeatedly correcting the same nominal plan. In a non-stationary benchmark, CERT-Replan achieves an \(83.3\%\) collision reduction relative to the safety-filter-only baseline \textcolor{black}{and a \(77.8\%\) reduction relative to simple replanning triggers}, while reducing average safety-filter intervention by \(32.4\%\). \textcolor{black}{With Trajectron++, CERT-Replan achieves \(96\%\) collision-free operation. Hardware experiments and onboard runtime profiling demonstrate computational feasibility.}

## TL;DR

Safe navigation in dynamic environments requires robots to plan under obstacle predictions whose errors are uncertain, non-stationary, and can induce rare but safety-critical failures. Existing control-barrier-function safety filters can reject immediately unsafe controls, but they provide little guidance on when the current finite-horizon planning mode itself is becoming unsafe as prediction uncertainty evolves.

## Related
<!-- [[other-paper-citekey]] -->
