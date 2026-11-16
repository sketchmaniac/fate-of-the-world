# Fate of the New World

A personal game project. The initial focus is on developing the game's world and assets—such as races, classes, weapons, items, factions, and enemies—before building the game itself.

## Project structure

- `assets/` — structured game data
- `notes/` — worldbuilding and design notes

## Status

Early planning; game code has not started yet.

## Game Assets

The `assets` directory contains JSON data for the game's weapons and armor. Weapons are organized by weapon class and include base-damage ranges. All weapons can critically hit, dealing 50% more damage than the rolled base damage.

Armor is organized into Body Armor, Head Armor, Hands, Feet, Pants, and Shields. Each item has a defense range; shields are wielded to block rather than worn.

Items also have level and stat requirements. The first item in each class has no requirements. For each following item, the level and applicable stat requirements increase by 10. Armor and shields use Strength; weapon requirements vary by weapon class.
