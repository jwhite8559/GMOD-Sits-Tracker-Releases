# GMOD Sits Tracker — official downloads

Designed by **Orion8559**. This repository distributes official Windows releases;
the application source is maintained privately.

Download **GMOD-Sits-Tracker-Setup.zip** from the [latest release](https://github.com/jwhite8559/GMOD-Sits-Tracker-Releases/releases/latest),
extract it into a dedicated folder, and open **GMOD Sits Tracker.exe**.
The EXE checks for updates on launch, downloads and verifies a newer official
release automatically, and then opens the tracker. No GitHub sign-in is needed.
The initial download needs internet access; existing installations can open
their installed application if update checks fail.

## Which ZIP should I download?

| File | Who it is for | What to do |
| --- | --- | --- |
| **GMOD-Sits-Tracker-Setup.zip** | New installations | Download this ZIP, extract it into a dedicated folder, then open **GMOD Sits Tracker.exe**. The launcher downloads the latest application automatically. |
| **GMOD-Sits-Tracker-2.0.1.zip** | The automatic updater | This is the versioned application package. Your installed launcher downloads and installs it for you. You do not need to download or extract it manually. |

**Already have the tracker installed?** Close it and reopen your usual **GMOD Sits Tracker.exe**.
It checks for updates automatically and preserves your records, evidence, settings and backups.
The number in the versioned ZIP's filename changes with each release.

GitHub's additional **Source code** ZIP/TAR downloads contain this public repository's
documentation, not the application or its private source. Use **Setup.zip** to install the app.

Records, evidence, drafts, settings and backups are stored in your installation's
`data` folder. Updates install separately in `.updates` and preserve that folder.
Keep an independent backup. Do not run the app directly inside its downloaded ZIP.

## License

This application is proprietary, not open source. You may use unmodified official
releases and share links to this download page. Modification, redistribution,
selling and rebranding of original project materials require written permission.
See [LICENSE.txt](LICENSE.txt); applicable law, GitHub terms and third-party
licenses retain their respective rights. Full notices accompany each release.

The public verification key in the application authenticates update packages.
No GitHub tokens, account passwords or signing private keys are included.
Update signing is separate from Windows publisher/code signing; Windows may
independently restrict execution of a downloaded EXE.
