---
layout: page
title: FastTrust-WAM
description: Fast world-action models for robot control (ongoing).
img:
importance: 2
category: research
---

<span class="badge font-weight-bold danger-color-dark text-uppercase align-middle">Ongoing research</span>

**FastTrust-WAM** studies *fast world-action models* for robot control. The idea is to keep the low-latency, action-chunk execution style of Fast-WAM, while giving the action head direct access to compact predicted future tokens at inference — so the policy conditions on its own predicted consequences instead of acting future-free.

The architecture sketches three parts: a shared backbone over history, proprioception, observations, and task context; a future-token head that predicts compact latent futures supervised by rollout visual latents (e.g., DINO / V-JEPA); and an action head that attends to those future tokens when producing the next action chunk — robustness from imagined consequences, without paying for full future-video rollout.
