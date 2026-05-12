---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fraif
- ttrpg-cli/monster/cr/16
- ttrpg-cli/monster/environment/underdark
- ttrpg-cli/monster/environment/urban
- ttrpg-cli/monster/size/small-or-medium
- ttrpg-cli/monster/type/humanoid
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Dead Three Scion"
---
# [Dead Three Scion](3-Mechanics/CLI/bestiary/humanoid/dead-three-scion-fraif.md)
*Source: Forgotten Realms: Adventures in Faerûn p. 256*  

## Dead Three Scion

*Inheritor of a Malevolent Deific Triumvirate*

Some wicked mortals have bound their souls to Bane, Bhaal, and Myrkul and gained a portion of malevolent divine power from each. A scion of the Dead Three might have seized this power in a sinister ritual or had it thrust on them by an evil Artifact or a god's malevolent will. In any case, they possess cruelty, bloodlust, and necromantic power in equal measure and serve the Dead Three with their soul.

A Dead Three scion leads cults to Bane, Bhaal, or Myrkul—and often to all three. Sometimes the scion commands a single cult with an uneasy mix of adherents of each god, but a scion might lead separate cults from the shadows, playing them against each other and coordinating their efforts to bring the greatest amount of misery to a region.

```statblock
"name": "Dead Three Scion (FRAiF)"
"size": "Small or Medium"
"type": "humanoid"
"alignment": "Neutral Evil"
"ac": !!int "17"
"hp": !!int "221"
"hit_dice": "26d8 + 104"
"modifier": !!int "7"
"stats":
  - !!int "20"
  - !!int "14"
  - !!int "19"
  - !!int "18"
  - !!int "21"
  - !!int "24"
"speed": "30 ft."
"saves":
  - "constitution": !!int "9"
  - "wisdom": !!int "10"
"skillsaves":
  - "name": "Arcana"
    "desc": "+9"
  - "name": "Intimidation"
    "desc": "+12"
  - "name": "Stealth"
    "desc": "+7"
"damage_immunities": "necrotic"
"condition_immunities": "charmed, frightened"
"senses": "Truesight 120 ft., passive Perception 15"
"languages": "Common"
"cr": "16"
"traits":
  - "desc": "*Constitution Saving Throw:* DC 20, each Bloodied creature in a 30-foot\
      \ <span title=\"Player's Handbook (2024)\">Emanation</span> originating from\
      \ the scion at the end of the scion's turn. *Failure:* The target can't regain\
      \ <span title=\"Player's Handbook (2024)\">Hit Points</span> until the start\
      \ of the scion's next turn."
    "name": "Culling Aura"
  - "desc": "If the scion fails a saving throw, it can choose to succeed instead."
    "name": "Legendary Resistance (3/Day)"
  - "desc": "The scion has <span title=\"Player's Handbook (2024)\">Advantage</span>\
      \ on saving throws against spells and other magical effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "The scion makes two attacks, using Death Touch or Mindwrack Bolt in any\
      \ combination."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +12, reach 5 ft. *Hit:* 25 (4d8 + 7) Necrotic\
      \ damage."
    "name": "Death Touch"
  - "desc": "*Ranged Attack Roll:* +12, range 120 ft. *Hit:* 21 (6d6) Psychic\
      \ damage and the target has the Poisoned condition until the start of the scion's\
      \ next turn."
    "name": "Mindwrack Bolt"
  - "desc": "The scion casts one of the following spells, requiring no Material components\
      \ and using Charisma as the spellcasting ability (spell save DC 20):\n\n**At\
      \ will:** Detect Thoughts, Dispel Magic\n\n**2/day each:** Dimension Door, Invisibility,\
      \ Scrying\n\n**1/day each:** Circle of Death, Create Undead"
    "name": "Spellcasting"
"legendary_description": "Legendary Action Uses: 3. Immediately after another creature's\
  \ turn, the dead three scion can expend a use to take one of the following actions.\
  \ The dead three scion regains all expended uses at the start of each of its turns."
"legendary_actions":
  - "desc": "The scion makes a Death Touch or Mindwrack Bolt attack."
    "name": "Attack"
  - "desc": "The scion casts Command (level 2 version), using the same spellcasting\
      \ ability as Spellcasting. The scion can't take this action again until the\
      \ start of its next turn.\n"
    "name": "Command"
"source":
  - "FRAiF"
"image": "3-Mechanics/CLI/bestiary/humanoid/token/dead-three-scion-fraif.webp"
```
^statblock

## Environment

underdark, urban