---
citekey: "dijkstraEnablingMotionInducedWiFiCSISensingMultiSystems2026"
title: "Enabling Motion-Induced WiFi-CSI Sensing in Multi-Robot Systems: A Simulation Framework"
authors: ["Brendan Dijkstra", "Ninad Jadhav", "Maurice Stoffijn", "Stephanie Gil", "Bahar Haghighat"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.34034"
doi: "10.48550/arXiv.2610.34034"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-28
---

# Enabling Motion-Induced WiFi-CSI Sensing in Multi-Robot Systems: A Simulation Framework

> Brendan Dijkstra, Ninad Jadhav, Maurice Stoffijn, Stephanie Gil, Bahar Haghighat · 2026
> [arXiv](https://arxiv.org/abs/2610.34034) · [PDF](https://arxiv.org/pdf/2610.34034)

## Abstract

WiFi Channel State Information (CSI) enables fine-grained sensing of spatial relationships between wireless devices. The WiFi Sensor for Robotics (WSR) toolbox demonstrated that WiFi-CSI measurements collected during robot motion, combined with odometry, can be used to synthesize virtual antenna arrays, enabling motion-induced bearing estimation in multi-robot experiments. However, deploying the WSR approach has remained challenging due to its limited integration with standard robotics tools and reliance on deprecated WiFi-CSI acquisition hardware. This work presents an open-source simulation framework that integrates the WSR sensing pipeline within the robotic simulator Gazebo. The framework generates synthetic WiFi-CSI measurements with realistic physical signal properties and leverages realistic robot motion required for motion-induced sensing and downstream localization. It further supports processing both simulated and real WiFi-CSI data for direct comparison and validation. Our aim is to make WSR-style sensing accessible as a modular sensing modality for robotic research. We validate our framework by comparing simulated and real-world experiments using TurtleBot3 robots, and demonstrate its use for bearing estimation and robot localization. This work lowers the barrier to entry for WiFi-CSI-based sensing in multi-robot systems and provides a foundation for integrating WiFi-CSI sensing with multi-modal perception for localization and coordination. All code and experimental details are publicly available at https://github.com/baharhaghighat/DARS_2026_Dijkstra_et_al

## TL;DR

WiFi Channel State Information (CSI) enables fine-grained sensing of spatial relationships between wireless devices. The WiFi Sensor for Robotics (WSR) toolbox demonstrated that WiFi-CSI measurements collected during robot motion, combined with odometry, can be used to synthesize virtual antenna arrays, enabling motion-induced bearing estimation in multi-robot experiments.

## Related
<!-- [[other-paper-citekey]] -->
