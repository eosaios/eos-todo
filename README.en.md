# EOS Todo

[English](./README.en.md) | [中文](./README.md)

A local-first desktop todo app: todos, screenshots, a focus timer, and folder browsing. The free local core works without an EOS account, and data stays on your device by default. Sign-in, optional cloud sync and AI, update checks, and feedback use the network. Anonymous launch statistics are optional and off by default.

> **This repository is the public portal for EOS Todo**, used for:
> - Backup download mirrors: see [Releases](https://github.com/eosaios/eos-todo/releases)
> - Bug reports and feature requests: please open an [Issue](https://github.com/eosaios/eos-todo/issues)
>
> EOS Todo is closed-source commercial software; **the source code does not live here**. Prefer downloading from the [official site](https://eosaios.com/) or the [account portal](https://account.eosaios.com/).

## Download & Install

**Prefer the [official site](https://eosaios.com/) or the [account portal](https://account.eosaios.com/).** [GitHub Releases](https://github.com/eosaios/eos-todo/releases) ([latest release](https://github.com/eosaios/eos-todo/releases/latest)) is a backup mirror.

| Platform | Package | Notes |
|---|---|---|
| macOS (Apple Silicon) | DMG (see latest Release assets) | [Official macOS installation guide](https://eosaios.com/guides/todo/?lang=en#macos), including signing and notarization |
| Windows (x64) | EXE (see latest Release assets) | [Per-user installation with a WebView2 check](https://eosaios.com/guides/todo/?lang=en#windows) |
| Linux (x64) | tar.gz (see latest Release assets) | [Ubuntu 24.04+ dependencies and user-level installation](https://eosaios.com/guides/todo/?lang=en#linux) |

- Data lives in your user directory (e.g. `~/Library/Application Support/eos-todolist/` on macOS); upgrades keep your todos
- Integrity: verify the installer against the `SHA256SUMS.txt` file attached to its release.

The free local core is ready to use; optional Pro features and pricing are on the [official site](https://eosaios.com/).

## Features

- **Todos** — quick add, inline edit, complete/undo, auto-flagged red after 24 hours unfinished
- **Screenshot** — fullscreen & region capture, can exclude the app window, save or open the folder
- **Focus timer** — countdown presets from 30s to 2h with a reminder popup
- **Folder explorer** — browse local directories in-app
- **Personalization** — light/dark theme, English & Chinese UI, customizable shortcuts
- **Local core** — todos and local tools need no account; data stays on your device by default
- **Optional Pro AI** — bring your own key (BYOK) or use managed credits; an EOS account is required for managed AI
- **Optional encrypted cloud sync** — Todo Pro lets you enable cloud sync. Synced task content and attachments are encrypted before upload. EOS manages the account sync key. Tasks marked local-only stay on that device.

## Feedback guide

- 🐛 Bugs: include your OS version, the EOS Todo version, and steps to reproduce
- 💡 Feature requests: describe your use case, not just a proposed solution
- 🔒 Privacy: see the [official product page](https://eosaios.com/products/todo/) for network usage, and report any unexpected outbound traffic.

## License

© 2026 EOSAIOS. All rights reserved. This software may not be copied or redistributed without authorization.
