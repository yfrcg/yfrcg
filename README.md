<!-- Profile README for yfrcg -->

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:6EE7F9,50:8B5CF6,100:F472B6&height=180&section=header&text=Hi,%20I'm%20yfrcg%20👋&fontSize=42&fontColor=ffffff&animation=fadeIn&fontAlignY=35" />

<p>
  <b>CS Undergraduate · Agent System Builder · MCP / Gateway / Local-first Memory Explorer</b>
</p>

<p>
  我喜欢把课程项目、系统设计、AI Agent、工程实践揉在一起，做成真正能跑、能测、能迭代的东西。
</p>

<p>
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=1200&color=8B5CF6&center=true&vCenter=true&width=760&lines=Building+local-first+AI+agents;Designing+Gateway+%2B+Memory+%2B+Tool+systems;Exploring+MCP%2C+OpenClaw-like+architectures;Learning+by+shipping+real+projects" />
</p>

</div>

---

## 🧑‍💻 About Me

我是一名计算机专业本科生，主要兴趣集中在：

- **AI Agent 系统架构**：Gateway、Tool Loop、Memory、Multi-Agent、Sandbox、安全审计
- **MCP 工具生态**：课程项目情报检索、GitHub 项目发现、Agent 工具路由
- **系统与性能优化**：SIMD、并行程序设计、Linux perf、ARM NEON
- **课程项目工程化**：把算法、数据库、FPGA、LLM 训练、Web 后端做成可复现项目
- **开发体验设计**：希望让 Agent 不只是“聊天”，而是真的能帮我读代码、跑测试、写报告、总结项目

我比较喜欢的工作方式是：  
**先把系统跑通，再逐步加抽象；先做可验证结果，再写漂亮报告。**

---

## 🚀 Current Focus

### 🧠 Agent Rebuild

我正在构建一个类 OpenClaw / Claude Code 风格的本地 Agent 框架，目标是实现：

- 长驻式 **Gateway Daemon**
- Typed WebSocket 协议
- Tool Registry / Tool Call Protocol
- Local-first Memory：Markdown + JSONL + SQLite FTS + Vector Search
- Session 管理与上下文压缩
- 安全工具执行与审计日志
- 后续扩展到 Multi-Agent 与 Verify Agent

关键词：

```txt
Gateway · WebSocket · Tool Loop · Memory · RAG · SQLite · BM25 · Vector Search · Audit Log
```

---

### 🔎 Course Project Intelligence MCP Server

我也在做一个面向高校计算机课程项目的 MCP Server，用来帮助 Agent 检索和分析课程项目资源。

它关注：

- GitHub 课程项目搜索
- 项目结构分析
- 多项目对比
- Evidence Card 上下文构造
- 风险提示：过时、非官方、低置信度、复制风险
- 对接 Claude Code / Cursor / Trae / 自研 Agent

核心目标不是“直接给答案”，而是给 Agent 提供更好的学习参考和项目情报。

---

### ⚙️ Performance & Systems

课程项目里我也做过一些偏底层的性能优化，例如：

- ARM Kunpeng 920 上的 SVD / Golub-Kahan 双对角化优化
- Linux `perf` 热点分析
- ARM NEON SIMD 点积与 AXPY 优化
- FPGA / Vivado 上的 8 位定点 CNN 链式运算器资源优化
- Verilog、时序报告、LUT / CARRY4 / IOB 资源分析

我很喜欢这种从“能跑”到“跑得快、说得清楚、测得明白”的过程。

---

## 🧩 Tech Stack

<div align="center">

### Languages

<img src="https://skillicons.dev/icons?i=ts,js,python,cpp,c,java,go,rust,html,css,md" />

### Frameworks & Tools

<img src="https://skillicons.dev/icons?i=nodejs,react,vite,spring,sqlite,git,github,docker,linux,vscode" />

### Also Exploring

<img src="https://skillicons.dev/icons?i=pytorch,cmake,nginx,bash" />

</div>

---

## 🛠️ Projects I Care About

### 🧠 Local-first Agent Framework

> 一个从零实现的本地 Agent 系统实验场。

我希望它具备：

- 类 Claude Code 的工具循环
- 类 OpenClaw 的本地工作区记忆
- 可审计的工具调用协议
- 多前端统一接入能力
- 安全沙箱与权限控制
- Multi-Agent 协作能力

设计理念：

```txt
Agent should not only answer.
Agent should remember, inspect, verify, execute, and explain.
```

---

### 🔍 MCP for Course Project Intelligence

> 面向课程项目发现、比较、学习参考的 MCP 工具服务。

它尝试解决的问题：

- 不知道课程项目能做什么
- 不知道 GitHub 上有哪些参考项目
- 不知道不同项目的技术路线差异
- 不知道哪些项目适合学习，哪些有复制风险
- 不知道如何把搜索结果变成 Agent 可用上下文

---

### 🧪 CS Coursework Lab Notes

我会把很多课程实验都当成完整工程来做，包括：

- 算法与动态规划
- 信息检索与 RAG
- 数据库建模与 Spring Boot 后端
- 并行程序设计与 SIMD 优化
- 数字逻辑、FPGA、Verilog
- CS336 风格的 LLM 基础训练作业

---

## 📌 My Engineering Taste

我偏好的系统设计方式：

```txt
1. 可运行 > 纯概念
2. 可测试 > 靠感觉
3. 可追踪 > 黑盒魔法
4. 可解释 > 堆功能
5. 可迭代 > 一步到位
```

我不太喜欢只停留在 PPT 上的架构图。  
我更喜欢这样的路线：

```txt
Idea → Minimal Prototype → Test → Log → Refactor → Report → Demo
```

---

## 📊 GitHub Stats

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=yfrcg&show_icons=true&theme=tokyonight&hide_border=true&rank_icon=github" />

<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=yfrcg&layout=compact&theme=tokyonight&hide_border=true" />

</div>

<div align="center">

<img src="https://github-readme-streak-stats.herokuapp.com?user=yfrcg&theme=tokyonight&hide_border=true" />

</div>

---

## 🌱 Currently Learning

- Multi-Agent Architecture
- Tool-use Agent Runtime
- Agent Sandbox & Security
- MCP Server Design
- RAG / Hybrid Search
- LLM Training Basics
- Performance Engineering
- Better Technical Writing

---

## 🎮 Fun Zone

我喜欢把主页做得更像一个“个人技术空间”，不只是简历。

```txt
            ┌──────────────────────────────┐
            │  Build systems.              │
            │  Break assumptions.          │
            │  Learn by shipping.          │
            └──────────────────────────────┘
```

<!-- 
如果你后续想做吃豆人贡献图，可以配合 GitHub Actions 生成：
https://github.com/abozanona/pacman-contribution-graph

生成后可以放开下面这行：

<p align="center">
  <img src="https://raw.githubusercontent.com/yfrcg/yfrcg/output/pacman-contribution-graph.svg" />
</p>
-->

---

## 📫 Contact

<div align="center">

<a href="https://github.com/yfrcg">
  <img src="https://img.shields.io/badge/GitHub-yfrcg-181717?style=for-the-badge&logo=github" />
</a>

<!-- 可以把下面替换成你的邮箱、博客或个人主页 -->
<!--
<a href="mailto:your-email@example.com">
  <img src="https://img.shields.io/badge/Email-Contact_Me-EA4335?style=for-the-badge&logo=gmail&logoColor=white" />
</a>
-->

</div>

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:F472B6,50:8B5CF6,100:6EE7F9&height=120&section=footer" />

</div>
