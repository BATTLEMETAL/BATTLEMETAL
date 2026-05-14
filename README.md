# Hi, I'm Michał 👋

**Python & AI Engineer** — I build autonomous systems that work in production, not just in demos.

---

## 📊 By the Numbers

| Metric | Value |
|---|---|
| 🎬 YouTube views generated autonomously | **18,049+** |
| 📹 Videos published without human intervention | **95+** |
| 📅 Pipeline active days (no human intervention) | **73+** |
| 🧪 Unit tests across production systems | **38** |
| 💾 VRAM reduction via custom Windows patches | **−68%** (14.2 GB → 4.5 GB) |
| 🤖 Specialized AI agents in Synapsa | **7** |
| 💰 Cost per AI-generated video | **$0** (100% local LLM) |


---

## 🧠 Synapsa — Autonomous Local LLM Agent System

Multi-agent AI platform running **Qwen 2.5 7B** fully offline. The technically unique part: a custom Triton compatibility layer that makes NF4 quantization work on Windows where no upstream solution exists. Features a self-healing "Ultimate Auditor" loop, teacher-student LoRA fine-tuning pipeline, FastAPI REST layer, and 38 unit tests.

`Python` · `PyTorch` · `Transformers` · `PEFT/LoRA` · `bitsandbytes` · `FastAPI` · `Streamlit` · `Docker` · `pytest`

→ [Synapsa-Local-LLM-Agent](https://github.com/BATTLEMETAL/Synapsa-Local-LLM-Agent)

---

## 📹 Shortsyt — Autonomous YouTube Shorts Factory

Production pipeline running daily since March 2026. Researches trends, generates scripts via local LLM (Qwen 2.5), audits quality through an 8-dimensional NLP scorer, renders TTS video with FFmpeg, and auto-publishes via YouTube Data API v3. Includes a **MicroEVS** real-time adaptation engine that mutates its own generation prompts based on live view velocity scores — proven 6.8× performance gap between algorithmically detected title formats.

`Python` · `Edge-TTS` · `Whisper` · `MoviePy` · `FFmpeg` · `YouTube API` · `sklearn` · `subprocess IPC`

→ [Shortsyt](https://github.com/BATTLEMETAL/Shortsyt)

---

## 📊 SalesBot — AI-Powered Sales Report Pipeline

Excel → pandas aggregation → **OpenAI GPT-4o-mini executive summary** → matplotlib charts → ReportLab PDF. Clean modular architecture, 12 pytest unit tests across 3 test classes, GitHub Actions CI on every push. AI summary falls back to rule-based analysis in CI (no API key needed).

`Python` · `pandas` · `OpenAI API` · `matplotlib` · `ReportLab` · `pytest` · `GitHub Actions`

→ [SalesBot](https://github.com/BATTLEMETAL/SalesBot)

---

## 📱 Android Projects

**CineMatch** — Movie/TV recommendation app with TMDB API + OpenAI personalization + OMDB ratings. Firebase Auth, Room DB, Retrofit, Glide, MVVM. SDK 35.

**SmartBudget-OCR** — Budget manager with ML Kit OCR receipt scanning, Firebase Auth, financial analytics. B.Eng. thesis project.

**TimePal** — AI-powered task manager with GPT-4 task decomposition, lifecycle-aware Focus Engine (Normal/Pressure/Hardcore modes), Room DB with async Executor pattern (no ANR). Secret management via BuildConfig — API keys never hardcoded.


`Kotlin` · `Java` · `Android SDK 35` · `Firebase` · `ML Kit` · `Room` · `Retrofit` · `OpenAI API` · `TMDB API`

---

📧 mz10062001@gmail.com | 📍 Poland / Remote EU

*All metrics are live and verified from production systems.*
