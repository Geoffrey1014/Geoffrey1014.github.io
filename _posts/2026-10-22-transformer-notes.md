---
title: 'Transformer 技术笔记：以 Gemma 2 27B 为例'
date: 2026-10-22
permalink: /posts/2026/10/transformer-notes/
excerpt: '以 Gemma 2 27B 的真实参数为主线，从 KV cache、注意力和 FFN 一路讲到信息论、对齐训练和评测统计。'
tags:
  - transformer
  - llm
---

这是一份以 **Gemma 2 27B** 为解剖对象的 Transformer 技术笔记。每个结论都尽量落到这个模型的真实参数上，能算出来的数字都算出来。

**[阅读全文 →](/notes/transformer/)**

内容包括：

- **模型骨架**：d_model 与 head_dim、GQA、RoPE 与长度外推、ALiBi / NoPE、MLA、FFN 与 MoE、RMSNorm 与 Pre-LN
- **训练**：反向传播、优化器、训练显存账
- **损失与信息论**：交叉熵、信息论视角、模型能存多少知识
- **推理工程**：KV cache、带宽瓶颈、投机解码、FlashAttention、量化（GPTQ / AWQ / SmoothQuant）
- **对齐**：SFT、RLHF / PPO、DPO、GRPO 的训练流水线，LoRA / QLoRA
- **评测统计**：一个分数有多可信、多次采样的两种方差、怎样比较两个模型

本文由我与 Claude（Anthropic）多轮对话整理而成，具体数字和论文结论都对照原始论文、官方配置或数值实验核实过，不确定的地方标了"待核实"，发现的错误记在附录 A。欢迎指错。
