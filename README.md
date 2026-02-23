# SpiritOfTheWoof

**Version:** 1.1.1  
**Author:** the-xorcist  
**Release Date:** 2026-02-24

## Description

SpiritOfTheWoof adds a complete line of Druid movement speed buff spells to Erenshor, inspired by classic MMO gameplay. The mod introduces four tiers of "Spirit of the Wolf" spells that Druids can learn and cast on themselves or other players, providing increasingly powerful movement speed bonuses.

## Features

- **Four-Tier Spell Progression**: Lesser, Standard, Greater, and Elder variants with increasing power
  - Lesser Spirit of the Wolf (Level 5): 1.5x movement speed for 15 minutes
  - Spirit of the Wolf (Level 15): 2.5x movement speed for 30 minutes
  - Spirit of the Greater Wolf (Level 25): 3.5x movement speed for 45 minutes
  - Spirit of the Elder Wolf (Level 35): 5.0x movement speed for 60 minutes

- **Vendor Integration**: Spell scrolls are automatically added to Tiver Banes (Druid vendor) in Port Azure

- **SimPlayer Interactions**: NPCs will whisper or shout requests for Spirit of the Wolf buffs, adding immersive MMO-style social gameplay (configurable)

- **Proper Spell Mechanics**: Full integration with Erenshor's spell system including visual effects, status messages, and spell line management

## Installation

1. Install BepInEx for Erenshor (if not already installed)
2. Copy `SpiritOfTheWoof.dll` to `BepInEx/plugins` folder
3. Launch the game
4. (Optional) Copy `the-xorcist.spiritofthewoof.cfg` to `BepInEx/config` folder for preset default configuration

## Configuration

The mod includes configurable options for SimPlayer SoW requests:
- Enable/disable SimPlayer buff requests
- Adjust whisper and shout frequency
- Customize request behavior in dungeons and groups

Edit the config file in `BepInEx/config/the-xorcist.spiritofthewoof.cfg` after first launch.

## Changelog

### v1.1.1 (2026-02-24)
- Initial release

## Source Code

Source code is included in the `-source.zip` archive.
