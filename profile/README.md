<div align="center">

# 让架构师驾驭 AI，而非被 AI 牵引

### 一套以「架构治理」驯化「AI 编码」的企业级工程体系

<sub>**ArchAIHarness** · AI 架构实验室</sub>

[![MIT License](https://img.shields.io/badge/License-MIT-success.svg?style=flat-square)](LICENSE)
[![GitHub Org](https://img.shields.io/badge/Organization-ArchAIHarness-181717?style=flat-square&logo=github)](https://github.com/ArchAIHarness)
[![Paradigm](https://img.shields.io/badge/Paradigm-DDD-blue?style=flat-square)](https://github.com/ArchAIHarness)
[![Stack](https://img.shields.io/badge/Stack-Spring%20Cloud-6DB33F?style=flat-square&logo=spring)](https://github.com/ArchAIHarness)
[![Architecture](https://img.shields.io/badge/Architecture-Multi--Tenant-orange?style=flat-square)](https://github.com/ArchAIHarness)

</div>

<br/>

## 🌪 问题 · 失控的代际

AI 编码正在以前所未有的速度涌入工程现场。

它写得很快，也错得很快。它生成的代码能跑，却不一定属于这个系统；能交付功能，却在悄悄腐蚀架构。当团队把"提效"作为唯一指标，**架构的熵增，正在被 AI 加速。**

我们看到三类正在发生的崩塌：

- **领域语言的失守**——AI 不懂业务，于是用通用语义覆盖领域语义，限界上下文被悄悄抹平。
- **架构纪律的瓦解**——AI 不懂规范，于是按"互联网最常见写法"产出代码，分层、依赖、隔离被随手击穿。
- **审计链路的断裂**——AI 不留意图，于是产物无法回溯，问题无法归因，责任无法落地。

提效从来不是问题。**失控才是。**

<br/>

## 🧭 主张 · 重建秩序

> **架构师定义秩序，AI 在秩序中生长。**

AI 编码的上限，不取决于模型多强，而取决于**约束多清晰**。
一个没有架构师定义边界的 AI 工程，是放养；一个被架构师定义边界的 AI 工程，才是协同。

我们相信下一代研发范式不是"人 vs AI"，也不是"人被 AI 替代"，而是：

**人立法，AI 执行，体系审计。**

- 架构师 retreat 回到他真正不可替代的位置——**定义领域、制定规范、守护底线**。
- AI 走到它最擅长的位置——**承载样板、消化重复、加速交付**。
- 中间需要一套**可被 AI 理解、可被 AI 执行、可被人类审计**的工程基座，把两者咬合起来。

这套基座，就是 **ArchAIHarness**。

<br/>

## 🛠 方法 · 四根支柱

我们没有发明新的银弹，我们做的是把成熟范式"翻译"成 AI 能听懂的语言：

**第一，用 DDD 做语义骨架。**
领域驱动设计天然提供了"业务语义 + 边界 + 分层"，这恰恰是 AI 最缺、又最需要被喂进上下文的东西。我们把限界上下文、聚合根、领域服务做成可被 AI 识别的模板与约束，让 AI 在生成代码时**先理解领域，再写代码**。

**第二，用 agents.md 做工程契约。**
我们把团队的架构规范、命名约定、分层规则、禁止事项，全部沉淀为 `agents.md`——一份既是给人看的规范、也是给 AI 看的指令的文档。它不是注释，是**合约**。AI 越界，体系即可识别。

**第三，用 MCP 做语义通信。**
模型不该靠"猜"来理解你的系统。我们通过 MCP（Model Context Protocol）把领域参数、上下文、租户语义结构化地传递给 AI，让 AI 的每一次生成都有据可依、有界可循。

**第四，用 Skill Market 做能力插拔。**
没有放之四海皆准的 AI 技能。我们把领域能力封装为可插拔的技能包，团队按需引入，**避免万能 Agent，拥抱专用 Agent**。

<br/>

## 📈 成效 · 可验证的收益

我们不承诺银弹，我们承诺**可验证的工程收益**：

- **交付节奏** — 通过样板代码、工程契约与重复劳动消化，降低协作成本并提升交付可控性。
- **架构一致性** — 规范在 AI 生成阶段即被显式约束，而非完全依赖 Code Review 事后补救。
- **心智负担** — 工程师从"写胶水代码"中解放，把精力还给真正的业务建模与系统设计。
- **可审计性** — 每一段 AI 产物都可追溯到约束、上下文与意图，问题可归因、责任可落地。
- **团队可复制性** — 新成员（包括 AI 新成员）通过规范文档即可对齐工程标准，组织能力沉淀为体系能力。

<br/>

## 🎯 场景 · 为谁而生

如果你正面对以下场景，这套体系为你而生：

构建**多租户 SaaS 平台**，需要租户隔离、上下文透传与领域权限基座；
搭建**云原生微服务体系**，希望深度契合 Spring Cloud 生态、开箱即用；
治理**企业业务中台**，需要 DDD 限界上下文与业务域天然映射；
交付**金融、供应链、政企等强合规系统**，要求架构纪律不可妥协；
带领团队**拥抱 AI 提效，又拒绝放养式 AI 编码**。

如果你只是想让 AI 帮你写个脚本，这套体系对你过重。
如果你想让 AI 成为团队可信赖的工程伙伴，欢迎对号入座。

<br/>

## 🧩 生态 · 四位一体

ArchAIHarness 由四个相互咬合的开源项目组成，分别承担**骨架、神经、能力、思想**四个角色。

<br/>

### 🦴 [`framework`](https://github.com/ArchAIHarness/framework) — 骨架

**AI 架构 DDD 脚手架**

整套生态的核心底座。内置 `agents.md` 工程契约、DDD 分层模板与多租户基础架构，是 AI 生成代码时"必须遵守的法律"。

<br/>

### 🧠 [`gateway`](https://github.com/ArchAIHarness/gateway) — 神经

**反应式 API 网关与统一接入层**

承载鉴权链路、租户上下文透传与接入层治理，让业务服务在统一边界内对外协作。

<br/>

### ⚡ [`skills`](https://github.com/ArchAIHarness/skills) — 能力

**AI 架构领域技能库**

可插拔的 DDD 专属 AI 技能包。按需引入，能力即装即用，让团队拥有"专用 AI"而非"万能 AI"。

<br/>

### 📖 [`docs`](https://github.com/ArchAIHarness/docs) — 思想

**AI 架构白皮书与布道文档**

设计哲学、落地案例、架构图纸、工程培训素材的统一出口。体系背后的"为什么"，都在这里。

<br/>

## 🤝 同行 · 与我们共建

ArchAIHarness 以 **MIT 协议** 全面开源。

我们不只在写代码，我们在尝试回答一个更大的问题：

> **当 AI 全面进入工程现场，架构师的位置在哪里？**

我们相信答案不在"对抗"，也不在"投降"，而在**重建秩序**。

如果你是**架构师**，欢迎把你对 AI 编码的焦虑写成 Issue；
如果你是**领域专家**，欢迎贡献你的限界上下文设计；
如果你是**AI 工程师**，欢迎共建 MCP 协议与技能市场；
如果你是**开源爱好者**，欢迎用 Star 告诉我们：这条路值得走下去。

<br/>

<div align="center">

**ArchAIHarness · AI 架构实验室**

<sub>Engineered by Architects · Empowered by AI · Audited by Discipline</sub>

</div>
