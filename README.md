<div align="center">

# Michał Zalewski — AI & Python Systems Engineer

**Building production local-GPU AI systems, Computer Vision pipelines, and native Desktop Studios that run on consumer hardware at $0 cloud inference cost.**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/micha%C5%82-zalewski-46476138a)
[![Tests](https://img.shields.io/badge/Tests-480%2B%20Passed%20(pytest)-2EA44F?style=for-the-badge)](https://github.com/BATTLEMETAL/Shortsyt/actions/workflows/ci.yml)
[![Production Views](https://img.shields.io/badge/YouTube-515K%2B%20Views-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/@dwannellenga471/shorts)
[![Local LLM](https://img.shields.io/badge/Local%20AI-Qwen%202.5%207B%20QLoRA-8A2BE2?style=for-the-badge)](https://github.com/BATTLEMETAL/Synapsa-Local-LLM-Agent)

</div>

---

## 🏭 Flagship Production Systems

### 🎬 [Flikcut Studio (Shortsyt)](https://github.com/BATTLEMETAL/Shortsyt) — Autonomous Local-GPU Video & Publishing Engine

> **Synapsa Qwen2.5-7B-4bit QLoRA v2 · OpenCV + FFmpeg NVENC · Binary LevelDB V8 Parser · FastAPI + SQLite WAL · Electron 32 + React 18**

End-to-end video engineering, telemetry calibration, and 4-platform distribution system running locally on an **RTX 3060 (12 GB VRAM)**:
- **Local LLM Engine (`Synapsa QLoRA v2`):** Fine-tuned **Qwen2.5-7B-4bit** replaces paid cloud APIs for hook generation, pinned comments, multi-platform copywriting, and watchability defect prediction (`eval 68.33 → 100.0`, `$0` cloud cost).
- **Binary Outplayed LevelDB / V8 Parser (`outplayed_db.py`):** Custom zero-dependency decoder reading raw Chromium IndexedDB `.log` wire records to anchor kill events and match K/D/A directly from gameplay telemetry.
- **Smart Camera, Unified Timeline & Defect Gate:** 1080p HP-bar tracking + NVENC 60FPS rendering (`9:16` Shorts & `16:9` compilations via zero-byte NTFS `Viral Vault` hardlinks) guarded by explicit failure assertions (`offscreen`, `camera_jump > 220px`, `intro > 3.5s`) instead of opaque heuristic scores.
- **48h Reality Gate & Empirical Bayes Learning:** Reconciles live YouTube Data & Analytics API retention (`213` verified videos, `66.2% FIT_CONFIRMED`) back into median-shrunk format weights and duration bounds.
- **Concurrent Storage & DFY Niche Engine:** Multi-network scheduling (`YouTube`, `TikTok Direct Post`, `Instagram`, `Facebook`) protected by `SQLite WAL` + OS file locks (`msvcrt`/`fcntl`), plus autonomous DFY niche analysis with strict anti-plagiarism gating (`<= 0.35`).

📺 **Live Production Channel & Recent Hits:** [Dwannellenga (@dwannellenga471)](https://www.youtube.com/@dwannellenga471/shorts) · [Recent 7K+ Viral Triple Kill](https://www.youtube.com/shorts/4Fyn2vIfQv8) · [Katarina Engage Lead](https://www.youtube.com/shorts/POgSCGC9yvQ) · [1v5 Chase Speedup](https://www.youtube.com/shorts/cVTTQASHe9w)

```text
📊 515K+ Views (230+ Shorts) | 🎯 97.4% Avg % Viewed · 17.3% Swiped Away | 🧪 430 pytest CI Tests | 💰 $0 API Cost
```

---

### 🧠 [Synapsa-Local-LLM-Agent](https://github.com/BATTLEMETAL/Synapsa-Local-LLM-Agent) — Offline Multi-Agent AI Platform

> **Qwen 2.5 7B · NF4 Quantization · Custom Windows Triton Patches · ChromaDB RAG · RTX 3060**

Modular autonomous agent architecture running **100% offline** for GDPR-safe document auditing (Polish VAT validation — KSeF 2026, MPP threshold detection, NIP verification) and self-healing code execution (`generate → execute → read traceback → patch`):
- **Custom CUDA / Triton Windows Layer:** Resolves Windows `bitsandbytes`/Triton compatibility without WSL while cutting VRAM footprint from **14.2 GB → 4.5 GB (−68%)**.
- **Teacher–Student Fine-Tuning Pipeline:** Synthesizes verified reasoning traces into **Unsloth LoRA (r=16)** adapters later deployed inside **Flikcut Studio**.

```text
⚡ −68% VRAM (14.2 GB → 4.5 GB) | ✅ 100% Offline (GDPR-safe) | 🧪 38 unit tests CI | 🔒 Zero External Calls
```

---

### ☁️ [Synapsa Cloud API](https://github.com/BATTLEMETAL/synapsa-cloud-api) — Production Serverless RAG API

> **FastAPI · Pinecone Vector DB · Groq Llama 3.3 70B · Docker · Render.com**

Cloud-native companion exposing Synapsa's document validation and RAG pipeline as a containerized REST API with rate-limit fallback chains and interactive [Swagger UI Live Demo](https://synapsa-cloud-api.onrender.com/docs).

---

## 📦 Engineering & Mobile Portfolio

- **[SalesBot](https://github.com/BATTLEMETAL/SalesBot)** — Automated Excel → PDF reporting pipeline (`pandas`, `matplotlib`, `ReportLab`, `OpenAI GPT-4o-mini` with rule-based CI fallback, `12` passing `pytest` tests on GitHub Actions).
- **[CineMatch](https://github.com/BATTLEMETAL/CineMatch)** — Android movie & TV advisor in **Kotlin / MVVM** (`TMDB` + `OMDB` + `OpenAI GPT-4`, `Firebase Auth/Firestore`, `Room DB`).
- **[SmartBudget-OCR](https://github.com/BATTLEMETAL/SmartBudget-OCR)** — B.Eng. thesis Android budget manager in **Kotlin / Jetpack Compose** with real-time **Google ML Kit OCR** receipt scanning and `Room DB`.
- **[TimePal](https://github.com/BATTLEMETAL/TimePal)** — Android productivity & focus engine (`Java`, `MVVM`, `Room`, `WorkManager`, `MPAndroidChart`, offline task heuristics).

---

## 🛠️ Core Technical Stack

```text
AI & Fine-Tuning │ Qwen 2.5 7B (NF4 / QLoRA) · Unsloth · PEFT · ChromaDB · Pinecone · Groq Llama 3.3 70B
Computer Vision  │ OpenCV (HP-bar tracking, spatial exclusion) · Tesseract OCR · Google ML Kit OCR
Backend & Data   │ Python 3.13 · FastAPI · SQLite WAL · OS File Locking (msvcrt/fcntl) · Binary LevelDB V8 Parser · Empirical Bayes
Video & Audio    │ FFmpeg (NVENC, 9:16 smart pan, 1080p60 long-form) · Beat-sync & sidechain ducking · Hardlink Viral Vault
Desktop & Mobile │ Electron 32 · React 18 · TypeScript · TailwindCSS · Kotlin · Jetpack Compose · Java · Room
Testing & DevOps │ pytest (480+ tests across CI) · GitHub Actions CI/CD · Docker · pre-commit · GitHub Pages
```

---

## 📊 What Separates My Work From Tutorials

| Engineering Area | Production Evidence |
|---|---|
| **Real-World Production Scale** | Live YouTube Shorts channel (`230+` automated videos, `515K+` views, `97.4%` avg percentage viewed) + live [Swagger API](https://synapsa-cloud-api.onrender.com/docs) |
| **Low-Level Systems Engineering** | Binary Chromium IndexedDB/V8 `.log` wire decoder (`outplayed_db.py`), Windows Triton kernel patches, `SQLite WAL` + OS lock concurrency |
| **Honest Telemetry & QA** | Backtested `Quality Scorer` (`r = -0.079` on `94` clips) → replaced guesswork with explicit defect gates and **48h Reality Gate** (`213` clips audited, `66.2%` confirmed) |
| **Full-Stack Delivery** | End-to-end ownership from Python/CUDA GPU inference & FastAPI (`:8765`) to native Electron 32 / React / TypeScript Desktop Studio |
| **Test Discipline** | **430** passing unit/integration tests in `Shortsyt` + **38** in `Synapsa` + **12** in `SalesBot` verified in GitHub Actions CI |

---

<div align="center">
<sub>📍 Wrocław, Poland · Open to AI Engineer / Python Backend / Computer Vision roles</sub>
</div>
