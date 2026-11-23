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
[![Discord](https://img.shields.io/badge/discord-join-5865F2?logo=discord&logoColor=white)](https://discord.com/invite/Er6NUcx)

</div>

---

[Echophrase](https://echophrase.com) is a free, open-source (MPL-2.0) desktop dictation app that turns your
speech into text in **any** application. It runs fully **offline** after a one-time model download, accelerated
by your **GPU**, with local models (Parakeet-TDT, Qwen3-ASR, Parakeet Lite, plus optional T5 grammar cleanup).
Push-to-talk, no account, no cloud, no telemetry. A native Tauri + Rust app, not Electron.

> This repository holds **release artifacts only**. The source code lives at
> [Imperium42/echophrase](https://github.com/Imperium42/echophrase). Signed builds are published as
> [GitHub Releases](../../releases), tagged `v<version>` to match the app, so the
> [Homebrew tap](https://github.com/imperium42/homebrew-tap) and winget have a public, versioned,
> checksummable URL to install from.

## 🍺 Install (macOS, Apple Silicon)

```bash
brew install --cask imperium42/tap/echophrase
```

Requires **macOS 13.3+ (Ventura)** on **Apple Silicon** (`arm64`).
Prefer a manual install? Grab the `.dmg` from the
[latest release](../../releases/latest).

## 🪟 Install (Windows)

```powershell
winget install Imperium42.Echophrase
```

Or download the signed installer (`Echophrase_<version>_x64-setup.exe`) from the
[latest release](../../releases/latest). GPU acceleration works out of the box
via DirectML, which is bundled with the app. No CUDA needed.

## 🐧 Linux

There are no official Linux downloads. Linux is community-supported and CPU-only:
[build from source](https://github.com/Imperium42/echophrase#build-from-source).

## ✨ Why Echophrase?

| | |
|---|---|
| 🔒 **Private by design** | Audio is processed on-device and never uploaded. No account, no cloud sync, no telemetry. The app only contacts huggingface.co (model downloads) and cdn.crabnebula.app (update checks). |
| ⚡ **GPU-accelerated** | DirectML on Windows (bundled), CoreML/Metal on macOS. Nothing extra to install. |
| 🌍 **Multilingual** | Parakeet-TDT for European languages, Qwen3-ASR for Chinese and 50+ more, Parakeet Lite for light English dictation. |
| ✍️ **Grammar cleanup** | An optional on-device T5 pass polishes grammar and punctuation. |
| 🎙️ **Push-to-talk** | Dictate into any text field with a hotkey. |
| 🆓 **Free and open source** | MPL-2.0. [Source on GitHub](https://github.com/Imperium42/echophrase). |

## 🔗 Links

- **Website & downloads:** [echophrase.com](https://echophrase.com)
- **Docs:** [docs.echophrase.com](https://docs.echophrase.com)
- **Source (MPL-2.0):** [Imperium42/echophrase](https://github.com/Imperium42/echophrase)
- **Community:** [Discord](https://discord.com/invite/Er6NUcx)

---

<div align="center">
<sub>© Imperium42 LLC · <a href="https://echophrase.com/privacy">Privacy</a> · <a href="https://echophrase.com/terms">Terms</a></sub>
</div>
