# Gameplay Guide

## Overview
Dungeon of the Wild is an action-adventure RPG that combines strategic combat, exploration, and progression mechanics. Players navigate through custom-built maps, battle AI-driven enemies, and acquire weapons and items to enhance their journey.

## Game Progression
- Players start in an overworld map, selecting levels based on unlocked progress.
- Completing levels unlocks new areas and challenges.
- Game progress is saved to a file, allowing players to continue from their last checkpoint.

## Controls
| Action           | Keybinding |
|----------------|------------|
| Move Up        | `W` |
| Move Down      | `S` |
| Move Left      | `A` |
| Move Right     | `D` |
| Attack         | `Space` |
| Dash           | `E` |
| Sword Attack   | `1` |
| Arrow Attack   | `2` |
| Beam Attack    | `3` |
| Pause          | `P` |
| Quit           | `Escape` |
| Inventory      | `I` |
| Teleport       | `Q` |
| Save           | `Backspace` |
| Toggle Collision | `C` |
| Toggle Follow | `Y` |
| Toggle Grid    | `G` |
| Toggle Texture | `T` |

## Combat System
- **Dash Ability**: Provides temporary invincibility and consumes stamina.
- **Rewind Mechanic**: Allows a one-time checkpoint-based rewind.
- **Weapons**:
  - Sword (Melee attack, high damage)
  - Arrows (Ranged attack, requires arrows as ammunition)
  - Beam (Powerful ranged attack)
- **Enemies & AI**:
  - **Dragon**: Shoots fireballs when the player enters its line of sight.
  - **Samurai**: Uses pathfinding to locate and attack the player.
  - **Slime**: Multiplies if left alone for too long.
  - **Bomb Enemy**: Approaches the player and explodes on proximity.

## Status Effects
- **Burn**: Inflicted by fireballs, reduces HP over time.
- **Slow Down**: Inflicted by slimes, reduces movement speed.
- **Dizzy**: Inflicted by samurais, temporarily inverts controls.

## Environmental Interactions
- **Moving Platforms**: Timed movement challenges.
- **Limited Visibility Areas**: Dark caves with raycasting-based lighting.
- **Parallax Backgrounds**: Enhances the visual experience.

For additional information on technical mechanics, refer to the [Mechanics Overview](mechanics.md).

