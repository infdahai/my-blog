---
citekey: "schottROS2ConnectNewROS2WANSolution2026"
title: "ROS2 Connect: A new ROS2 over WAN Solution"
authors: ["Daniel Schott", "Lakshminarasimhan Srinivasan", "Christian Herrmann", "Andreas N\\\"uchter"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2608.25102"
doi: "10.48550/arXiv.2608.25102"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-08-27
---

# ROS2 Connect: A new ROS2 over WAN Solution

> Daniel Schott, Lakshminarasimhan Srinivasan, Christian Herrmann, Andreas N\"uchter · 2026
> [arXiv](https://arxiv.org/abs/2608.25102) · [PDF](https://arxiv.org/pdf/2608.25102)

## Abstract

The Robot Operating System 2 (ROS2) has become a widely adopted framework for the development of distributed robotic systems. However, its communication architecture, based on DDS and RTPS, relies on multicast discovery mechanisms that are typically unavailable in wide-area network (WAN) environments, making remote operation challenging. This work presents ROS2 Connect, a WebSocket-based communication framework that enables transparent and secure ROS2 interaction across routed networks without requiring modifications to network infrastructure or DDS configurations. The proposed client-server architecture supports bidirectional exchange of topics, services, actions, and system data while integrating authentication and access control mechanisms. Experimental evaluation over a real WAN connection demonstrates significantly lower latency, higher stability, and improved scalability compared to existing solutions, including DDS Router, rosbridge and Zenoh. Initial results show that ROS2 Connect provides a reliable foundation for teleoperation and distributed robotics applications over wide-area networks.

## TL;DR

The Robot Operating System 2 (ROS2) has become a widely adopted framework for the development of distributed robotic systems. However, its communication architecture, based on DDS and RTPS, relies on multicast discovery mechanisms that are typically unavailable in wide-area network (WAN) environments, making remote operation challenging.

## Related
<!-- [[other-paper-citekey]] -->
