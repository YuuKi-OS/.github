<div align="center">

<br>

<img src="https://img.shields.io/badge/%E2%9C%A6-OPCEANAI_MODELS-000000?style=for-the-badge&labelColor=000000" alt="OpceanAI Models" height="60">

<br><br>

# OpceanAI — Model Ecosystem

**Open-source bilingual language models for the Spanish-speaking world.**<br>
**Trained efficiently. Benchmarked honestly. Published openly.**

<br>

[![HuggingFace](https://img.shields.io/badge/All_Models-Hugging_Face-ffd21e?style=for-the-badge&logo=huggingface&logoColor=black)](https://huggingface.co/OpceanAI)
&nbsp;
[![Website](https://img.shields.io/badge/Website-opceanai.com-000000?style=for-the-badge)](https://opceanai.com)
&nbsp;
[![Contact](https://img.shields.io/badge/Contact-contacto@opceanai.com-d63384?style=for-the-badge)](mailto:contact@opceanai.com)

<br>

---

<br>

</div>

## Overview

This repository documents the complete AI model ecosystem developed by OpceanAI. All models are open-source, bilingual (Spanish/English), and trained with verified benchmarks. The ecosystem is organized into two model lines: **Yuuki** for conversational and multimodal tasks, and **OwO** for reasoning-intensive applications.

The entire model family was developed by a single independent researcher based in Mexico at a total compute cost of under $100 USD.

<br>

---

<br>

<div align="center">

## Model Lines

</div>

<br>

### Yuuki — NxG Family

**Yuuki** (勇気, *courage*) is OpceanAI's primary model line. The NxG (Next Generation) series consists of fine-tuned models with a distinctive bilingual, identity-rich training composition that produces strong honesty metrics relative to model size.

All Yuuki NxG models share the following characteristics:
- Native bilingual performance in Spanish and English
- Training dataset: Imprint-Train-v3 (OpceanAI curated dataset)
- Identity-heavy composition contributing to above-average TruthfulQA scores
- Apache 2.0 license — free for commercial and research use

<br>

<table>
<tr>
<td width="33%" valign="top">

### Yuuki NxG

[![Model](https://img.shields.io/badge/OpceanAI%2FYuuki--NxG-Hugging_Face-ffd21e?style=flat-square&logo=huggingface&logoColor=black)](https://huggingface.co/OpceanAI/Yuuki-NxG)

| Attribute | Value |
|:----------|:------|
| Parameters | 3B |
| Base model | Qwen2.5-3B-Instruct |
| Type | Text generation |
| Languages | EN / ES |
| License | Apache 2.0 |

The primary conversational model of the NxG family. Outperforms Meta Llama 3.1 8B on TruthfulQA despite being 2.6x smaller. Designed for bilingual conversation, instruction following, and general-purpose use.

</td>
<td width="33%" valign="top">

### Yuuki NxG Nano

[![Model](https://img.shields.io/badge/OpceanAI%2FYuuki--NxG--Nano-Hugging_Face-ffd21e?style=flat-square&logo=huggingface&logoColor=black)](https://huggingface.co/OpceanAI/Yuuki-NxG-Nano)

| Attribute | Value |
|:----------|:------|
| Parameters | 81M |
| Base model | Qwen2.5-0.5B-Instruct |
| Type | Text generation |
| Languages | EN / ES |
| License | Apache 2.0 |

The lightweight edge-optimized model of the NxG family. At 81M parameters, it achieves competitive TruthfulQA performance against models 10–20x its size. Designed for low-resource devices and on-device deployment across Latin America.

</td>
<td width="33%" valign="top">

### Yuuki NxG VL

[![Model](https://img.shields.io/badge/OpceanAI%2FYuuki--NxG--vl-Hugging_Face-ffd21e?style=flat-square&logo=huggingface&logoColor=black)](https://huggingface.co/OpceanAI/Yuuki-NxG-vl)

| Attribute | Value |
|:----------|:------|
| Parameters | 7B |
| Base model | Qwen2.5-VL-7B-Instruct |
| Type | Vision + Text |
| Languages | EN / ES |
| License | Apache 2.0 |

The multimodal model of the NxG family. Processes both images and text, enabling visual question answering, image description, and document understanding in Spanish and English. The first multimodal model published by OpceanAI.

</td>
</tr>
</table>

<br>

#### Community Quantizations

Yuuki NxG VL is available in GGUF format for local inference:

| Repository | Maintainer | Formats |
|:-----------|:-----------|:--------|
| [mradermacher/Yuuki-NxG-vl-GGUF](https://huggingface.co/mradermacher/Yuuki-NxG-vl-GGUF) | Community | Q2\_K (3.02 GB) through F16 (15.2 GB) |

<br>

---

<br>

### OwO — Omnireasoning Family

**OwO** stands for *OpceanAI with Omnireasoning*. This model line is specialized for complex reasoning tasks across mathematics, code, science, and general logic. OwO models are built on top of QwQ-32B — one of the strongest open-source reasoning models available — with Yuuki's bilingual personality and instruction tuning applied on top.

The name is both a technical designation and a deliberate aesthetic choice consistent with OpceanAI's identity. It is serious in documentation and unmistakable in community.

<br>

<table>
<tr>
<td width="50%" valign="top">

### OwO NxG *(in development)*

[![Status](https://img.shields.io/badge/Status-In_Development-orange?style=flat-square)](https://huggingface.co/OpceanAI)

| Attribute | Value |
|:----------|:------|
| Parameters | 32B |
| Base model | QwQ-32B |
| Type | Reasoning — text, math, code |
| Languages | EN / ES |
| License | Apache 2.0 |
| Training | LoRA+ + Flash Attention 2 |

OwO NxG is trained across seven phases covering mathematical reasoning (NuminaMath, GSM8K), code reasoning (CodeForces), scientific reasoning (ARC Challenge, GPQA), general reasoning (OpenHermes), and honesty (TruthfulQA), with Yuuki personality anchoring phases at start and end.

</td>
<td width="50%" valign="top">

**What Omnireasoning means**

OwO is designed to reason across domains — not only mathematics. The seven training phases cover:

| Domain | Dataset |
|:-------|:--------|
| Mathematics | NuminaMath / GSM8K |
| Code | CodeForces CoT |
| Science | ARC Challenge / GPQA |
| General | OpenHermes |
| Honesty | TruthfulQA |
| Identity | Yuuki 5K (x2) |

QwQ's chain-of-thought reasoning capability is preserved intact. Yuuki's personality is layered on top without modifying the base reasoning architecture.

</td>
</tr>
</table>

<br>

---

<br>

<div align="center">

## Benchmark Results

</div>

<br>

OpceanAI publishes all benchmark results openly through the [NHE-Benchmark](https://huggingface.co/OpceanAI) dataset.

**Key findings across the NxG family:**

| Model | Parameters | TruthfulQA | Notable Comparison |
|:------|:----------:|:----------:|:-------------------|
| Yuuki NxG | 3B | Above Llama 3.1 8B | Outperforms a model 2.6x its size |
| Yuuki NxG Nano | 81M | Competitive | Outperforms models 10–20x its size on honesty |
| Yuuki NxG VL | 7B | In evaluation | First bilingual VL model from OpceanAI |

**Cost efficiency:**

| Organization | Compute Cost | Parameters | Team Size |
|:-------------|:------------:|:----------:|:---------:|
| OpceanAI (NxG family) | < $100 USD | Up to 7B | 1 person |
| LATAM GPT (comparable) | $550,000 USD | 70B | 100+ researchers |

OpceanAI's cost per billion parameters: approximately **$1.43 USD**. Market average for equivalent work: $1,428–7,142 USD.

<br>

---

<br>

<div align="center">

## Roadmap

</div>

<br>

### NxG — Current generation *(fine-tuning on existing bases)*

| Model | Status |
|:------|:------:|
| Yuuki NxG (3B) | Published |
| Yuuki NxG Nano (81M) | Published |
| Yuuki NxG VL (7B) | Published |
| OwO NxG (32B) | In development |

### NxE — Next Evolution *(planned, post-investment)*

The NxE line will introduce larger models, partial proprietary architecture, and expanded multimodal capabilities. Planned for August 2026 and beyond, contingent on infrastructure upgrade (Mac Mini M4) and funding.

| Model | Parameters | Type |
|:------|:----------:|:----:|
| Yuuki NxE Nano | 150M | Text |
| Yuuki NxE | 7B | Text + Vision |
| Yuuki NxE Omni | 30B | Audio + Vision + Text |
| Yuuki NxE Reasoning | 72B | Reasoning |
| Yuuki NxE Origin | 100M | 100% proprietary architecture |

<br>

---

<br>

<div align="center">

## Technical Details

</div>

<br>

### Training Stack

| Component | Technology |
|:----------|:-----------|
| Framework | Unsloth + HuggingFace Transformers |
| Quantization | QLoRA 4-bit during training |
| Adapters | LoRA / LoRA+ |
| Attention | Flash Attention 2 (OwO NxG) |
| Hardware | Google Colab Pro (A100 / H100) |
| Format | SafeTensors (merged) + GGUF (community) |

### Inference

All models support inference via HuggingFace Transformers:

```python
from transformers import pipeline

# Text models
pipe = pipeline("text-generation", model="OpceanAI/Yuuki-NxG")

# Vision-language model
pipe = pipeline("image-text-to-text", model="OpceanAI/Yuuki-NxG-vl")
```

Local inference via GGUF quantizations is available through [yuy](https://github.com/YuuKi-OS/yuy), OpceanAI's Rust-based CLI tool.

<br>

---

<br>

<div align="center">

## Design Philosophy

</div>

<br>

**Honesty over capability.** TruthfulQA performance is prioritized above raw benchmark scores. A smaller model that does not hallucinate is more useful than a larger model that does.

**Bilingual by design.** Spanish is not post-hoc localization. All models are trained from the ground up for native bilingual performance, targeting the 650 million Spanish speakers underserved by current AI systems.

**Efficiency as a principle.** The NxG family demonstrates that production-quality models do not require institutional infrastructure. Every model in this family was trained on consumer-accessible cloud hardware at minimal cost.

**Radical transparency.** All training configurations, benchmark results, and datasets are published openly. No proprietary claims are made without verifiable public evidence.

<br>

---

<br>

<div align="center">

[![HuggingFace](https://img.shields.io/badge/OpceanAI-Hugging_Face-ffd21e?style=for-the-badge&logo=huggingface&logoColor=black)](https://huggingface.co/OpceanAI)
&nbsp;
[![Apache 2.0](https://img.shields.io/badge/License-Apache_2.0-000000?style=for-the-badge)](https://apache.org/licenses/LICENSE-2.0)

<br>

*Open source. Bilingual. Built from nothing.*

</div>
