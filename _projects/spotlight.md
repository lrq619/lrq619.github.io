---
layout: page
title: Spotlight
description: Cost-efficient DiT reinforcement learning with spot GPUs, dynamic seed exploration, and elastic sequence parallelism.
importance: 1
category: research
---

**March 2026 – June 2026 · Beijing, China**

Spotlight uses low-cost spot GPUs for reinforcement learning post-training of Diffusion Transformers (DiTs), reducing training costs to **one-seventh of the baseline**.

I led the project, jointly optimizing system infrastructure and post-training algorithms:

- Designed **dynamic seed exploration** to offload the search for high-quality seeds to spot GPUs during training.
- Developed **elastic sequence parallelism** that adjusts its parallelism degree to spot GPU availability in real time.
- Built a **preemption-aware scheduler with tensor checkpointing** to bound lost computation when spot instances are preempted.

[Read the preprint](https://arxiv.org/abs/2606.19004)
