<div align="center">

# Damon

<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=20&pause=1000&color=00D4FF&center=true&vCenter=true&width=600&lines=AI+Agent+Engineer;LLM+%E5%B7%A5%E7%A8%8B%E5%8C%96+专家;大数据架构师;从+0+到+1+构建核心平台" alt="Typing SVG" />

### 🧠 AI Agent · 大数据架构 · LLM 工程化

> *"将前沿技术快速落地为业务价值"*

[![Email](https://img.shields.io/badge/Email-chenblue1224@gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:chenblue1224@gmail.com)
[![WeChat](https://img.shields.io/badge/WeChat-DamonYang9202-07C160?style=for-the-badge&logo=wechat&logoColor=white)]()

</div>

---

## ⚡ 我能做什么

<div align="center">

| 🤖 LLM 工程化 | 🧩 Agent 构建 | 🏗️ 从 0 到 1 |
|:---:|:---:|:---:|
| 模型部署·量化·微调·推理加速<br/>本地部署实现 **20x** 性能提升 | LangGraph 多步骤 Agent<br/>Skills / MCP / RAG 集成 | 非结构化处理中台<br/>多模态搜索 · AI PaaS |

| 🔥 大数据架构 | 📐 工程范式 |
|:---:|:---:|
| Spark / Flink 全栈<br/>离线 + 实时 · TB 级数据 | YAML 驱动开发<br/>CICD 自动化 · 消灭重复 |

</div>

---

## 🔥 技术栈

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white"/>
  <img src="https://img.shields.io/badge/Scala-DC322F?style=for-the-badge&logo=scala&logoColor=white"/>
  <img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Spark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white"/>
  <img src="https://img.shields.io/badge/Flink-E6522C?style=for-the-badge&logo=apacheflink&logoColor=white"/>
  <img src="https://img.shields.io/badge/Hadoop-66CCFF?style=for-the-badge&logo=apachehadoop&logoColor=black"/>
  <img src="https://img.shields.io/badge/Airflow-017CEE?style=for-the-badge&logo=apacheairflow&logoColor=white"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white"/>
  <img src="https://img.shields.io/badge/LangChain-12900C?style=for-the-badge&logo=langchain&logoColor=white"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/>
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white"/>
  <img src="https://img.shields.io/badge/ClickHouse-FFCC00?style=for-the-badge&logo=clickhouse&logoColor=black"/>
  <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white"/>
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white"/>
</p>

---

## 🌟 开源项目

<div align="center">

### [Atlas — 金融可信 AI 问数平台](https://github.com/VinderDiesel/Atlas)

<img src="https://img.shields.io/badge/Status-Active%20Development-10B981?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Python-3.11-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/License-Apache%202.0-D14836?style=for-the-badge"/>

</div>

> **以 FIBO 本体为语义锚点的金融可信 AI 问数平台**
> 
> 业务术语 → FIBO 概念 → 指标计划 → 安全查询 → 可解释结果 → 评测回流

<div align="center">

| 核心能力 | 技术实现 |
|:---|:---|
| 🧩 **统一语义层** | Apache Ossie + 治理扩展，指标/维度/权限声明式定义 |
| 🎯 **确定性编译器** | Plan → SQL 确定性转换，不经过 LLM，零幻觉 |
| 🛡️ **只读安全网关** | 纵深防御：白名单 + 谓词注入 + 行级权限 + 审计 |
| 📊 **评测驱动** | 自建黄金集 + 固定快照 + 脚本化评测，数字必须可复现 |
| 🤖 **Agent 编排** | LangGraph 状态机，clarify → retrieve → plan → execute → explain |
| 🔍 **可解释结果** | 每步决策可追溯，SQL 血缘 + 指标定义 + 权限策略 |

</div>

<details>
<summary><b>🏗️ 架构亮点</b></summary>

```
┌─────────────────────────────────────────────────────────────────────┐
│                        Atlas Architecture                           │
├─────────────────────────────────────────────────────────────────────┤
│                                                                     │
│   问句 ──→ Planner ──→ Plan ──→ Compiler ──→ SQL ──→ Guard ──→ 执行 │
│              ↑                    ↑                    ↑             │
│              │                    │                    │             │
│         语义层(Ossie)        确定性编译           只读安全网关        │
│         指标/维度/权限       零 LLM 参与          纵深防御           │
│                                                                     │
│   ┌─────────────────────────────────────────────────────────────┐  │
│   │  FIBO 本体 ←── 语义锚点 ──→ 业务术语归一 ──→ 可解释归因      │  │
│   └─────────────────────────────────────────────────────────────┘  │
│                                                                     │
│   评测闭环：黄金集 → 固定快照 → 脚本化评测 → 失败样本 → SFT 回流    │
│                                                                     │
└─────────────────────────────────────────────────────────────────────┘
```

</details>

<details>
<summary><b>📐 技术栈</b></summary>

| 层 | 选型 |
|---|---|
| 语义规范 | Apache Ossie（ADR-0002） |
| Agent | LangGraph ≥ 0.2 |
| SQL 解析 | sqlglot ≥ 25 |
| OLAP | Apache Doris 4.1 |
| 表格式 | Apache Iceberg V2 |
| Catalog | Apache Polaris |
| 向量检索 | Milvus 2.4 |
| LLM 推理 | vLLM ≥ 0.6 |

</details>

<div align="center">

**[🔗 访问项目](https://github.com/VinderDiesel/Atlas)** · **[📖 阅读文档](https://github.com/VinderDiesel/Atlas/blob/main/README.md)**

</div>

---

## 🚀 代表性成果

<details open>
<summary><h3 style="display:inline">🧠 AI PaaS 智能数据平台</h3></summary>

<br/>

> 企业级 AI 平台，统一 LLM 网关 + Advanced RAG + 知识蒸馏 + 全链路监控

```
┌─────────────────────────────────────────────────────────┐
│  LLM Gateway  →  Advanced RAG  →  Agent Orchestrator    │
│       ↓              ↓                    ↓              │
│  知识蒸馏      GraphRAG           Skills / MCP          │
└─────────────────────────────────────────────────────────┘
```

`vLLM` `GraphRAG` `Ray` `OTel` `Agent`

</details>

<details open>
<summary><h3 style="display:inline">⚡ LLM 推理加速 — 20x 性能提升</h3></summary>

<br/>

> 本地部署大模型，通过量化 + 推理加速，将多模态搜索延迟从秒级降至毫秒级

```
Before:  ████████████████████████████████████████  8.2s
After:   ██                                        0.4s
                                    ↑ 20x FASTER
```

`量化` `vLLM` `多模态搜索` `文搜图/视频`

</details>

<details>
<summary><h3 style="display:inline">🏗️ 非结构化数据处理中台</h3></summary>

<br/>

> 从 0 到 1 搭建，支持文档/图片/音视频/网页，CICD 自动部署 k8s

`LangGraph` `Layout AI` `k8s` `CICD`

</details>

<details>
<summary><h3 style="display:inline">📐 YAML 驱动的数据开发范式</h3></summary>

<br/>

> 用 YAML 定义任务，CICD 自动生成 Airflow DAG，消灭重复性开发

```yaml
# 一个 YAML 文件 = 一条完整数据流水线
pipeline:
  name: daily_etl
  schedule: "0 2 * * *"
  steps:
    - extract: s3://raw/
    - transform: spark_job.py
    - load: clickhouse.metrics
```

`Airflow` `YAML` `gitlab-ci` `自动化`

</details>

---

## 🎯 技术信仰

<div align="center">

```
╔═══════════════════════════════════════════════════════════╗
║                                                           ║
║   🔹 确定性优先    能用编译器解决的，不交给 LLM 猜         ║
║                                                           ║
║   🔹 工程化落地    再前沿的技术，不能落地就是玩具           ║
║                                                           ║
║   🔹 源码驱动学习  读 GitHub 优秀项目源码，理解本质         ║
║                                                           ║
║   🔹 数据即资产    治理不是事后补救，是第一天就开始的设计   ║
║                                                           ║
╚═══════════════════════════════════════════════════════════╝
```

</div>

---

<div align="center">

### 📫 找到我

**Email**: [chenblue1224@gmail.com](mailto:chenblue1224@gmail.com) · **WeChat**: `DamonYang9202` · 📍 苏州

<br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=80&section=footer&text=Thanks%20for%20visiting!&fontSize=24&fontColor=fff&animation=twinkle&fontAlignY=32" width="100%"/>

</div>
