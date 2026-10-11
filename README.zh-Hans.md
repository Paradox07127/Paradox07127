<h3 align="center">AI 工程师 · 2027 届校招 · AI/ML & SWE</h3>

<p align="center">Agent 系统 · 多模态 AI · 开发者工具<br>NYU 计算机科学硕士 · 预计 2026.12 毕业 · 2027.01 可入职<br><a href="README.md">English</a> · <b>简体中文</b> · <a href="mailto:tl4549@nyu.edu">邮箱</a> · <a href="https://linkedin.com/in/taijia-liang-1151ba265/">LinkedIn</a></p>

<table>
<tr>
<td width="50%" align="center" valign="top"><a href="https://github.com/Paradox07127/Spatial-Video-Agent"><img src=".assets/spatial-preview.png" width="420" alt="Spatial Video Agent: 3D measurement with linked source video and evidence"></a><br><b>Spatial Video Agent · 测量与证据</b></td>
<td width="50%" align="center" valign="top"><a href="https://github.com/Paradox07127/Urban-Dossier"><img src=".assets/urban-preview.png" width="420" alt="Urban Dossier: NYC neighborhood map with safety, transit, amenities and evidence coverage"></a><br><b>Urban Dossier · 纽约社区情报</b></td>
</tr>
</table>

### 🎬 [Spatial Video Agent](https://github.com/Paradox07127/Spatial-Video-Agent) · 有测量证据的视频调查

结合 Cosmos 3 Nano、Cosmos Embed1、VSS/VastDB 与 W&B Inference/Weave，调查多摄像头仓库、车载及街景视频。

将原始帧与 3D / 地图视图联动；数值结论来自 CV / 几何或遥测证据，证据不足时明确标记无法判定。**Real-Time Video Hack 决赛入围。**

<picture><source media="(max-width: 600px)" srcset=".assets/tags-spatial-compact.svg"><img src=".assets/tags-spatial.svg" width="528" alt="Cosmos 3 Nano · Cosmos Embed1 · VSS / VastDB · W&amp;B Inference · Weave · Finalist · Real-Time Video Hack finalist"></picture><br><a href="https://github.com/Paradox07127/Spatial-Video-Agent/blob/main/CONTRACT.md">↗ 证据契约</a> · <a href="https://github.com/Paradox07127/Spatial-Video-Agent#pipeline">↗ GPU 流水线</a>

### 🗺️ [Urban Dossier](https://github.com/Paradox07127/Urban-Dossier) · 本地纽约社区情报

以 DuckDB/Parquet/H3 提供确定性的纽约社区指标，使用 vLLM 以 NVFP4 运行 Nemotron 3.5 Lightning。

NemoClaw/OpenShell 工具基于既有证据生成地址比较与分析报告。**Spark Hack NYC 2026 参赛项目。**

<picture><source media="(max-width: 600px)" srcset=".assets/tags-urban-compact.svg"><img src=".assets/tags-urban.svg" width="441" alt="Nemotron 3.5 · NVFP4 · vLLM · DuckDB / H3 · NemoClaw / OpenShell"></picture><br><a href="https://github.com/Paradox07127/Urban-Dossier/blob/main/docs/ARCHITECTURE.md">↗ 系统架构</a> · <a href="https://github.com/Paradox07127/Urban-Dossier/blob/main/docs/architecture/PUBLIC_METHODOLOGY.md">↗ 数据方法</a>

## 🛠 更多项目

### 🖥️ [Loomscreen](https://github.com/Paradox07127/macos-wallpaperengine) · macOS 原生渲染与多显示器桌面

独立实现 macOS 上的 Wallpaper Engine Metal 场景渲染，支持粒子、骨骼形变、音频响应着色器和 SceneScript。

每显示器渲染 Actor 驱动多屏工作区，并提供视频 / 网页壁纸、同步转场、播放列表及自适应播放；Lite 与 Pro 均免费开源。

<picture><source media="(max-width: 600px)" srcset=".assets/tags-loomscreen-compact.svg"><img src=".assets/tags-loomscreen.svg" width="468" alt="Metal · Particles · Puppet Warp · Audio FX · SceneScript · Per-display Threads"></picture><br><a href="https://github.com/Paradox07127/macos-wallpaperengine/blob/main/docs/zh-Hans/architecture.md">↗ 渲染架构</a> · <a href="https://github.com/Paradox07127/macos-wallpaperengine/releases">↗ 正式版本</a>

### 📊 [Analyst Copilot](https://github.com/Paradox07127/Analyst-Copilot) · 有界 Agent 与可核查分析

将确定性数据画像、有界 LangGraph 工作流和持久化检查点结合的本地数据分析工作区。

类型化产物、claim ledger 与证据校验让报告结论可核查；模型编写的 Python 在独立 Docker 沙箱中执行，并提供工作流评估与自包含 HTML 报告。

<picture><source media="(max-width: 600px)" srcset=".assets/tags-analyst-compact.svg"><img src=".assets/tags-analyst.svg" width="473" alt="LangGraph · DuckDB · Claim Ledger · Evidence Gates · Docker Sandbox"></picture><br><a href="https://github.com/Paradox07127/Analyst-Copilot#langgraph-execution-architecture">↗ LangGraph 设计</a> · <a href="https://github.com/Paradox07127/Analyst-Copilot#agent-harness-and-evaluation">↗ 评估框架</a>

### 🧩 [claude-utopia](https://github.com/Paradox07127/claude-utopia) · 编程 Agent 的开发工作台

通过 Claude Code mods 提供 Agent 仪表盘、模型 / 工具调用时间线与持久化进度板。

mmrun CLI 支持跨模型代码审查及独立 Git 工作树委派，工作流保护机制覆盖共享改动与敏感配置。

<picture><source media="(max-width: 600px)" srcset=".assets/tags-utopia-compact.svg"><img src=".assets/tags-utopia.svg" width="400" alt="Claude Mods · mmrun · Timeline · Worktrees · Guards · Progress"></picture><br><a href="https://github.com/Paradox07127/claude-utopia#screenshots">↗ 工作台界面</a> · <a href="https://github.com/Paradox07127/claude-utopia#install">↗ 安装与选项</a>

### 🩺 [Clinical Simulator](https://github.com/Paradox07127/Clinical-Simulator) · 多模态临床训练

团队开发的临床训练平台，结合 Gemini 病人对话与基于量表的问诊评估。

MediaPipe Pose 跟踪 33 个人体关键点，提供摄像头心肺复苏指导、动作反馈及训练后评分。**Cornell AI Hackathon 大奖。**

<picture><source media="(max-width: 600px)" srcset=".assets/tags-clinical-compact.svg"><img src=".assets/tags-clinical.svg" width="501" alt="MediaPipe Pose · Gemini · Pose Coaching · Rubric Scoring · Cornell · Grand Prize · Cornell AI Hackathon Grand Prize"></picture><br><a href="https://github.com/Paradox07127/Clinical-Simulator#training-modules">↗ 训练模块</a> · <a href="https://github.com/Paradox07127/Clinical-Simulator#product-flow">↗ 产品流程</a>

## 🧭 Focus Areas · 关注方向

- 🧠 **多模态 / Physical AI** — 视频理解、空间推理与测量证据
- 🧩 **可靠 Agent** — 有界工作流、证据校验与评估
- ⚙️ **推理 / 系统** — 本地 GPU 推理服务与原生图形渲染

## 📦 Selected Releases · 精选版本

- **[Loomscreen 0.8.6](https://github.com/Paradox07127/macos-wallpaperengine/releases/tag/loomscreen-v0.8.6)** · 静态场景空闲节能、多屏每帧呈现协调及恢复修复。
- **[Loomscreen 0.8.2](https://github.com/Paradox07127/macos-wallpaperengine/releases/tag/loomscreen-v0.8.2)** · 同步转场、每日时间表与播放列表 / 随机轮播自动化。

## 📝 Engineering Notes · 工程笔记

- **[视频证据契约](https://github.com/Paradox07127/Spatial-Video-Agent/blob/main/CONTRACT.md)** · 来源追溯、结论判定与持久化调查。
- **[有界 LangGraph 工作流](https://github.com/Paradox07127/Analyst-Copilot#langgraph-execution-architecture)** · 检查点、类型化产物与报告发布的证据门槛。
- **[确定性的纽约社区指标](https://github.com/Paradox07127/Urban-Dossier/blob/main/docs/ARCHITECTURE.md)** · DuckDB/H3 分析、vLLM 推理与 OpenShell 边界。
- **[原生 Metal 渲染](https://github.com/Paradox07127/macos-wallpaperengine/blob/main/docs/zh-Hans/architecture.md)** · 场景图、帧输入与每显示器渲染 Actor。

<details>
<summary><b>⚙️ 完整技术栈</b></summary>

<table>
<tr><td align="right"><b>编程语言</b></td><td>

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![Swift](https://img.shields.io/badge/Swift-F05138?style=flat-square&logo=swift&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square)

</td></tr>
<tr><td align="right"><b>Agent / 模型</b></td><td>

![Claude Code](https://img.shields.io/badge/Claude%20Code-D97757?style=flat-square&logo=claude&logoColor=white) ![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langgraph&logoColor=white) ![Transformers](https://img.shields.io/badge/Transformers-FFD21E?style=flat-square&logo=huggingface&logoColor=black) ![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)

</td></tr>
<tr><td align="right"><b>视觉 / Physical AI</b></td><td>

![Cosmos 3 Nano](https://img.shields.io/badge/Cosmos%203%20Nano-76B900?style=flat-square&logo=nvidia&logoColor=white) ![Cosmos Embed1](https://img.shields.io/badge/Cosmos%20Embed1-76B900?style=flat-square&logo=nvidia&logoColor=white) ![MediaPipe Pose](https://img.shields.io/badge/MediaPipe%20Pose-0097A7?style=flat-square&logo=mediapipe&logoColor=white) ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)

</td></tr>
<tr><td align="right"><b>推理 / GPU</b></td><td>

![W&B Inference](https://img.shields.io/badge/W%26B%20Inference-FFBE00?style=flat-square&logo=weightsandbiases&logoColor=black) ![vLLM](https://img.shields.io/badge/vLLM-76B900?style=flat-square&logo=nvidia&logoColor=white) ![NVFP4](https://img.shields.io/badge/NVFP4-76B900?style=flat-square&logo=nvidia&logoColor=white) ![CUDA](https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white) ![llama.cpp](https://img.shields.io/badge/llama.cpp-343434?style=flat-square)

</td></tr>
<tr><td align="right"><b>数据 / 检索</b></td><td>

![VSS](https://img.shields.io/badge/VSS-006B5E?style=flat-square) ![VastDB](https://img.shields.io/badge/VastDB-006B5E?style=flat-square) ![DuckDB](https://img.shields.io/badge/DuckDB-FFF000?style=flat-square&logo=duckdb&logoColor=black) ![Parquet](https://img.shields.io/badge/Parquet-50ABF1?style=flat-square&logo=apacheparquet&logoColor=white) ![H3](https://img.shields.io/badge/H3-396CB2?style=flat-square)

</td></tr>
<tr><td align="right"><b>运行时 / API</b></td><td>

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![Pydantic](https://img.shields.io/badge/Pydantic-E92063?style=flat-square&logo=pydantic&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![OpenShell](https://img.shields.io/badge/OpenShell-76B900?style=flat-square&logo=nvidia&logoColor=white)

</td></tr>
<tr><td align="right"><b>前端 / 图形</b></td><td>

![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB) ![Three.js](https://img.shields.io/badge/Three.js-20232A?style=flat-square&logo=threedotjs&logoColor=white) ![MapLibre](https://img.shields.io/badge/MapLibre-396CB2?style=flat-square&logo=maplibre&logoColor=white) ![Metal](https://img.shields.io/badge/Metal-181717?style=flat-square&logo=apple&logoColor=white)

</td></tr>
<tr><td align="right"><b>可观测性 / 验证</b></td><td>

![W&B Weave](https://img.shields.io/badge/W%26B%20Weave-FFBE00?style=flat-square&logo=weightsandbiases&logoColor=black) ![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square) ![mmrun](https://img.shields.io/badge/mmrun-6B46C1?style=flat-square)

</td></tr>
</table>

</details>

<p align="center">弗吉尼亚理工大学 · 计算机科学学士 · 2024 年 12 月</p>
