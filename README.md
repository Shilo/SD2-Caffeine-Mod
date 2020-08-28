# Soda Dungeon 2 - Caffeine Mod [Windows/Steam]
[![Caffeine](README/showcase.gif)](https://github.com/Shilo/SD2-Caffeine-Mod/releases)  
[Caffeine](https://github.com/Shilo/SD2-Caffeine-Mod/releases)  
Author: [Shilo](https://github.com/Shilo)  

Caffeine Mod boosts Soda Dungeon 2's energy and smartness.  
Includes quality of life features and fixes.  
Guaranteed free, safe, and no cheats.  
> Compatible with Windows/Steam only.  
> Official Mac OS X support in the future. It may work out of the box with "Manual" installation (not tested).

## Table Of Contents
- [Changes](#changes)
  * [Features](#features)
  * [Fixes](#fixes)
- [Disclaimer](#disclaimer)
- [Compatibility Warning](#compatibility-warning)
- [Download](#download)
- [In-game Usage](#in-game-usage)
- [Installation](#installation)
  * [1. Mod Auto Install](#1-mod-auto-install)
  * [2. Manual](#2-manual)
- [Uninstallation](#uninstallation)
  * [1. Mod Auto Uninstall](#1-mod-auto-uninstall)
  * [2. Steam's "Verify Integrity of Game Files..."](#2-steams-verify-integrity-of-game-files)
  * [3. Manual](#3-manual)
- [Roadmap](#roadmap)
  * [Completed](#completed)
  * [Incompleted](#incompleted)
    + [General](#general)
    + [Town Productivity (Opt-In)](#town-productivity-opt-in)
    + [Fun](#fun)
    + [Code](#code)
- [Special Thanks](#special-thanks)
- [Versioning](#versioning)
  * [Chronological Order](#chronological-order)

## Changes

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

## Compatibility Warning
Only install this mod with the compatible SD2 version specified (for example, Caffeine Mod v1.0.5.X only supports SD2 v1.0.5). The numerical version of the mod will always match the supported version of the game. If you install the mod with an incompatible SD2 version, unwanted results will happen. The game will most likely freeze or crash. The game may also downgrade to an older SD2 version. If you happen to run into this issue, you can [uninstall the mod](#uninstallation) to revert back to the original working game. Or you can repair your game via Steam's ["Verify Integrity of Game Files..."](https://support.steampowered.com/kb_article.php?ref=2037-QEUH-3335) button.

## Download
[Latest version](https://github.com/Shilo/SD2-Caffeine-Mod/releases)

## In-game Usage
- Open options and about window by clicking the [![Options](README/logo.png)](README/options.png) button at bottom-right of the game.
- Toggle options to turn on/off features and fixes.
- Enjoy the caffeine rush!

## Installation
> Note: If the game is updated, the mod will be automatically uninstalled.
- Download the [mod here](https://github.com/Shilo/SD2-Caffeine-Mod/releases).
- Unzip downloaded folder.
- Install with one of two methods:
### 1. Mod Auto Install
- Launch `install.bat`.
- Press `Y` when prompted.
- You should see a success message.
- If game is running, exit and restart it.
### 2. Manual
- Navigate to folder: `C:\Program Files (x86)\Steam\steamapps\common\Soda Dungeon 2\SodaDungeon2_Data\Managed\`
- Create a copy/backup of `Assembly-CSharp.dll` (preferably in the same folder).
- Replace `Assembly-CSharp.dll` with the exact file that was downloaded.
- If game is running, exit and restart it.

## Uninstallation
> Note: If the game is updated, the mod will be automatically uninstalled.
- Uninstall with one of three methods:
### 1. Mod Auto Uninstall
- Launch `uninstall.bat`.
- Press `Y` when prompted.
- You should see a success message if the mod was previously installed.
- If game is running, exit and restart it.
### 2. Steam's "Verify Integrity of Game Files..."
- If game is running, exit it.
- Repair your game via Steam's ["Verify Integrity of Game Files..."](https://support.steampowered.com/kb_article.php?ref=2037-QEUH-3335) button.
### 3. Manual
- Locate file: `C:\Program Files (x86)\Steam\steamapps\common\Soda Dungeon 2\SodaDungeon2_Data\Managed\Assembly-CSharp.dll`
- Replace file with a backup/original version. There should be a backup in the same folder if you followed the installation correctly.
> If you previously used `installer.bat`: file named will be `_BACKUP_Assembly-CSharp.dll`.
- If game is running, exit and restart it.

## Roadmap
[Submit ideas, feature and bug fix requests on issues page.](https://github.com/Shilo/SD2-Caffeine-Mod/issues)

### Completed
- ~~Feature: Display realtime FPH and Warped FPH in dungeon run.~~
- ~~Feature: Export script with 'Copy Script To Clipboard' button in script menu.~~
- ~~Feature: Customizable mod options.~~
- ~~Fix: Improved character stats positions in party window.~~  
[See detailed changes...](#changes)

### Incompleted

#### General
- Feature: Add "remaining gold" counter to essence fountain. @caviyacht
- Feature: Change essence fountain "remaining gold" text to red when not enough gold to warp to highest floor.
- Feature: Change warp gold text to red when not enough gold to use desired warp.
- Feature: Warp screen icon button to select highest afforable floor button at warp.
- Feature: Click on FPH counters to toggle showing warped and non-warped floor counts.
- Feature: Add "Fullscreen Windowed" option in SD2's advanced options window.
- Feature: Additional settings page that will toggle off individial UI elements during dungeon run. Maybe even a "Hardcore" or "Camera" mode that turns off all UI elements besides the bottom buttons for dungeon run and town. @Darzk
- Feature: "Show FPS" setting to enable the built-in debug fps counter.
- Fix: Remove "Defend" dropdown option when selecting action for "self" and "ally" target. (Since defend doesn't work when targetting self/ally.) @ElJay
- Feature: Show "Best Fph" in record book (will use Warp Fph, if applicable). Requires a minimal of 1 hour runs. @anpShawn
- Fix: If only "Warp Fph" is enabled, temporarily show "Fph" if no warps have been activated yet.
- Feature: Show warped floor count in "Adventure Progress", after the manual cleared flors with "(+WARPED_FLOORS_COUNT)".
- Fix: "Adventure Progress" timer should show time after 24 hours, and possibly seconds too. @Smgy
- Feature: Show "essence gnome" essence earings during dungeon run instead of only at end. @caviyacht
- Testing: Test mod installation and usage on Mac OS X.
- Testing: Find someone to test installation and usage on Linux.
- Feature: Improve Windows installer/uninstaller to dynamically find Steam folder location (and possibly allow specifying the location).
- Feature: Add Mac OS X installer and release zip (with cmd files).
- Feature: Add Linux installer and release zip (with text files explaining how to manually setup).
- Documentation: Add specific Windows, Mac, Linux install/uninstall instructions.
- Feature: Uninstall mod button in options.
- Feature: Export/import scripts with files and raw non-localized data format.
- Feature: Import scripts from text previously copied to clipboard from this mod.
- Feature: Hourly stats in "Adventure Progress" window.
- Feature: Add an extra decimal place (or two extra) for big numbers (e.g. 1.5k = 1.52k).
- Feature: Tab hotkey to toggle "Adventure Progress" visibility.
- Feature: Play sound effect when run ends.
- Feature: Allow relic window viewing while in dungeon run.
- Feature: Allow party window viewing while in dungeon run.
- Feature: Allow book window viewing while in dungeon run.
- Feature: Allow soda script viewing/copying while in dungeon run.
- Feature: Death tracker on-screen log.
- Feature: Opt-in dungeon party stats condensing (e.g. 100,000 = 100k).
- Feature: Show owned item counts in Item Compendium book.
- Feature: Copy "Adventure Progress" full-stats to clipboard.
- Fix: Reposition dungeon character stats to avoid being off screen or covered.
- Fix: Improve fit of large numbers in Hire window.
- Fix: Improve sorting of "Adventure Progress" items (sort by rarity).
- Feature: Organize and improve options window with tabs, checkboxes, and scrollviews to allow for infinite settings without users getting or overwhelmed.
- Feature: A new page in record book for caffeine mod related stats.

#### Town Productivity (Opt-In)
> These would be disabled by default and opt-in options.  
> Seperate "Town Productivity" settings page with a lock icon.
> Attempting to unlock specific page will warn the user that it affects "Town Productivity", and asks if user wants to continue.  
> If user confirms to unlock feature. The Caffeine option button will permanently turn orange instead of green. The warning will never show again on further lock changes.  
> This is not to shame users who use the feature(s), but only to credit the users who want to keep a vanilla experience.  
> Also allow users to re-lock options page. (Relocking will not change options button back to green.)
- Feature: Essence fountain to start with max gold minus warp cost. So you can keep enough gold to warp.
- Feature: Ability to increase tick count for essence fountain.
- Feature: Ability to increase tick count for relic leveling.
- Feature: Settings to allow constant arrow clicking on holding mouse down also, instead of only mouse up.
- Feature: Move all Soda Junkies to the back of the tavern (infront of the stools) when they aren't enabled in the book.

#### Fun
- Feature: Caffeine top secret (easter egg). @caviyacht
- Feature: Record book stat "Caffeine Top Secret Uncovered" with count.
- Feature: Interactive pixel art version of myself in tavern. @caviyacht
- Feature: "Wood Mode" where dimension title shows as "Wood Dimension" and loot only shows "Wood" (maybe each count shows as a new stack). @caviyacht @Retropaint
- Feature: Show visual effects (fireworks) at 1 million floor milestone.

#### Code
- Prioritize hooks more. Minimize any core code changes by implementing 1 line method calls and add most code changes in my custom classes. (This will make code a lot more portable between SD2 updates.)
- Possibly export to Visual Studio for better code and revision management.

## Special Thanks
- [Shawn Tanner](https://www.sodadungeon.com)
- [Tilli](https://discord.gg/y93QchM)
- [XenosTec](https://discord.gg/y93QchM)
- [caviyacht](https://github.com/caviyacht)

## Versioning
Format of versions: `SD2_VERSION.MOD_VERSION [SODA|SKILL|CHARACTER|DIMENSION]`
> Example: v1.0.5.0 Dinner Boy
### Chronological Order
0. Dinner Boy
1. Soda Junkie
2. Hammerin' Ale
3. Quarry Quench
4. RN Cola
5. Mystic Fizz
6. Loot Beer
7. Wildberry Blast
8. Corrupted Cola
9. Double Bubble
10. The Dark Lord
11. Big Burp
12. Nailed it
13. Transmute
14. First Aid
15. Torment
16. Ransack
17. Mark
18. Noxin
19. Double Strike
20. Shadow Slicer
21. Healing Fairy
22. The Janitor
23. Chameleon Lord
24. Lobster Lord
25. The Darker Lord
26. Mecha-Lord
27. The Dark Lady
28. Dark Dialer
29. The Lord of Light
30. Vacation Lord
31. Grill of Darkness
32. The Darkest Lord
33. The Darkest One
34. Dimension 1
35. Dimension 2
36. Dimension 3
37. Dimension 4
38. Dimension 5
39. Dimension 6
40. Dimension 7
41. Dimension 8
42. Dimension 9
43. Ruin
44. Warrior's Dimension
45. Warrior's Dimension 2  
(ect)
