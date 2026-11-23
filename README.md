# Hi, I'm Kaio Lima 👋

<div align="center">

[![GitHub followers](https://img.shields.io/github/followers/Kaio-Comk?label=Follow&style=social)](https://github.com/Kaio-Comk)
[![GitHub stars](https://img.shields.io/github/stars/Kaio-Comk?style=social)](https://github.com/Kaio-Comk)

**Systems Engineer • Autonomous Multi-Agent Orchestration • High-Performance Async Architectures**  
*Building sovereign local AI tools, deterministic runtime guardrails, and privacy-first software.*

</div>

---

### 🚀 About Me

I focus on building developer tools, autonomous agent systems, and resilient backend pipelines that run fast, deterministically, and privately:

* 🧠 **Sovereign Local AI:** Orchestrating local LLMs (Ollama) on consumer hardware with zero data leakage to cloud APIs.
* ⚡ **Async & Concurrency:** High-throughput streaming, non-blocking asynchronous architectures, and zero-broker queues with PostgreSQL (`SKIP LOCKED`).
* 📱 **Native Mobile:** Privacy-first, 100% offline-native Android apps built with modern Scoped Storage and Room.
* 🛡️ **Defensive Engineering:** Pure AST static inspection for Python (stopping event-loop freezes before CI), atomic disk operations, and non-destructive data recovery.

---

### 🌟 Featured Flagship Projects

<table>
  <tr>
    <td width="50%">
      <h3 align="center">👑 <a href="https://github.com/Kaio-Comk/Hera-Multiagent">HERA Multiagent</a></h3>
      <p align="center">
        <b>Sovereign Local AI Orchestrator for Windows</b>
      </p>
      <p>Connects, routes, and orchestrates Ollama, Claude Code CLI, and Antigravity with DAG scheduling, isolated Git Worktrees, SQLite WAL state, and pre-flight DLP guardrails.</p>
      <p align="center">
        <code>Python 3.12</code> • <code>FastAPI</code> • <code>DAG</code> • <code>SQLite WAL</code> • <code>MCP</code>
      </p>
    </td>
    <td width="50%">
      <h3 align="center">📱 <a href="https://github.com/Kaio-Comk/Argos-Android">Argos-Android</a></h3>
      <p align="center">
        <b>Privacy-First Duplicate Cleaner for Android</b>
      </p>
      <p>100% offline native cleaner with zero network permissions. Byte-exact local scanning, non-blocking streaming checksums, and native Android trash recovery.</p>
      <p align="center">
        <code>Kotlin</code> • <code>Jetpack</code> • <code>Room DB</code> • <code>MediaStore</code> • <code>Offline</code>
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%">
      <h3 align="center">🛠️ <a href="https://github.com/Kaio-Comk/Disk-Rescue">Disk-Rescue</a></h3>
      <p align="center">
        <b>Deep Diagnostic & Filesystem Recovery Suite</b>
      </p>
      <p>Autonomous hardware SMART diagnosis, non-destructive GPT/MBR partition table recalculation (CRC32), and surgical NTFS/FAT boot sector repair.</p>
      <p align="center">
        <code>Python</code> • <code>GPT / MBR</code> • <code>NTFS Parser</code> • <code>SMART</code> • <code>Pytest</code>
      </p>
    </td>
    <td width="50%">
      <h3 align="center">🛡️ <a href="https://github.com/Kaio-Comk/Cerberus-Gates">Cerberus-Gates</a></h3>
      <p align="center">
        <b>AST Static Regression Gates for Python</b>
      </p>
      <p>Zero-execution AST quality gates. Catches event-loop freezes (blocking calls in async def), swallowed cancellations, and silent exceptions before production.</p>
      <p align="center">
        <code>Python</code> • <code>AST</code> • <code>Static Analysis</code> • <code>CI/CD Gate</code>
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%">
      <h3 align="center">🐘 <a href="https://github.com/Kaio-Comk/Talos-Queue">Talos-Queue</a></h3>
      <p align="center">
        <b>Durable Job Queue for PostgreSQL & Supabase</b>
      </p>
      <p>Eliminates Redis/Celery complexity. Non-blocking parallel worker claims via <code>FOR UPDATE SKIP LOCKED</code>, atomic leases, crash recovery, and deduplication.</p>
      <p align="center">
        <code>PostgreSQL</code> • <code>SKIP LOCKED</code> • <code>Supabase</code> • <code>Zero Redis</code>
      </p>
    </td>
    <td width="50%">
      <h3 align="center">🔊 <a href="https://github.com/Kaio-Comk/Orpheus-Audio">Orpheus-Audio</a></h3>
      <p align="center">
        <b>Fast Async Video Audio Repair & Remuxing</b>
      </p>
      <p>Transcodes incompatible audio (AC3/DTS to AAC) for Chrome, Safari & Chromecast in seconds via stream copy (<code>-c:v copy</code>) with 100% lossless video.</p>
      <p align="center">
        <code>Python</code> • <code>FFmpeg</code> • <code>AsyncIO</code> • <code>Lossless Stream-Copy</code>
      </p>
    </td>
  </tr>
</table>

---

### 📦 Specialized Open-Source Libraries & Utilities

Production-ready standalone modules and tools extracted from high-scale systems:

| Category | Repository | Description | Highlights |
|---|---|---|---|
| **Media & Streaming** | 🎵 [**Intro-Skipper**](https://github.com/Kaio-Comk/Intro-Skipper) | Acoustic fingerprint TV intro & credits detector | Chromaprint • NumPy popcount • Bitwise XOR |
| | 📝 [**Subtitle-Forge**](https://github.com/Kaio-Comk/Subtitle-Forge) | Broadcast-grade subtitle formatter (strict 42 chars / 2 lines) | WebVTT • SRT • Broadcast Standard |
| | 👥 [**Watch-Together-Core**](https://github.com/Kaio-Comk/Watch-Together-Core) | Synchronized playback rooms: shared position extrapolation and host handoff (bring your own WebSocket) | Python • State Extrapolation • Host Handoff |
| | ⚡ [**Tiered-Storage-Cache**](https://github.com/Kaio-Comk/Tiered-Storage-Cache) | Two-tier (SSD+HDD) LRU cache with active stream backpressure | Python • LRU Cache • Backpressure Throttle |
| | ⚡ [**Hermes-Telegram**](https://github.com/Kaio-Comk/Hermes-Telegram) | High-performance chunked parallel MTProto downloader | Telethon • Session Pool • FloodWait Backoff |
| **AI & Commerce** | 🤖 [**AI-Support-Agent**](https://github.com/Kaio-Comk/AI-Support-Agent) | Deterministic support building blocks: regex fast-path, debounce & HITL silence (pair with your local LLM) | Python • Fast-Path • HITL Guardrails • Zero-Dependency |
| | 💳 [**Payment-Resilience**](https://github.com/Kaio-Comk/Payment-Resilience) | Multi-gateway router with 3-state Circuit Breaker & failover | Python • Circuit Breaker • Zero-Dependency |
| | 🌍 [**Geo-Pricing**](https://github.com/Kaio-Comk/Geo-Pricing) | Country-based localized pricing (BRL / EUR / ARS / USD); PPP and GeoIP on the roadmap | Python • Multi-Currency • Zero-Dependency |
| **Search & DevOps** | 🔎 [**Pythia-Search**](https://github.com/Kaio-Comk/Pythia-Search) | Forgiving title search for media catalogs (accents, typos, years) | Python • pg_trgm Candidates • In-Memory Ranking |
| | ⚙️ [**Hephaestus-Services**](https://github.com/Kaio-Comk/Hephaestus-Services) | Declarative Windows service orchestration with NSSM & PowerShell | PowerShell • NSSM • Online Log Rotation |
| | 🔍 [**Argos-Cleaner**](https://github.com/Kaio-Comk/Argos-Cleaner) | Fast desktop duplicate cleaner + Google Takeout metadata fixer | Python • BLAKE3 • Perceptual dHash • GUI |

---

### 🧰 Tech Stack & Ecosystem

```text
Languages:    Python (AsyncIO), Kotlin, PowerShell, Bash, SQL, TypeScript/JavaScript
Core Engines: Local LLMs (Ollama), FFmpeg, Git Worktrees, Pure AST, Android SDK
Persistence:  PostgreSQL (SKIP LOCKED, Trigram), Supabase, SQLite WAL, Room
Orchestration:FastAPI, DAG Toposort, NSSM Windows Services, GitHub Actions CI/CD
Security:     Data Loss Prevention (DLP), Scoped Storage, Subprocess Sandboxing (shell=False)
```

---

<div align="center">
  <sub>Engineered with precision. All open-source tools are designed to solve concrete problems with zero unnecessary dependencies.</sub>
</div>
