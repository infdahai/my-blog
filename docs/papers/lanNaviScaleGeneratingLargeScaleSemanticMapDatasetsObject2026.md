---
citekey: "lanNaviScaleGeneratingLargeScaleSemanticMapDatasetsObject2026"
title: "NaviScale: Generating Large-Scale Semantic Map Datasets for Object Navigation"
authors: ["Chuanlin Lan", "Yanwei Zheng", "Weijian Liu", "Zhitong Zhou", "Xiao Zhang", "Fuzhen Zhuang", "Dongxiao Yu"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.27218"
doi: "10.48550/arXiv.2609.27218"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-25
---

# NaviScale: Generating Large-Scale Semantic Map Datasets for Object Navigation

> Chuanlin Lan, Yanwei Zheng, Weijian Liu, Zhitong Zhou, Xiao Zhang, Fuzhen Zhuang, Dongxiao Yu · 2026
> [arXiv](https://arxiv.org/abs/2609.27218) · [PDF](https://arxiv.org/pdf/2609.27218)

## Abstract

Embodied navigation requires spatial representations that generalize across unseen environments, yet collecting large amounts of annotated data from real 3D environments is difficult. We propose NaviScale for semantic-map-based object navigation (ObjectNav), whose predictor can be trained on pairs of partial and complete semantic maps without reconstructing a complete 3D environment for every training sample. The framework generates large-scale semantic map training data by composing floorplans of real homes with room-level semantic and obstacle maps extracted from MP3D and HM3DSem. NaviScale increases data diversity in two ways: inter-room scaling increases floorplan-level structural diversity, while intra-room scaling fills each fixed floorplan with different combinations of room maps matched by room category. Visibility through Ray Casting (VisRC) converts the composed maps into partial observations that account for field of view, sensing range, and occlusion. The resulting dataset contains 192,000 semantic maps generated from 24,000 floorplans associated with 12,794 properties. With 300k training iterations and the training and inference settings described in this paper, the system reaches 64.3% SR and 34.8% SPL on HM3D, together with 43.1% SR and 16.8% SPL on MP3D, without changing the prediction architecture. Additional experiments evaluate the quality of the composed maps, the effects of semantic-segmentation errors, and deployment on a physical robot.

## TL;DR

Embodied navigation requires spatial representations that generalize across unseen environments, yet collecting large amounts of annotated data from real 3D environments is difficult. We propose NaviScale for semantic-map-based object navigation (ObjectNav), whose predictor can be trained on pairs of partial and complete semantic maps without reconstructing a complete 3D environment for every training sample.

## Related
<!-- [[other-paper-citekey]] -->
