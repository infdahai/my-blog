---
citekey: "oleschObservationReferencedTissueDeformationForecastingToolDrivenResidual2026"
title: "Observation-Referenced Tissue Deformation Forecasting with Tool-Driven and Residual Dynamics"
authors: ["Tom Olesch", "Nan Xiao", "Xiongye Xiao", "Jonathan C. DeLong", "Fei Liu"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.14191"
doi: "10.48550/arXiv.2610.14191"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-15
---

# Observation-Referenced Tissue Deformation Forecasting with Tool-Driven and Residual Dynamics

> Tom Olesch, Nan Xiao, Xiongye Xiao, Jonathan C. DeLong, Fei Liu · 2026
> [arXiv](https://arxiv.org/abs/2610.14191) · [PDF](https://arxiv.org/pdf/2610.14191)

## Abstract

Forecasting tissue deformation from future instrument motion could support predictive planning and increasingly autonomous surgical systems. We study this problem using a scene-specific differentiable surface model fitted to an observed tool-tissue interaction window. Rather than forecasting absolute simulated positions, we introduce an \textit{observation-referenced} formulation that anchors each tissue point to its last valid observation and adds only the deformation induced by the known, preplanned future tool trajectory. This reduces sensitivity to reconstruction, initialization, and persistent simulation offsets while preserving the predicted deformation response. The physical model uses differentiable, mesh-free position-based dynamics with scene-specific rigidity, attachment, region scale, and grasp coupling. We further introduce an optional \textit{observation-referenced residual model} combining graph-spectral spatial modes with periodic harmonic dynamics for structured motion not explained by the tool input. We evaluate the framework retrospectively on 12 surgical manipulation clips from three datasets. Observation referencing provides the largest gain, with a median within-clip error ratio of $0.598$ relative to the corresponding absolute simulation forecast. The optional periodic residual further improves forecasting when the remaining motion exhibits periodic structure. These results support observation-referenced deformation prediction as a practical building block for future surgical world models, digital twins, and generative simulators that must predict how tissue evolves under instrument actions.

## TL;DR

Forecasting tissue deformation from future instrument motion could support predictive planning and increasingly autonomous surgical systems. We study this problem using a scene-specific differentiable surface model fitted to an observed tool-tissue interaction window.

## Related
<!-- [[other-paper-citekey]] -->
