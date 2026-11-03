Project Hub 1.0.4 includes Worktable 2.0.1 and fixes automatic updates for Electron applications.

Download `Project-Hub-Setup-1.0.4-x64.exe` and run it over your existing Hub installation. It downloads verified setup files, offers all four tools, and detects existing installations. Existing Worktable tables, projects and files are retained.

- Worktable project cards snap live to the visible 20 px grid, including at different zoom levels and after panning.
- Small drags retain aligned positions. Cancelled drags restore the original position, and saved positions survive restart.
- Project Hub detects Worktable 2.0.0 as older than 2.0.1 and updates it in its existing folder when automatic updates are enabled and Worktable is closed.
- Electron app archives are copied and backed up as physical files, fixing an update failure in Hub 1.0.3. Install Hub 1.0.4 to receive this correction.

Available versions: Sonora 1.0.0 (collection identifier), Worktable 2.0.1, PadForge 0.2.2 and Velvet 1.4.0. Windows 10/11 x64; Internet required. The Windows installer is unsigned.

Verified: 52 Hub tests, 17 Worktable storage tests, 47 Worktable desktop checks and nine pointer/restart snap checks. The actual packaged Hub automatically updated a complete Worktable 2.0.0 installation in place, retained a personal file, rescanned the new version, and launched the updated app for all nine snap checks. Simulated activation failure restored all 74 runtime files byte-for-byte, and both restored and updated apps launched. Native setup, selected-tool installation, existing-app reuse, 20 installed-Hub desktop checks, eight existing-app checks and uninstall passed. All release payload sizes and SHA-256 digests match the validated local files.

The tiny download launcher verifies each supporting part and the assembled setup before opening it. Physical controller/audio acceptance and second-PC AI first-run setup are outside these checks.
