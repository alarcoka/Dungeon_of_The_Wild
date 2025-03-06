# Mechanics Overview

## Movement & Physics
- **Gravity & Acceleration**: Applied to all entities, affecting movement and jumps.
- **Collision System**: Handles interactions between the player, enemies, and environment.
- **Camera System**:
  - Primary camera follows the player dynamically.
  - Minimap provides an overview of enemy positions.

## Combat System
- **Melee & Ranged Combat**:
  - Weapons include sword (melee), arrows (ranged), and beam (powerful ranged attack).
  - Certain weapons require ammunition (arrows).
- **Enemy AI Mechanics**:
  - Pathfinding system using vector fields.
  - Aggro system where NPCs react based on line-of-sight detection.
- **Damage & Health System**:
  - All entities have health points (HP) and take damage accordingly.
  - Invincibility frames are applied after taking damage.
  - Enemy HP is displayed on screen.

## Game World
- **Level Design**:
  - Overworld map with progressive unlocking.
  - Individual levels with increasing difficulty and complexity.
- **Raycasting for Visibility**:
  - Used for lighting effects in dark areas.
  - Determines enemy aggro behavior.
- **Parallax Backgrounds**:
  - Multiple layers to create depth perception in various environments.
- **Shaders & Special Effects**:
  - Burn effect (for fire-based damage)
  - Dizzy effect (for status condition)
  - SuperSayian (cheat mode visual effect)
  - Ray-traced shadows for enhanced visuals.

## UI & User Interaction
- **Heads-Up Display (HUD)**:
  - Displays player health, weapon status, inventory, and status effects.
  - Shows remaining enemies on the map.
- **Options Menu**:
  - Adjust music and sound effects.
  - Set difficulty levels (Easy, Normal, Hard).
  - (Planned) Key rebinding functionality.

For insights into the development process and implementation details, refer to [Development Insights](development.md).

