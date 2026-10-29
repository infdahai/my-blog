---
citekey: "zhangFrameLevelTemporalAlignmentHumanVisualAdaptation2026"
title: "Frame-Level Temporal Alignment for Human-to-Robot Visual Adaptation"
authors: ["Xizhe Zhang", "Jingfeng Zhang", "Zirun Zhou", "Hong Jia"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.04372"
doi: "10.48550/arXiv.2610.04372"
tags: [paper, embodied-ai, "cs.LG", "cs.RO"]
status: unread
rating:
created: 2026-10-07
---

# Frame-Level Temporal Alignment for Human-to-Robot Visual Adaptation

> Xizhe Zhang, Jingfeng Zhang, Zirun Zhou, Hong Jia · 2026
> [arXiv](https://arxiv.org/abs/2610.04372) · [PDF](https://arxiv.org/pdf/2610.04372)

## Abstract

Transferring visual representations pretrained on human videos to robot manipulation requires learning reliable correspondences between human and robot demonstrations. However, paired demonstrations can differ in execution rate and in the proportion of non-key frames that do not directly reflect task progress. Frames at the same relative timestamp may therefore represent different task stages, which can cause correspondence learning to fail. To address these issues, we propose Frame-Level Temporal Alignment (FLTA), a framework that uses two temporal priors to adapt visual encoders pretrained on human videos for robot manipulation. It learns shared task-progress representations without frame-level correspondence annotations, allowing frames at different relative temporal positions to match. A global progress prior combines normalized temporal positions with visual similarity to construct a soft correspondence target. A local temporal order prior penalizes backward transitions while allowing stays and varying forward rates to accommodate execution-rate differences. With ResNet-50 and ViT encoders, our method achieves relative improvements of 46.93% and 65.96%, respectively, over the best baselines in average simulation success rates and achieves higher task success rates on real-world manipulation tasks. These results also suggest that effective human-robot adaptation depends less on the number of parameters updated than on which parameters are selected. Our project page is available at https://rtx5090ultra.github.io/FLTA-Project-Page/.

## TL;DR

Transferring visual representations pretrained on human videos to robot manipulation requires learning reliable correspondences between human and robot demonstrations. However, paired demonstrations can differ in execution rate and in the proportion of non-key frames that do not directly reflect task progress.

## Related
<!-- [[other-paper-citekey]] -->
