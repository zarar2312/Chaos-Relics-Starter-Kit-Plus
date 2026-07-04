# Chaos Relics - Starter Kit Plus

Balanced Day 1 starter support bundle for 7 Days to Die.

## Overview
This mod gives players a balanced starter kit at game start through a custom `starterKit` bundle.
It is designed to reduce early grind without skipping core survival progression.

- Mod Name: ChaosRelicsStarterKitPlus
- Display Name: Chaos Relics - Starter Kit Plus v3.0
- Version: 3.0.0
- Author: Efraim K
- Website: https://discord.gg/tHChNCMhMV

## What You Get
The `starterKit` bundle contains:

- 1x Bicycle
- 1x Hunting Knife
- 1x Stone Axe
- 1x Primitive Bow
- 30x Stone Arrow
- 6x First Aid Bandage
- 2x First Aid Kit
- 4x Pure Mineral Water
- 2x Chili Can
- 2x Repair Kit
- 10x Lockpick
- 3x Duct Tape

## Spawn Behavior
The mod injects `starterKit` into player start inventory entries in:

- Survival
- SurvivalSP
- SurvivalMP

## Installation
1. Close the game.
2. Copy this mod folder into your `Mods` directory.
3. Ensure folder structure is:

```text
Mods/
  Chaos Relics - Starter Kit Plus/
    ModInfo.xml
    Config/
    Assets/
```

4. Start the game and create/load a world.

## Compatibility
- Built as an XML modlet.
- Should be compatible with most mods unless they overwrite the same `ItemsOnEnterGame` nodes or `starterKit` item key.

## File Structure

```text
ModInfo.xml
Assets/
  Images/
Config/
  entityclasses.xml
  items.xml
  Localization.csv
```

## Screenshots

![Mod Banner](Assets/Images/Chaos%20Relics%20-%20Starter%20Kit%20Plus.png)

![Items Showcase](Assets/Images/starterkit-items-showcase.jpg)

## Notes
If you maintain forks, please keep bundle balance and localization keys (`starterKit`, `StarterKitDesc`) consistent to avoid UI text issues.
