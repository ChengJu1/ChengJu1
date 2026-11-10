### 你好，我是孙心远 👋

UCL 计算机科学硕士在读（2027 届），方向是 **AI 应用开发 / Agent 开发**。我关心的是怎么让 Agent 在真实任务里可控、可评估、成本可接受。

- 🛠️ 主要用 Python、FastAPI、LangChain / LangGraph、Deep Agents 和 MCP
- 🔍 关注多 Agent 协作、工具调用安全、RAG 检索评测和 token 成本控制
- 🧠 也做过深度学习：用 Transformer 做毫米波雷达手势识别

---

#### 精选项目

**[AI Agent Workbench](https://github.com/ChengJu1/AI-Agent-workbench)** — 可自托管的 AI Agent 工作台

- 网页里配置 Agent，接入工具、Skill、知识库和 MCP；有副作用的操作要人工确认并写审计日志
- 多 Agent 团队：任务台账 + 进度判断的内外层循环，卡住时复盘重规划；三组对照评测中完成率 14/14
- 定位并修复 DeepSeek 适配层把中文工具结果转义成 `\uXXXX` 的问题，同一任务输入 token 从 24.4 万降到 8.5 万

`FastAPI` `React` `Deep Agents` `MCP` `SQLite`

**[毫米波雷达手势识别](https://github.com/ChengJu1/FYP_Gesture_Recognition_mmWave)** — 本科毕业设计

- TI IWR6843AOP 采集点云，DBSCAN 去噪，Transformer 编码器做 4 类手势时序分类
- 实时推理接入系统媒体控制，带置信度阈值和冷却防误触

`PyTorch` `Transformer` `scikit-learn`

**[项目材料管理平台](https://github.com/ChengJu1/project_manage)** — Flask 全栈小系统

- 项目台账、材料归档、Excel 导出、批量打包下载；分级权限、软删除与恢复

`Flask` `SQLAlchemy` `Flask-Login`

---

#### 技术栈

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
