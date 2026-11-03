# Project Hub 1.1.0

AI Nook joins the installer as the fifth optional tool. Install and automatic-update choices remain independent for Sonora, Worktable, PadForge, Velvet, and Nook. Existing installations are detected and reused; older verified copies update in their original folder after the app closes.

Included: Sonora 1.0.1, Worktable 2.2.0, PadForge 0.2.2, Velvet 1.5.0, and AI Nook 0.4.0.

Worktable, Nook, and Velvet now exchange local project briefs and assistant replies. Worktable adds project search, reviewed edits across several selected files, backups and recovery, and explicitly confirmed npm project checks. Qwen2.5-Coder 7B remains the initial coding model; 14B is an optional separate download with a memory/performance warning. Models and personal chat histories are not bundled in this installer. Nook needs an installed, signed-in Codex app or a running local model server. Worktable's Qwen workflow needs Ollama.

Update Project Hub first. Hubs 1.0.8 and newer support the signed Hub update through Settings → Automatic updates for Project Hub or the manual Hub controls on Updates. Earlier versions need the current installer run once. Older Hubs understand four tools and cannot use the new five-tool catalog until their separate Hub updater finishes. Nook is then available to select; adding it never silently installs it.

Hub and individual-tool automatic updates are separate opt-ins. Running tools defer their updates. Settings, Worktable tables, Velvet libraries, Nook chats, and existing shortcuts are retained. Older downloaded bootstrap EXEs remain pinned to their original release; the current download page provides the latest installer.

Windows 10/11 x64 and Internet access required. The installer is unsigned; pinned Ed25519 update signatures and package SHA-256 verification are separate from Windows Authenticode. Keep Windows security enabled. See VERIFICATION.json and SHA256SUMS.txt in this release for exact tested payloads.
