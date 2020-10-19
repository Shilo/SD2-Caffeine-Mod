# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]
[See detailed tasks in roadmap...](https://github.com/Shilo/SD2-Caffeine-Mod/projects/1)

### Added

### Fixed

### Security

### Changed

### Removed

## [1.0.6.2] - 2020-10-18
### Added
- Ported/upgraded mod to SD2 v1.0.6.
- Created Caffeine Pill (Lite) version. Contains FPS counter, compatibility protection, backup/recovery system, and performance bug fixes.
- Added chef to game report.
- Added support for free warps and chef for auto essence fountain.
- Added FPS counter with settings.
- Added copy to clipboard support for dungeon level and fph text.
- Added option to turn off "All" button for relic menu.
- Added a "relic spend all" option with the settings: off, on, rounded dynamic, rounded to 10's, rounded to 100's, rounded to 1,000's.
- Added various hotkeys.

### Fixed
- Various bug fixes and improvements.
- Improved party slot stats formatting (commas and dynamic spacing).

### Security
- Added compatibility protection screen when error is encountered on load.

### Removed
- Removed Caffeine FPH counters.

## [1.0.5.1] - 2020-10-15
### Added
- Right clicking on Caffeine logo button will toggle mod on/off.
- Added "C" hotkey to toggle options window for Caffeine mod during anytime.
- Added settings to customize format for splash and gold numbers.
SD2 Default, 0 Decimal Places, 1 Decimal Place, 2 Decimal Places, 3 Decimal Places, Scientific Notation, Whole (Full), Hidden (None)
- Created automatic backup system. It will backup the previous save file right before every save event. It will backup a total of 24 different files, based on the current hour.
- Automatic backup recovery system. Will prompt uses to import best backup file, if new file.
- Added "Vanilla Experience (Disable Mod)" button to options window, will disable all mod changes.
- Added "Darken Throne Room" option.
- Added "Copy Relics To Clipboard" button to relics window.
- Added "Restore Defaults" button to options window.
- Added tab hotkey to toggle "Adventure Progress" window in dungeon.
- In Records book, format and appended detail to playtime stat.
- Display caffeine version in title screen.
- Added localization in English.
- Added additional files and metadata information in release zip.
- Added Essence Fountain QoL improvements.
- Added Essence Conversion detailed statistics.
- Easier essence conversion: arrow button clicks will trigger on mouse continuously held down instead of mouse up. Faster and less clicking. Help prevent Carpal Tunnel.
- Attempting to use essence fountain with not enough gold for expenses, will display warning.
- Added "auto" button for quick essence conversion.
- Added explanation button and dialog for essence conversion.
- Added non-interactive party view menu to options menu. Will allow viewing party anywhere in the game.
- Added "X of all levels owned" to item tooltips.
- Added item count description to Item compendium menu.
- Created notification system.
- Add setting to auto save game report when the game is saved and show notification on save.
- Created report window that shows game data.
- Added additional relic purchase increments based on half the relic level. +1k, +10k, +100k. And added comma formatting.
- Enable additional relic level increments if enough essence to purchase it.
- Added additional relic purchase increment for "all".
- Copy level and FPH stats to clipboard when left clicking text in dungeon screen.
- F12 to screenshot.
- Added tooltip system.
- Shift+C hotkey to toggle mod.
- Added tooltips to all interactive Caffeine elements.
- Added hotkey info to tooltips.
- Added tooltips for various default game elements.
- Added hotkeys for various default game windows.
- Added player and enemy percentage settings.
- Added 10k and 100k warp increments if your highest level is double those values.
- Added dimension and highest level numbers to town hud.
- Clicking level text in town will copy to clipboard.
- Added copy town dimension/level hotkey info to options window.
- Added Compatible Game Version data to game report.
- Added relic window hotkey and view-only relic window to dungeon.
- Added helpful tooltips to party window when in dungeon.
- Added F hotkey to turn off auto or exit dungeon. (Opt-in only)
- Added "Auto battle on dungeon enter", with settings:Always On, Always Off, Previous State
- Added in-dungeon HUD elapsed time.

### Fixed
- Fix dungeon elapsed timer to increment over 24 hours.
- Improved character stats size/positions in hire window.
- Fixed bug where relic "All" button didn't refresh after purchasing levels.

### Security
- Add compatibility protection screen that will protect and warn the user immediately when mod version isn't compatible with game version.

### Changed
- New and improved project workflow.
- Rewrote project from scratch.
- When only "Warp Fph" is enabled, will temporarily show "Fph" if no warps have been activated yet.
- Simplified options window and unified/revamped options.
- Overhaul options and about window.
- About menu is now scrollable.
- Caffeine logo button will now always show on top of menus. The Caffeine menu is always accessible, even during loading.
- Changed menu buttons to be smaller size.
- Added adventure keys comma formatting.
- Added comma formatting to most number texts in the game.
- Added commas to all status numbers for enemies and players in dungeon.
- Warp cost will turn red if unable to afford it.
- Updated installer and uninstaller to use dynamic Steam path.
- Opening party view with hotkey in town will no longer disable interaction.
- Closing relics window with R key will close specific relic window too.
- Closing party window with P key will close specific relic window too.
- Hotkeys are now disable-able.
- Tab hotkey will now open Adventure progress menu anytime.
- Updated about window with latest info.

### Removed
- Small performance improvement by removing unnecessary loading and rendering.
- Removed mouse over effect for Tavern stairs that have no interaction.

## [1.0.5.0] - 2020-08-27
### Added
- Display realtime FPH and Warped FPH in dungeon run.
- Export script with 'Copy Script To Clipboard' button in script menu.
- Customizable mod options.
- Installer and uninstaller.

### Fixed
- Improved character stats positions in party window.

[Unreleased]: https://github.com/Shilo/SD2-Caffeine-Mod/compare/v1.0.5.0...HEAD
[1.0.6.2]: https://github.com/Shilo/SD2-Caffeine-Mod/compare/v1.0.5.1..v1.0.6.2
[1.0.5.1]: https://github.com/Shilo/SD2-Caffeine-Mod/compare/v1.0.5.0...v1.0.5.1
[1.0.5.0]: https://github.com/Shilo/SD2-Caffeine-Mod/releases/tag/v1.0.5.0
