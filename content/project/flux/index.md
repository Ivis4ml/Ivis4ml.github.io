---
title: 'Flux: Adaptive Async RL Training Framework'
summary: Adaptive sync/async RL framework with PID controller for dynamic async ratio adjustment. Supports PPO, GRPO, DPO, DAPO, RLOO.
tags:
  - Reinforcement Learning
  - Training Infrastructure
date: '2025-01-01'
external_link: ''
links:
  - icon: github
    icon_pack: fab
    name: Code
    url: https://github.com/Ivis4ml/flux
---

Flux is an **adaptive synchronous/asynchronous RL training framework** with a PID controller for dynamic async_ratio adjustment.

**Architecture:**
- Megatron training + SGLang inference + CUDA IPC weight sync
- PID controller dynamically adjusts the sync/async ratio based on training signal quality

**Supported algorithms:** PPO, GRPO, DPO, DAPO, RLOO
