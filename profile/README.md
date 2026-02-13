<div align="center">

<br>

<img src="https://img.shields.io/badge/%E2%9C%A6-YUUKI_PROJECT-000000?style=for-the-badge&labelColor=000000" alt="Yuuki Project" height="60">

<br><br>

# Training AI on a Phone. Zero Budget. Pure Determination.

**A code-generation language model trained entirely on a smartphone.**<br>
**GPT-2 architecture. Snapdragon 685. CPU only. 50+ hours. $0.00.**

<br>

[![Model Weights](https://img.shields.io/badge/Model_Weights-Hugging_Face-ffd21e?style=for-the-badge&logo=huggingface&logoColor=black)](https://huggingface.co/OpceanAI/Yuuki-best)
&nbsp;
[![Live Demo](https://img.shields.io/badge/Live_Demo-Spaces-ffd21e?style=for-the-badge&logo=huggingface&logoColor=black)](https://huggingface.co/spaces/OpceanAI/Yuuki)
&nbsp;
[![Sponsor](https://img.shields.io/badge/Sponsor-GitHub_Sponsors-ea4aaa?style=for-the-badge&logo=githubsponsors&logoColor=white)](https://github.com/sponsors/aguitauwu)

<br>

---

<br>

</div>

## About Yuuki

**Yuuki** (勇気 - *courage/bravery*) is an open-source code-generation language model being trained entirely on a **Redmi 12 smartphone** with a Snapdragon 685 processor running in CPU-only mode. No cloud GPUs. No training clusters. No budget. Just a phone, patience, and the determination to make AI accessible to everyone.

Started in January 2026 by **agua_omg**, a young independent developer who couldn't afford Claude subscriptions anymore, Yuuki represents a radical experiment in democratizing AI training. The project proves that you don't need expensive infrastructure to contribute to the AI ecosystem -- you just need time, creativity, and a willingness to think differently.

The name combines the Japanese word for snow (Yuki) with the character Yuu from *Girls' Last Tour*, reflecting both the project's Japanese aesthetic and its scrappy, survival-against-the-odds spirit.

<br>

---

<br>

<div align="center">

## Current Status

</div>

<br>

<table>
<tr>
<td width="50%" valign="top">

**Training Progress**

| Metric | Value |
|:-------|:------|
| Base model | GPT-2 (124M parameters) |
| Training type | Continued pre-training |
| Hardware | Snapdragon 685, CPU only |
| Device | Redmi 12 (smartphone) |
| Training time | 50+ hours |
| Progress | 2,000 / 37,500 steps (5.3%) |
| Cost | **$0.00** |

</td>
<td width="50%" valign="top">

**Model Performance** *(Checkpoint 2000)*

| Language | Score |
|:---------|:------|
| Agda | 55 / 100 |
| C | 20 / 100 |
| Assembly | 15 / 100 |
| Python | 8 / 100 |

*Scores improving with each checkpoint.*

</td>
</tr>
</table>

<br>

---

<br>

<div align="center">

## Ecosystem

</div>

<br>

<table>
<tr>
<td width="50%" valign="top">

### Web Applications

**[Yuuki Chat](https://yuuki-chat.vercel.app)**<br>
macOS-inspired chat interface with three model variants, web research mode powered by Tavily, YouTube search integration, and deeply customizable themes with dark, pastel, and light modes.

<br>

**[Yuuki Web](https://yuuki-web.vercel.app)**<br>
Official landing page showcasing the model, embedding the live demo, presenting evaluation data, and telling the origin story. Dark cyberpunk-minimal design with sakura pink accents.

</td>
<td width="50%" valign="top">

### Command Line Tools

**[yuy](https://github.com/YuuKi-OS/yuy)**<br>
CLI for downloading, managing, and running Yuuki models locally. Built in Rust for performance and reliability. Model registry, version management, and inference engine in one tool.

<br>

**[yuy-chat](https://github.com/YuuKi-OS/yuy-chat)**<br>
Terminal-based TUI chat interface for local AI conversations. Conversation history, syntax highlighting, and a beautiful terminal UI powered by Ratatui.

</td>
</tr>
</table>

<br>

---

<br>

<div align="center">

## Repositories

</div>

<br>

| Repository | Description | Language |
|:-----------|:------------|:---------|
| [yuuki-training](https://github.com/YuuKi-OS/yuuki-training) | Training code, scripts, and configuration for the Yuuki models | Python |
| [yuy](https://github.com/YuuKi-OS/yuy) | CLI for model management and local inference | Rust |
| [yuy-chat](https://github.com/YuuKi-OS/yuy-chat) | TUI chat interface for terminal-based conversations | Rust |
| [Yuuki-web](https://github.com/YuuKi-OS/Yuuki-web) | Official landing page and project showcase | TypeScript |
| [Yuuki-chat](https://github.com/YuuKi-OS/Yuuki-chat) | Web-based chat interface with research and YouTube modes | TypeScript |

<br>

---

<br>

<div align="center">

## Research & Documentation

</div>

<br>

### Academic Paper

Detailed technical documentation, training methodology, evaluation benchmarks, and the complete story of training a language model on a smartphone is available in our research paper:

**[📄 Read the Paper](https://drive.google.com/drive/folders/1IVoaI_FdNBxWGH-zBsnG24Gc5hIxKc4A)**

Topics covered: hardware constraints, training optimization for mobile CPUs, dataset composition, evaluation methodology, checkpoint comparisons, and future roadmap.

<br>

---

<br>

<div align="center">

## Community

</div>

<br>

Join the Yuuki community to discuss the project, share results, contribute ideas, and connect with other developers interested in democratizing AI training.

<br>

<div align="center">

[![Reddit](https://img.shields.io/badge/Reddit-r%2Fyuuki__omg-FF4500?style=for-the-badge&logo=reddit&logoColor=white)](https://www.reddit.com/r/yuuki_omg)
&nbsp;&nbsp;
[![Discord](https://img.shields.io/badge/Discord-Join_Server-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/Mh2gvBdn4)

</div>

<br>

---

<br>

<div align="center">

## Design Philosophy

</div>

<br>

<table>
<tr>
<td width="50%" valign="top">

**Accessibility First**

AI training shouldn't require a PhD, a lab, or a six-figure cloud bill. Yuuki proves that meaningful contributions to open-source AI can come from anyone with a consumer device and determination.

<br>

**Radical Transparency**

Every training step, every checkpoint, every mistake is documented and shared publicly. The goal isn't just to build a model -- it's to show others that they can do it too.

</td>
<td width="50%" valign="top">

**Zero-Budget Innovation**

By embracing extreme hardware constraints, Yuuki explores training techniques that work on edge devices. These optimizations benefit everyone -- from hobbyists to enterprises looking to reduce costs.

<br>

**Community-Driven**

Yuuki belongs to the community. Whether you contribute code, share ideas, report bugs, or just star the repos -- you're part of this journey.

</td>
</tr>
</table>

<br>

---

<br>

<div align="center">

## Tech Stack

</div>

<br>

### Core Technologies

| Category | Technologies |
|:---------|:-------------|
| **Model Training** | Python, PyTorch, Transformers, GPT-2 architecture |
| **CLI Tools** | Rust, Tokio, Clap, Ratatui, HuggingFace Hub |
| **Web Apps** | Next.js 16, React 19, TypeScript, Tailwind CSS v4 |
| **APIs** | HuggingFace Inference API, Tavily Search, YouTube Data API v3 |
| **Deployment** | Vercel, HuggingFace Spaces |
| **Design** | Dark cyberpunk aesthetic, sakura pink (#f472b6) accents, Geist font |

<br>

---

<br>

<div align="center">

## Statistics

</div>

<br>

<div align="center">

![Training Device](https://img.shields.io/badge/Training_Device-Redmi_12-000000?style=for-the-badge&logo=xiaomi&logoColor=white)
&nbsp;
![Processor](https://img.shields.io/badge/Processor-Snapdragon_685-000000?style=for-the-badge&logo=qualcomm&logoColor=white)
&nbsp;
![Budget](https://img.shields.io/badge/Budget-%240.00-000000?style=for-the-badge&logo=cashapp&logoColor=white)

<br>

![Parameters](https://img.shields.io/badge/Parameters-89M-f472b6?style=for-the-badge)
&nbsp;
![Training Steps](https://img.shields.io/badge/Steps-11900%2F37500-f472b6?style=for-the-badge)
&nbsp;
![Progress](https://img.shields.io/badge/Progress-31.73%%25-f472b6?style=for-the-badge)

<br>

![License](https://img.shields.io/badge/License-MIT-222222?style=flat-square&logo=opensourceinitiative&logoColor=white)
&nbsp;
![HuggingFace](https://img.shields.io/badge/HuggingFace-YuuKi--OS-222222?style=flat-square&logo=huggingface&logoColor=white)
&nbsp;
![GitHub Org](https://img.shields.io/badge/GitHub-YuuKi--OS-222222?style=flat-square&logo=github&logoColor=white)

</div>

<br>

---

<br>

<div align="center">

## Support the Project

</div>

<br>

Yuuki is a zero-budget project built by an independent developer. If you find value in this work and want to support continued development, training, and community building, consider sponsoring:

<br>

<div align="center">

[![GitHub Sponsors](https://img.shields.io/badge/Sponsor_on-GitHub_Sponsors-ea4aaa?style=for-the-badge&logo=githubsponsors&logoColor=white)](https://github.com/sponsors/aguitauwu)

<br>

*Every contribution helps keep the phone charged and the training running.*

</div>

<br>

---

<br>

<div align="center">

## Quick Links

</div>

<br>

<div align="center">

### Model & Demo

[![Model Weights](https://img.shields.io/badge/Yuuki--best-Hugging_Face-ffd21e?style=for-the-badge&logo=huggingface&logoColor=black)](https://huggingface.co/OpceanAI/Yuuki-best)
&nbsp;
[![Live Demo](https://img.shields.io/badge/Try_Demo-Spaces-ffd21e?style=for-the-badge&logo=huggingface&logoColor=black)](https://huggingface.co/spaces/OpceanAI/Yuuki)

<br>

### Web Apps

[![Yuuki Chat](https://img.shields.io/badge/Yuuki_Chat-Web_App-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://yuuki-chat.vercel.app)
&nbsp;
[![Yuuki Web](https://img.shields.io/badge/Yuuki_Web-Landing_Page-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://yuuki-web.vercel.app)

<br>

### CLI Tools

[![yuy](https://img.shields.io/badge/yuy-CLI_Tool-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/YuuKi-OS/yuy)
&nbsp;
[![yuy-chat](https://img.shields.io/badge/yuy--chat-TUI_Chat-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/YuuKi-OS/yuy-chat)

<br>

### Community

[![Reddit](https://img.shields.io/badge/r%2Fyuuki__omg-Reddit-FF4500?style=for-the-badge&logo=reddit&logoColor=white)](https://www.reddit.com/r/yuuki_omg)
&nbsp;
[![Discord](https://img.shields.io/badge/Join-Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/Mh2gvBdn4)
&nbsp;
[![Paper](https://img.shields.io/badge/Read-Paper-4285F4?style=for-the-badge&logo=googledrive&logoColor=white)](https://drive.google.com/drive/folders/1IVoaI_FdNBxWGH-zBsnG24Gc5hIxKc4A)

</div>

<br>

---

<br>

<div align="center">

## The Story Behind Yuuki

</div>

<br>

**Yuuki** started out of necessity. In January 2026, agua_omg -- a young developer -- could no longer afford Claude API subscriptions. But instead of giving up on AI entirely, they asked a different question: *What if I could train my own model with nothing but the phone in my pocket?*

The name "Yuuki" is a fusion of two inspirations:

1. **雪 (Yuki)** -- Japanese for "snow", representing purity and the cold reality of having zero budget
2. **ユー (Yuu)** -- The character from *Girls' Last Tour*, an anime about survival in a post-apocalyptic world with minimal resources

Together, they form **勇気 (Yuuki)** -- *courage* -- which perfectly captures the audacity of training a language model on a smartphone.

The training happens on a **Redmi 12** with a Snapdragon 685 processor, running pure CPU inference with no GPU acceleration. Each training step takes seconds. Each epoch takes hours. The phone gets warm. The progress is slow. But it's working.

Yuuki is proof that innovation doesn't require money -- it requires persistence, creativity, and a willingness to try the impossible.

<br>

---

<br>

<div align="center">

**Built with patience, a phone, and zero budget.**

<br>

[![Yuuki Project](https://img.shields.io/badge/Yuuki_Project-2026-000000?style=for-the-badge)](https://huggingface.co/OpceanAI)

<br>

*Training the future of AI, one step at a time.*

</div>

