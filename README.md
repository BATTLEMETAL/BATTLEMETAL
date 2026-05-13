<div align="center">

# Michał Zalewski — AI/Python Engineer

**Building production AI systems that run offline, cost $0 to operate, and serve real paying clients.**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/michał-zalewski-46476138a)
[![GitHub followers](https://img.shields.io/github/followers/BATTLEMETAL?style=for-the-badge&color=333)](https://github.com/BATTLEMETAL)

</div>

---

## 🏭 Production Systems (Live)

### 🧠 [Synapsa-Local-LLM-Agent](https://github.com/BATTLEMETAL/Synapsa-Local-LLM-Agent) — Offline AI Agent Platform

> **Qwen 2.5 7B · NF4 Quantization · Custom Triton Patches · RTX 3060**

Autonomous multi-agent system running 100% offline. Solves the "Triton on Windows" problem with a custom compatibility layer — reducing VRAM from 14.2 GB → 4.5 GB (**−68%**) without losing inference quality.

- 📋 Accounting office: daily VAT invoice auditing (KSeF 2026 compliance, MPP threshold detection)
- 🏗️ Construction company: natural language → cost estimate → VAT invoice

```
⚡ −68% VRAM   |   ✅ 100% Offline (GDPR)   |   🧪 38 unit tests   |   $0 API cost
```

---

### 📺 [Shortsyt](https://github.com/BATTLEMETAL/Shortsyt) — Autonomous YouTube Shorts Pipeline

> **95 videos published · 18,049 views · $0/video · 0 human interventions · 58+ days running**

Full pipeline: LLM script generation → TTS narration → Whisper subtitles → FFmpeg render → YouTube API publish. Self-optimizes via **MicroEVS** — reads live YouTube Analytics and mutates its own prompts based on performance data.

```
📊 18,049 views   |   🎬 95 videos   |   💰 $0/video   |   🤖 Fully autonomous
```

---

## 📦 Other Projects

| Project | What it does | Tech |
|---|---|---|
| [SalesBot](https://github.com/BATTLEMETAL/SalesBot) | Excel → AI executive summary → PDF report | Python, GPT-4o-mini, ReportLab |
| [SmartBudget-OCR](https://github.com/BATTLEMETAL/SmartBudget-OCR) | Android budget app with OCR receipt scanning *(Engineering Thesis)* | Java, Android, ML Kit |
| [TimePal](https://github.com/BATTLEMETAL/TimePal) | AI task manager with GPT integration | Java, Android, OpenAI API |

---

## 🛠️ Core Stack

```
AI/LLM      │ Qwen 2.5 7B · NF4/QLoRA quantization · Unsloth · bitsandbytes · RAG (ChromaDB)
Frameworks  │ Python · FastAPI · Streamlit · custom agentic orchestration
Video/Media │ FFmpeg · MoviePy · OpenAI Whisper · edge-tts
Mobile      │ Android (Java) · Room · Retrofit · ML Kit OCR
MLOps       │ pytest · GitHub Actions CI/CD · Docker · pre-commit
```

---

## 📊 What separates my work from tutorials

| Claim | Proof |
|---|---|
| **Production systems, not demos** | 1 paying B2B client (Synapsa, daily use) + autonomous YouTube pipeline live since March 2026 |
| **Solved unsolved problems** | Triton on Windows — no upstream fix exists, I patched it |
| **Real metrics** | 18,049 YouTube views, 95 videos, $0/video — verified YouTube Analytics API |
| **CI/CD discipline** | 38 unit tests, GitHub Actions on every push |
| **Cost-aware engineering** | Entire AI stack: $0/inference, $0/video, offline-first |

---

<div align="center">
<sub>📍 Poland · Open to remote AI/Python Engineering roles</sub>
</div>
