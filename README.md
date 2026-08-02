<div align="center">

# Taijia Liang

**AI Engineer** · LLM Agents — Retrieval — Local Inference

`M.S. Computer Science, NYU '26` · `New York, NY`

[![Email](https://img.shields.io/badge/tl4549@nyu.edu-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:tl4549@nyu.edu)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge)](https://linkedin.com/in/taijia-liang-1151ba265/)

<sub>I build systems where the language model is one component among many — retrieval, evaluation<br>
harnesses, GPU data paths, sandboxed tool execution. Most of what I ship runs locally:<br>
on-device inference, no data leaving the machine.</sub>

**🔍 Open to Fall 2026 internships and new-grad roles starting Jan 2027.**

</div>

<img src=".assets/divider.svg" width="100%" height="3" alt="">

## 🛠 Building

### [Loomscreen](https://github.com/Paradox07127/Loomscreen) &nbsp;·&nbsp; macOS live-wallpaper platform

![Swift](https://img.shields.io/badge/Swift-F05138?style=flat-square&logo=swift&logoColor=white)
![Metal](https://img.shields.io/badge/Metal-000000?style=flat-square&logo=apple&logoColor=white)
![MIT](https://img.shields.io/badge/license-MIT-A5A5A5?style=flat-square)
![Commits](https://img.shields.io/badge/1%2C285%20commits-2F855A?style=flat-square&logo=git&logoColor=white)
![Releases](https://img.shields.io/badge/9%20releases-2B6CB0?style=flat-square&logo=github&logoColor=white)

Every connected display runs its own video, sandboxed web page, Metal procedural shader, or Wallpaper
Engine scene. Menu-bar first, with playlists, scheduled rotation, and auto-pause on full-screen, game
windows, occlusion, and battery. No accounts, no telemetry. Lite and Pro are split at compile time
(`#if LITE_BUILD`) rather than by hiding UI.

### [Analyst-Copilot](https://github.com/Paradox07127/Analyst-Copilot) &nbsp;·&nbsp; local-first agent platform for data analysis

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![DuckDB](https://img.shields.io/badge/DuckDB-FFF000?style=flat-square&logo=duckdb&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

Deterministic profiling and validation come first; LLM workflows extend those facts under constraints.
Every claim in a generated report is backed by a claim ledger and checked by hard validators, and
open-ended Python analysis runs isolated in a sandbox. Pydantic-typed artifacts end to end, DuckDB for
multi-table join discovery and validation.

### [Urban-Dossier](https://github.com/Paradox07127/Urban-Dossier) &nbsp;·&nbsp; fully-offline NYC neighborhood intelligence

![vLLM](https://img.shields.io/badge/vLLM-000000?style=flat-square&logo=vllm&logoColor=white)
![RAPIDS](https://img.shields.io/badge/RAPIDS%20%2F%20CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Award](https://img.shields.io/badge/🏆%20Spark%20Hack%20NYC%202026-76B900?style=flat-square)

Click anywhere on a map of New York and get a data-driven dossier on safety, transit, amenities, and
building conditions — scored against the city, trended over time, narrated by an on-device LLM, with no
cloud calls. One vLLM stack co-tenants Nemotron-30B (NVFP4) and Qwen3-Embedding-4B on a single DGX Spark
GB10 alongside a ~30 GiB cuDF/cuVS dataset cache, while cuML DBSCAN clusters incident hotspots across
17 NYC open-data sources.

### [Clinical-Simulator](https://github.com/Paradox07127/Clinical-Simulator) &nbsp;·&nbsp; AI clinical training platform

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![MediaPipe](https://img.shields.io/badge/MediaPipe-0097A7?style=flat-square&logo=google&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![Award](https://img.shields.io/badge/🏆%20Cornell%20AI%20Hackathon%20—%20Grand%20Prize-B31B1B?style=flat-square)

Two training modules for medical students. An AI patient you interview from first question to final
diagnosis, scored on a 6-dimension rubric with live coverage tracking. And camera-based CPR practice —
MediaPipe pose tracking at 33 landmarks / 30 fps, compression detection from wrist-motion peaks, scored
on 7 dimensions against the full 30:2 BLS protocol.

### [rag-agent](https://github.com/guochenmeinian/rag-agent) &nbsp;·&nbsp; hybrid-retrieval agent for vehicle QA

![Milvus](https://img.shields.io/badge/Milvus-00A1EA?style=flat-square&logo=milvus&logoColor=white)
![BGE-M3](https://img.shields.io/badge/BGE--M3-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![Role](https://img.shields.io/badge/role-retrieval%20%26%20eval%20owner-6B46C1?style=flat-square)

I owned hybrid retrieval — BGE-M3 dense + sparse over Milvus, SQLite FTS, and web search — and a
5-metric evaluation harness covering tool recall/precision, parallel-call correctness, keyword hit
rate, and hallucination, which regression-tests every change.

<img src=".assets/divider.svg" width="100%" height="3" alt="">

## 💼 Experience

**AI Engineering Intern** — China-ASEAN Information Harbor &nbsp;·&nbsp; `Jan – Mar 2026`

Shipped production Dify workflows extracting structured fields from customs and certificate documents
(image + PDF), and built an internal RAG assistant — intent recognition, multimodal extraction, tool
routing — over a local corpus with zero external data egress.

<img src=".assets/divider.svg" width="100%" height="3" alt="">

## ⚙️ Stack

<table>
<tr><td align="right"><b>Languages</b></td><td>

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Swift](https://img.shields.io/badge/Swift-F05138?style=flat-square&logo=swift&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![C++](https://img.shields.io/badge/C%2FC%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)

</td></tr>
<tr><td align="right"><b>AI / ML</b></td><td>

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Transformers](https://img.shields.io/badge/Transformers-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![Milvus](https://img.shields.io/badge/Milvus-00A1EA?style=flat-square&logo=milvus&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI%20SDK-412991?style=flat-square)

</td></tr>
<tr><td align="right"><b>Inference&nbsp;/&nbsp;GPU</b></td><td>

![vLLM](https://img.shields.io/badge/vLLM-000000?style=flat-square&logo=vllm&logoColor=white)
![CUDA](https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white)
![RAPIDS](https://img.shields.io/badge/RAPIDS-76B900?style=flat-square&logo=nvidia&logoColor=white)
![TensorRT](https://img.shields.io/badge/TensorRT-76B900?style=flat-square&logo=nvidia&logoColor=white)
![llama.cpp](https://img.shields.io/badge/llama.cpp-1A1A1A?style=flat-square)

</td></tr>
<tr><td align="right"><b>Backend&nbsp;/&nbsp;Data</b></td><td>

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![DuckDB](https://img.shields.io/badge/DuckDB-FFF000?style=flat-square&logo=duckdb&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square)

</td></tr>
<tr><td align="right"><b>Hardware</b></td><td>

![DGX Spark](https://img.shields.io/badge/DGX%20Spark%20GB10-76B900?style=flat-square&logo=nvidia&logoColor=white)
![Jetson](https://img.shields.io/badge/Jetson%20AGX%20Orin-76B900?style=flat-square&logo=nvidia&logoColor=white)
![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white)

</td></tr>
</table>

<div align="center">
<sub>Virginia Tech · B.S. Computer Science · 2021 – 2024</sub>
</div>

<!-- profile -->
