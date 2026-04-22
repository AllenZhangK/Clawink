<p align="center">
  <img src="assets/clawink_logo.png" alt="Clawink — OpenClaw for Business Systems" width="800" />
</p>

<p align="center">
  <strong>Clawink — OpenClaw for Business Systems</strong><br />
  把复杂业务系统升级为 AI 可理解、可规划、可执行的产品层。
</p>

<p align="center">
  接入你的系统 · 发布可执行能力 · 让 AI 规划、预览、确认并执行真实业务
</p>

<p align="center">
  <a href="LICENSE"><img src="https://img.shields.io/badge/License-Apache%202.0-blue.svg" alt="Apache 2.0 License" /></a>
  <img src="https://img.shields.io/badge/Open%20Source-Preview-black" alt="Open Source Preview" />
  <img src="https://img.shields.io/badge/Code%20Release-Planned-0A7EA4" alt="Code Release Planned" />
</p>

<p align="center">
  <a href="README.md">English</a> ·
  <a href="README_zh-CN.md">中文</a> ·
  <a href="README_ja.md">日本語</a> ·
  <a href="README_ko.md">한국어</a> ·
  <a href="README_es.md">Español</a>
</p>

<p align="center">
  <a href="#why-clawink-zh">为什么是 Clawink</a> ·
  <a href="#architecture-zh">架构图</a> ·
  <a href="#status-zh">当前状态</a> ·
  <a href="#roadmap-zh">开放路线</a> ·
  <a href="#community-zh">社区参与</a>
</p>

---

<a id="why-clawink-zh"></a>

## 为什么是 Clawink

大多数业务系统真正的问题，不是能力不够，而是使用门槛太高。

用户往往要先理解菜单、流程、权限和操作规则，系统能力才真正用得起来。Clawink 要做的，不是在复杂系统外面再包一层聊天界面，而是把系统能力整理成 AI 可以稳定理解、规划和执行的操作层，让用户从“先学系统”切换为“直接说目标”。

Clawink 的核心机制建立在两条打通但分离的主链上：

- 规划线：读取文档、识别能力、生成工作流草稿、校验并发布运行时可用资产。
- 对话运行线：只消费已发布资产，不在用户发消息时临场重建整套能力。

正因为这两条主链是分离的，Clawink 才不是简单的聊天壳，而是面向真实业务系统的 AI 操作层。

<a id="architecture-zh"></a>

## 架构图

规划侧负责沉淀和发布资产，运行侧只执行已经发布的能力，并在预览、确认和运行约束下完成真实操作。

<p align="center">
  <img src="assets/clawink_arch_zh.png" alt="Clawink 架构图" width="1400" />
</p>

<a id="status-zh"></a>

## 当前状态

当前仓库是 Clawink 的公开预览仓。

- 目前只公开产品介绍、架构图、开放路线和品牌素材。
- 核心运行时代码与产品代码仍保留在私有主仓，等待产品机制进一步稳定。
- 后续代码开放会通过“私有主仓 -> 公开仓”的单向同步方式分阶段发布。

这意味着 Clawink 正在走向开源，但当前仓库还不是完整代码开源版。

<a id="roadmap-zh"></a>

## 开放路线

当前的开放计划分为四个阶段：

1. 公开预览阶段：只发布 README、架构、路线图和品牌素材。
2. 核心能力开放：择机开放部分运行时模块、打包结构和最小开发流程。
3. 扩展能力开放：逐步开放部分 Skill、集成示例和外部扩展文档。
4. 更完整的开源版本：逐步扩大公开模块范围，并完善 CI 与社区协作路径。

详细计划见 [ROADMAP.md](ROADMAP.md)。

<a id="community-zh"></a>

## 社区参与

- 关注仓库，跟踪公开发布节点。
- 通过 Issues 或 Discussions 提交场景需求、接入诉求和反馈。
- 在正式代码开放前，请以路线图和公开说明为准评估接入计划。

