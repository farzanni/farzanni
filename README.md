<div align="center">

# Hi, I'm Farzan 👋
### Software Engineer · Autonomous AI Systems & Full-Stack Builder

<p align="center">
  <a href="https://github.com/farzanni"><img src="https://img.shields.io/badge/Focus-Autonomous_AI_Agents-6366F1?style=flat-square&logo=openai&logoColor=white" alt="Focus: Autonomous AI Agents" /></a>
  <a href="https://github.com/farzanni"><img src="https://img.shields.io/badge/Vision-OpenCV_5_%26_AWS_Bedrock-FF9900?style=flat-square&logo=amazon-aws&logoColor=white" alt="Vision: OpenCV & AWS Bedrock" /></a>
  <a href="https://github.com/farzanni"><img src="https://img.shields.io/badge/Stack-Next.js_15_%26_Python-000000?style=flat-square&logo=next.js&logoColor=white" alt="Stack: Next.js & Python" /></a>
  <a href="https://github.com/farzanni"><img src="https://img.shields.io/badge/Evaluation-Brier_Score_%26_Evals-059669?style=flat-square&logo=speedtest&logoColor=white" alt="Evaluation: Brier Score & Evals" /></a>
  <a href="https://github.com/farzanni"><img src="https://img.shields.io/badge/Shipping-In_Public-10B981?style=flat-square&logo=rocket&logoColor=white" alt="Shipping in Public" /></a>
</p>

<p align="center">
  <em>Designing autonomous agentic architectures, real-time spatial computer vision, and resilient full-stack platforms.</em><br />
  <em>Hypothesis-driven engineering · Tight feedback loops · Empirical evaluation · Production-grade code.</em>
</p>

</div>

---

### ⚡ Engineering Focus & Architecture

I build systems where **probabilistic AI meets deterministic execution and measurement**. My work centers on autonomous multi-step reasoning, real-time spatial perception, disciplined LLM evaluation harnesses, and high-performance web applications.

```mermaid
flowchart LR
    subgraph Perception["1. Perception & Ingestion"]
        direction TB
        CV[Spatial Vision: OpenCV 5]
        Stream[Video Feeds / APIs / Webhooks]
        CV --- Stream
    end

    subgraph Reasoning["2. Agentic Reasoning"]
        direction TB
        LLM[AWS Bedrock / Claude / Multimodal]
        Audit[AgentReflex: Ambiguity & Error Guard]
        LLM --- Audit
    end

    subgraph Action["3. Deterministic Execution"]
        direction TB
        Tool[PLC Interlocks & SMS Relays]
        Web[Next.js 15 & FastAPI Systems]
        Tool --- Web
    end

    subgraph Evaluation["4. Empirical Evals"]
        direction TB
        Brier[Brier Score Calibration Loop]
        Evals[Agent Lab: Multi-Step Benchmarks]
        Brier --- Evals
    end

    Perception --> Reasoning
    Reasoning --> Action
    Action --> Evaluation
    Evaluation -.->|Calibration Feedback| Reasoning

    classDef primary fill:#1e1e2e,stroke:#6366f1,stroke-width:2px,color:#cdd6f4;
    class Perception,Reasoning,Action,Evaluation primary;
```

---

### 🚀 Featured Systems & Projects

| Project | Highlights & Capabilities | Stack | Stage |
|---|---|---|---|
| 🛡️ [**SafeSight AI**](https://github.com/farzanni/safesight-ai) | **Autonomous Physical Site Safety Supervisor Agent**<br />Pairs OpenCV 5 edge spatial tracking with AWS Bedrock multimodal tool reasoning. Monitors exclusion zones, verifies OSHA mandates in real time, and executes automated PLC interlocks. | ![OpenCV](https://img.shields.io/badge/OpenCV_5-5C3EE8?style=flat-square&logo=opencv&logoColor=white) ![AWS Bedrock](https://img.shields.io/badge/AWS_Bedrock-FF9900?style=flat-square&logo=amazon-aws&logoColor=white) ![Python](https://img.shields.io/badge/Python_3.12-3776AB?style=flat-square&logo=python&logoColor=white) ![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white) | `OpenCV AI 2026` |
| ⚡ [**AgentReflex**](https://github.com/farzanni/agent-reflex) | **Prompt & Spec Diagnostic Workbench for Coding Agents**<br />Interactive diagnostic auditor stress-testing coding agent specifications across error boundaries, schema ambiguity, and security traps before dispatching tasks. | ![JavaScript](https://img.shields.io/badge/JavaScript_ES6+-F7DF1E?style=flat-square&logo=javascript&logoColor=black) ![Claude Code](https://img.shields.io/badge/Claude_Code-D97706?style=flat-square&logo=anthropic&logoColor=white) ![Zero-Dep](https://img.shields.io/badge/Zero--Dep-10B981?style=flat-square) | `Devpost Learn` |
| 💈 [**BrbiTime**](https://github.com/farzanni/brbitime) · [🔴 Live: muucut.ir](https://muucut.ir) | **Real-Time Salon Scheduling & Operations Platform**<br />High-throughput appointment booking platform with atomic slot locking, instant SMS alerts via Kavenegar, automated reminder crons, and an HMAC-authenticated business analytics dashboard. | ![Next.js](https://img.shields.io/badge/Next.js_15-000000?style=flat-square&logo=next.js&logoColor=white) ![React](https://img.shields.io/badge/React_19-20232A?style=flat-square&logo=react&logoColor=61DAFB) ![Tailwind](https://img.shields.io/badge/Tailwind_4-38BDF8?style=flat-square&logo=tailwindcss&logoColor=white) ![Postgres](https://img.shields.io/badge/Neon_Serverless-00E599?style=flat-square&logo=neondatabase&logoColor=black) | `Production` |
| 📈 [**PredictMarket Lab**](https://github.com/farzanni/predict-market-lab) | **Polymarket Forecasting & Scoring Engine**<br />Systematic probabilistic forecasting lab featuring automated market tracking, Brier score resolution, and calibration analysis. Pure Python stdlib without bloated dependencies. | ![Python](https://img.shields.io/badge/Python_Stdlib-3776AB?style=flat-square&logo=python&logoColor=white) ![Polymarket](https://img.shields.io/badge/Polymarket_API-2563EB?style=flat-square) ![Stats](https://img.shields.io/badge/Brier_Scoring-059669?style=flat-square) | `Active` |
| 🤖 [**Agent Lab**](https://github.com/farzanni/agent-lab) | **Evaluation & Benchmarking Harness for LLM Agents**<br />Empirical evaluation framework for benchmarking autonomous agent reliability, reasoning fidelity, and tool-calling failure recovery under reproducible synthetic test suites. | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![Evals](https://img.shields.io/badge/LLM_Evals-8B5CF6?style=flat-square) ![Pytest](https://img.shields.io/badge/Pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white) | `Active` |
| 🎬 [**Fistream**](https://github.com/farzanni/persian-stream) | **FastAPI Streaming Engine & AI Subtitle Pipeline**<br />Zero-bandwidth CDN media proxy paired with Stremio Cinemeta catalog search, multi-provider player failover, and automated AI subtitle translation fallback. | ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![Cinemeta](https://img.shields.io/badge/Cinemeta_API-5C3EE8?style=flat-square) | `Engineered` |

<details>
<summary><b>🔬 Systems & Research in Progress</b></summary>
<br />

- 🧭 **Conductor Linux** — Parallel AI coding agent orchestrator managing isolated `git-worktree` workspaces from a unified CLI.
- 📱 **Mobile Retail POS Assistant** — Offline-first transaction and inventory assistant engineered in Kotlin.
- 🎙️ **Voice Agent Pipeline** — Low-latency audio streaming, voice activity detection (VAD), and realtime transcription pipeline.
- 🛍️ **Multi-Tenant DM Commerce Agent** — Automated conversational sales assistant utilizing Meta Graph APIs and webhooks.
</details>

---

### 🛠️ Technical & Engineering Toolbox

<table width="100%">
  <tr>
    <td width="50%" valign="top">
      <h4>🤖 Autonomous AI, Vision & Evaluation</h4>
      <img src="https://img.shields.io/badge/OpenCV_5-5C3EE8?style=flat-square&logo=opencv&logoColor=white" alt="OpenCV" />
      <img src="https://img.shields.io/badge/AWS_Bedrock-FF9900?style=flat-square&logo=amazon-aws&logoColor=white" alt="AWS Bedrock" />
      <img src="https://img.shields.io/badge/Claude_3.5_Sonnet-D97706?style=flat-square&logo=anthropic&logoColor=white" alt="Claude" />
      <img src="https://img.shields.io/badge/LLM_Agent_Harnesses-6366F1?style=flat-square&logo=openai&logoColor=white" alt="Agents" />
      <img src="https://img.shields.io/badge/Brier_Score_Calibration-059669?style=flat-square" alt="Brier Scoring" />
      <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white" alt="Streamlit" />
    </td>
    <td width="50%" valign="top">
      <h4>💻 Languages</h4>
      <img src="https://img.shields.io/badge/Python_3.12-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
      <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
      <img src="https://img.shields.io/badge/JavaScript_ES6+-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript" />
      <img src="https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white" alt="Kotlin" />
      <img src="https://img.shields.io/badge/SQL_PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="SQL" />
      <img src="https://img.shields.io/badge/Bash_Shell-4EAA25?style=flat-square&logo=gnubash&logoColor=white" alt="Bash" />
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h4>🌐 Full-Stack & Systems Architecture</h4>
      <img src="https://img.shields.io/badge/Next.js_15-000000?style=flat-square&logo=next.js&logoColor=white" alt="Next.js" />
      <img src="https://img.shields.io/badge/React_19-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React" />
      <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI" />
      <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white" alt="Node.js" />
      <img src="https://img.shields.io/badge/Tailwind_CSS_4-38BDF8?style=flat-square&logo=tailwindcss&logoColor=white" alt="Tailwind" />
      <img src="https://img.shields.io/badge/Jinja2-B41717?style=flat-square&logo=jinja&logoColor=white" alt="Jinja2" />
    </td>
    <td width="50%" valign="top">
      <h4>⚙️ DevOps, Cloud & Rigor</h4>
      <img src="https://img.shields.io/badge/Linux_Ubuntu-FCC624?style=flat-square&logo=linux&logoColor=black" alt="Linux" />
      <img src="https://img.shields.io/badge/Git_Worktrees-F05032?style=flat-square&logo=git&logoColor=white" alt="Git" />
      <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
      <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white" alt="GitHub Actions" />
      <img src="https://img.shields.io/badge/Neon_Serverless-00E599?style=flat-square&logo=neondatabase&logoColor=black" alt="Neon" />
      <img src="https://img.shields.io/badge/Pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white" alt="Pytest" />
    </td>
  </tr>
</table>

---

### 📊 GitHub Activity & Metrics

<div align="center">
  <img height="180" src="https://github-readme-stats-eight-theta.vercel.app/api?username=farzanni&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&title_color=6366f1&icon_color=38bdf8" alt="GitHub stats" />
  <img height="180" src="https://streak-stats.demolab.com/?user=farzanni&theme=tokyonight&hide_border=true&background=1a1b26&ring=6366f1&fire=f59e0b&currStreakLabel=6366f1" alt="GitHub streak" />
</div>

<p align="center">
  <img src="https://github-readme-stats-eight-theta.vercel.app/api/top-langs/?username=farzanni&layout=compact&theme=tokyonight&hide_border=true&title_color=6366f1" alt="Top languages" />
</p>

---

<div align="center">
  <h3>📫 Let's Connect</h3>
  <p>Always open to collaborating on autonomous AI agents, multimodal vision architectures, or high-reliability products.</p>
  <a href="https://github.com/farzanni"><img src="https://img.shields.io/badge/GitHub-farzanni-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub Profile" /></a>
  <a href="mailto:farzannaghi3413@gmail.com"><img src="https://img.shields.io/badge/Email-Get_in_touch-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://muucut.ir"><img src="https://img.shields.io/badge/Production_System-muucut.ir-00E599?style=for-the-badge&logo=vercel&logoColor=black" alt="Live System" /></a>
</div>
