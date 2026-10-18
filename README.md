# Claude Bridge — releases

**English** · [简体中文](#简体中文)

Windows installers and module packages for **Claude Bridge**, a self-hosted AI agent workspace: run Claude Code on your own machine and use it from the desktop app, the Android app or any browser. This repository only hosts the release files; there is no source code here.

## Download

Get the latest version from [Releases](../../releases/latest).

| File | What it is |
|---|---|
| `bridge-client-setup-<version>.exe` | Windows installer (current user, no administrator rights needed) |
| `bridge-module-vertex-<version>.zip` | Module: the Gemini page, image / video / speech / music generation, and Claude's media tools |
| `bridge-module-codex-<version>.zip` | Module: the ChatGPT · Codex page (Codex binaries included) |
| `bridge-module-dimensio-<version>.zip` | Module: the dimensio page (multi-provider agent workspace) |

## Install

1. Run the installer and pick a role:
   - **Server**: this PC is the host. Everything runs locally, and your phone and other computers connect to it.
   - **Client**: connect to an existing host with a pairing code from the host's tray menu. Agents run on this PC; AI requests are relayed through the host.
2. The installer is the **base edition**: the Claude page plus browser, workspace, terminal and extensions.
3. For more pages, download the matching module package **from the same release**, open **Settings → Extensions → Modules**, choose **Install offline package**, and restart. Packages from a different release are rejected.

Installed modules can be switched off, uninstalled or undone at any time. When the app updates itself, installed modules are updated along with it.

Third-party services (Anthropic, Google, OpenAI and others) are used under your own accounts and their terms. Interface assets that resemble those services belong to their respective owners.

---

## 简体中文

**Claude Bridge** 的 Windows 安装包与功能扩展离线包。Claude Bridge 是自托管的 AI agent 工作台：把 Claude Code 跑在你自己的电脑上，从电脑客户端、安卓 App 或浏览器使用。本仓库只放发布文件，没有源码。

### 下载

到 [Releases](../../releases/latest) 下载最新版。

| 文件 | 内容 |
|---|---|
| `bridge-client-setup-<版本>.exe` | Windows 安装包（装在当前用户下，不用管理员权限） |
| `bridge-module-vertex-<版本>.zip` | 功能扩展：Gemini 分页、图像 / 视频 / 语音 / 音乐生成，以及 Claude 的媒体工具 |
| `bridge-module-codex-<版本>.zip` | 功能扩展：ChatGPT · Codex 分页（自带 Codex 程序） |
| `bridge-module-dimensio-<版本>.zip` | 功能扩展：dimensio 分页（多厂商 agent 工作台） |

### 安装

1. 运行安装包，二选一：
   - **成为服务端**：这台电脑就是主机，全部跑在本机，手机和别的电脑连它。
   - **成为客户端**：用主机托盘里拿到的配对码连到已有主机，agent 跑在这台电脑上，AI 请求经主机中转。
2. 安装包是**基础版**：Claude 分页加浏览器、工作空间、终端、扩展中心。
3. 要更多分页，从**同一个 Release** 下载对应的离线包，在「设置 → 扩展 → 功能扩展」点「安装离线包」，重启后生效。不同版本的离线包会被拒装。

装好的扩展可以随时关闭、卸载或撤销；客户端自动更新时，已装的扩展会一起换成新版。

第三方服务（Anthropic、Google、OpenAI 等）用的是你自己的账号，遵守各自的条款；界面上与这些服务相似的素材归各自所有者。
