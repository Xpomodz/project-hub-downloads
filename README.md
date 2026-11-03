# Project Hub for Windows

One installer for **Sonora, Worktable, PadForge, Velvet, and AI Nook**. Choose the tools you want, detect and reuse existing installations, and turn automatic updates on separately for each app.

## Download

**[Download Project Hub for Windows x64](https://github.com/Xpomodz/project-hub-downloads/releases/latest/download/Project-Hub-Setup-x64.exe)**

[Release notes and files](https://github.com/Xpomodz/project-hub-downloads/releases/latest) · [SHA-256 checksums](https://github.com/Xpomodz/project-hub-downloads/releases/latest/download/SHA256SUMS.txt)

1. Open the installer on Windows 10/11 x64 and click **Next**. It downloads and verifies about 111 MB of setup files automatically.
2. The tool-choice screen then opens. Choose tools and optional automatic updates. Existing copies are marked **installed** and reused.
3. Choose a folder. The app-installation window opens automatically with progress for each selected tool: downloaded bytes, percentage, verification, and file extraction.
4. Wait for the selected apps to finish, review any errors or remaining audio setup, and choose **Finish**. Installed apps can then be opened from Project Hub.

Versions older than 1.0.8 need this installer once. Hubs 1.0.8 and newer can get 1.1.0 through the Hub Updates page or automatic Hub updates. **Update the Hub first**: older Hubs understand four tools, and their separate self-updater upgrades them to support Nook's five-tool catalog. Current copies of all five apps are reused. A failed app keeps an error and **Retry** action; other selected apps continue. Closing during installation keeps progress visible. Use **Minimize** while work continues.

**New in 1.1.0:** Nook is an optional fifth tool. Worktable, Nook, and Velvet exchange project briefs and replies. Worktable adds local Qwen coding, project search, reviewed changes across selected files, backups, and confirmed npm project checks. A real public-download Hub 1.0.8 → 1.1.0 upgrade was verified with settings, installed Worktable, custom files, and uninstaller preserved.

**Update Project Hub itself:** versions older than 1.0.8 need this download once. Then enable **Settings → Automatic updates for Project Hub**. Future Hub updates download automatically and apply when the Hub is minimized or in the tray and app installation/audio setup is idle. This separate preference defaults off and enables Start with Windows. **Updates → Restart to update** applies a prepared Hub update manually. Installed tools and settings are preserved.

**Windows file-lock recovery:** if Windows temporarily blocks the final app-folder move, the Hub retries the same verified files and shows a waiting stage. Persistent denial keeps a Retry action with guidance. Existing installations remain intact.

**Sonora audio drivers:** setup checks existing VB-CABLE and Hi-Fi Cable drivers and offers missing ones. The original base VB-CABLE package is included; Hi-Fi Cable downloads directly from VB-Audio when selected. Click **Install**, approve the Windows administrator prompt, then restart Windows after installing drivers. Reopen **Audio drivers** in Project Hub or **Audio driver setup** in Sonora Connections to finish later. Background updates never launch driver installers.

VB-CABLE and Hi-Fi Cable are separate VB-Audio donationware products: [origin](https://www.vb-cable.com/), [Hi-Fi Cable](https://vb-audio.com/Cable/), [licenses and donations](https://vb-audio.com/Services/licensing.htm). All participation is welcome. Hi-Fi Cable setup requires Internet access even with an offline Sonora package.

An Internet connection is required. Download only the EXE linked above; it fetches and verifies the setup parts automatically, then downloads the tools you select. The individual `.part` assets are supporting files, not separate steps for you. Automatic update checks use this repository's signed public release feed; only newer published app versions are installed. Updates wait while an app is running. Existing user data is preserved, and standalone updates retain the original app folder.

Velvet downloads its local AI engine and models on first launch, which can require several GB. Nook requires an installed, signed-in Codex app or a running Ollama/compatible model server. Worktable's Qwen coding requires Ollama; 7B is the initial default, and 14B is an optional separate download with a memory/performance warning. Model weights are not included in this installer. PadForge's optional virtual controller driver may need a Windows administrator prompt and restart. The hub does not silently install system drivers or change audio devices.

The installer updates selected older apps and preserves their saved data. Newly added tools are never silently installed. A bootstrap EXE already downloaded to your PC remains pinned to its original version; download the current EXE above or use the installed Hub's own updater.

This Windows installer is **unsigned**. Keep Windows security enabled if Windows blocks the download or installer, and report the exact message to the developer.

## Included versions

| Tool | Version |
|---|---|
| Sonora | 1.0.1 |
| Worktable | 2.2.0 |
| PadForge | 0.2.2 |
| Velvet | 1.5.0 |
| AI Nook | 0.4.0 |

This repository contains public installers, verified component packages, the signed update catalog, and release documents. It contains no private developer data, chat history, API keys, or release-signing private keys. Source repositories are maintained separately.

## Update feed

The feed URL for Project Hub Settings is:

`https://github.com/Xpomodz/project-hub-downloads/releases/latest/download/`

Each release publishes ZIP packages first and its signed `catalog.json` last. The installer pins the publisher's public key and verifies exact package sizes and SHA-256 hashes before installing.
