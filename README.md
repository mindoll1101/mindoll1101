<div align="center">

<!-- Header Banner -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f172a,50:1e3a8a,100:06b6d4&height=220&section=header&text=mindoll1101&fontSize=56&fontColor=ffffff&fontAlignY=38&desc=On-Premise%20AI%20Systems%20%7C%20LLM%20Infrastructure%20Engineer&descAlignY=60&descSize=18&animation=fadeIn" width="100%" />

<h3>Building Sovereign, Air-Gapped AI Appliances & High-Performance Local LLM Systems</h3>

<p>
  <img src="https://img.shields.io/badge/Focus-Local_LLM_Inference-0ea5e9?style=flat-square" />
  <img src="https://img.shields.io/badge/Architecture-Hybrid_RAG_Agents-6366f1?style=flat-square" />
  <img src="https://img.shields.io/badge/Systems-Cross--Platform_Zero--Trust-10b981?style=flat-square" />
</p>

</div>

---

### 👨‍💻 About Me

<div align="center">
  <a href="https://solimatics.co.kr" target="_blank">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="./assets/solimatics-logo-dark.png" />
      <source media="(prefers-color-scheme: light)" srcset="./assets/solimatics-logo.png" />
      <img src="./assets/solimatics-logo.png" alt="SOLIMATICS" height="28" />
    </picture>
  </a>
  <br />
  <sub>Currently Engineer at <b>SOLIMATICS</b> — Building Enterprise Sovereign AI Appliance</sub>
</div>
데이터 유출 없는 **온프레미스·폐쇄망(Air-Gapped) AI 인프라**와 **크로스 플랫폼 네이티브 소프트웨어**를 설계하고 구현합니다.  
초거대 언어 모델(LLM)의 로컬 서빙 최적화부터 하이브리드 RAG, 에이전틱 워크플로우, 네이티브 바이너리 보호 및 배포 자동화까지 엔드투엔드(End-to-End) 시스템을 다룹니다.

- 🔭 **Currently working on:** Enterprise Sovereign AI Appliance (Local LLM Serving, Hybrid RAG, Agentic Workspace)
- ⚡ **Core Interests:** GPU Offloading (`CUDA` / `ROCm` / `Vulkan` / `Metal`), Inference Optimization (`vLLM`, `llama.cpp`), Zero-Trust Security
- 🛠️ **Engineering Approach:** Zero-Dependency Packaging, Deterministic Pipelines, Native Performance (`C++`, `Rust`, `Cython`)

---

### 🧩 Engineering Focus

| Domain | What I Build |
| :--- | :--- |
| **🧠 Local LLM & Inference** | 소비자/엔터프라이즈 GPU 환경에서의 양자화 모델 서빙, 멀티 가속기 자동 감지 및 오프로드 파이프라인 |
| **🔎 Hybrid RAG & Agents** | 사내 문서(PDF/Office/HWPX) 파싱, 벡터·키워드 하이브리드 검색(FAISS), MCP 기반 에이전트 오케스트레이션 |
| **🖥️ Cross-Platform Studio** | `Tauri` + `Vite` 기반 네이티브 데스크톱 AI 스튜디오 및 Windows / Linux / macOS 단일 파일 인스톨러 구축 |
| **🛡️ Systems & Security** | 네이티브 성능 최적화, Zero-Trust 인증 아키텍처 및 폐쇄망(Air-Gapped) 배포 자동화 |

---

### 🏗️ Typical System Architecture I Build

```mermaid
flowchart LR
    Client["Desktop Studio\n(Tauri + Vite)"] -->|Zero-Trust PoP| Gateway["Appliance Server\n(FastAPI + Cython Core)"]
    Gateway --> RAG["Hybrid RAG\n(FAISS + Document Parser)"]
    Gateway --> Agents["Agentic Runtime\n(MCP Tools & Connectors)"]
    Gateway --> Inference["Local LLM Engine\n(vLLM / llama.cpp)"]
    Inference --> HW["Multi-Accelerator\n(CUDA / ROCm / Vulkan / Metal)"]
```

---

### 🛠️ Tech Stack

<div align="center">

#### Languages
<img src="https://img.shields.io/badge/Python-0f172a?style=for-the-badge&logo=python&logoColor=38bdf8" />
<img src="https://img.shields.io/badge/C++-0f172a?style=for-the-badge&logo=cplusplus&logoColor=38bdf8" />
<img src="https://img.shields.io/badge/Rust-0f172a?style=for-the-badge&logo=rust&logoColor=f97316" />
<img src="https://img.shields.io/badge/JavaScript-0f172a?style=for-the-badge&logo=javascript&logoColor=facc15" />
<img src="https://img.shields.io/badge/Dart-0f172a?style=for-the-badge&logo=dart&logoColor=38bdf8" />

#### AI / LLM & Inference
<img src="https://img.shields.io/badge/PyTorch-0f172a?style=for-the-badge&logo=pytorch&logoColor=ee4c2c" />
<img src="https://img.shields.io/badge/CUDA-0f172a?style=for-the-badge&logo=nvidia&logoColor=76b900" />
<img src="https://img.shields.io/badge/ONNX_Runtime-0f172a?style=for-the-badge&logo=onnx&logoColor=38bdf8" />
<img src="https://img.shields.io/badge/vLLM_%2F_llama.cpp-0f172a?style=for-the-badge&logo=huggingface&logoColor=ffd21e" />

#### Backend, Desktop & Infrastructure
<img src="https://img.shields.io/badge/FastAPI-0f172a?style=for-the-badge&logo=fastapi&logoColor=009688" />
<img src="https://img.shields.io/badge/Tauri-0f172a?style=for-the-badge&logo=tauri&logoColor=24c8db" />
<img src="https://img.shields.io/badge/Vite-0f172a?style=for-the-badge&logo=vite&logoColor=a855f7" />
<img src="https://img.shields.io/badge/Docker-0f172a?style=for-the-badge&logo=docker&logoColor=2496ed" />
<img src="https://img.shields.io/badge/Linux_%2F_WSL2-0f172a?style=for-the-badge&logo=linux&logoColor=facc15" />

#### Databases & Tools
<img src="https://img.shields.io/badge/MySQL-0f172a?style=for-the-badge&logo=mysql&logoColor=38bdf8" />
<img src="https://img.shields.io/badge/PostgreSQL-0f172a?style=for-the-badge&logo=postgresql&logoColor=60a5fa" />
<img src="https://img.shields.io/badge/Git-0f172a?style=for-the-badge&logo=git&logoColor=f05032" />

</div>

<!-- Footer Banner -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:06b6d4,50:1e3a8a,100:0f172a&height=110&section=footer" width="100%" />
