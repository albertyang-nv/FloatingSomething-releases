# FLOAT / DECK — releases

Installers and update packages for **FLOAT / DECK** (Floating Something), a floating workspace for Windows: AI translation and polishing, word lookup, Markdown ⇄ HTML, AI chat and web search, and other apps' windows docked in tabs. The source code is not in this repository.

## 安裝 / Install

1. 到 [Releases](https://github.com/albertyang-nv/FloatingSomething-releases/releases/latest) 下載 `FloatDeck-win-Setup.exe`，點兩下安裝。
   Download `FloatDeck-win-Setup.exe` from the latest release and run it.
2. 安裝到使用者自己的資料夾，不需要系統管理員權限；開始選單與桌面會有「FLOAT DECK」捷徑。
   It installs for the current user (no administrator rights) with Start menu and desktop shortcuts.
3. 安裝檔沒有程式碼簽章，Windows 可能顯示「Windows 已保護您的電腦」：按「其他資訊 → 仍要執行」。
   The installer is not code-signed; if SmartScreen warns, choose "More info → Run anyway".

## 更新 / Updates

安裝版會自動檢查這裡的新版本並在背景下載，下次結束程式時套用，也可以在「說明 → 版本」立即更新。
The installed app checks this repository, downloads new versions in the background and applies them when it exits (or at once from Help → Version).

## 免安裝版 / Portable

`FloatingSomething-vX.Y.Z-win-x64.zip`：解壓縮後執行 `FloatingSomething.exe`，設定放在程式旁邊，不會自動更新。
Unzip and run `FloatingSomething.exe`; settings stay next to it and it does not update itself.

---

Copyright © 2026 Albert Yang (CFY). Third-party components and their licenses: Help → Copyright in the app, and `THIRD-PARTY-NOTICES.txt` in every release.
