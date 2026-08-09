# `ui_script.rpak`

### Decompiled Apex Legends UI Script Archive

This repository contains a collection of **decompiled and extracted scripts from `ui_script.rpak`**, the RPAK package used by *Apex Legends*.

The goal of this project is to provide a readable, searchable reference of the game's UI scripting and supporting systems for **research, education, modding research, and understanding Respawn's game technology**.

>  **This is a reverse-engineering archive, not an official Respawn Entertainment project.**

---

## What's in it?

The repository contains recovered `.nut.ui` scripts organized roughly according to their original package structure.

Some of the major directories include:

| Directory          | Description                             |
| ------------------ | --------------------------------------- |
| `abilities/`       | Ability-related UI and scripting        |
| `ai/`              | AI-related functionality                |
| `class/`           | Class and type definitions              |
| `client/`          | Client-side systems                     |
| `conversation/`    | Conversation-related systems            |
| `cups/`            | CUP/event-related functionality         |
| `dev/`             | Development and debugging functionality |
| `gamemodes/`       | Game-mode specific systems              |
| `inventory/`       | Inventory and item systems              |
| `lobby/`           | Lobby and matchmaking functionality     |
| `match_modifiers/` | Match modifier systems                  |
| `melee/`           | Melee-related functionality             |
| `mp/`              | Multiplayer systems                     |
| `npc/`             | NPC-related functionality               |
| `objectives/`      | Objective and objective-system scripts  |
| `pilot/`           | Pilot/player-related functionality      |
| `respawning/`      | Respawn systems                         |
| `rtk/`             | RTK-related UI functionality            |
| `startFlow/`       | Startup and initialization flow         |
| `ui/`              | Core UI functionality                   |
| `weapons/`         | Weapon-related UI and scripting         |

The repository also contains standalone utility and initialization scripts such as `_threads.nut.ui`, `init.nut.ui`, `feature_flags.gnut.ui`, and various perk, event, menu, and customization scripts.

---

##  What Can You Use This For?

This archive can be useful for:

* Studying how Apex structures its UI scripting
* Learning about Respawn's scripting conventions
* Researching `.nut` / Squirrel-based game scripting
* Understanding relationships between UI systems and gameplay systems
* Searching for references to specific UI elements, weapons, abilities, perks, or game modes
* Reverse-engineering research
* Modding research and experimentation
* Comparing implementations across different game systems

For example, searching the repository can help locate where particular systems are referenced without having to manually inspect the original RPAK.

---

## File Format

Most of the recovered scripts use the following naming convention:

```text
<original_filename>.nut.ui
```

For example:

```text
init.nut.ui
feature_flags.gnut.ui
perk_revive_expert.nut.ui
sh_character_abilities.gnut.ui
```

The `.ui` suffix is retained to distinguish the recovered files from ordinary standalone Squirrel source files.

---

## Important Notes

### Decompiled Code

The source contained here is **decompiled output**.

As a result:

* Formatting may differ from the original source.
* Variable and function names may not always be preserved perfectly.
* Comments from the original source may be missing.
* Decompiled control flow may not exactly represent the original implementation.
* Some files or dependencies may be incomplete.
* The recovered code should not necessarily be expected to compile as-is.

Think of this repository as a **research/reference archive**, rather than a clean recreation of Respawn's original source tree.

---

## About Apex

*Apex Legends* is developed by **Respawn Entertainment** and published by **Electronic Arts**.

This repository is **not affiliated with, endorsed by, or sponsored by Respawn Entertainment or Electronic Arts**.

All game names, trademarks, source material, and other intellectual property remain the property of their respective owners.

---

## Purpose

This project exists primarily for:

> **Education, research, interoperability, and preservation of publicly discussed game-engine and scripting knowledge.**

It is intended to make the recovered material easier for researchers and developers to inspect and understand.

Please respect the rights of the original developers and publishers when using material from this repository.
---

## Disclaimer

This repository contains material recovered through reverse-engineering and decompilation.

**No claim of ownership is made over the original game assets or source material.**

The repository is provided for educational and research purposes. Users are responsible for complying with applicable laws, licenses, and the terms governing any software or game they investigate.

---

This archive is maintained as part of **Goose Goose Interactive's** game research and reverse-engineering projects.

**Not affiliated with Respawn Entertainment or Electronic Arts.**
