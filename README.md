# Project Hub for Windows

One installer for **Sonora, Worktable, PadForge, and Velvet**. Choose the tools you want, detect and reuse existing installations, and turn automatic updates on separately for each app.

## Download

**[Download Project Hub for Windows x64](https://github.com/Xpomodz/project-hub-downloads/releases/latest/download/Project-Hub-Setup-1.0.3-x64.exe)**

[Release notes and files](https://github.com/Xpomodz/project-hub-downloads/releases/latest) · [SHA-256 checksums](https://github.com/Xpomodz/project-hub-downloads/releases/latest/download/SHA256SUMS.txt)

1. Open the installer on Windows 10/11 x64 and click **Next**. It downloads and verifies about 111 MB of setup files automatically.
2. The tool-choice screen then opens. Choose tools and optional automatic updates. Existing copies are marked **installed** and reused.
3. Choose a folder and finish setup. Open Project Hub to launch apps or add more later.

An Internet connection is required. Download only the EXE linked above; it fetches and verifies the setup parts automatically, then downloads the tools you select. The individual `.part` assets are supporting files, not separate steps for you. Automatic update checks use this repository's signed public release feed; only newer published app versions are installed. Updates wait while an app is running. Existing user data is preserved, and standalone updates retain the original app folder.

Velvet downloads its local AI engine and models on first launch, which can require several GB. PadForge's optional virtual controller driver may need a Windows administrator prompt and restart. The hub does not silently install system drivers or change audio devices.

This Windows installer is **unsigned**. Keep Windows security enabled if Windows blocks the download or installer, and report the exact message to the developer.

## Included versions

| Tool | Version |
|---|---|
| Sonora | 1.0.0 (collection release identifier) |
| Worktable | 2.0.0 |
| PadForge | 0.2.2 |
| Velvet | 1.4.0 |

This repository contains public installers, verified component packages, the signed update catalog, and release documents. It contains no private developer data, chat history, API keys, or release-signing private keys. Source repositories are maintained separately.

## Update feed

The feed URL for Project Hub Settings is:

`https://github.com/Xpomodz/project-hub-downloads/releases/latest/download/`

Each release publishes ZIP packages first and its signed `catalog.json` last. The installer pins the publisher's public key and verifies exact package sizes and SHA-256 hashes before installing.
