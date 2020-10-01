# SD2 - Caffeine Mod [Steam / Windows / Mac OS X]
[![Caffeine](README/showcase.gif)](README)  

[![Caffeine](README/logo.png)](#download)  
A Caffeine-addicting mod that boosts [Soda Dungeon 2](https://www.sodadungeon.com/)'s energy and smartness.  
Includes quality of life features and fixes.  
Guaranteed free, safe, and no cheats.  
> Compatible with Steam, Windows and Mac OS X only.  
> Mac OS X installer coming in the future.

Author: [Shilo](https://github.com/Shilo)  

## Table Of Contents
- [Overview](#overview)
  * [Features](#features)
  * [Fixes](#fixes)
- [Disclaimer](#disclaimer)
- [Security](#security)
- [Compatibility Warning](#compatibility-warning)
- [Download](#download)
- [In-game Usage](#in-game-usage)
- [Installation](#installation)
  * [Windows](#windows)
    * [Mod Auto Install](#mod-auto-install)
    * [Manual](#manual)
  * [Mac OS X](#mac-os-x)
    * [Manual](#manual-1)
- [Uninstallation](#uninstallation)
  * [Steam's "Verify Integrity of Game Files..."](#steams-verify-integrity-of-game-files-recommended)
  * [Windows](#windows-1)
    * [Mod Auto Uninstall](#mod-auto-uninstall)
    * [Manual](#manual-2)
  * [Mac OS X](#mac-os-x-1)
    * [Manual](#manual-3)
- [Roadmap](#roadmap)
- [Versioning](#versioning)
- [Special Thanks](#special-thanks)

## Overview
[See detailed changes in changelog...](/CHANGELOG.md)

### Features
- Display realtime FPH and Warped FPH in dungeon run.
- Export script with 'Copy Script To Clipboard' button in script menu.
- Customizable mod options.

### Fixes
- Improved character stats positions in party window.

## Disclaimer
All code and rights belong to their respective owners: AN Productions, Poxpower, Armor Games Studios or other.  
I take no credit for any of the original code and assets.  
Use this mod at your own risk: I am not responsible for any results of using this mod.  
The terms "safe" and "cheats" are subjective.   
By using this mod, you agree to the above terms.

## Security
Guaranteed safe and virus free.  
[See security report...](SECURITY_REPORT.md).

## Compatibility Warning
Only install this mod with the compatible SD2 version specified (for example, Caffeine Mod v1.0.5.X only supports SD2 v1.0.5). The numerical version of the mod will always match the supported version of the game. If you install the mod with an incompatible SD2 version, unwanted results will happen. The game will most likely freeze or crash. The game may also downgrade to an older SD2 version. If you happen to run into this issue, you can [uninstall the mod](#uninstallation) to revert back to the original working game. Or you can repair your game via Steam's ["Verify Integrity of Game Files..."](https://support.steampowered.com/kb_article.php?ref=2037-QEUH-3335) button.

## Download
[![Options](README/logo.png) Pre-Release: v1.0.5.1 Soda Junkie [PRE-RELEASE]](https://github.com/Shilo/SD2-Caffeine-Mod/releases/tag/v1.0.5.1-pre-release)  
[![Options](README/logo.png) Latest: SD2-Caffeine-Mod.zip](https://github.com/Shilo/SD2-Caffeine-Mod/releases/latest/download/SD2-Caffeine-Mod-v1.0.5.0.zip)
- Navigate to [latest version](https://github.com/Shilo/SD2-Caffeine-Mod/releases/latest).
- Scroll down to "Assets" and open the first link named "[SD2-Caffeine-Mod.zip](https://github.com/Shilo/SD2-Caffeine-Mod/releases/latest/download/SD2-Caffeine-Mod-v1.0.5.0.zip)".
> Source code links are irrelevant as it is just the [documentation](https://github.com/Shilo/SD2-Caffeine-Mod) only.  
> If your browser indicates that download may be dangerous, instruct it to continue/keep download.  
> If your antivirus software reports a virus, it is a false positive and should be reported to the antivirus company.

## In-game Usage
- Open options and about window by clicking the [![Options](README/logo.png)](README/options.png) button at bottom-right of the game.
- Toggle options to turn on/off features and fixes.
- Enjoy the caffeine rush!

## Installation
> Note: If the game is updated, the mod will be automatically uninstalled.
- [Download](#download) the latest version.
- Unzip downloaded folder.
- Install with one of below methods:
### Windows
#### Mod Auto Install
- Launch `install.bat`.
- Press `Y` when prompted.
- You should see a success message.
- If game is running, exit and restart it.
#### Manual
> Only follow these steps if you are competent with computers and file management.
- Navigate to folder: `C:\Program Files (x86)\Steam\steamapps\common\Soda Dungeon 2\SodaDungeon2_Data\Managed\`
- Create a copy/backup of `Assembly-CSharp.dll` (preferably in the same folder).
- Replace `Assembly-CSharp.dll` with the exact file that was downloaded.
- If game is running, exit and restart it.
> Warning: Make sure not to confuse `Assembly-CSharp.dll` with `Assembly-CSharp-firstpass.dll`, only replace `Assembly-CSharp.dll`.  
> If you have issues or made a mistake, repair your files with [Steam's "Verify Integrity of Game Files..."](#steams-verify-integrity-of-game-files-recommended) and attempt to install again.
### Mac OS X
#### Manual
> Only follow these steps if you are competent with computers and file management.  
> More detailed instructions in the future.
- Locate your Steam apps: `Steam -> Preferences -> Downloads -> Steam Library Folders`
- Show package contents: `Right click SodaDungeon2 -> Show Package Contents`
- Navigate to the following folder: `Contents -> Resources -> Data -> Managed`
- Create a copy/backup of `Assembly-CSharp.dll` (preferably in the same folder).
- Replace `Assembly-CSharp.dll` with the exact file that was downloaded.
- If game is running, exit and restart it.
> Warning: Make sure not to confuse `Assembly-CSharp.dll` with `Assembly-CSharp-firstpass.dll`, only replace `Assembly-CSharp.dll`.  
> If you have issues or made a mistake, repair your files with [Steam's "Verify Integrity of Game Files..."](#steams-verify-integrity-of-game-files-recommended) and attempt to install 

## Uninstallation
> Note: If the game is updated, the mod will be automatically uninstalled.  
- Uninstall with one of below methods:
### Steam's "Verify Integrity of Game Files..." (Recommended)
- If game is running, exit it.
- Repair your game via Steam's ["Verify Integrity of Game Files..."](https://support.steampowered.com/kb_article.php?ref=2037-QEUH-3335) button.
### Windows
#### Mod Auto Uninstall
- Launch `uninstall.bat`.
- Press `Y` when prompted.
- You should see a success message if the mod was previously installed.
- If game is running, exit and restart it.
#### Manual
> Only follow these steps if you are competent with computers and file management.
- Locate file: `C:\Program Files (x86)\Steam\steamapps\common\Soda Dungeon 2\SodaDungeon2_Data\Managed\Assembly-CSharp.dll`
- Replace `Assembly-CSharp.dll` with a backup/original version. There should be a backup in the same folder if you followed the installation correctly.
> If you previously used `installer.bat`: file named will be `_BACKUP_Assembly-CSharp.dll`.
- If game is running, exit and restart it.
> Warning: Make sure not to confuse `Assembly-CSharp.dll` with `Assembly-CSharp-firstpass.dll`, only replace `Assembly-CSharp.dll`.  
> If you have issues or made a mistake, repair your files with [Steam's "Verify Integrity of Game Files..."](#steams-verify-integrity-of-game-files-recommended) and it will automatically uninstall mod also.
### Mac OS X
#### Manual
> Only follow these steps if you are competent with computers and file management.  
> More detailed instructions in the future.
- Locate your Steam apps: `Steam -> Preferences -> Downloads -> Steam Library Folders`
- Show package contents: `Right click SodaDungeon2 -> Show Package Contents`
- Navigate to the following folder: `Contents -> Resources -> Data -> Managed`
- Replace file with a backup/original version. There should be a backup in the same folder if you followed the installation correctly.
- If game is running, exit and restart it.
> Warning: Make sure not to confuse `Assembly-CSharp.dll` with `Assembly-CSharp-firstpass.dll`, only replace `Assembly-CSharp.dll`.  
> If you have issues or made a mistake, repair your files with [Steam's "Verify Integrity of Game Files..."](#steams-verify-integrity-of-game-files-recommended) and it will automatically uninstall mod also.

## Roadmap
[See detailed tasks in roadmap...](https://github.com/Shilo/SD2-Caffeine-Mod/projects/1)  
> Use [Issues page](https://github.com/Shilo/SD2-Caffeine-Mod/issues) to submit requests for features and bug fixes, as well as other ideas.

## Versioning
[See product names in version format...](VERSION_FORMAT.md)  

## Special Thanks
- [Shawn Tanner](https://www.sodadungeon.com) for creating Soda Dungeon 2 and allowing this mod and community to thrive. Check out his fun [game](https://www.sodadungeon.com)!
- [DeathTruction](https://github.com/Death-Truction) for creating flexible new installer and other support behind the scenes. Check him out on [Github](https://github.com/Death-Truction).
- [LJ](https://discord.com/invite/sodadungeon) for creating powerful backend for website and leaderboard API. Check him out on [Discord: ElJay#7711](https://discord.com/invite/sodadungeon).
- [Kubis_sakti](https://www.fiverr.com/kubis_sakti) for help in creating beautiful high-quality character. Check him out on [Fiverr](https://www.fiverr.com/kubis_sakti).
- [Benvictus](https://www.fiverr.com/benvictus) for creating a new and improved high-quality logo/button (soda sprite). Check him out on [Fiverr](https://www.fiverr.com/benvictus).
- [Nikoleta Jovanovic](https://www.artstation.com/niko-art) for helping create lovely high-quality initial logo. Check out her [portfolio](https://www.artstation.com/niko-art).
- [caviyacht](https://github.com/caviyacht) for the very appreciated help and support behind the scenes. Check him out on [GitHub](https://github.com/caviyacht).
- [Tilli](https://discord.gg/y93QchM) for the very appreciated help and support behind the scenes. Check out the [Discord server](https://discord.gg/y93QchM).
- [XenosTec](https://discord.gg/y93QchM) for the very appreciated help and support behind the scenes. Check out the [Discord server](https://discord.gg/y93QchM).
- [Etatauri](https://github.com/Etatauri) for the very appreciated help with documentation and other support behind the scenes. Check her out on [GitHub](https://github.com/Etatauri).
