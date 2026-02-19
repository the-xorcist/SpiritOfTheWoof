# SpiritOfTheWoof

**Version:** 1.1.0  
**Author:** the-xorcist  
**Release Date:** 2026-02-22

## Description

SpiritOfTheWoof adds a complete line of Druid movement speed buff spells to Erenshor, inspired by classic MMO gameplay. This mod introduces four tiers of "Spirit of the Wolf" spells that Druids can learn and cast on themselves or other players, providing increasingly powerful movement speed bonuses.

## Features

- **Four-Tier Spell Progression**: Lesser, Standard, Greater, and Elder variants of Spirit of the Wolf
  - **Lesser Spirit of the Wolf** (Level 5): 1.5x movement speed for 15 minutes
  - **Spirit of the Wolf** (Level 15): 2.5x movement speed for 30 minutes
  - **Spirit of the Greater Wolf** (Level 25): 3.5x movement speed for 45 minutes
  - **Spirit of the Elder Wolf** (Level 35): 5.0x movement speed for 60 minutes

- **Vendor Integration**: Spell scrolls are automatically added to Tiver Banes (Druid vendor) in Port Azure

- **SimPlayer Interactions**: NPCs (SimPlayers) will whisper or shout requests for Spirit of the Wolf buffs when they see a Druid, adding immersive social gameplay
  - Configurable request frequency and behavior
  - Smart AI: SimPlayers won't request buffs they already have or when grouped

- **Custom Spell Icons**: Unique wolf-themed spell icons

- **Fully Configurable**: Adjust SimPlayer request rates via BepInEx configuration file

## Installation

1. Install **BepInEx** for Erenshor (if not already installed)
2. Copy `SpiritOfTheWoof.dll` to your `BepInEx/plugins` folder
3. Launch the game
4. (Optional) Copy `the-xorcist.spiritofthewoof.cfg` to `BepInEx/config` folder for preset default settings

The spells will automatically appear in Tiver Banes' shop in Port Azure once you load into the game.

## Changelog

### v1.1.0 - Initial Release (2026-02-22)
- Initial release with four-tier Spirit of the Wolf spell line
- Vendor integration with Tiver Banes
- SimPlayer request system for immersive NPC interactions
- Configurable settings for request frequency

## Source Code

Source code is included in the `-source.zip` archive.
