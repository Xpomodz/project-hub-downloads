Project Hub 1.0.3 brings Sonora, Worktable, PadForge and Velvet into one Windows installer.

Download `Project-Hub-Setup-1.0.3-x64.exe`. This small launcher automatically downloads and verifies the setup files, then opens the tool chooser. Internet access is required; app downloads follow your selections. You do not need to download or combine the `.part` files yourself.

- Choose each tool and its automatic-update preference on the first setup screen.
- Detect and reuse existing installations; current versions do not create duplicate copies.
- Update older verified standalone apps in their original folder, with backups and protected user data.
- Keep all tool choices and the install action visible on smaller windows.
- Receive signed app updates from this public GitHub release channel.

Included: Sonora 1.0.0, Worktable 2.0.0, PadForge 0.2.2 and Velvet 1.4.0. Sonora's version is the collection's release identifier.

Windows 10/11 x64. The installer is unsigned. Velvet's first-run engine/model setup requires Internet access and several GB; PadForge's optional driver can require administrator approval and restart. No signing private key, personal project seed or developer runtime data is included.

Validation covers 52 updater/discovery/setup/distribution/bootstrap tests, 20 installed-hub desktop checks, eight existing-install checks, actual public-feed package installation, native selected-tool installation and reuse, and uninstall. The launcher downloaded and verified all seven public setup parts and exited successfully in verification-only mode; the public installer download was also checked without a GitHub login and matched its SHA-256. The app sources were exported and tested separately. Physical audio/controller/game acceptance and a second-PC first-run AI setup are not covered by those installer checks.
