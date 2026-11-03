# Project Hub 1.3.1

Worktable 2.4.1 adds persistent local project environments and fixes their creation when Windows redirects the roaming-data folder. Create a new project or a separate working copy, save a goal and acceptance criteria, and let the local model work, run approved checks, and revise the result within your chosen limits. Goals, files, check output, activity, and recovery checkpoints remain available after reopening.

Quick work uses Qwen2.5-Coder 7B. Deep work offers Qwen3.8 27B IQ4_XS as an optional approximately 15 GB download. Closing Worktable's window while environments are active keeps work running in the tray. Quitting pauses work; saved environments resume when selected after reopening. The PC must remain running and awake. Passing checks and model completion lead to human review, not a guarantee of perfection.

The installer now offers six optional tools: Sonora 1.0.1, Worktable 2.4.1, PadForge 0.2.2, Velvet 1.5.0, AI Nook 0.4.1, and Umbra 1.2.0. Nook and Worktable show local AI requirements and provide Ollama/model setup with progress, Stop, and Retry. Model weights and personal project/chat data are not bundled.

Update Project Hub first. The separate Hub updater can move supported older Hubs to this six-tool version even when their component catalog cannot read the new collection. Tool and Hub automatic updates remain separate opt-ins. Newly introduced tools are never installed without selection, and running tools defer their updates. Existing data, settings, custom files, shortcuts, and install locations are preserved by the verified update paths.

Windows 10/11 x64 and Internet access are required for the public download. The small `Project-Hub-Setup-x64.exe` downloads and verifies its setup parts automatically, then opens the tool chooser. Individual `.part` files are supporting assets, not manual installation steps. Previously downloaded bootstrap EXEs remain pinned to their original version.

The installer does not have a Windows Authenticode publisher certificate. The component catalog and Hub update metadata use the existing pinned Ed25519 identity, with exact package sizes and SHA-256 verification. Keep Windows security enabled. See `VERIFICATION.json` and `SHA256SUMS.txt` for the actual verification evidence and final artifact hashes.
