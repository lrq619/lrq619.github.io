---
layout: page
title: ROLL Diffusion RL
description: End-to-end Qwen-Image post-training with FlowGRPO, DiffNFT, FSDP2, and vLLM-Omni, released in ROLL v0.4.0.
importance: 4
category: open source
---

**March 2026 – Present · Alibaba, Platform Technology – AI Training Engine · Beijing, China**

As a research intern, I built core infrastructure and algorithm support for Diffusion Transformer (DiT) post-training in **ROLL**.

- Independently designed and implemented the **DiT model abstraction layer**, with unified interfaces for forward passes, sampling, trajectory generation, and intermediate training states. This decouples model implementations from training and inference backends.
- Implemented full support for **FlowGRPO and DiffNFT**, completing end-to-end, multi-node, multi-GPU training of the **20B-parameter Qwen-Image** model.
- Across approximately **400 GPU-hours** of experiments, improved aggregate scores on multiple established DiT post-training datasets from approximately **0.3 to 0.9**. Human evaluation confirmed improvements in rendered text accuracy, semantic consistency, and overall visual quality.
- Integrated **FSDP2 distributed training** with **vLLM-Omni parallel inference and rollout generation**, covering model loading, online sampling, reward computation, and post-training inference validation.

This work was released as Diffusion RL support in **ROLL v0.4.0**, with the contribution credited in the official release notes.

[ROLL v0.4.0 release notes](https://github.com/alibaba/ROLL/releases/tag/v0.4.0)
