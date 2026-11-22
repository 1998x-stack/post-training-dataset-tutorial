# 🎛️ 后训练数据集分析与构建流程 · 从入门到精通

> 📘 28章 实战体系 · 交互式 HTML 课程

> **English TL;DR:** An all-Chinese 28-chapter course on **post-training datasets** (SFT / RM / DPO / RLVR) — how data drives model behavior after pretraining. Covers the data taxonomy (SFT / preference / reasoning), formats & standards (instruction/input/output, prompt/chosen/rejected, ShareGPT/OpenAI), acquisition (human annotation, model generation, real-user logs), quality frameworks & lifecycle (data flywheel, versioning, lineage), the HuggingFace ecosystem, and the landmark datasets: English SFT (FLAN, Alpaca, OpenHermes), multi-turn (UltraChat/ShareGPT/Vicuna), reasoning (OpenOrca/GSM8K/MATH), Chinese (Firefly/BELLE/UltraChat-zh), vertical (CodeAlpaca/Medical), preference (HH-RLHF, UltraFeedback, HelpSteer2), safety (BeaverTails/ToxicChat), CoT reasoning (OpenThoughts), GRPO/RLVR (verifiable rewards), tool/function-calling (Glaive, ToolBench), and agent/ multi-step (SWE-bench) sets. Then mixing recipes, dedup/denois, a quality pipeline (NeMo Curator / FineWeb2), fine-tuning framework adapters (TRL/Axolotl/LLaMA-Factory), license compliance, and the new 2026 paradigms (PiKa small data, synthetic self-play, auto curriculum) — plus a from-scratch post-training data pipeline capstone.

## 📖 课程简介

本课程围绕 **后训练（SFT / 偏好对齐 / 推理增强）数据**做系统分析：从后训练数据分类（SFT / 偏好 / 推理）与格式标准讲起，介绍采集策略、质量评估与数据生命周期，再逐一罗列主流标杆数据集——英文/多轮/推理/中文/垂直 SFT 数据、HH-RLHF 等偏好数据、CoT 与 GRPO/RLVR 推理数据、工具调用与 Agent 多步数据。工程侧覆盖 SFT 数据配比与去噪去重、质量管线（NeMo Curator）、训练框架适配（TRL/Axolotl/LLaMA-Factory）与许可证合规，并展望 2025–26 新范式，最后以「从零构建后训练数据流水线」的综合实战收束。

## 🚀 快速开始

```bash
open index.html   # macOS，纯静态即开即看
```

## 📂 项目结构

```text
post-training-dataset-tutorial/
├── index.html / 01.html ~ 28.html / theme.css
```

## 📖 章节分段

| 阶段 | 章节 | 核心 |
|------|------|------|
| **概念与标准** | 01–06 | 后训练定位、分类、格式、采集、质量、生命周期 |
| **生态与数据集系** | 07–14 | HuggingFace 生态、英文/多轮/推理/中文/垂直 SFT、配比、去噪 |
| **偏好与推理数据** | 15–22 | 偏好基础、HH-RLHF 等、DPO/ORPO、安全中文、CoT、RLVR/GRPO、工具、Agent |
| **工程与合规** | 23–26 | 质量管线、框架适配、许可合规、新范式 |
| **实战** | 27–28 | 数据策略设计、端到端流水线 |

## ✨ 亮点

- 覆盖 SFT / 偏好 / 推理 / 工具 / Agent 全套后训练数据
- 从数据飞轮到 NeMo Curator 质量管线到 TRL/LLaMA-Factory 适配
- 含 2025–26 π-cumference 新范式与端到端实战

## 🎯 前置知识

- 适合：后训练 / 对齐工程师、数据科学
- 建议具备：Python + 基础 LLM 训练概念

## ✨ 特色

- 以「数据驱动行为」为主线，构建可落地的后训练数据体系
- 即开即用纯静态 HTML

---
*本课程由 `post-training-dataset-tutorial/` 项目维护。*