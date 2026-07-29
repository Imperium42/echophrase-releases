<div align="center">

<a href="https://echophrase.com">
  <img src="https://echophrase.com/images/echophrase-logo.svg" alt="Echophrase" width="360" />
</a>

### Privacy-first, GPU-accelerated local AI dictation

**Your voice never leaves your computer.**

[![Latest release](https://img.shields.io/github/v/release/imperium42/echophrase-releases?include_prereleases&label=release&color=22d3ee)](../../releases/latest)
[![Downloads](https://img.shields.io/github/downloads/imperium42/echophrase-releases/total?color=a855f7)](../../releases)
[![Homebrew](https://img.shields.io/badge/homebrew-imperium42%2Ftap-f9d094?logo=homebrew&logoColor=white)](https://github.com/imperium42/homebrew-tap)
<!-- winget: re-enable once Imperium42.Echophrase clears winget-pkgs moderation
[![winget](https://img.shields.io/badge/winget-Imperium42.Echophrase-0078d4?logo=windows&logoColor=white)](https://winstall.app/apps/Imperium42.Echophrase)
-->
[![Website](https://img.shields.io/badge/echophrase.com-visit-22d3ee)](https://echophrase.com)
[![Discord](https://img.shields.io/badge/discord-join-5865F2?logo=discord&logoColor=white)](https://discord.com/invite/XVGXRzq)

</div>

---

Echophrase is a desktop dictation app that turns your speech into text in **any**
application — fully **offline** after a one-time model download, accelerated by your **GPU**, with multilingual
models (Whisper, Parakeet, Qwen3-ASR). Push-to-talk, no account, no cloud.

> This repository holds **release artifacts only** — no source code. Signed,
> notarized macOS `.dmg` builds are published as
> [GitHub Releases](../../releases), tagged `v<version>` to match the app.
> It exists so the [Homebrew tap](https://github.com/imperium42/homebrew-tap)
> has a public, versioned, checksummable URL to install from.

## 🍺 Install (macOS, Apple Silicon)

```bash
brew install --cask imperium42/tap/echophrase
```

Requires **macOS 13.3+ (Ventura)** on **Apple Silicon** (`arm64`).
Prefer a manual install? Grab the `.dmg` from the
[latest release](../../releases/latest).

<!-- winget: re-enable once Imperium42.Echophrase clears winget-pkgs moderation
## 🪟 Install (Windows)

```powershell
winget install Imperium42.Echophrase
```
-->

Prefer a manual install, or want other platforms? Windows builds (with CUDA GPU
acceleration) are also distributed from
[echophrase.com/download](https://echophrase.com/download).

## ✨ Why Echophrase?

| | |
|---|---|
| 🔒 **100% offline** | Audio is processed on-device — nothing is ever uploaded (models are a one-time download on first run) |
| ⚡ **GPU-accelerated** | Native DirectML on Windows, Metal on macOS — nothing extra to install |
| 🌍 **Multilingual** | Qwen3-ASR delivers strong Chinese & international accuracy |
| 🎙️ **Push-to-talk** | Dictate into any text field with a hotkey |
| 🪶 **Featherweight** | Native Tauri + Rust — not an Electron memory hog |

## 🔗 Links

- **Website & downloads:** [echophrase.com](https://echophrase.com)
- **Docs:** [docs.echophrase.com](https://docs.echophrase.com)
- **Community:** [Discord](https://discord.com/invite/XVGXRzq)
- **Source:** private repository — see the website for product info

---

<div align="center">
<sub>© Imperium42 LLC · <a href="https://echophrase.com/privacy">Privacy</a> · <a href="https://echophrase.com/terms">Terms</a></sub>
</div>
