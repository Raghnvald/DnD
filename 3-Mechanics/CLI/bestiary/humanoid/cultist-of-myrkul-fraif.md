---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fraif
- ttrpg-cli/monster/cr/11
- ttrpg-cli/monster/environment/urban
- ttrpg-cli/monster/size/small-or-medium
- ttrpg-cli/monster/type/humanoid
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Cultist of Myrkul"
---
# [Cultist of Myrkul](3-Mechanics/CLI/bestiary/humanoid/cultist-of-myrkul-fraif.md)
*Source: Forgotten Realms: Adventures in Faerûn p. 255*  

Cultists of Myrkul dominate the dead, whether to raise Undead servants, terrorize the living, or extract secrets known only to the deceased. Most are more interested in amassing knowledge than power or wealth. Many cultists of Myrkul are sinister manipulators who hoard necromantic lore and gather in cults to share their gruesome secrets. Such secrets often require unsavory experimentation, which these heartless cultists relish.

## Cultists

*Wicked Zealots of the Dead Three*

The adventurers Bane, Bhaal, and Myrkul seized divinity but were slain for their hubris. All three have been reborn and are now known as the Dead Three. Each of the Dead Three has inspired wicked cults that follow their paths of tyranny, murder, and necromancy.

More than any other gods, the Dead Three directly influence Faerûn—and particularly the city of Baldur's Gate—in malign ways. Cultists who receive orders from their patron god directly are often the most ambitious and most dangerous.

```statblock
"name": "Cultist of Myrkul (FRAiF)"
"size": "Small or Medium"
"type": "humanoid"
"alignment": "Neutral Evil"
"ac": !!int "16"
"hp": !!int "204"
"hit_dice": "24d8 + 96"
"modifier": !!int "6"
"stats":
  - !!int "13"
  - !!int "14"
  - !!int "18"
  - !!int "20"
  - !!int "18"
  - !!int "15"
"speed": "30 ft."
"saves":
  - "constitution": !!int "8"
  - "intelligence": !!int "9"
  - "wisdom": !!int "8"
  - "charisma": !!int "6"
"skillsaves":
  - "name": "Arcana"
    "desc": "+9"
  - "name": "Insight"
    "desc": "+8"
  - "name": "Religion"
    "desc": "+9"
"damage_resistances": "necrotic"
"gear":
  - "breastplate"
  - "holy symbol"
"senses": "Darkvision 60 ft., passive Perception 14"
"languages": "Common"
"cr": "11"
"traits":
  - "desc": "While Bloodied, the cultist has <span title=\"Player's Handbook (2024)\"\
      >Immunity</span> to the Frightened and Poisoned conditions."
    "name": "Nearer to the Dead"
"actions":
  - "desc": "The cultist makes three Necrotic Burst attacks."
    "name": "Multiattack"
  - "desc": "*Melee  or Ranged Attack Roll:* +9, reach 5 ft. or range 120 ft. *Hit:*\
      \ 27 (5d10) Necrotic damage and the target can't regain <span title=\"Player's\
      \ Handbook (2024)\">Hit Points</span> until the end of the cultist's next turn."
    "name": "Necrotic Burst"
  - "desc": "The cultist casts one of the following spells, using Intelligence as\
      \ the spellcasting ability (spell save DC 17):\n\n**At will:** Speak with Dead,\
      \ Thaumaturgy\n\n**1/day each:** Animate Dead, Circle of Death"
    "name": "Spellcasting"
"source":
  - "FRAiF"
"image": "3-Mechanics/CLI/bestiary/humanoid/token/cultist-of-myrkul-fraif.webp"
```
^statblock

## Environment

urban