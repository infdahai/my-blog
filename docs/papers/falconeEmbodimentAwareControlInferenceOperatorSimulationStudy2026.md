---
citekey: "falconeEmbodimentAwareControlInferenceOperatorSimulationStudy2026"
title: "Embodiment-aware control by inference over the operator: a simulation study"
authors: ["Sara Falcone"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.38437"
doi: "10.48550/arXiv.2609.38437"
tags: [paper, embodied-ai, "cs.HC", "cs.RO", "q-bio.NC"]
status: unread
rating:
created: 2026-10-04
---

# Embodiment-aware control by inference over the operator: a simulation study

> Sara Falcone · 2026
> [arXiv](https://arxiv.org/abs/2609.38437) · [PDF](https://arxiv.org/pdf/2609.38437)

## Abstract

Teleoperation systems are tuned for channel fidelity, while whether the operator experiences the device as part of the body, the Sense of Embodiment (SoE), is measured only afterwards, by questionnaire. Predictive-processing accounts suggest controlling devices to reduce the mismatch between the operator's predictions and the returned feedback, but those predictions are unobservable, and an objective that only penalizes mismatch is minimized by removing feedback. We formulate an embodiment-aware controller, the Universal Embodiment Engine (UEE), that infers the operator's embodiment and visuo-proprioceptive cue weighting from implicit gaze and pupil signals and task outcome, and chooses bounded device settings under explicit preferences, cast as a discrete Active Inference agent. In simulations with 300 heterogeneous synthetic operators, the UEE found the suitable setting within half a minute for most operators, before identifying their exact type, and came close to an oracle in the second half of the session (embodiment 1.68 against 0.73 for the best fixed setting, on a 0-2 scale). Adapting without reading the operator did no better than fixed control, and model-free bandits did worse, whereas an expected-utility controller with the same inference did exactly as well: the benefit comes from Bayesian inference over the operator with explicit preferences, not from the information-seeking term of Active Inference. A naive prediction-error minimizer withheld feedback, as its objective implies, and lost task success (0.74 vs 0.90). The benefit shrank but persisted for operators outside the controller's model family, grew with the variety of the population, and vanished when the controller trusted an uninformative signal or when cue weighting changed mid-session without being modeled. These failures show what studies with people must establish first: calibrated signals and a model of change.

## TL;DR

Teleoperation systems are tuned for channel fidelity, while whether the operator experiences the device as part of the body, the Sense of Embodiment (SoE), is measured only afterwards, by questionnaire. Predictive-processing accounts suggest controlling devices to reduce the mismatch between the operator's predictions and the returned feedback, but those predictions are unobservable, and an objective that only penalizes mismatch is minimized by removing feedback.

## Related
<!-- [[other-paper-citekey]] -->
