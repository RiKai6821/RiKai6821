<h1 align="center">Hi 👋, I'm RiKai</h1>
<h3 align="center">Computer Science MS · AI Agent & LLM Engineering</h3>
<p align="center">Multi-Agent · Agentic RAG · LLMOps&nbsp;&nbsp;|&nbsp;&nbsp;Full-stack: LLM apps ↔ RISC-V · RTOS · bare-metal</p>

---

🤖 主攻 **AI Agent · 多智能体 · Agentic RAG** — Function Calling 工具编排 · 手写 ReAct · 多 Agent 协作 · 检索增强 + 双层防幻觉

🌱 深入 **LangChain / LangGraph · LlamaIndex · RAG 检索优化 · LLM 工程化 (LLMOps)** — 评估 (LLM-as-a-Judge) · 可观测 (p50/p95) · 限流 / 重试 / 超时 / 背压 · Docker / K8s

🔩 **软硬件全栈,上能 LLM、下能裸机** — 手写 **RISC-V 指令集模拟器 · Cortex-M 抢占式 RTOS 内核 · STM32 裸寄存器驱动**（见下方 Systems & Embedded）

🔗 **端云协同** — 用 **ESP32** 把 AI Agent 接到物理设备

💬 关于 **AI Agent / RAG / LLM 应用 / Python / 嵌入式 C** 的问题都可以问我

📫 联系我：GitHub Issues 或主页邮箱

---


### 🚀 Featured Projects · AI Agent / LLM

#### 🏭 Manufacturing Multi-Agent System · Multi-Agent + Agentic RAG
面向半导体设备诊断的多智能体系统：1 协调 + 6 执行 Agent 协作完成「数据查询 → 知识检索 → 根因诊断 → 质量评审 → 生成工单」全闭环。
`Function Calling` · `手写 ReAct` · `FAISS / Milvus / LlamaIndex` · `三层记忆` · `双层防幻觉` · `模型路由 ↓28%` · `FastAPI` · `Docker / K8s`

#### 🎙️ End–Cloud AI Agent Service · Function Calling + RAG + 端云协同
生产级 AI Agent 语音助手：手写工具调用编排 + 三层记忆 + RAG + Prompt 工程，并与 ESP32 物联网设备端云协同集成。
`Function Calling` · `RAG` · `异步 5 并发 3.8×` · `限流 / 重试 / 超时 / 背压` · `可观测 p50·p95` · `LLM-as-a-Judge` · `FastAPI` · `Docker / CI`

---

### 🔩 Systems & Embedded · 底层 / 系统能力

#### 🧩 [riscv-rv32-emulator](https://github.com/RiKai6821/riscv-rv32-emulator) · 从零用 C 实现 RISC-V RV32I(+M) 指令集模拟器
取指-译码-执行 · CSR / 陷阱 / CLINT 定时器中断 · **手写 GDB RSP 调试桩**（真实 gdb 远程单步）· 自研抢占式 OS + **在其上跑起官方 FreeRTOS**
`RISC-V` · `RV32I/M` · `ISA Simulator` · `GDB RSP` · `FreeRTOS` · `68 单测 / ASan 干净 / CI ✅`

#### 📟 [stm32-sensor-hub](https://github.com/RiKai6821/stm32-sensor-hub) · STM32F103 寄存器级多传感器采集系统
**裸寄存器**驱动 GPIO / ADC / SPI / I2C / DHT11（不用 HAL）· FreeRTOS 采集·通信·显示多任务（队列 + 互斥量）· 串口帧协议 + PyQt 上位机实时画波形
`STM32F103` · `Bare-metal` · `FreeRTOS` · `逻辑分析仪抓波形` · `Python 上位机`

#### ⚙️ [cortex-m-rtos](https://github.com/RiKai6821/cortex-m-rtos) · 从零写 Cortex-M3 抢占式 RTOS 内核
PendSV 汇编上下文切换 · **优先级继承互斥量** · 消息队列 · 软件定时器 · 内核做 port 抽象，可在宿主机 **39 单测**验证
`Cortex-M3` · `RTOS Kernel` · `优先级继承` · `Context Switch` · `Host-tested / CI ✅`

---

### 🛠️ Tech Stack

![C](https://img.shields.io/badge/C-A8B9CC?style=flat&logo=c&logoColor=black)
![C++](https://img.shields.io/badge/C++-00599C?style=flat&logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=flat&logo=rust&logoColor=white)

![RISC-V](https://img.shields.io/badge/RISC--V-283272?style=flat&logo=riscv&logoColor=white)
![STM32](https://img.shields.io/badge/STM32-03234B?style=flat&logo=stmicroelectronics&logoColor=white)
![FreeRTOS](https://img.shields.io/badge/FreeRTOS-2D7D46?style=flat&logo=freertos&logoColor=white)
![Arduino](https://img.shields.io/badge/Arduino-00979D?style=flat&logo=arduino&logoColor=white)
![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=flat&logo=espressif&logoColor=white)
![Raspberry Pi](https://img.shields.io/badge/Raspberry%20Pi-A22846?style=flat&logo=raspberrypi&logoColor=white)

![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=flat&logo=visualstudiocode&logoColor=white)
![CLion](https://img.shields.io/badge/CLion-000000?style=flat&logo=clion&logoColor=white)
![Vim](https://img.shields.io/badge/Vim-019733?style=flat&logo=vim&logoColor=white)

![Claude](https://img.shields.io/badge/Claude-D97757?style=flat&logo=claude&logoColor=white)
![ChatGPT](https://img.shields.io/badge/ChatGPT-412991?style=flat&logo=openai&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=flat&logo=googlegemini&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat&logo=langchain&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat&logo=huggingface&logoColor=black)

---

### 📊 GitHub Stats

<p align="center">
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=RiKai6821&show_icons=true&theme=default&count_private=true" />
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=RiKai6821&layout=compact&count_private=true" />
</p>

---

### 🐍 Contribution Snake

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/RiKai6821/RiKai6821/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/RiKai6821/RiKai6821/output/github-contribution-grid-snake.svg" />
  <img alt="snake" src="https://raw.githubusercontent.com/RiKai6821/RiKai6821/output/github-contribution-grid-snake.svg" />
</picture>
