# Shantae Risky's Revenge: Enhanced Mod

A mod for the Steam PC version of *Shantae: Risky's Revenge – Director's Cut* that brings back the DSi look and feel and changes several things with the PC port.

> **AI disclaimer:** This mod heavily uses AI but does not include any AI-generated images, videos etc. I also didn't originally intend to share this but thought I might as well in case someone wants to use it.

## Features

### DSi-style menus

- The original WayForward intro in 16:9
- Changes the title screen, file select, options, control config and pause screen to look more like the original DSi version
- Pause menu also pauses the music like the original
- Inventory, world map and shop restyled to match
- Using the same sound effects the DSi version used

### In-game Mod Settings (Options > Mod Settings, with both menu styles)

- **Text Speed:** Normal, 1.5x, 2x, 3x, Instant
- **Better Portraits:** dialogue portraits slide in over the black bars at the screen edges so you can see more of the gameplay
- **Out of Focus:** pause the game or keep running when the window isn't focused
- **Item Info:** still or scrolling item descriptions

### Other improvements

- Portraits without the white outlines
- Side borders: black, or a picture (a grey background with sprites from the game is included, or use your own)
- Skippable WayForward intro
- Experimental 16:9 widescreen (has visual bugs, not recommended for first time players)

## Installation

1. Install [Python](https://www.python.org/downloads/) (tick **"Add python.exe to PATH"**). The installer doesn't install anything else.
2. Download the latest release and extract the `EnhancedMod` folder into the game folder, for example:
   `C:\Program Files (x86)\Steam\steamapps\common\RiskysRevenge\EnhancedMod`
3. Double-click `install.bat`.
4. Use **Up/Down** to move and **Left/Right** to change a setting, then choose **Save config** and press **Enter**.

Run `install.bat` again any time to change settings. The original files are backed up (`.bak`) and the game is always patched from those backups. Choose **Uninstall** in the menu to restore the original game.

After a Steam update or "Verify integrity of game files", run `install.bat` again.

## Custom border picture

Replace `BorderImages/border.png` with your own 16:9 PNG (for example 1920x1080). Its middle is hidden behind the game. Then run `install.bat` again and choose the picture border.

## Troubleshooting

If the game crashes or something doesn't work, open an issue and attach `executable/rr_mod_log.txt` from the game folder.

## Credits

- File select text font: [Inter](https://rsms.me/inter/) (SIL Open Font License, see `files/fonts`)
- *Shantae: Risky's Revenge* © WayForward. This is an unofficial fan mod and is not affiliated with WayForward. You need your own copy of the game.

## Screenshots

| Title screen | File select |
|---|---|
| ![Title screen](screenshots/title.png) | ![File select](screenshots/file_select.png) |

**Side borders with sprites from the game**

![Gameplay with the sprite side borders](screenshots/sprite_border.png)

**Better Portraits:** portraits slide in over the black bars so you can see more of the gameplay.

| Better Portraits on | Better Portraits off |
|---|---|
| ![Better Portraits on](screenshots/better_portraits_on.png) | ![Better Portraits off](screenshots/better_portraits_off.png) |

**Portrait outlines**

| Outlines removed | Original outlines |
|---|---|
| ![Outlines removed](screenshots/portrait_outlines_removed.png) | ![Original outlines](screenshots/portrait_outlines_original.png) |

**Experimental 16:9 widescreen**

| | |
|---|---|
| ![Widescreen](screenshots/widescreen_1.png) | ![Widescreen](screenshots/widescreen_2.png) |
