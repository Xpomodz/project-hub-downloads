Project Hub 1.0.6 makes app downloads and installation visible from start to finish.

Download `Project-Hub-Setup-1.0.6-x64.exe` and run it over the existing Hub. Choose the missing apps, then watch the app-installation window. Select **Finish** after the selected apps have a result.

- Each app shows actual download percentage and downloaded/total bytes, followed by verification and installation progress.
- File extraction reports measured progress. Checking installed apps and final setup steps clearly show their current stage.
- Apps waiting their turn stay visible as queued. Existing current apps are reused.
- Interrupted transfers have bounded retries; a stopped extraction worker produces an error rather than leaving an endless Installing state.
- Errors remain on the affected app with a Retry action. A failed app does not stop the remaining selected apps.
- Closing during installation keeps the progress window visible. Use Minimize while installation continues.
- Controls and progress remain usable at 800 by 560. Audio setup and restart requirements remain separate from successful app installation.

Worktable's app package remains version 2.0.1. Fresh installation with existing PadForge and Velvet copies was verified, including launching the installed Worktable and retaining the existing applications unchanged. The exact failure on the reported second PC was not reproduced; the new build exposes each stage and a persistent error if it occurs again.

Included versions: Sonora 1.0.1, Worktable 2.0.1, PadForge 0.2.2 and Velvet 1.4.0. Internet required. Windows 10/11 x64. The installer is unsigned.

Sonora retains its VB-CABLE/Hi-Fi Cable setup. Driver installation requires the user's choice and Windows administrator approval; a restart may be required. Hi-Fi Cable downloads directly from VB-Audio. No driver is installed automatically by background app updates.
