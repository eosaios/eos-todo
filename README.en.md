# EOS Todo

[English](./README.en.md) | [中文](./README.md)

A local-first desktop todo app: all data stays on your own machine — no accounts, no cloud sync, no telemetry. Todos, screen capture (fullscreen / region, with an option to exclude the app's own window), folder browsing and timer reminders. Built with Wails + Vue 3.

> **This repository is the public home of EOS Todo**, used for:
> - Downloads: see [Releases](https://github.com/eosaios/eos-todo/releases)
> - Bug reports and feature requests: please open an [Issue](https://github.com/eosaios/eos-todo/issues)
> - Multi-platform builds (GitHub Actions)
>
> EOS Todo is closed-source commercial software; **the source code does not live here**. Installers are distributed through official channels.

## Download & Install

**Free while in beta.** Pricing for the stable release will be announced closer to launch.

| Platform | Package | Notes |
|---|---|---|
| Windows | `*-installer.exe` | NSIS installer, optional WebView2 runtime |
| macOS | `*.dmg` | universal (Intel + Apple Silicon), unsigned |
| Linux | `*.deb` / `*.AppImage` | both formats provided |

- If Gatekeeper blocks the unsigned macOS app on first launch, run `xattr -cr "/Applications/EOS Todo.app"`
- Data lives in your user directory (e.g. `~/Library/Application Support/eos-todolist/` on macOS); upgrades keep your todos
- Integrity: each Release ships a SHA256SUMS.txt

## Features

- **Todos** — quick add, inline edit, complete/undo, auto-flagged red after 24 hours unfinished
- **Screenshot** — fullscreen & region capture, can exclude the app window, save or open the folder
- **Focus timer** — countdown presets from 30s to 2h with reminder popup
- **Folder explorer** — browse local directories in-app
- **Personalization** — light/dark theme, English & Chinese UI, customizable global shortcuts
- **100% local** — zero network requests at runtime (verified); your data never leaves your machine

## Feedback guide

- 🐛 Bugs: include your OS version, the EOS Todo version, and steps to reproduce
- 💡 Feature requests: describe your use case, not just a proposed solution
- 🔒 Privacy: this app makes no network requests at runtime — if you observe otherwise, please report it immediately

## License

© 2026 EOSAIOS. All rights reserved. This software may not be copied or redistributed without authorization.
