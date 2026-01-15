# ACRONYM Releases

This repository hosts binary releases for the ACRONYM application.

The binaries are provided for download and use only.
Source code is proprietary and not included in this repository.

## Installation

📥 Install ACRONYM

1. Download: https://github.com/goacronym/acronym-releases/releases/latest
   (Click on the ZIP file under "Assets")
2. Unzip → Drag to Applications folder
3. Open Terminal and paste this command:

```bash
xattr -cr /Applications/ACRONYM.app
```

4. Right-click ACRONYM in Applications → "Open" → "Open" (first time only)
5. Done! Once code signing works, future updates install automatically.

> **Why the Terminal command?**
> macOS blocks unsigned apps downloaded from the internet. This one-time command removes that block. Once we get code signing, this won't be needed!

## Updating

Until auto-updates are fully functional, you'll have to uninstall and reinstall to update.

🗑️ **Uninstall ACRONYM**

1. Quit the ACRONYM app (if it's running)
2. Open Finder → Go to Applications folder
3. Find ACRONYM.app → Right-click → "Move to Trash"
4. Empty Trash

**Optional: Remove app data**
If you want to also remove saved settings and data:

```bash
rm -rf ~/Library/Application\ Support/acronym
rm -rf ~/Library/Logs/acronym
```

That's it!
