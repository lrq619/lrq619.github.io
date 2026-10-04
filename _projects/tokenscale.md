---
layout: page
title: TokenScale
description: Proactive autoscaling for disaggregated LLM serving, driven by token-level workload dynamics.
importance: 2
category: research
---

**October 2024 – November 2025 · Singapore**

TokenScale is a proactive autoscaling system for LLM inference with prefill/decode disaggregation. It enables timely and accurate resource scaling based on token-level workload dynamics. The work was **accepted to ACM SoCC’26**.

- Implemented a cluster-level LLM inference control plane in approximately **6,000 lines of Go**, including a traffic gateway, autoscaler, and router.
- Supported advanced routing and autoscaling policies for disaggregated serving.
- Demonstrated operation on a **32-node AMD/NVIDIA cluster**, improving performance by **up to 36%** while reducing costs.

[Read the paper](https://arxiv.org/abs/2512.03416)
