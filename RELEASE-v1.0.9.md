Project Hub 1.0.9 handles Windows blocking an app's final installation-folder move.

Previously, one EPERM error after extraction ended the installation. The Hub now retries EPERM, EACCES and EBUSY up to nine times over 19.75 seconds using the already verified files. Progress shows that it is waiting for Windows. If access remains blocked, the app retains an actionable Retry message with the Windows error code.

Every attempt rechecks the stage, managed parent and absent destination. A folder appearing during the wait is retained. Existing apps and their active receipts stay intact until the new version is committed. The Hub does not stop processes, change permissions or disable Windows protection.

**Already on 1.0.8:** enable Settings → Automatic updates for Project Hub, or choose Updates → Check → Download → Restart to update. Automatic replacement waits until the Hub is minimized/in the tray and idle. **Older than 1.0.8:** install Project-Hub-Setup-1.0.9-x64.exe once. Existing tools are detected and reused.

The four tools remain Sonora 1.0.1, Worktable 2.0.1, PadForge 0.2.2 and Velvet 1.4.0. Per-app progress, existing-app detection, Sonora's explicit audio-driver setup and opt-in Hub/tool updates are retained.

Validation passed 95 unit tests and a real Windows lock test: four EPERM errors, success on the fifth move after unlock, one download/extraction, delayed activation, unchanged existing apps and an installed Worktable launch. Native installation, selected-tool setup, existing-app reuse, 22 installed desktop checks and eight existing-app checks passed. A real packaged 1.0.8 → 1.0.9 automatic Hub upgrade passed all 14 checks, preserving settings and installed Worktable and relaunching successfully. The public download bootstrap passed reconstruction and hash verification. Exact asset hashes are recorded in VERIFICATION.json. Windows 10/11 x64; Internet required. The installer is unsigned. Signed update verification is separate from Windows Authenticode. Power-loss recovery was not verified.
