---
layout: page
title: Reason–Imagine–Act (RIA)
description: Closed-loop LLM decision making with world models for autonomous driving (ITSC 2026, oral).
img:
importance: 1
category: research
related_publications: true
---

**Reason–Imagine–Act (RIA)** is a closed-loop framework that couples an **LLM reasoner** with an **action-conditioned world model** for autonomous driving. At each step the LLM proposes an action template and candidate sub-actions, the world model rolls out short-horizon futures, and a safety scorer selects the safest executable action — closing the loop with feedback to the next reasoning step.

Under a unified CARLA point-goal protocol (1000 episodes), RIA reaches **80.05% route completion**, **51.10% arrival rate**, and **0.20% collision rate**, consistently outperforming training-free baselines.

- **Venue:** IEEE ITSC 2026 (**Oral Presentation**)
- **Paper:** [arXiv:2605.24004](https://arxiv.org/abs/2605.24004)
- **Code:** [pku-smart-city/source_code/tree/main/RIA](https://github.com/pku-smart-city/source_code/tree/main/RIA)
