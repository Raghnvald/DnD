---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/rot
- ttrpg-cli/monster/cr/5
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/any-race
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Half-Red Dragon Gladiator"
---
# [Half-Red Dragon Gladiator](3-Mechanics/CLI/bestiary/humanoid/half-red-dragon-gladiator-rot.md)
*Source: The Rise of Tiamat p. 56, Tyranny of Dragons p. 142*  

```statblock
"name": "Half-Red Dragon Gladiator (RoT)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Any alignment"
"ac": !!int "16"
"ac_class": "[studded leather](3-Mechanics/CLI/items/studded-leather-armor-xphb.md),\
  \ [shield](3-Mechanics/CLI/items/shield-xphb.md)"
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
  - "[spear](3-Mechanics/CLI/items/spear-xphb.md)"
"senses": "[blindsight](3-Mechanics/CLI/rules/senses.md#Blindsight) 10 ft., [darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision)\
  \ 60 ft., passive Perception 11"
"languages": "any one language (usually Common), Draconic"
"cr": "5"
"traits":
  - "desc": "The half-dragon has advantage on saving throws against being [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened)."
    "name": "Brave"
  - "desc": "A melee weapon deals one extra die of its damage when the half-dragon\
      \ hits with it (included in the attack)."
    "name": "Brute"
"actions":
  - "desc": "The half-dragon makes three melee attacks or two ranged attacks."
    "name": "Multiattack"
  - "desc": "*Melee  or Ranged Weapon Attack:* +7 to hit, reach 5 ft. and range\
      \ 20/60 ft., one target. *Hit:* 11 (2d6 + 4) piercing damage, or 13 (2d8\
      \ + 4) piercing damage if used with two hands to make a melee attack."
    "name": "Spear"
  - "desc": "*Melee Weapon Attack:* +7 to hit, reach 5 ft., one creature. *Hit:*\
      \ 9 (2d4 + 4) bludgeoning damage. If the target is a Medium or smaller creature,\
      \ it must succeed on a DC 15 Strength saving throw or be knocked [prone](3-Mechanics/CLI/rules/conditions.md#Prone)."
    "name": "Shield Bash"
  - "desc": "The half-dragon exhales fire in a 15-foot cone. Each creature in that\
      \ area must make a DC 13 Dexterity saving throw, taking 24 (7d6) fire damage\
      \ on a failed save, or half as much damage on a successful one."
    "name": "Fire Breath (Recharge 5-6)"
"reactions":
  - "desc": "The half-dragon adds 3 to its AC against one melee attack that would\
      \ hit it. To do so, the half-dragon must see the attacker and be wielding a\
      \ melee weapon."
    "name": "Parry"
"source":
  - "RoT"
  - "ToD"
"image": "3-Mechanics/CLI/bestiary/humanoid/token/half-red-dragon-gladiator-rot.webp"
```
^statblock