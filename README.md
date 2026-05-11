# Creature Quest: Heroes' Journey

A single-player RPG inspired by Pokémon and other creature-collecting games. Explore a pixel art world, battle wild creatures, catch them, train them, and take on NPC trainers in turn-based combat.

## Tech Stack

- **Language:** Python
- **Framework:** Pygame
- **Testing:** pytest

## Features

- Turn-based combat — attack, defend, heal, or catch wild creatures
- 7 unique abilities: Heal, Fireball, Scratch, Stab, Smack, Headbutt, Hellfire
- NPC encounters — trainers that initiate combat or dialogue on sight
- Quest system with creature battle and training objectives
- Pixel art graphics with sound effects and background music
- Auto-save system
- HUD displaying real-time player health and creature stats

## Controls

| Key | Action |
|-----|--------|
| `W A S D` | Move character |
| `E` | Interact with NPCs / objects |
| `Esc` | Pause / Menu |
| `Left Click` | Navigate menus |

## Getting Started

### Requirements

- Python 3.10
- Pygame

```bash
pip install pygame
```

### Run

```bash
git clone https://github.com/your-username/creature-quest.git
cd creature-quest
python main.py
```

## Project Structure

```
creature-quest/
├── assets/
│   ├── images/
│   ├── sounds/
│   └── music/
├── src/
│   ├── creatures/
│   ├── player/
│   ├── npc/
│   ├── combat/
│   ├── quests/
│   └── ui/
├── tests/
└── main.py
```

## OOP Concepts Used

- **Inheritance** — `Player` and `NPC` extend a shared `Character` base class; creature types inherit from a base `Creature` class
- **Encapsulation** — creature attributes (health, attack, abilities) are private and accessed through methods
- **Polymorphism** — `Ability` base class with specific implementations (e.g., `Fireball`, `Heal`) for flexible combat logic

## System Requirements

| | Minimum | Recommended |
|-|---------|-------------|
| OS | Windows 7/8/10 | Windows 10 |
| CPU | 1.8 GHz Dual-Core | 2.5 GHz Quad-Core |
| RAM | 4 GB | 8 GB |
| Storage | 500 MB | 1 GB |

## Team

| Name |
|------|
| John Gabriel M. Milka |
| Joshua Adrian M. Mortel |

> Object Oriented Programming Project — Columban College, Inc. | BSCS
