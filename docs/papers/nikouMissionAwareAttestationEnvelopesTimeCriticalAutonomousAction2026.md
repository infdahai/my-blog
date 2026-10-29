---
citekey: "nikouMissionAwareAttestationEnvelopesTimeCriticalAutonomousAction2026"
title: "Mission-Aware Attestation Envelopes for Time-Critical Autonomous Action: A Hardware-in-the-Loop V2I Study"
authors: ["Dimitrios Nikou", "Nikolaos Kekatos", "Sophia Petridou", "Stylianos Basagiannis"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.08771"
doi: "10.48550/arXiv.2610.08771"
tags: [paper, embodied-ai, "cs.CR", "cs.RO", "eess.SY"]
status: unread
rating:
created: 2026-10-08
---

# Mission-Aware Attestation Envelopes for Time-Critical Autonomous Action: A Hardware-in-the-Loop V2I Study

> Dimitrios Nikou, Nikolaos Kekatos, Sophia Petridou, Stylianos Basagiannis · 2026
> [arXiv](https://arxiv.org/abs/2610.08771) · [PDF](https://arxiv.org/pdf/2610.08771)

## Abstract

An autonomous system that asks for a privileged physical action is usually gated on integrity evidence: a platform proves what it is running, and the request is granted or refused on that basis. Such a gate is normally treated as a predicate, yet the evidence behind it has an age, the decision that consumes it has a latency, and the physical system that waits for it has a deadline. We formulate mission-aware attestation as a runtime assurance contract that holds only when integrity is valid, the evidence is fresh enough, and the decision completes inside a budget derived from the current physical state. The contract yields four operational outcomes where a binary gate yields two, separating a refusal caused by tampering from one caused by stale evidence and from one caused by a late decision. We evaluate it on a hardware-in-the-loop vehicle-to-infrastructure platform: a driving simulator supplies the physical state and the authorisation deadline, while a microcontroller on-board unit and a TPM-backed roadside unit running Linux integrity measurement supply the assurance evidence. A security-blind model admits the whole operating space and a hardware-informed one three quarters of it, and every point it refuses fails the freshness margin rather than the response margin. Moving the attestation interval across the range the verifier permits costs about as much as a fivefold scaling of the latency distribution, and the interval is directly configurable, which makes it the immediately actionable deployment parameter. If the freshness bound does not exceed the authorisation budget, every late decision is also stale and lateness becomes unobservable, so the attestation interval and the freshness bound cannot be chosen from security requirements alone.

## TL;DR

An autonomous system that asks for a privileged physical action is usually gated on integrity evidence: a platform proves what it is running, and the request is granted or refused on that basis. Such a gate is normally treated as a predicate, yet the evidence behind it has an age, the decision that consumes it has a latency, and the physical system that waits for it has a deadline.

## Related
<!-- [[other-paper-citekey]] -->
