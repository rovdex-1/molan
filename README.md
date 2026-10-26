# MOLAN

**MOLAN 是一款跨平台桌面浏览器：日常上网够快够干净，登录 MOLAN 账号后，还能把整个窗口切换成思维导图、白板、设计这些 MOLAN 自己的应用，文件保存在你的 MOLAN 云端。**

支持 macOS（Apple Silicon）、Windows（x64）和 Linux（x64）。

👉 [下载最新版本](https://github.com/rovdex-1/molan/releases/latest) · [安装说明](INSTALL.md)

---

## 亮点

### 一个窗口，浏览器和应用随时切换
- 左上角的切换器把整个 MOLAN 窗口变成某个应用，标签页原样留在后面；`⌃1`–`⌃9`（Windows / Linux 上是 `Alt+1`–`Alt+9`）一键切换。
- 应用按需安装：在「MOLAN 应用市场」里挑你需要的，装好就出现在切换器里，不用的随时卸载。
- 应用在后台自动保持最新，不需要手动更新。

### MOLAN 自己的应用
- **MOLAN 思维导图**：自研引擎，思维导图、逻辑图、组织架构图、树形图、时间轴、鱼骨图等 7 种结构，8 套主题，大纲视图双向编辑；导入导出 Markdown、OPML、XMind，导出 PNG 和 PDF。
- **MOLAN 白板**：手绘风格的草图、线框和流程图。
- **MOLAN 设计**：界面设计与原型，组件、自动布局、多人协作（基于开源项目 Penpot），用 MOLAN 账号直接进入，不用另外注册。
- 登录后文件自动保存到 MOLAN 云端，每个账号 1 GB，换一台电脑也能接着做；冲突时自动另存副本，不丢内容。

### 好用的浏览器本身
- 标签页分组、固定、静音，分屏浏览，标签页搜索，最近关闭的标签页一键恢复。
- 阅读模式、网页缩放（按网站记住）、网站权限管理、隐私窗口。
- 书签栏与书签管理，可从本机的 Chrome 导入书签和历史记录。
- 密码库与自动填充（系统钥匙串加密），下载管理，任务管理器。
- 把网站安装成独立的桌面应用（PWA）。
- 小程序：开箱即用的小游戏，支持和朋友在线开房间一起玩。

### 为 AI 时代准备
- 内置 MCP 服务：Claude 等 AI 助手可以在你的授权下操作浏览器，完成搜索、比价、整理资料等任务；高风险操作始终需要你确认。
- 规则包可以限定 AI 能在哪些网站、用哪些能力工作，每分钟的操作次数也可以设上限。

### 安全、透明
- 每个安装包都附带 `SHA256SUMS.txt`，安装前可以自行核对。
- 应用市场的目录由 MOLAN 的 Ed25519 密钥签名，浏览器验签、核对每个应用包的 SHA-256 后才会安装。
- 不是 MOLAN 出品的内容（本地应用文件夹、其他开发者的规则包）必须先打开「开发者模式」才能安装，和 Chrome 的扩展程序一样。
- 应用和小程序只在登录 MOLAN 账号后出现；不登录时，MOLAN 就是一个干净的普通浏览器。

---

## 下载

| 系统 | 安装包 |
|---|---|
| macOS（Apple Silicon） | `MOLAN-<版本>-macos-arm64.dmg` |
| Windows（x64） | `MOLAN-<版本>-windows-x64-Setup.exe` |
| Linux（x64） | `MOLAN-<版本>-linux-x64.deb` |

都在 [Releases](https://github.com/rovdex-1/molan/releases) 页面，每个版本另有 `.zip` 免安装包。安装完成后，MOLAN 会自动检查并安装新版本。

> 目前的安装包尚未经过 Apple / Microsoft 代码签名：macOS 首次打开可能需要在「访达」里右键选择「打开」，或在「系统设置 → 隐私与安全性」中允许；Windows 可能出现 SmartScreen 提示，选择「仍要运行」即可。详见 [INSTALL.md](INSTALL.md)。

---

## English

**MOLAN** is a cross-platform desktop browser for macOS (Apple Silicon), Windows (x64) and Linux (x64). Besides a fast, clean browser, signing in with a MOLAN account turns the whole window into MOLAN's own apps — a mind map, a whiteboard and a design tool — with your files saved to your MOLAN cloud.

- **Switch between the browser and apps** in one window (`⌃1`–`⌃9`); install apps from the MOLAN App Store; they keep themselves up to date.
- **MOLAN Mind Map** (own engine: 7 structures, 8 themes, outline view, Markdown / OPML / XMind import and export, PNG / PDF export), **MOLAN Whiteboard**, **MOLAN Design** (built on the open-source Penpot); 1 GB of cloud storage per account.
- **The browser itself**: tab groups, split view, tab search, reader mode, per-site zoom and permissions, private windows, bookmarks, Chrome import, password vault with autofill, PWAs, mini programs with online rooms.
- **Ready for AI**: a built-in MCP server lets AI assistants work in the browser with your permission; rule packs limit where and how.
- **Secure by design**: checksums for every installer, an Ed25519-signed app catalog, and developer mode required for anything not made by MOLAN.

[Download the latest release](https://github.com/rovdex-1/molan/releases/latest) · [Installation guide](INSTALL.md)

---

This repository distributes MOLAN releases: release notes, installers and checksums. Before installing, download `SHA256SUMS.txt` from the same release to verify the package.
