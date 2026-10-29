---
citekey: "kreisOMAROpenWorldMultiAttributeReasoningSceneConditioned2026"
title: "OMAR: Open-World Multi-Attribute Reasoning for Scene-Conditioned Shelf Organization"
authors: ["Benedikt Kreis", "Rohit Menon", "Benno Wingender", "Muhammad Ehsan Ullah", "Nils Dengler", "Maren Bennewitz"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.29761"
doi: "10.48550/arXiv.2610.29761"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-23
---

# OMAR: Open-World Multi-Attribute Reasoning for Scene-Conditioned Shelf Organization

> Benedikt Kreis, Rohit Menon, Benno Wingender, Muhammad Ehsan Ullah, Nils Dengler, Maren Bennewitz · 2026
> [arXiv](https://arxiv.org/abs/2610.29761) · [PDF](https://arxiv.org/pdf/2610.29761)

## Abstract

With the advent of foundation models, robots are increasingly capable of understanding and executing explicitly specified human tasks. Extending these capabilities to open-ended tasks, however, requires robots to infer appropriate actions from the observed scene. Household organization exemplifies this challenge, as robots must often act without detailed instructions, predefined object vocabularies, or known object-receptacle associations. While robots may follow instructions or learn organization preferences from demonstrations, inferring the latent organization of an occasionally changing scene and placing a novel object consistently with it remains challenging. We propose an open-world multi-attribute reasoning pipeline that grounds unknown objects across views and constructs an instance-level 3D scene graph for placement reasoning. First, a vision-language model proposes labels together with attributes such as content and packaging type, which are grounded through segmentation, depth, and multi-view association. Then, an LLM reasons over this representation to infer the latent shelf organization and rank scene-consistent object placements without explicitly user-provided preferences. The resulting placement rankings guide subsequent geometric and kinematic feasibility checks for execution. Our experimental evaluation shows that our approach leads to improved instance mapping and placement coherence over single-view language-grounding and geometry-only baselines, enabling autonomous placement of previously unseen objects without predefined object-receptacle mappings or class-specific retraining.

## TL;DR

With the advent of foundation models, robots are increasingly capable of understanding and executing explicitly specified human tasks. Extending these capabilities to open-ended tasks, however, requires robots to infer appropriate actions from the observed scene.

## Related
<!-- [[other-paper-citekey]] -->
