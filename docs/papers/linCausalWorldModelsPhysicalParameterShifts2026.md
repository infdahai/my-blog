---
citekey: "linCausalWorldModelsPhysicalParameterShifts2026"
title: "Causal world models under physical parameter shifts"
authors: ["Chu Lin", "Yi Sun"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.29088"
doi: "10.48550/arXiv.2610.29088"
tags: [paper, embodied-ai, "cs.LG", "cs.RO"]
status: unread
rating:
created: 2026-10-23
---

# Causal world models under physical parameter shifts

> Chu Lin, Yi Sun · 2026
> [arXiv](https://arxiv.org/abs/2610.29088) · [PDF](https://arxiv.org/pdf/2610.29088)

## Abstract

World models predict how embodied systems evolve under actions, but their accuracy can degrade when physical conditions move outside the training distribution. We study two components of causal modeling: which inputs a predictor may use, and how its mechanism computes their effects. In a synthetic benchmark with shortcut features, a frozen dependency mask derived from paired interventions reduces mean out-of-distribution (OOD) RMSE from 1.769 for a fully connected predictor to 0.697, close to the generator-oracle mask (0.694). For robot link-mass extrapolation in CausalWorld, with disjoint training and test mass ranges, we develop finger-local world models in which link masses enter inertia and dynamics-bias terms through explicit affine coefficients, actions act through either a learned torque network or the known PD controller, and learned residuals capture contact-related effects. Compared with a separately trained control whose mass inputs are fixed at training means, the known-PD model turns out-of-range masses into a consistent predictive gain: median time-averaged joint R2 over 150-step rollouts rises from 0.609 to 0.727, with improvement in all ten task-seed runs (exact two-sided sign test, p = 0.002). In a shared 100-step forecast, the learned-torque model is competitive with the strongest recurrent robotic world model (RWM) configuration (median joint R2 of 0.755 - 0.768 versus 0.752), whereas supplying out-of-range masses sharply degrades the MLP and recurrent predictors. These results indicate that how a physical parameter enters the dynamics mechanism determines whether its out-of-range value helps or harms prediction.

## TL;DR

World models predict how embodied systems evolve under actions, but their accuracy can degrade when physical conditions move outside the training distribution. We study two components of causal modeling: which inputs a predictor may use, and how its mechanism computes their effects.

## Related
<!-- [[other-paper-citekey]] -->
