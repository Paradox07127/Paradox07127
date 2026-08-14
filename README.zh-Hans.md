<div align="center">

# 梁泰珈

**AI 工程师** · LLM Agent — 检索增强 — 本地推理

`纽约大学 计算机科学硕士 '26` · `美国 纽约`

[![Email](https://img.shields.io/badge/tl4549@nyu.edu-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:tl4549@nyu.edu)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge)](https://linkedin.com/in/taijia-liang-1151ba265/)

[English](README.md) · **简体中文**

<sub>我做的系统里,语言模型只是其中一个部件 —— 检索、评测框架、GPU 数据通路、<br>
沙箱化的工具执行同样重要。交付的大部分东西都跑在本地:端侧推理,数据不出机器。</sub>

**🔍 2026 年 12 月毕业,正在寻找 AI / 机器学习 与 软件工程方向的实习及全职机会。**

</div>

<img src=".assets/divider.svg" width="100%" height="3" alt="">

## 🛠 在做的项目

### [Loomscreen](https://github.com/Paradox07127/macos-wallpaperengine) &nbsp;·&nbsp; 在 macOS 上跑 Wallpaper Engine 场景

![Swift](https://img.shields.io/badge/Swift-F05138?style=flat-square&logo=swift&logoColor=white)
![Metal](https://img.shields.io/badge/Metal-000000?style=flat-square&logo=apple&logoColor=white)
![MIT](https://img.shields.io/badge/license-MIT-A5A5A5?style=flat-square)

用 Metal 独立实现的 Wallpaper Engine 场景渲染器,与 Wallpaper Engine 官方无关联。同时支持视频和沙箱网页壁纸,每块接入的显示器可以跑各自的内容。菜单栏优先的交互,支持播放列表、定时轮换,以及全屏、游戏窗口、窗口遮挡和电池模式下的自动暂停。不需要账号,没有遥测。Lite 与 Pro 在编译期分版(`#if LITE_BUILD`),而不是把功能藏在 UI 后面。

### [Analyst-Copilot](https://github.com/Paradox07127/Analyst-Copilot) &nbsp;·&nbsp; 本地优先的数据分析 Agent 平台

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![DuckDB](https://img.shields.io/badge/DuckDB-FFF000?style=flat-square&logo=duckdb&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

先做确定性的数据画像与校验,再让 LLM 工作流在约束下扩展这些既定事实。生成报告里的每一条论断都有 claim ledger 支撑、并经过硬校验器检查;开放式的 Python 分析隔离在沙箱中运行。全链路 Pydantic 类型化产物,多表关联的发现与验证走 DuckDB。

### [Urban-Dossier](https://github.com/Paradox07127/Urban-Dossier) &nbsp;·&nbsp; 完全离线的纽约社区情报系统

![vLLM](https://img.shields.io/badge/vLLM-000000?style=flat-square&logo=vllm&logoColor=white)
![RAPIDS](https://img.shields.io/badge/RAPIDS%20%2F%20CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Award](https://img.shields.io/badge/🏆%20Spark%20Hack%20NYC%202026-76B900?style=flat-square)

在纽约地图上点任意一处,就能拿到一份关于治安、交通、配套和建筑状况的数据档案 —— 与全市水平对标、按时间成趋势、由端侧 LLM 生成叙述,全程不调用云端。单台 DGX Spark GB10 上,一套 vLLM 同时承载 Nemotron-30B(NVFP4)与 Qwen3-Embedding-4B,并与约 30 GiB 的 cuDF / cuVS 数据缓存共存;cuML DBSCAN 在 17 个纽约开放数据源上做事件热点聚类。

### [Clinical-Simulator](https://github.com/Paradox07127/Clinical-Simulator) &nbsp;·&nbsp; AI 临床训练平台

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![MediaPipe](https://img.shields.io/badge/MediaPipe-0097A7?style=flat-square&logo=google&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![Award](https://img.shields.io/badge/🏆%20Cornell%20AI%20Hackathon%20—%20Grand%20Prize-B31B1B?style=flat-square)

面向医学生的两个训练模块。一个是能从第一句问诊聊到最终诊断的 AI 标准化病人,按 6 个维度评分并实时追踪问诊覆盖度;另一个是基于摄像头的心肺复苏练习 —— MediaPipe 姿态追踪 33 个关键点 / 30 fps,用手腕运动峰值检测按压,按 7 个维度对照完整的 30:2 BLS 流程评分。

### [rag-agent](https://github.com/guochenmeinian/rag-agent) &nbsp;·&nbsp; 车载问答的混合检索 Agent

![Milvus](https://img.shields.io/badge/Milvus-00A1EA?style=flat-square&logo=milvus&logoColor=white)
![BGE-M3](https://img.shields.io/badge/BGE--M3-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![Role](https://img.shields.io/badge/负责-检索%20%26%20评测-6B46C1?style=flat-square)

我负责混合检索(BGE-M3 稠密 + 稀疏向量走 Milvus、SQLite FTS、联网搜索),以及一套 5 指标评测框架 —— 工具召回率 / 准确率、并行调用正确性、关键词命中率、幻觉率 —— 每次改动都要过一遍回归。

<img src=".assets/divider.svg" width="100%" height="3" alt="">

## 💼 实习经历

**AI 工程实习生** — 中国—东盟信息港 &nbsp;·&nbsp; `2026 年 1 月 – 3 月`

交付了生产环境的 Dify 工作流,从报关单与证书类图片 / PDF 中抽取结构化字段;并搭建了内部 RAG 助手 —— 意图识别、多模态抽取、工具路由 —— 基于本地语料,数据零外发。

<img src=".assets/divider.svg" width="100%" height="3" alt="">

## ⚙️ 技术栈

<table>
<tr><td align="right"><b>编程语言</b></td><td>

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Swift](https://img.shields.io/badge/Swift-F05138?style=flat-square&logo=swift&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![C++](https://img.shields.io/badge/C%2FC%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)

</td></tr>
<tr><td align="right"><b>AI&nbsp;/&nbsp;机器学习</b></td><td>

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Transformers](https://img.shields.io/badge/Transformers-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![Milvus](https://img.shields.io/badge/Milvus-00A1EA?style=flat-square&logo=milvus&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI%20SDK-412991?style=flat-square)

</td></tr>
<tr><td align="right"><b>推理&nbsp;/&nbsp;GPU</b></td><td>

![vLLM](https://img.shields.io/badge/vLLM-000000?style=flat-square&logo=vllm&logoColor=white)
![CUDA](https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white)
![RAPIDS](https://img.shields.io/badge/RAPIDS-76B900?style=flat-square&logo=nvidia&logoColor=white)
![TensorRT](https://img.shields.io/badge/TensorRT-76B900?style=flat-square&logo=nvidia&logoColor=white)
![llama.cpp](https://img.shields.io/badge/llama.cpp-1A1A1A?style=flat-square)

</td></tr>
<tr><td align="right"><b>后端&nbsp;/&nbsp;数据</b></td><td>

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![DuckDB](https://img.shields.io/badge/DuckDB-FFF000?style=flat-square&logo=duckdb&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square)

</td></tr>
<tr><td align="right"><b>硬件</b></td><td>

![DGX Spark](https://img.shields.io/badge/DGX%20Spark%20GB10-76B900?style=flat-square&logo=nvidia&logoColor=white)
![Jetson](https://img.shields.io/badge/Jetson%20AGX%20Orin-76B900?style=flat-square&logo=nvidia&logoColor=white)
![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white)

</td></tr>
</table>

<div align="center">
<sub>弗吉尼亚理工大学 · 计算机科学学士 · 2021 – 2024</sub>
</div>
