# Project Hub for Windows

One installer for **Sonora, Worktable, PadForge, Velvet, AI Nook, and Umbra**. Choose the tools you want, detect and reuse existing installations, and turn automatic updates on separately for each app.

## Download

**[Download Project Hub for Windows x64](https://github.com/Xpomodz/project-hub-downloads/releases/latest/download/Project-Hub-Setup-x64.exe)**

[Release notes and files](https://github.com/Xpomodz/project-hub-downloads/releases/latest) · [SHA-256 checksums](https://github.com/Xpomodz/project-hub-downloads/releases/latest/download/SHA256SUMS.txt)

1. Open the installer on Windows 10/11 x64 and click **Next**. It downloads and verifies the setup files automatically.
2. The tool-choice screen then opens. Choose tools and optional automatic updates. Existing copies are marked **installed** and reused.
3. Choose a folder. The app-installation window opens automatically with progress for each selected tool: downloaded bytes, percentage, verification, and file extraction.
4. Wait for the selected apps to finish, review any errors or remaining audio setup, and choose **Finish**. Installed apps can then be opened from Project Hub.

Versions older than 1.0.8 need this installer once. Hubs 1.0.8 and newer can get 1.3.3 through the Hub Updates page or automatic Hub updates. **Update the Hub first**: older Hubs may reject the expanded six-tool catalog until their separate self-updater upgrades the Hub. Current copies of the selected apps are reused. A failed app keeps an error and **Retry** action; other selected apps continue. Closing during installation keeps progress visible. Use **Minimize** while work continues.

## What's new in 1.3.3

Project Hub 1.3.3 updates all six tools: Sonora 1.0.3, Worktable 2.9.3, PadForge 0.3.1, Velvet 1.5.2, AI Nook 0.4.6, and Umbra 1.2.1. Worktable includes recovery checkpoints, managed web previews, bounded worker tools, a larger environment workspace, updated branding, and Nook companion integration. PadForge adds game discovery and profile linking, tuning controls, and tray preferences. Nook connects its companion and project chats with Worktable. Velvet improves window presentation when opened from another app. The collection also includes current Sonora and Umbra startup presentation.

Hub and app updates remain separate opt-ins. Update Project Hub first when upgrading an older installation; running apps defer their updates. Settings, saved projects, conversations, and controller profiles stay in their existing data folders.

## Earlier collection (1.3.2)

The cumulative release includes **Worktable 2.6.0**, with live environment statistics, activity and preview panels, file-change inspection, device detection, GPU-memory placement, performance presets and Custom CPU/GPU/context controls. **AI Nook 0.4.2** includes current local-chat response and personality improvements. **Sonora 1.0.2** includes current output routing, saved playback settings and branding. PadForge, Velvet and Umbra retain their exact previous packages.

The installer already supported signed component updates. Local project changes do not publish themselves; this release adds the missing verified packages to the public channel. The offline bundle and signed catalog contain the same current six versions.

## Earlier environment updates

**Worktable 2.4.1 fixes environment creation on Windows PCs with a redirected roaming-data folder.** Existing files are kept; retry **Create environment** after updating.

**Worktable 2.4.0 adds persistent project environments.** Give an existing project or a new JavaScript/blank project a goal, acceptance criteria, and work limits. Worktable saves a separate working copy, makes backed-up changes, runs the project checks you enable, and uses failures to guide another iteration. Environments run one at a time in a saved queue. Passing checks make a result ready for your review; they do not guarantee every acceptance criterion is satisfied.

Choose **Quick work** with Qwen2.5-Coder 7B, or optionally download **Deep work** with Unsloth Qwen3.8 27B IQ4_XS (about 15 GB) from Worktable's Environment model settings. Deep work uses system RAM as well as GPU memory on an 8 GB card and can take much longer. The engines and model weights are separate downloads; no model weights are included in the Hub installer.

Closing Worktable's window while an environment is active keeps work running in its Windows tray. Quitting saves and pauses environments; after reopening, choose **Resume work**. Keep the PC running and awake. The first version suits small source projects and scoped folders; dependency installation and deployment remain manual.

**Umbra 1.2.0** is the sixth optional tool, for reviewing cleanup, storage, and startup items. The collection also includes **AI Nook 0.4.1**. Each tool keeps its own install and automatic-update choice. Worktable, Nook, and Velvet continue to exchange local project briefs and replies.

## Installation and updates

**Update Project Hub itself:** versions older than 1.0.8 need this download once. Then enable **Settings → Automatic updates for Project Hub**. Future Hub updates download automatically and apply when the Hub is minimized or in the tray and app installation/audio setup is idle. This separate preference defaults off and enables Start with Windows. **Updates → Restart to update** applies a prepared Hub update manually. Installed tools and settings are preserved.

**Windows file-lock recovery:** if Windows temporarily blocks the final app-folder move, the Hub retries the same verified files and shows a waiting stage. Persistent denial keeps a Retry action with guidance. Existing installations remain intact.

**Sonora audio drivers:** setup checks existing VB-CABLE and Hi-Fi Cable drivers and offers missing ones. The original base VB-CABLE package is included; Hi-Fi Cable downloads directly from VB-Audio when selected. Click **Install**, approve the Windows administrator prompt, then restart Windows after installing drivers. Reopen **Audio drivers** in Project Hub or **Audio driver setup** in Sonora Connections to finish later. Background updates never launch driver installers.

VB-CABLE and Hi-Fi Cable are separate VB-Audio donationware products: [origin](https://www.vb-cable.com/), [Hi-Fi Cable](https://vb-audio.com/Cable/), [licenses and donations](https://vb-audio.com/Services/licensing.htm). All participation is welcome. Hi-Fi Cable setup requires Internet access even with an offline Sonora package.

An Internet connection is required. Download only the EXE linked above; it fetches and verifies the setup parts automatically, then downloads the tools you select. The individual `.part` assets are supporting files, not separate steps for you. Automatic update checks use this repository's signed public release feed; only newer published app versions are installed. Updates wait while an app is running. Existing user data is preserved, and standalone updates retain the original app folder.

Velvet downloads its local AI engine and models on first launch, which can require several GB. Nook requires an installed, signed-in Codex app or a running Ollama/compatible model server. Worktable's Qwen coding desk uses Ollama; its initial 7B model and optional 14B model are separate downloads. Persistent environments support Ollama or LM Studio's local server, with an optional approximately 15 GB Deep model. Worktable project checks require Node.js with npm. PadForge's optional virtual controller driver may need a Windows administrator prompt and restart. The hub does not silently install system drivers or change audio devices.

The installer updates selected older apps and preserves their saved data. Newly added tools are never silently installed. A bootstrap EXE already downloaded to your PC remains pinned to its original version; download the current EXE above or use the installed Hub's own updater.

This Windows installer is **unsigned**. Keep Windows security enabled if Windows blocks the download or installer, and report the exact message to the developer.

## Included versions

| Tool | Version |
|---|---|
| Sonora | 1.0.3 |
| Worktable | 2.9.3 |
| PadForge | 0.3.1 |
| Velvet | 1.5.2 |
| AI Nook | 0.4.6 |
| Umbra | 1.2.1 |

This repository distributes public installers, component packages, the signed update catalog, and release documents. Source repositories are maintained separately.

## Update feed

The feed URL for Project Hub Settings is:

`https://github.com/Xpomodz/project-hub-downloads/releases/latest/download/`

Each release publishes ZIP packages first and its signed `catalog.json` last. The installer pins the publisher's public key and verifies exact package sizes and SHA-256 hashes before installing.
