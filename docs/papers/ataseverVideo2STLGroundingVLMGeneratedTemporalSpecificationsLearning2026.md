---
citekey: "ataseverVideo2STLGroundingVLMGeneratedTemporalSpecificationsLearning2026"
title: "Video2STL: Grounding VLM-Generated Temporal Specifications for Robot Learning"
authors: ["Merve Atasever", "Keyan Azbijari", "Cagan Bakirci", "Bo-Ruei Huang", "Tolga Izdas", "Zahra Shahrooei", "Richard Yang", "Erdem Biyik", "Jyotirmoy V. Deshmukh"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.37519"
doi: "10.48550/arXiv.2609.37519"
tags: [paper, embodied-ai, "cs.AI", "cs.RO"]
status: unread
rating:
created: 2026-10-03
---

# Video2STL: Grounding VLM-Generated Temporal Specifications for Robot Learning

> Merve Atasever, Keyan Azbijari, Cagan Bakirci, Bo-Ruei Huang, Tolga Izdas, Zahra Shahrooei, Richard Yang, Erdem Biyik, Jyotirmoy V. Deshmukh · 2026
> [arXiv](https://arxiv.org/abs/2609.37519) · [PDF](https://arxiv.org/pdf/2609.37519)

## Abstract

Video-based policy learning is particularly promising, as it illustrates target behaviors without requiring action annotations or embodiment-matched demonstrations. A central challenge is deciding what information should be transferred from the video to the robot. Existing approaches commonly convert visual observations into scalar similarity or value signals, or ask foundation models to directly generate reward code. These approaches can make the temporal structure of a task difficult to inspect, ground, and reuse. We present Video2STL, a framework that converts observation-only videos into parametric Signal Temporal Logic (STL) specifications and uses the resulting formal representation for robot learning. A vision-language model extracts an embodiment-independent semantic event trace and constructs a bank of symbolic temporal specifications. The model determines the task structure, while numerical predicate thresholds and temporal bounds are grounded from successful robot trajectories. For policy learning, we separate short- and long-timescale temporal information: short-horizon specifications provide dense rewards through rolling-window quantitative robustness, while a causal monitor over a retained long-horizon specification provides one-time progress rewards for valid temporal prefixes. The same representation supports cross-embodiment transfer from human or animal videos to robot control. Across four manipulation tasks, Video2STL achieves $85.8\%$ average success-once and $67.0\%$ success-at-end, compared with $81.5\%/59.5\%$ for native dense PPO and $65.0\%/42.3\%$ for Text2Reward; in quadruped locomotion, Qwen-3.8 and GPT-5.6-based Video2STL policies achieve $100\%$ success across velocities from $0.3$ to $2.1\,\mathrm{m/s}$ while remaining competitive in high-speed energy efficiency. Project webpage: \href{https://video2stl.github.io/}{video2stl}.

## TL;DR

Video-based policy learning is particularly promising, as it illustrates target behaviors without requiring action annotations or embodiment-matched demonstrations. A central challenge is deciding what information should be transferred from the video to the robot.

## Related
<!-- [[other-paper-citekey]] -->
