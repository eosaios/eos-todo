# EOS Todo

[English](./README.en.md) | [中文](./README.md)

本地优先的桌面待办清单应用：全部数据留在你自己的电脑上，没有账号，没有云端同步，没有遥测。待办管理、屏幕截图（全屏 / 区域，可排除应用自身窗口）、目录浏览与计时提醒，基于 Wails + Vue 3 构建。

> **本仓库是 EOS Todo 的公开门户**，用于：
> - 安装包下载：见 [Releases](https://github.com/eosaios/eos-todo/releases)
> - 问题反馈与功能建议：请提 [Issues](https://github.com/eosaios/eos-todo/issues)
> - 多平台构建（GitHub Actions）
>
> EOS Todo 是闭源商业软件，**源码不在本仓库**。

## 下载与安装

**beta 期间免费使用**，正式版定价将在临近发布时公布。

| 平台 | 安装包 | 说明 |
|---|---|---|
| Windows | `*-installer.exe` | NSIS 安装器，可选安装 WebView2 运行时 |
| macOS | `*.dmg` | universal（Intel + Apple Silicon），未签名 |
| Linux | `*.deb` / `*.AppImage` | deb 与 AppImage 双格式 |

- macOS 首次打开如被 Gatekeeper 拦截，请执行 `xattr -cr "/Applications/EOS Todo.app"`
- 数据保存在用户目录（如 macOS 的 `~/Library/Application Support/eos-todolist/`），升级安装不影响已有待办
- 完整性校验：各 Release 附带 SHA256SUMS.txt

## 功能

- **待办**：快速添加、行内编辑、完成 / 撤销、超过 24 小时未完成自动标红
- **截图**：全屏与区域截取，可排除应用自身窗口，保存或直接打开所在目录
- **专注计时**：30 秒到 2 小时多档倒计时，到点弹窗提醒
- **文件夹浏览**：应用内浏览本地目录
- **个性化**：明暗主题、中英文界面、可自定义全局快捷键
- **100% 本地**：运行时零网络请求（实测验证），数据永不离开你的电脑

## 反馈指南

- 🐛 Bug 反馈：请附上操作系统版本、EOS Todo 版本号与复现步骤
- 💡 功能建议：描述你的使用场景，而不仅仅是方案
- 🔒 隐私相关：本应用运行时不发起任何网络请求，如你观察到可疑行为请立即反馈

## 许可

© 2026 EOSAIOS. All rights reserved. 未经授权不得复制或再分发本软件。
