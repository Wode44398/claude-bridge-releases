# Bridge — releases (moved)

**English** · [简体中文](#简体中文)

> **Releases have moved to [Wode44398/bridge](https://github.com/Wode44398/bridge/releases).** Starting with 2026.11.24.0643, installers, module packages and the Android app are published there, next to the source code. This repository is archived (read-only). Installed apps keep updating on their own: older versions first update to 2026.11.24.0643 from here, and that version follows Wode44398/bridge from then on. Releases up to 2026.11.24.0643 stay available below. Please open new issues in [Wode44398/bridge](https://github.com/Wode44398/bridge/issues).

Windows installers and module packages for **Bridge** (formerly Claude Bridge), a self-hosted AI agent workspace: run Claude Code on your own machine and use it from the desktop app, the Android app or any browser. This repository holds the release files up to 2026.11.24.0643; the source code and newer releases are in [Wode44398/bridge](https://github.com/Wode44398/bridge).

## Download

Get the latest version from [Wode44398/bridge Releases](https://github.com/Wode44398/bridge/releases/latest).

| File | What it is |
|---|---|
| `bridge-client-setup-<version>.exe` | Windows installer (current user, no administrator rights needed) |
| `bridge-module-studio-<version>.zip` | Module: Media Studio — image / video / speech / music generation, and Claude's media tools |
| `bridge-module-codex-<version>.zip` | Module: the ChatGPT · Codex page (Codex binaries included) |
| `bridge-module-agy-<version>.zip` | Module: the Antigravity page (requires Google's Antigravity CLI, `agy`, installed and signed in on this PC; not included) |
| `bridge-module-dimensio-<version>.zip` | Module: the dimensio page (multi-provider agent workspace) |
| `ClaudeBridge-offline-<versionCode>.apk` | Android app (your server also offers it at `/download/android`) |

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

> **发布已迁到 [Wode44398/bridge](https://github.com/Wode44398/bridge/releases)。** 从 2026.11.24.0643 起，安装包、功能扩展离线包和安卓 App 都发在那边，和源码放在一起。本仓库已归档（只读）。已经装好的电脑和手机照常自动更新：更早的版本先从这里升到 2026.11.24.0643，这一版起改从 Wode44398/bridge 更新。2026.11.24.0643 及以前的版本仍留在本仓库。新问题请到 [Wode44398/bridge](https://github.com/Wode44398/bridge/issues) 提。

**Bridge**（原名 Claude Bridge）的 Windows 安装包与功能扩展离线包。Bridge 是自托管的 AI agent 工作台：把 Claude Code 跑在你自己的电脑上，从电脑客户端、安卓 App 或浏览器使用。本仓库存放 2026.11.24.0643 及以前的发布文件；源码和更新的版本在 [Wode44398/bridge](https://github.com/Wode44398/bridge)。

### 下载

到 [Wode44398/bridge 的 Releases](https://github.com/Wode44398/bridge/releases/latest) 下载最新版。

| 文件 | 内容 |
|---|---|
| `bridge-client-setup-<版本>.exe` | Windows 安装包（装在当前用户下，不用管理员权限） |
| `bridge-module-studio-<版本>.zip` | 功能扩展：Media Studio——图像 / 视频 / 语音 / 音乐生成，以及 Claude 的媒体工具 |
| `bridge-module-codex-<版本>.zip` | 功能扩展：ChatGPT · Codex 分页（自带 Codex 程序） |
| `bridge-module-agy-<版本>.zip` | 功能扩展：Antigravity 分页（这台电脑要先装好并登录 Google 的 Antigravity CLI，也就是 `agy`；离线包不带它） |
| `bridge-module-dimensio-<版本>.zip` | 功能扩展：dimensio 分页（多厂商 agent 工作台） |
| `ClaudeBridge-offline-<版本号>.apk` | 安卓 App（你的服务端也会在 `/download/android` 提供同一版） |

### 安装

1. 运行安装包，二选一：
   - **成为服务端**：这台电脑就是主机，全部跑在本机，手机和别的电脑连它。
   - **成为客户端**：用主机托盘里拿到的配对码连到已有主机，agent 跑在这台电脑上，AI 请求经主机中转。
2. 安装包是**基础版**：Claude 分页加浏览器、工作空间、终端、扩展中心。
3. 要更多分页，从**同一个 Release** 下载对应的离线包，在「设置 → 扩展 → 功能扩展」点「安装离线包」，重启后生效。不同版本的离线包会被拒装。

装好的扩展可以随时关闭、卸载或撤销；客户端自动更新时，已装的扩展会一起换成新版。

第三方服务（Anthropic、Google、OpenAI 等）用的是你自己的账号，遵守各自的条款；界面上与这些服务相似的素材归各自所有者。
