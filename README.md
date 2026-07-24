<div align="center">

<!-- 波浪动画横幅（头部） -->
<a href="https://github.com/kesepain-KE">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:00C9FF,100:92FE9D&height=200&section=header&text=kesepain&fontSize=60&fontAlignY=35&animation=fadeIn&fontColor=white" />
</a>

<h1 align="center">你好呀 👋 我是 kesepain</h1>

<p align="center">
  <img src="https://img.shields.io/badge/构建-AI%20Agent-00C9FF?style=for-the-badge&logo=robotframework&logoColor=white" />
  <img src="https://img.shields.io/badge/拆解独立-不继承整合-92FE9D?style=for-the-badge&logo=awesomewm&logoColor=white" />
  <img src="https://img.shields.io/badge/嵌入式计算-爱好者-36D1DC?style=for-the-badge&logo=raspberrypi&logoColor=white" />
  <img src="https://img.shields.io/badge/嵌入式-学习中-FF6B6B?style=for-the-badge&logo=espressif&logoColor=white" />
</p>

</div>

---

## 🧑‍💻 关于我

- 🔭 正在搭建 **AI Agent 生态**：核心框架 + 网关适配层 + 知识图谱 + 硬件技能，模块化拆解独立维护
- 🧩 信奉「**拆解独立，不继承整合**」——单一职责，通过 API / 协议通信，不共享代码库
- 🖥️ 多设备分布式部署：树莓派 · J1900-ITX · x86 服务器 · 软路由，Agent 跑在各种边缘节点上
- 🌱 正在探索 **任务驱动的动态 Agent 集群** 和 **Loop 式智能体**
- 📟 最近在学习 **ESP32 / STM32 嵌入式开发**，把 AI 能力延伸到物理世界
- 💬 聊天可以聊 **Python、AI Agent、LLM、工具调用、知识图谱、边缘部署、嵌入式**
- ⚡ 有趣的事实：**我给自己造的 AI Agent 当猫猫助手 🐱**
- 📫 联系我：**[kesepain@github](https://github.com/kesepain-KE)**

<br>

<!-- 分隔线 -->
<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=gradient&height=1" />

<br>

## 🚀 项目展示

| 项目 | 描述 | 技术栈 | ⭐ |
|:-----|:-----|:--------|:--:|
| [**kemo-agent**](https://github.com/kesepain-KE/votx-agent) 🔥 | 🚀 多用户 AI Agent 框架 — 事件驱动架构、工具调用、持久记忆、自我改进、多模态、外部消息路由、子代理系统 | Python / Flask / React / TypeScript | ⭐7 |
| [**kemo-graph**](https://github.com/kesepain-KE/kesepain-graph) 🧠 | 📊 本地知识图谱管理服务 — 图数据库 + 知识检索 + Obsidian 兼容（已归档，新版本重构中） | Python / FastAPI / Vue 3 / D3.js | ⭐1 |
| [**llm-adapter-kemo**](https://github.com/kesepain-KE/llm-adapter-votx) | 🔌 LLM API 调用适配层 — 多提供商并发管理 + 多模态中转 + Token 精确统计 | Python / FastAPI / Node.js | ⭐1 |
| [**raspberry-pi-skill**](https://github.com/kesepain-KE/raspberry-pi-skill) | 🥧 树莓派硬件控制技能包 — GPIO 读写 / PWM / I2C / SPI / UART / 传感器 + 系统监控 | Python | ⭐1 |
| [**esp32-control**](https://github.com/kesepain-KE/votx-agent) | 📡 ESP32 远程控制拓展 — WiFi 远程 GPIO 操控 / 传感器采集 / 实时状态监控（kemo-agent 拓展模块） | Python / Arduino | - |
| [**kesepain-Agent**](https://github.com/kesepain-KE/kesepain-Agent) | 📦 初代终端 Agent 框架（已归档） | Python | ⭐3 |

<br>

## 🏗️ 项目生态

```
┌─ 网关层 ───────────────────────────┐
│  llm-adapter-kemo                    │  ← 多提供商 API 中转 + 多模态
└──────────────┬──────────────────────┘
               │ 提供 LLM 能力
┌──────────────▼──────────────────────┐
│  kemo-agent (votx-agent ✦)          │  ← Agent 核心框架（事件驱动 / 自迭代）
└──┬──────────┬──────────┬───────────┘
   │          │          │
   ▼          ▼          ▼
┌──────┐  ┌────────┐  ┌──────────┐
│ 知识  │  │  硬件   │  │  外部    │
│ 图谱  │  │  技能   │  │  消息    │
│kemo- │  │ pi-skill│  │  QQ/TG   │
│graph │  │ esp32-  │  │  Telegram│
│      │  │ control │  │          │
└──────┘  └────────┘  └──────────┘
```

> 每个模块独立仓库，通过 API / 协议通信。不搞单体，不搞继承。

<br>

<!-- 分隔线 -->
<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=gradient&height=1" />

<br>

## 🛠️ 技术栈

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black" />
  <img src="https://img.shields.io/badge/Vue.js-4FC08D?style=for-the-badge&logo=vuedotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" />
  <img src="https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white" />
  <img src="https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white" />
  <img src="https://img.shields.io/badge/Raspberry%20Pi-A22846?style=for-the-badge&logo=raspberrypi&logoColor=white" />
  <img src="https://img.shields.io/badge/ESP32-E7352C?style=for-the-badge&logo=espressif&logoColor=white" />
  <img src="https://img.shields.io/badge/STM32-03234B?style=for-the-badge&logo=stmicroelectronics&logoColor=white" />
</p>

<p align="center">
  <img src="https://skillicons.dev/icons?i=py,flask,fastapi,react,vue,ts,docker,git,linux,sqlite,nginx,bash&perline=12" />
</p>

<br>

<!-- 分隔线 -->
<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=gradient&height=1" />

<br>

## 📊 GitHub 数据

<div align="center">
  <img height="170" src="https://github-readme-stats-sigma-five.vercel.app/api?username=kesepain-KE&show_icons=true&theme=tokyonight&hide_border=true" />
  <img height="170" src="https://github-readme-stats-sigma-five.vercel.app/api/top-langs/?username=kesepain-KE&layout=compact&theme=tokyonight&hide_border=true" />
</div>

<br>

<div align="center">
  <img src="https://github-readme-streak-stats-eight.vercel.app/?user=kesepain-KE&theme=tokyonight&hide_border=true" width="75%" />
</div>

<br>

<!-- 分隔线 -->
<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=gradient&height=1" />

<br>

<div align="center">
  
  ## 📦 近期动态
  
  | 时间 | 事件 |
  |:----|:-----|
  | 🆕 | **kemo-agent** 本地演进中 — votx-agent 架构升级，事件驱动 + 子代理系统 |
  | 🆕 | **ESP32 远程控制** 上线 — WiFi GPIO 操控，AI 能力延伸到物理世界 |
  | 🔄 | **kesepain-graph** 归档中 — 新 kemo-graph 采用知识图谱替换方案 |
  | 📚 | 学习 **STM32 / ESP32** 裸机开发 — 零基础入门嵌入式 |
  
</div>

<br>

---

<br>

<div align="center">
  <i>✨ 用优雅的架构，让代码改变世界 ✨</i>
  <br><br>
  <img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=tokyonight" width="80%" />
</div>

<br>

<!-- 波浪动画横幅（尾部） -->
<a href="https://github.com/kesepain-KE">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:92FE9D,100:00C9FF&height=120&section=footer&animation=twinkling" />
</a>
