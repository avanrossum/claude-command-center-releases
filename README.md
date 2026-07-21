# CC Command Center — Releases

This repository is the **public release feed** for CC Command Center. It exists so the desktop app can auto-update without embedding any credentials in the shipped binary.

It holds two things:

- **GitHub Releases** — the signed, notarized `.dmg` / `.zip` build artifacts and the `latest-mac.yml` metadata that the app's updater reads to decide whether a newer version exists.
- **`changelog.json`** — the per-version release notes the app shows in its update and post-update windows.

The application source code lives in a separate repository. This repo contains no source — only release artifacts and release notes.

Builds are arm64 macOS only, signed under a Developer ID and notarized by Apple.