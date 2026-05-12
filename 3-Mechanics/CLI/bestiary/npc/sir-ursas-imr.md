---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/imr
- ttrpg-cli/monster/cr/5
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/human
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Sir Ursas"
---
# [Sir Ursas](3-Mechanics/CLI/bestiary/npc/sir-ursas-imr.md)
*Source: Infernal Machine Rebuild p. 56*  

> [!note] Out on Loan
> 
> The powerful relics possessed by Lynx Creatlach and Sir Ursas (see the "Special Equipment" section of their stat blocks) have been granted to them by their diabolical masters, and are not meant to be claimed as treasure. If either agent is killed in the course of the adventure, their special equipment vanishes, returning to Bel or Zariel.
^out-on-loan

```statblock
"name": "Sir Ursas (IMR)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Lawful Evil"
"ac": !!int "20"
"ac_class": "[plate armor](3-Mechanics/CLI/items/plate-armor.md), [shield](3-Mechanics/CLI/items/shield.md)"
"hp": !!int "112"
"hit_dice": "15d8 + 45"
"modifier": !!int "2"
"stats":
  - !!int "18"
  - !!int "15"
  - !!int "16"
  - !!int "10"
  - !!int "12"
  - !!int "15"
"speed": "30 ft."
"saves":
  - "strength": !!int "7"
  - "dexterity": !!int "5"
  - "constitution": !!int "6"
"skillsaves":
  - "name": "[Athletics](3-Mechanics/CLI/rules/skills.md#Athletics)"
    "desc": "+10"
  - "name": "[Intimidation](3-Mechanics/CLI/rules/skills.md#Intimidation)"
    "desc": "+5"
"damage_resistances": "fire"
"gear":
  - "[spear](3-Mechanics/CLI/items/spear.md)"
"senses": "passive Perception 11"
"languages": "Common, Infernal"
"cr": "5"
"traits":
  - "desc": "Sir Ursas wears a ring of mind shielding and plate armor of fire resistance."
    "name": "Special Equipment"
  - "desc": "Sir Ursas has advantage on saving throws against being [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened)."
    "name": "Brave"
  - "desc": "A melee weapon deals one extra die of its damage when Sir Ursas hits\
      \ with it (included in his attack)."
    "name": "Brute"
"actions":
  - "desc": "Sir Ursas makes three melee attacks or two ranged attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +7 to hit, reach 5 ft., one target. *Hit:* 11\
      \ (2d6 + 4) slashing damage."
    "name": "Claw"
  - "desc": "*Melee  or Ranged Weapon Attack:* +7 to hit, reach 5 ft. and range\
      \ 20/60 ft., one target. *Hit:* 11 (2d6 + 4) piercing damage, or 13 (2d8\
      \ + 4) piercing damage if used with two hands to make a melee attack."
    "name": "Spear"
  - "desc": "*Melee Weapon Attack:* +7 to hit, reach 5 ft., one target. *Hit:* 9\
      \ (2d4 + 4) bludgeoning damage, and if the target is a Medium or smaller creature,\
      \ it must succeed on a DC 15 Strength saving throw or be knocked [prone](3-Mechanics/CLI/rules/conditions.md#Prone)."
    "name": "Shield Bash"
"reactions":
  - "desc": "Sir Ursas adds 3 to his AC against one melee attack that would hit him.\
      \ To do so, he must see the attacker and be wielding a melee weapon."
    "name": "Parry"
"source":
  - "IMR"
"image": "3-Mechanics/CLI/bestiary/npc/token/sir-ursas-imr.webp"
```
^statblock