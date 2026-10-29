---
citekey: "landegIfFirstYouDonTSucceedBacktrackLightweight2026"
title: "If at First You Don't Succeed, Backtrack: Lightweight Recovery for Frozen VLAs"
authors: ["Thomas Landeg", "Thierry Tambe"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.32941"
doi: "10.48550/arXiv.2610.32941"
tags: [paper, embodied-ai, "cs.LG", "cs.RO"]
status: unread
rating:
created: 2026-10-27
---

# If at First You Don't Succeed, Backtrack: Lightweight Recovery for Frozen VLAs

> Thomas Landeg, Thierry Tambe · 2026
> [arXiv](https://arxiv.org/abs/2610.32941) · [PDF](https://arxiv.org/pdf/2610.32941)

## Abstract

Vision-Language-Action (VLA) models perform well on robotic manipulation, yet remain brittle once their own actions carry them into states their training data barely covers. Recovering from such failures usually requires recovery demonstrations, policy retraining, or a separate model at inference time. We introduce Backtrack, a lightweight failure detection and recovery mechanism for frozen VLAs that needs none of these. A small failure prediction head, trained only on outcome-labeled rollouts of the frozen policy, reads the VLA's existing internal representations to estimate whether the current episode will fail. When the predicted failure probability exceeds a threshold, a controller pauses the policy, retraces the arm's recently achieved motion, and hands control back to the unchanged policy so it can retry from an earlier configuration. The head adds only 0.48-0.88% to the policy's parameter count. We evaluate Backtrack on LIBERO with three VLAs spanning two action-generation families: SmolVLA and $\pi$0.5, which use flow-matching action experts, and the autoregressive $\pi$0-FAST. On LIBERO-Long, the suite of long-horizon multi-step tasks and the one on which all three policies fail most often, Backtrack reduces each policy's failure rate by 19-48%, raising success by up to 7.4 percentage points; on the three shorter suites, where control success is already 85-99%, its effect is smaller. On MetaWorld, all twelve controller configurations tested with SmolVLA improve on the unassisted policy.

## TL;DR

Vision-Language-Action (VLA) models perform well on robotic manipulation, yet remain brittle once their own actions carry them into states their training data barely covers. Recovering from such failures usually requires recovery demonstrations, policy retraining, or a separate model at inference time.

## Related
<!-- [[other-paper-citekey]] -->
