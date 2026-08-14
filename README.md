<div align="center">

<a href="https://echophrase.com">
  <img src="https://echophrase.com/images/echophrase-logo.svg" alt="Echophrase" width="360" />
</a>

### Privacy-first, GPU-accelerated local AI dictation

**Your voice never leaves your computer.**

[![Latest release](https://img.shields.io/github/v/release/imperium42/echophrase-releases?include_prereleases&label=release&color=22d3ee)](../../releases/latest)
[![Homebrew](https://img.shields.io/badge/homebrew-imperium42%2Ftap-f9d094?logo=homebrew&logoColor=white)](https://github.com/imperium42/homebrew-tap)
[![winget](https://img.shields.io/badge/winget-Imperium42.Echophrase-0078d4?logo=windows&logoColor=white)](https://winstall.app/apps/Imperium42.Echophrase)
[![Website](https://img.shields.io/badge/echophrase.com-visit-22d3ee)](https://echophrase.com)
[![Discord](https://img.shields.io/badge/discord-join-5865F2?logo=discord&logoColor=white)](https://discord.com/invite/XVGXRzq)

</div>

---

[Echophrase](https://echophrase.com) is a desktop dictation app that turns your speech into text in **any**
application — fully **offline** after a one-time model download, accelerated by your **GPU**, with multilingual
models (Whisper, Parakeet, Qwen3-ASR). Push-to-talk, no account, no cloud - a polished, featherweight native app (Tauri + Rust, not Electron).

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

## 🪟 Install (Windows)

Download the signed installer (`Echophrase_<version>_x64-setup.exe`) from the
[latest release](../../releases/latest). GPU acceleration works out of the box
via DirectML; an optional CUDA plugin for NVIDIA GPUs is available in-app.

```powershell
winget install Imperium42.Echophrase
```

## 🐧 Install (Linux, Alpha)

Grab the [AppImage](https://cdn.crabnebula.app/download/imperium42/echophrase/latest/platform/appimage-x86_64)
(x86_64, NVIDIA CUDA required), then `chmod +x` and run.

On Debian/Ubuntu you can install the
[`.deb` package](https://cdn.crabnebula.app/download/imperium42/echophrase/latest/platform/debian-x86_64)
instead:

```bash
sudo dpkg -i echophrase.deb
```

Linux support is **Alpha** — see [echophrase.com/download](https://echophrase.com/download)
for requirements and known limitations.

## ✨ Why Echophrase?

| | |
|---|---|
| 🔒 **Unlimited Offline Transcriptions** | Your voice is processed on-device — recordings are never uploaded (models are a one-time download on first run). Optional online features (account, cloud sync, anonymous telemetry) can be turned off |
| ⚡ **GPU-accelerated** | Native DirectML on Windows, Metal on macOS — nothing extra to install |
| 🌍 **Multilingual** | Pick the model that fits: Whisper, Parakeet, or Qwen3-ASR — from fast English-first dictation to strong Chinese & international accuracy |
| ✍️ **Grammar cleanup** | An optional post-transcription transform model polishes grammar and punctuation, so your dictation reads the way you meant it |
| 🎙️ **Push-to-talk** | Dictate into any text field with a hotkey |
| 🪶 **Featherweight** | Native Tauri + Rust — not an Electron memory hog |

## 🔗 Links

- **Website & downloads:** [echophrase.com](https://echophrase.com)
- **Docs:** [docs.echophrase.com](https://docs.echophrase.com)
- **Community:** [Discord](https://discord.com/invite/XVGXRzq)
- **Source:** private repository — see [echophrase.com](https://echophrase.com) for product info

---

<div align="center">
<sub>© Imperium42 LLC · <a href="https://echophrase.com/privacy">Privacy</a> · <a href="https://echophrase.com/terms">Terms</a></sub>
</div>
