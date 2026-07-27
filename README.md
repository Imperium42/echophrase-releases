# echophrase-releases

Public release assets for [Echophrase](https://echophrase.com), a privacy-first
local speech-to-text desktop app.

This repository holds **no source code**. Signed, notarized macOS `.dmg`
builds are published here as [GitHub Releases](../../releases), tagged
`v<version>` to match the app's version. It exists so that
[homebrew-tap](https://github.com/imperium42/homebrew-tap) has a public,
versioned, checksummable URL to install from - Homebrew requires a publicly
downloadable asset, and the app's source repository (`dylanh724/echophrase`)
is private.

## Install the app

```bash
brew install imperium42/tap/echophrase
```

Or download the `.dmg` directly from the [Releases](../../releases) page.

## Source

The application source lives in a private repository. See
[echophrase.com](https://echophrase.com) for product information and other
platform downloads (Windows, Linux).
