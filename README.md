# End-Expansion Add-On
## Swordspark Games

A comprehensive Minecraft Bedrock Edition add-on that expands the End dimension with new biomes, flora, fauna, and building materials. Experience the Sovereign Chorus Valley and discover the secrets of the expanded End.

### Table of Contents
- [About](#about)
- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Documentation](#documentation)
- [Version and Changelog](#changelog)
- [Credits & Notes](#credits--notes)

---

### About
This is the official project hub for the **Swordspark Games** team's **End-Expansion Addon**. We are dedicated to creating immersive, high-quality content for the Minecraft Bedrock community.

This add-on is designed to breathe new life into the End dimension, adding depth, variety, and new gameplay mechanics. Soon, this project will be available on **CurseForge** for easy installation and updates.

### Introduction
The End is no longer just a barren wasteland of obsidian pillars and Endermen. With **End-Expansion**, players can explore the **Sovereign Chorus Valley**, a lush and mysterious biome featuring:
- **New Flora**: The unique *Sovereign Chorus Tree*, *Chorus Grass*, and custom leaves.
- **New Building Blocks**: Custom logs, planks, and decorative blocks inspired by the End's aesthetic.
- **Custom Generation**: New terrain generation rules that create rolling hills and valleys within the End.
- **Crafting Integration**: Fully integrated recipes allowing players to craft tools, boats, and structures using the new wood set.

### Features
- 🌲 **Sovereign Chorus Trees**: Custom tree generation with unique logs and leaves.
- 🏝️ **Sovereign Chorus Valley**: A new biome with custom climate and surface parameters.
- 🔨 **Full Wood Set**: Logs, Planks, Stairs, Slabs, Fences, Gates, and Boats.
- 🔥 **Realistic Physics**: Custom explosion resistance, mining speeds, and flammability settings.
- 🛠️ **Bedrock Optimized**: Built specifically for Minecraft Bedrock Edition (1.21+) using the latest feature flags.

### Installation
1. **Download**: Get the latest `.mcaddon` or `.mcpack` file from the [Releases](#) page (Coming Soon).
2. **Import**: Click the file to automatically import it into Minecraft Bedrock Edition.
3. **Activate**:
   - Go to **Settings** > **Global Resources** (for Resource Pack) and **Behavior Packs** (for Behavior Pack).
   - Activate both packs.
   - Create a **New World** and enable the packs in the world settings.
   - *Note: This add-on requires a fresh world to generate the new biomes correctly.*

### Documentation
For developers and advanced users, here is a summary of the technical implementation:

- **Biome Definition**: Uses `minecraft:biome` with custom `end_height` and `surface_parameters`.
- **Tree Feature**: Implements `minecraft:tree_feature` with custom `foliage_placer` and `trunk_height` ranges.
- **Feature Rules**: Utilizes `minecraft:feature_rules` with `surface_pass` for correct placement in the End.
- **Block Properties**: Custom `destructible_by_explosion`, `destructible_by_mining`, and `flammable` components defined in `blocks.json`.
- **Recipes**: Shaped crafting recipes defined in `recipes/` folder for all wood variants and boats.

*For full JSON schemas and API references, please refer to the `/docs` folder in this repository.*

### Version and Changelog

#### Previous Versions

##### v0.1.0-alpha
- **Added**: Sovereign Chorus Valley biome definition.
- **Added**: Sovereign Chorus Tree feature and generation rules.
- **Added**: Custom wood set (Logs, Planks).
- **Fixed**: Biome tag mismatch between biome and feature rules.
- **Fixed**: Explosion resistance and flammability settings for planks.
- **Changed**: Updated `format_version` to `1.21.0` for compatibility.

#### Current Version: v0.2.0-alpha
- **Added**: New native mobs for the Sovereign Chorus Valley.
  - *Chorus Slime* (Name subject to change)
  - *Sovereign Chorus Endermen* (Models currently in progress)
- **Added**: Expanded crafting recipes.
- **Updated**: Preparation for the official CurseForge release.

#### Upcoming Versions: v0.3.0-alpha (Planned)
- **Overhaul**: Generation code and advanced scripting.
- **Expansion**: Additional biomes and Enderman variants.
- **Content**: New structures and ambient particle effects.
- **Features**: Potential new boss encounters.
- **Progression**: New armor, custom ores, and advanced gameplay mechanics.

### Credits & Notes
- **Developer**: Swordspark Games
- **Platform**: Minecraft Bedrock Edition
- **License**: All rights reserved. Redistribution without permission is prohibited.
- **Support**: For bugs or feature requests, please open an issue in this repository.
- **Disclaimer**: This add-on is in active development. Features and content are subject to change or removal in future updates. Always backup your worlds before installing new modifications.

A sneak peek at upcoming features is available in the documentation. Check the release notes for detailed information on future versions.

---
*Made with ❤️ by Swordspark Games*
