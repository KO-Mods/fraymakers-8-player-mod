# Fraymakers 8 Player Mod

## Download

[![Download Fraymakers 8 Player Mod](https://img.shields.io/badge/Download-Fraymakers%208P%20Mod-2ea44f?style=for-the-badge&logo=github)](https://github.com/KO-Mods/fraymakers-8-player-mod/releases/latest)

**Current version:** TEST v0.2
**Compatible with:** Fraymakers 1.10.0

Experimental mod that expands Fraymakers local multiplayer beyond the normal 4-player limit, with experimental support for up to 8 players.

> [!WARNING]
> This mod is still experimental.
>
> TEST v0.2 has been personally tested on Fraymakers 1.10.0.
>
> Players using Fraymakers 0.9.0 should download the previous TEST v0.1 release.

[Download TEST v0.1 for Fraymakers 0.9.0](https://github.com/KO-Mods/fraymakers-8-player-mod/releases/download/v0.1-test/Fraymakers_8P_TEST_v0.1_COMMUNITY.zip)

## Current status

* Updated for Fraymakers 1.10.0
* More than 4 players working
* 6 simultaneous players tested in-game
* Experimental support for up to 8 players
* Local multiplayer
* Additional controller slots
* Three-column character selection layout
* Four-direction controller navigation
* Vertical scrolling in the character list
* Additional colors for player slots 5 through 8
* Improved spawn handling for additional players
* Some stages, HUD elements or game modes may still have issues with more than 4 players

## Installation

1. Go to the [Releases](https://github.com/KO-Mods/fraymakers-8-player-mod/releases) section.
2. Download the release made for your version of Fraymakers.
3. Extract the ZIP file.
4. Run `START_INSTALLER.bat`.
5. Select `INSTALL TEST MOD`.
6. Start Fraymakers.

The installer automatically creates a backup of the original `hlboot.dat`.

## Uninstall / Restore

Run `START_INSTALLER.bat` again and select:

`RESTORE ORIGINAL`

## Compatibility

| Mod version        | Fraymakers version | Status                |
| ------------------ | -----------------: | --------------------- |
| TEST v0.2          |             1.10.0 | Tested                |
| TEST v0.1          |              0.9.0 | Tested legacy version |
| Other combinations |     Other versions | Untested              |

Each release is designed for a specific version of Fraymakers. Do not install the v0.1 patch on Fraymakers 1.10.0 or the v0.2 patch on Fraymakers 0.9.0.

Untested does not necessarily mean incompatible, but incorrect version combinations may cause crashes or prevent the game from starting.

## Controllers

Testing additional players may require extra physical controllers or virtual controllers such as vJoy.

The character selection screen supports navigation in all four directions with a controller and automatically scrolls when moving through longer character lists.

## Known issues

Because Fraymakers was originally designed around 4-player matches, some content may behave unexpectedly with additional players.

Possible issues include:

* Stage spawn positions
* Camera behavior
* HUD layout
* Custom stages
* Some game modes
* Controller detection
* Content designed specifically for a maximum of 4 players

Please report problems through [GitHub Issues](https://github.com/KO-Mods/fraymakers-8-player-mod/issues). Include your Fraymakers version, mod version and the number of connected players.

## Important

This repository does not distribute Fraymakers' original `hlboot.dat`.

The installer applies a patch to an existing compatible installation of Fraymakers.

Always keep a backup before modifying game files.

## Development note

Parts of this mod and its installer were developed with the assistance of AI tools.

AI was mainly used to assist with bytecode analysis, prototyping modifications, tooling and documentation.

The mod itself has been manually tested and iterated in-game by the project author.

Final testing and release decisions are made by the project author.

## Disclaimer

This is an unofficial community modification.

It is not affiliated with or endorsed by Team Fray, McLeodGaming, or the developers of Fraymakers.
