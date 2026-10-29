---
citekey: "kozlovCognitiveRealityAgnosticSemanticGaussianMappingLLMAgentImmersive2026"
title: "CognitiveReality: Robot-Agnostic Semantic Gaussian Mapping with an LLM Agent for Immersive Collaborative VR Teleoperation"
authors: ["Timofei Kozlov", "Dmitrii Maliukov", "Andrey Marchenko", "Dmitrii Plotnikov", "Miguel Altamirano Cabrera", "Dzmitry Tsetserukou"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.31418"
doi: "10.48550/arXiv.2609.31418"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-29
---

# CognitiveReality: Robot-Agnostic Semantic Gaussian Mapping with an LLM Agent for Immersive Collaborative VR Teleoperation

> Timofei Kozlov, Dmitrii Maliukov, Andrey Marchenko, Dmitrii Plotnikov, Miguel Altamirano Cabrera, Dzmitry Tsetserukou · 2026
> [arXiv](https://arxiv.org/abs/2609.31418) · [PDF](https://arxiv.org/pdf/2609.31418)

## Abstract

A photorealistic 3D view tells a teleoperator where a robot is, but not what the scene contains, how well each object has been observed, or how to turn pointing and speech into robot action. CognitiveReality turns a robot's RGB-D stream into a live, semantically indexed Gaussian-TSDF map shared by an operator in virtual reality and a tool-using language agent. One mapper binary serves any platform through configuration alone: it ingests poses from robot SLAM, joint kinematics, motion capture or an inline visual tracker, bridges localization outages with a shadow tracker and keyframe-anchored PnP, and maintains open-vocabulary instance identities with per-object quality at 2 Hz. Speech and controller rays are grounded against persistent scene objects through validated typed tools and operator-confirmed robot actions. In the controlled agent evaluation, the deployed local Qwen3-VL-8B router reaches 81.24\% tool exact match, while merge-aware replay correctly redirects 101 absorbed object identifiers. On robot data CognitiveReality exceeds a Gaussian-plus-SDF baseline by 2-8 dB; pose error through 5-40 s SLAM outages stays within 1-8 cm. Deployed live on two quadrupeds, the agent executed 26 of 30 navigation requests and 20 of 20 re-observation requests, raising object quality by 2-5 dB.

## TL;DR

A photorealistic 3D view tells a teleoperator where a robot is, but not what the scene contains, how well each object has been observed, or how to turn pointing and speech into robot action. CognitiveReality turns a robot's RGB-D stream into a live, semantically indexed Gaussian-TSDF map shared by an operator in virtual reality and a tool-using language agent.

## Related
<!-- [[other-paper-citekey]] -->
