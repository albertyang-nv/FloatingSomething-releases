# FLOAT / DECK — releases

Installers and update packages for **FLOAT / DECK** (Floating Something), a floating workspace for Windows: AI translation and polishing, word lookup, Markdown ⇄ HTML, AI chat and web search, and other apps' windows docked in tabs. The source code is not in this repository.

## Install

1. Download [`FloatDeck-win-Setup.exe`](https://github.com/albertyang-nv/FloatingSomething-releases/releases/latest/download/FloatDeck-win-Setup.exe) from the [latest release](https://github.com/albertyang-nv/FloatingSomething-releases/releases/latest) and run it.
2. It installs for the current user (no administrator rights needed) and adds "FLOAT DECK" shortcuts to the Start menu and the desktop.
3. The installer is not code-signed. If Windows shows "Windows protected your PC", choose **More info → Run anyway**.

## Updates

The installed app checks this repository for new versions, downloads them in the background, and applies them the next time it exits. To update right away, open **Help → Version → Restart and update now**. Automatic checks can be turned off on the same page.

Settings, the key and the dictionary are kept in `%LocalAppData%\FloatingSomething\Data`, which updates and uninstalling leave alone.

## Portable

`FloatingSomething-vX.Y.Z-win-x64.zip`: unzip and run `FloatingSomething.exe`. Settings are kept next to it, and it does not update itself. Each zip has a `.sha256` file to verify the download.

## Release notes

See each [release](https://github.com/albertyang-nv/FloatingSomething-releases/releases) for what changed.

---

Copyright © 2026 Albert Yang (CFY). Third-party components and their licenses: **Help → Copyright** in the app, and `THIRD-PARTY-NOTICES.txt` in every release.
