---
citekey: "shcherbaEstimateDonTImitateReusingDifferentiableStateBased2026"
title: "Estimate, Don't Imitate: Reusing Differentiable State-Based Policies for Visuomotor Control"
authors: ["Denis Shcherba", "Adrian Abel", "Eckart Cobo-Briesewitz", "Paul Mattes", "Wojciech Samek", "Marc Toussaint"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.34018"
doi: "10.48550/arXiv.2609.34018"
tags: [paper, embodied-ai, "cs.LG", "cs.RO"]
status: unread
rating:
created: 2026-09-30
---

# Estimate, Don't Imitate: Reusing Differentiable State-Based Policies for Visuomotor Control

> Denis Shcherba, Adrian Abel, Eckart Cobo-Briesewitz, Paul Mattes, Wojciech Samek, Marc Toussaint · 2026
> [arXiv](https://arxiv.org/abs/2609.34018) · [PDF](https://arxiv.org/pdf/2609.34018)

## Abstract

Simulation-trained manipulation policies can exploit privileged state information to learn effective contact-rich behaviours, but deployment requires acting from partial observations such as noisy camera images. A common solution is teacher-student distillation, in which a visuomotor policy is trained to reproduce the actions of the privileged expert. This requires the student to jointly infer the task-relevant state and relearn the expert's action mapping that is already available. An alternative is to reuse the state-based expert and learn only a perceptual interface that reconstructs its missing state inputs. However, minimising the state estimate error alone does not necessarily minimise the downstream control error induced by these estimates. To bridge this gap, we train a visual state estimator using both direct state supervision and an action-consistency loss backpropagated through the frozen, differentiable expert. A scheduled objective first establishes a physically meaningful state estimate and progressively emphasises errors that affect the expert's actions. Across five goal-conditioned manipulation tasks, retaining the expert consistently outperforms direct pixel-to-action imitation from the same expert demonstration corpus. We further demonstrate sim-to-real transfer on a physical Panda robot, achieving 76% success without retraining the underlying expert.

## TL;DR

Simulation-trained manipulation policies can exploit privileged state information to learn effective contact-rich behaviours, but deployment requires acting from partial observations such as noisy camera images. A common solution is teacher-student distillation, in which a visuomotor policy is trained to reproduce the actions of the privileged expert.

## Related
<!-- [[other-paper-citekey]] -->
