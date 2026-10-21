# EOS Todo

[English](./README.en.md) | [中文](./README.md)

本地优先的桌面待办应用：待办、截图、专注计时与文件夹浏览。免费本地核心无需 EOS 账号，数据保存在本机；可选 Pro AI（自备密钥 / 托管积分）在使用托管 AI 时需登录账号。网络请求仅在你主动登录或使用 AI 时发生。

> **本仓库是 EOS Todo 的公开门户**，用于：
> - 安装包备份镜像：见 [Releases](https://github.com/eosaios/eos-todo/releases)
> - 问题反馈与功能建议：请提 [Issues](https://github.com/eosaios/eos-todo/issues)
>
> EOS Todo 是闭源商业软件，**源码不在本仓库**。请优先从[官网](https://eosaios.com/)或[账号门户](https://account.eosaios.com/)下载。

## 下载与安装

**推荐从官网下载。** GitHub Releases 为备份镜像。

当前镜像：[todo-mirror-v1.1.3](https://github.com/eosaios/eos-todo/releases/tag/todo-mirror-v1.1.3)

| 平台 | 安装包 | 说明 |
|---|---|---|
| macOS (Apple Silicon) | `eos-todo_1.1.3_darwin-arm64.dmg` | 未签名 |
| Windows (x64) | `eos-todo_1.1.3_windows-amd64.exe` | 便携 / 直接运行 |
| Linux (x64) | `eos-todo_1.1.3_linux-amd64.tar.gz` | 需 Ubuntu 24.04+ 或等效 GTK4 / WebKitGTK 6.0 |

- macOS 首次打开如被 Gatekeeper 拦截，请执行：`xattr -cr "/Applications/EOS Todo.app"`
- 数据保存在用户目录（如 macOS 的 `~/Library/Application Support/eos-todolist/`），升级安装不影响已有待办
- 完整性校验：Release 附带 `SHA256SUMS.txt`（及对应平台校验文件）

免费本地核心可直接使用；可选 Pro 能力与定价见[官网](https://eosaios.com/)。

## 功能

- **待办**：快速添加、行内编辑、完成 / 撤销、超过 24 小时未完成自动标红
- **截图**：全屏与区域截取，可排除应用自身窗口，保存或打开所在目录
- **专注计时**：30 秒到 2 小时多档倒计时，到点弹窗提醒
- **文件夹浏览**：应用内浏览本地目录
- **个性化**：明暗主题、中英文界面、可自定义全局快捷键
- **本地核心**：待办与本地功能无需账号；数据默认留在本机
- **可选 Pro AI**：支持自备密钥（BYOK）或托管积分；使用托管 AI 时需 EOS 账号

云同步尚未作为正式功能提供。

## 反馈指南

- 🐛 Bug 反馈：请附上操作系统版本、EOS Todo 版本号与复现步骤
- 💡 功能建议：描述你的使用场景，而不仅仅是方案
- 🔒 隐私相关：未登录、未使用 AI 时，应用不会为账号或模型发起请求；若观察到异常外连，请立即反馈

## 许可

© 2026 EOSAIOS. All rights reserved. 未经授权不得复制或再分发本软件。
