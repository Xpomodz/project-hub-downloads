Project Hub 1.0.8 can update itself, as well as Sonora, Worktable, PadForge and Velvet.

Install `Project-Hub-Setup-1.0.8-x64.exe` once over the older Hub. Then enable **Settings → Automatic updates for Project Hub**. Future Hub updates download automatically and install while the Hub is minimized or in the tray, after app installation and audio setup have finished. This preference is separate from automatic updates for the individual tools and defaults off.

- Checks run at startup and hourly while the Hub is running. Enabling Hub updates also enables Start with Windows.
- Visible sessions offer **Updates → Restart to update** so work is not interrupted.
- Downloads show real progress. The Hub verifies a signed release manifest, the full runtime ZIP, and every runtime file before replacement.
- Installed tools, settings, the install folder, custom files and the existing uninstaller are retained.
- An update worker must acknowledge readiness before the old Hub closes. Copy/commit errors restore the previous runtime; a failed version pauses automatic retries. The restarted Hub must report the expected version.

The four app versions remain Sonora 1.0.1, Worktable 2.0.1, PadForge 0.2.2 and Velvet 1.4.0. The visible installer, per-app progress, retry actions and existing-app detection from 1.0.6 are retained. Windows 10/11 x64; Internet required. Windows installer signing remains unsigned; cryptographic update verification does not bypass Windows security.

Validation passed 91 unit tests (including 19 self-updater and three publisher tests), 25 main/UI boundary checks, 31 app-progress checks and 22 desktop checks. A real packaged 1.0.7 → 1.0.8 automatic upgrade passed 14 checks using the public signed runtime: download, busy guard, background handoff, restart/version, original install folder, settings and installed-tool preservation, and a subsequent Worktable launch. The public bootstrap download and reconstruction also passed. See VERIFICATION.json for the final native-installer checks and asset digests. Power-loss recovery was not verified.
