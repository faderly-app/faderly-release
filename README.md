# Faderly Release

Signed & notarized Faderly releases — release binaries only; no source code lives here.

Faderly is an independent fork of [MacMix](https://github.com/ljmng7/MacMix) (MIT,
© 2026 ljmng7 (Jazmín)), a menu-bar audio mixer for macOS. See the Faderly source
repository for source, build docs, and license.

Downloads live on the [Releases](https://github.com/faderly-app/faderly-release/releases) page.
Each release attaches a stable artifact pair to a `v<version>` tag:

```
https://github.com/faderly-app/faderly-release/releases/download/v<version>/Faderly-<version>.zip
https://github.com/faderly-app/faderly-release/releases/download/v<version>/Faderly-<version>.dmg
```

- `Faderly-<version>.zip` — Sparkle update archive (auto-update enclosure).
- `Faderly-<version>.dmg` — first-install drag-to-Applications disk image.

This repository is currently **private**: downloads require GitHub authentication and the
Sparkle feed's update downloads resolve only for authorized clients. It will be made public
when Faderly launches.

The Sparkle update feed is served from `https://faderly-landing.pages.dev/appcast.xml`
(hosted from the Faderly source repository's landing microsite).
