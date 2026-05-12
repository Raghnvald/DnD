---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/rot
- ttrpg-cli/monster/cr/11
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/undead
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Naergoth Bladelord"
---
# [Naergoth Bladelord](3-Mechanics/CLI/bestiary/npc/naergoth-bladelord-rot.md)
*Source: The Rise of Tiamat p. 90, Tyranny of Dragons p. 186*  

```statblock
"name": "Naergoth Bladelord (RoT)"
"size": "Medium"
"type": "undead"
"alignment": "Neutral Evil"
"ac": !!int "18"
"ac_class": "[plate armor](3-Mechanics/CLI/items/plate-armor-xphb.md)"
"hp": !!int "135"
"hit_dice": "18d8 + 54"
"modifier": !!int "1"
"stats":
  - !!int "20"
  - !!int "12"
  - !!int "16"
  - !!int "12"
  - !!int "14"
  - !!int "16"
"speed": "30 ft."
"saves":
  - "dexterity": !!int "5"
  - "wisdom": !!int "6"
"skillsaves":
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+6"
  - "name": "[Stealth](3-Mechanics/CLI/rules/skills.md#Stealth)"
    "desc": "+5"
"damage_resistances": "necrotic; bludgeoning, piercing, slashing from nonmagical attacks\
  \ that aren't silvered"
"damage_immunities": "poison"
"condition_immunities": "[exhaustion](3-Mechanics/CLI/rules/conditions.md#Exhaustion),\
  \ [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)"
"gear":
  - "[longbow](3-Mechanics/CLI/items/longbow-xphb.md)"
  - "[longsword](3-Mechanics/CLI/items/longsword-xphb.md)"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., passive\
  \ Perception 16"
"languages": "Common, Draconic"
"cr": "11"
"traits":
  - "desc": "While in sunlight, Naergoth has disadvantage on attack rolls, as well\
      \ as on Wisdom ([Perception](3-Mechanics/CLI/rules/skills.md#Perception)) checks\
      \ that rely on sight."
    "name": "Sunlight Sensitivity"
"actions":
  - "desc": "Naergoth makes three attacks, either with his longsword or longbow. He\
      \ can use Life Drain in place of one longsword attack."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +9 to hit, reach 5 ft., one target. *Hit:* 20\
      \ (5d6 + 3) necrotic damage. The target must succeed on a DC 15 Constitution\
      \ saving throw or its hit point maximum is reduced by an amount equal to the\
      \ damage taken. This reduction lasts until the target finishes a long rest.\
      \ The target dies if this effect reduces its hit point maximum to 0."
    "name": "Life Drain"
  - "desc": "*Melee Weapon Attack:* +9 to hit, reach 5 ft., one target. *Hit:* 9\
      \ (1d8 + 5) slashing damage, or 10 (1d10 + 5) if used with two hands, plus\
      \ 10 (3d6) necrotic damage."
    "name": "Longsword"
  - "desc": "*Ranged Weapon Attack:* +5 to hit, range 150/600 ft., one target. *Hit:*\
      \ 5 (1d8 + 1) piercing damage plus 10 (3d6) necrotic damage."
    "name": "Longbow"
"source":
  - "RoT"
  - "ToD"
"image": "3-Mechanics/CLI/bestiary/npc/token/naergoth-bladelord-rot.webp"
```
^statblock