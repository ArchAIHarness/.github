<div align="center">

# ArchAIHarness

### 重塑 AI 时代下的软件开发新秩序

![License](https://img.shields.io/badge/Open%20Source-MIT-green?style=flat-square)
![Repos](https://img.shields.io/badge/Repos-30+-blue?style=flat-square)
![Articles](https://img.shields.io/badge/Articles-22-orange?style=flat-square)

</div>

---

## 我们在做什么

把多智能体协作从能演示推到能交付。

过去 6 个月交付了：

- **Agent 控制面** — `agent-master` 在 K8s 上按人调度 Agent 实例，TTL 租约回收，透明 API 代理
- **Agent Runtime 镜像** — `agent-image` / `agent-image-webui` / `build-on-vscode-opencode-image`，开箱即用的容器化 Agent 底座
- **Agent 插件框架** — `agent-plugin` 的 agents + skills + tools 插拔式扩展（建设中）
- **Agent IDE** — `agent-webui` 基于 OpenSumi 的 Web IDE 设计
- **社区 Agent 平台** — 9 个 `community-*` 私有仓库，从 cloudlab 开源项目改造中
- **22 篇专栏** — [看懂 AI 与智能体](https://github.com/ArchAIHarness/zhuanlan-ai-and-agents)，日均 2 篇连载

---

## 核心理念

**人立法，AI 执行，体系审计。**

架构师不写每一行代码。架构师写规则：

1. **定边界** — 领域划分、分层约束、上下文边界，写在 AGENTS.md 里，AI 能读、人能审
2. **给工具** — Skills / MCP / Plugins，让 AI 在规则内执行，不出界
3. **建审计** — 每步可检查、可回溯、可沉淀为新的规则

---

## 仓库速览

| 资产 | 说明 |
|------|------|
| [`docs`](https://github.com/ArchAIHarness/docs) | 方法论与实践指南 |
| [`framework`](https://github.com/ArchAIHarness/framework) | DDD 多租户工程底座 |
| [`gateway`](https://github.com/ArchAIHarness/gateway) | 反应式网关示例 |
| [`agent-master`](https://github.com/ArchAIHarness/agent-master) | Agent 控制面（K8s 调度） |
| [`agent-image`](https://github.com/ArchAIHarness/agent-image) | Agent 无头 Runtime 镜像 |
| [`agent-image-webui`](https://github.com/ArchAIHarness/agent-image-webui) | Agent WebUI Runtime 镜像 |
| [`agent-webui`](https://github.com/ArchAIHarness/agent-webui) | 基于 OpenSumi 的 Agent IDE |
| [`agent-plugin`](https://github.com/ArchAIHarness/agent-plugin) | 插件框架（建设中） |
| [`agent-workflows`](https://github.com/ArchAIHarness/agent-workflows) | 可复用 Agent 工作流模板（Pipeline / 审核 / 发布） |
| [`feishu-bot`](https://github.com/ArchAIHarness/feishu-bot) | 飞书 IM Agent 接入（WebSocket + 消息桥 + 三道闸） |
| [`community-*`](https://github.com/ArchAIHarness) | 社区 Agent 平台（私有，改造中） |

---

<div align="center">

**ArchAIHarness**

<sub>Engineered by Architects · Empowered by AI · Audited by Discipline</sub>

</div>
