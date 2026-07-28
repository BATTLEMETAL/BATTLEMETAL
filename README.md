# Michał Zalewski — AI / Python Engineer

Building autonomous AI systems and production-ready APIs.

---

### 🧠 [Synapsa-Local-LLM-Agent](https://github.com/BATTLEMETAL/Synapsa-Local-LLM-Agent) — Offline AI Agent Platform

Qwen 2.5 7B · NF4 Quantization · Custom Triton Patches · RTX 3060

Autonomous multi-agent system running 100% offline. Solves the "Triton on Windows" problem with a custom CUDA compatibility layer — reducing VRAM from 14.2 GB → 4.5 GB (−68%) without losing inference quality.

**Domain:** Automated document auditing (VAT invoice validation — KSeF 2026 compliance, MPP threshold detection, NIP format checks)

```
⚡ −68% VRAM | ✅ 100% Offline (GDPR-safe) | 🧪 38 unit tests | $0 API cost
```

---

### ☁️ [Synapsa Cloud API](https://github.com/BATTLEMETAL/synapsa-cloud-api) — Production REST API

FastAPI · Pinecone RAG · Groq Llama 3.3 70B · Docker · Railway.app

Cloud-native version of Synapsa — serverless VAT invoice audit API with RAG pipeline, rate-limit fallbacks, and production deployment.

```
🚀 Live on Railway.app | 🔍 Pinecone Vector DB | 🤖 Llama 3.3 70B
```

---

### 📺 [Shortsyt](https://github.com/BATTLEMETAL/Shortsyt) — Autonomous YouTube Shorts Pipeline

95 videos published · 18,049 views · $0/video · 0 human interventions · 73+ days autonomous operation

Full pipeline: LLM script generation → TTS narration → Whisper subtitles → FFmpeg render → YouTube API publish.
Self-optimizes via MicroEVS — reads live YouTube Analytics and mutates its own prompts based on real performance data.

```
📊 18,049 views | 🎬 95 videos | 💰 $0/video | 🤖 Fully autonomous
```

---

### 📦 Other Projects

- [SalesBot](https://github.com/BATTLEMETAL/SalesBot) — Excel → PDF sales report pipeline (pandas, matplotlib, pytest CI)
- [CineMatch](https://github.com/BATTLEMETAL/CineMatch) — Android movie recommendation app (TMDB + OpenAI + Firebase + Room DB)
- [SmartBudget-OCR](https://github.com/BATTLEMETAL/SmartBudget-OCR) — Android budget manager with ML Kit OCR (B.Eng. thesis)
- [TimePal](https://github.com/BATTLEMETAL/TimePal) — Android time tracking app (MVVM · WorkManager · OpenAI)

---

## 🛠️ Core Stack

```
AI/LLM     │ Qwen 2.5 7B · NF4/QLoRA · Unsloth · bitsandbytes · RAG (Pinecone, ChromaDB)
Frameworks │ Python · FastAPI · Streamlit · custom agentic orchestration
Video      │ FFmpeg · MoviePy · OpenAI Whisper · edge-tts
Mobile     │ Android (Java) · Room · Retrofit · ML Kit OCR · Firebase
MLOps      │ pytest · GitHub Actions CI/CD · Docker · pre-commit
```
