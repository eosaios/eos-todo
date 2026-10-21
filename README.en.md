# EOS Todo

[English](./README.en.md) | [中文](./README.md)

A local-first desktop todo app: todos, screenshots, a focus timer, and folder browsing. The free local core works without an EOS account — data stays on your device. Optional Pro AI (BYOK or managed credits) requires an account when you use managed AI. Network requests happen only when you choose to sign in or use AI.

> **This repository is the public portal for EOS Todo**, used for:
> - Backup download mirrors: see [Releases](https://github.com/eosaios/eos-todo/releases)
> - Bug reports and feature requests: please open an [Issue](https://github.com/eosaios/eos-todo/issues)
>
> EOS Todo is closed-source commercial software; **the source code does not live here**. Prefer downloading from the [official site](https://eosaios.com/) or the [account portal](https://account.eosaios.com/).

## Download & Install

**Prefer the official site.** GitHub Releases is a backup mirror.

Current mirror: [todo-mirror-v1.1.3](https://github.com/eosaios/eos-todo/releases/tag/todo-mirror-v1.1.3)

| Platform | Package | Notes |
|---|---|---|
| macOS (Apple Silicon) | `eos-todo_1.1.3_darwin-arm64.dmg` | Unsigned |
| Windows (x64) | `eos-todo_1.1.3_windows-amd64.exe` | Portable / run directly |
| Linux (x64) | `eos-todo_1.1.3_linux-amd64.tar.gz` | Ubuntu 24.04+ or equivalent GTK4 / WebKitGTK 6.0 |

- If Gatekeeper blocks the unsigned macOS app on first launch, run: `xattr -cr "/Applications/EOS Todo.app"`
- Data lives in your user directory (e.g. `~/Library/Application Support/eos-todolist/` on macOS); upgrades keep your todos
- Integrity: each Release ships `SHA256SUMS.txt` (and platform checksum files)

The free local core is ready to use; optional Pro features and pricing are on the [official site](https://eosaios.com/).

## Features

- **Todos** — quick add, inline edit, complete/undo, auto-flagged red after 24 hours unfinished
- **Screenshot** — fullscreen & region capture, can exclude the app window, save or open the folder
- **Focus timer** — countdown presets from 30s to 2h with a reminder popup
- **Folder explorer** — browse local directories in-app
- **Personalization** — light/dark theme, English & Chinese UI, customizable shortcuts
- **Local core** — todos and local tools need no account; data stays on your device by default
- **Optional Pro AI** — bring your own key (BYOK) or use managed credits; an EOS account is required for managed AI

Cloud sync is not offered as a shipped feature yet.

## Feedback guide

- 🐛 Bugs: include your OS version, the EOS Todo version, and steps to reproduce
- 💡 Feature requests: describe your use case, not just a proposed solution
- 🔒 Privacy: when you are signed out and not using AI, the app does not make account or model requests — if you observe unexpected outbound traffic, please report it

## License

© 2026 EOSAIOS. All rights reserved. This software may not be copied or redistributed without authorization.
