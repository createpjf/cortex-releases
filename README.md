<p align="center">
  <img width="96" alt="Cortex app icon" src="assets/icon.png" />
</p>

<h1 align="center">Cortex</h1>

<p align="center">
  <strong>Not just another agent harness.</strong>
</p>

<p align="center">
  A local-first AI workspace where agents work across your files, knowledge, apps, and chats — with you in control.
</p>

<p align="center">
  <a href="https://github.com/createpjf/cortex-releases/releases/latest"><img alt="Latest release" src="https://img.shields.io/github/v/release/createpjf/cortex-releases?label=release&color=111111" /></a>
  <img alt="macOS 13+ on Apple silicon" src="https://img.shields.io/badge/macOS-13%2B%20%C2%B7%20Apple%20silicon-111111?logo=apple" />
  <a href="https://github.com/createpjf/cortex-releases/releases"><img alt="Downloads" src="https://img.shields.io/github/downloads/createpjf/cortex-releases/total?color=111111" /></a>
</p>

<p align="center">
  English · <a href="#简体中文">简体中文</a>
</p>

<p align="center">
  <a href="#download">Download</a>
  ·
  <a href="#features">Features</a>
  ·
  <a href="#screenshots">Screenshots</a>
  ·
  <a href="#updates">Updates</a>
  ·
  <a href="#system-requirements">System requirements</a>
  ·
  <a href="#support">Support</a>
</p>

<p align="center">
  <img width="1024" alt="Cortex desktop app showing Cola, the personal work agent" src="assets/cortex-cola.png" />
</p>

## About

Most agent harnesses stop at a loop: a model, some tools, and a prompt. Cortex is the workspace around that loop. It gives the agent a place to work — projects and files, a verified knowledge base, a creative canvas, your desktop, and the chat apps your team already uses — and it keeps you in charge of what the agent may do.

Everything runs on your Mac. Conversations, projects, and settings are stored locally, and requests go only to the model providers you configure.

## Download

| Platform | Package |
| --- | --- |
| macOS 13 or later, Apple silicon | [Latest release (`.dmg`)](https://github.com/createpjf/cortex-releases/releases/latest) |

1. Open the latest release and download `Cortex-<version>-arm64.dmg`.
2. Drag **Cortex** into **Applications**.
3. On first launch, if macOS says the app can't be verified, open **System Settings › Privacy & Security** and click **Open Anyway**. Builds are signed with a Developer ID certificate but not yet notarized.

## Features

- **Cola, your work double.** A personal agent that follows up on work within the scope you allow, reads across your projects and conversations, and comes back when there is progress or a decision to make.
- **Agents with guardrails.** Choose **Ask for approval**, **Auto-approve**, or **Plan** for each conversation. Shell commands run in a write sandbox, and irreversible actions always need your confirmation.
- **Verified enterprise knowledge.** Answers cite their sources, and every citation is checked against the original document before it is shown.
- **Creative canvas.** Built on a design engine: generation nodes are artboards on the canvas, any layer can be a reference, and every version stays inside its node. Produce images and video, and run a selected chain after previewing it.
- **Computer use.** Let an agent operate apps on your Mac, with per-app permission prompts and one conversation in control at a time.
- **Skills and MCP connectors.** Install a dependency once and every conversation can use it. When a connector fails to start, Cortex shows why.
- **Interactive views.** Agents can answer with live charts, sliders, and demos that you can open beside the chat, tweak, and export as a web page.
- **Bots for WeChat, Feishu / Lark, DingTalk, and Telegram.** Send tasks from your phone and get results back in the same chat. Scan a QR code to create a Feishu app, and choose how replies stream back.
- **Built for daily work.** A per-conversation terminal, voice input with live transcription, subagents and background tasks, and automatic model routing.

## Screenshots

<p align="center">
  <img width="1000" alt="An interactive view in a reply, also opened in the right pane" src="assets/screenshot-view.png" />
</p>
<p align="center"><em>Interactive views: live demos in the reply and beside the chat</em></p>

<p align="center">
  <img width="1000" alt="Cola, the personal agent, with its profile panel" src="assets/screenshot-cola.png" />
</p>
<p align="center"><em>Cola: messenger-style chat with routines, memory, and model settings</em></p>

<p align="center">
  <img width="1000" alt="Knowledge base overview" src="assets/screenshot-knowledge.png" />
</p>
<p align="center"><em>Knowledge base: verified sources your agents can cite</em></p>

<p align="center">
  <img width="1000" alt="Bot settings with linking, routing, and reply mode" src="assets/screenshot-bots.png" />
</p>
<p align="center"><em>Bots: link a chat app, choose where messages go and how replies arrive</em></p>

## Updates

Cortex updates itself from this repository. The app checks for a new release shortly after launch and every four hours, downloads it in the background, and installs it the next time you quit — or right away from **Settings › Notifications & chats › Software update**, where you can also check manually or turn automatic checks off.

Release notes for each version (in English and Chinese) are on the [Releases](https://github.com/createpjf/cortex-releases/releases) page.

## System requirements

- macOS 13 Ventura or later
- Apple silicon (M1 or later)
- An API key for at least one model provider, added in **Settings › Models & providers**

Intel Macs, Windows, and Linux are not supported by these builds yet.

## Support

Found a bug or have a feature request? [Open an issue](https://github.com/createpjf/cortex-releases/issues/new) with your Cortex version (shown under **Settings › Notifications & chats › Software update**), your macOS version, and the steps to reproduce it. Please search [existing issues](https://github.com/createpjf/cortex-releases/issues) first.

## About this repository

This repository hosts signed release builds of Cortex and serves as its update feed. It does not contain source code.

© FLock.io. All rights reserved.

---

<a id="简体中文"></a>

## 简体中文

<p align="center">
  <strong>不只是又一个 Agent 外壳。</strong>
</p>

<p align="center">
  本地优先的 AI 工作台：Agent 在你的文件、知识库、应用和聊天之间协同工作，而你始终掌控全局。
</p>

### 简介

多数 Agent 外壳只做到一个循环：模型、几个工具和一段提示词。Cortex 是围绕这个循环搭起来的工作台：给 Agent 一个干活的地方——项目与文件、经过核验的知识库、创作画布、你的桌面，以及团队已在用的聊天应用——并让你决定它能做什么。

一切都在你的 Mac 上运行。对话、项目和设置都保存在本地，请求只发往你自己配置的模型供应商。

### 下载

| 平台 | 安装包 |
| --- | --- |
| macOS 13 及以上，Apple 芯片 | [最新版本（`.dmg`）](https://github.com/createpjf/cortex-releases/releases/latest) |

1. 打开最新版本，下载 `Cortex-<版本号>-arm64.dmg`。
2. 把 **Cortex** 拖进 **应用程序**。
3. 首次打开时，如果 macOS 提示无法验证，到「系统设置 › 隐私与安全性」点「仍要打开」。安装包已用 Developer ID 证书签名，但尚未公证。

### 功能

- **Cola，你的工作分身。** 个人 Agent，在你允许的范围内跟进工作，跨项目和对话查阅资料，有进展或需要你拍板时再来找你。
- **有边界的 Agent。** 每个对话可选「按需确认」「自动执行」或「计划」。命令在写入沙箱里运行，不可逆的操作一定要你确认。
- **经过核验的企业知识库。** 回答附带来源，每条引用都先和原文核对才会显示。
- **创作画布。** 以设计引擎为底：生成节点就是画布上的画板，任何图层都能作参考，每个版本都留在节点里。可生成图片和视频，并在预览确认后运行选定的链路。
- **操作电脑。** 让 Agent 操作你 Mac 上的应用，按应用逐个授权，同一时间只有一个对话在操作。
- **技能与 MCP 连接器。** 依赖装一次，所有对话都能用；连接器启动失败时，Cortex 会告诉你原因。
- **交互视图。** Agent 可以用可交互的图表、滑块和演示来回答，能在对话旁打开、调整并导出成网页。
- **微信、飞书 / Lark、钉钉、Telegram 机器人。** 在手机上发任务，结果回到同一个聊天。飞书扫码即可创建应用，回复方式也可以选。
- **为日常工作准备。** 每个对话一个终端、实时转写的语音输入、子代理与后台任务，以及自动选择模型。

### 截图

见上方英文部分的截图：交互视图、Cola、知识库、机器人设置。

### 更新

Cortex 从本仓库自动更新：启动后不久以及之后每四小时检查一次，后台下载，下次退出时安装；也可以在「设置 › 通知与对话 › 软件更新」里立即重启更新、手动检查或关闭自动检查。

每个版本的更新说明（中英双语）见 [Releases](https://github.com/createpjf/cortex-releases/releases) 页面。

### 系统要求

- macOS 13 Ventura 及以上
- Apple 芯片（M1 及以后）
- 至少一个模型供应商的 API Key，在「设置 › 模型」里添加

目前这些安装包暂不支持 Intel Mac、Windows 和 Linux。

### 支持

遇到问题或有功能建议？请 [提交 issue](https://github.com/createpjf/cortex-releases/issues/new)，附上 Cortex 版本（在「设置 › 通知与对话 › 软件更新」里查看）、macOS 版本和复现步骤。提交前请先搜索[已有 issue](https://github.com/createpjf/cortex-releases/issues)。

### 关于本仓库

本仓库存放 Cortex 已签名的发布版本，并作为更新源，不包含源代码。

© FLock.io。保留所有权利。
