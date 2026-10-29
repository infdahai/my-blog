---
citekey: "wangVisualWiFiNavigationSignalEmittingDevices2026"
title: "Visual-Wi-Fi Navigation to Signal-Emitting Devices"
authors: ["Lihao Wang", "Tianjian Xu", "Tianmin Shu", "Renjie Zhao"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.12733"
doi: "10.48550/arXiv.2610.12733"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-13
---

# Visual-Wi-Fi Navigation to Signal-Emitting Devices

> Lihao Wang, Tianjian Xu, Tianmin Shu, Renjie Zhao · 2026
> [arXiv](https://arxiv.org/abs/2610.12733) · [PDF](https://arxiv.org/pdf/2610.12733)

## Abstract

Indoor navigation to task-relevant targets remains difficult when the target is small, occluded, or visually indistinct. Meanwhile, smart appliances, mobile devices, and IoT tags emit Wi-Fi signals during everyday communication, providing a pervasive but underused spatial cue. We study visual-Wi-Fi navigation, where a robot reaches a signal-emitting device in an unmapped environment using onboard visual observations and Wi-Fi packets overheard from the device, without connecting to the device or modifying infrastructure. Realizing this requires pose-dependent Wi-Fi observations during closed-loop policy learning and reliable spatial cues from bearing measurements corrupted by indoor multipath propagation on a moving robot. We present WiFiSpaces, which extends the Habitat embodied simulator with online ray-traced Wi-Fi sensing, rendering Wi-Fi observations for a robot-mounted antenna array at continuous poses during policy rollouts. On top of it, we build ViFiNav, a localization-aware navigation framework: an online source-localization algorithm exploits robot motion to disambiguate and robustly aggregate bearings from multiple viewpoints into a confidence-aware source estimate, and a learned policy fuses this evolving estimate with depth observations and learns to act on it as it is refined. Experiments show that exploiting robot motion is key to accurate source estimates, and that fine-tuning on ray-traced Wi-Fi observations in WiFiSpaces improves the success rate of ViFiNav. The policy transfers zero-shot to unseen scene datasets, and we deploy it on a real robot with a Wi-Fi sensor built from a commodity router, without any real-world training.

## TL;DR

Indoor navigation to task-relevant targets remains difficult when the target is small, occluded, or visually indistinct. Meanwhile, smart appliances, mobile devices, and IoT tags emit Wi-Fi signals during everyday communication, providing a pervasive but underused spatial cue.

## Related
<!-- [[other-paper-citekey]] -->
