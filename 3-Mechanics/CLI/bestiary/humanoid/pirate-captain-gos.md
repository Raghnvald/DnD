---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/gos
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/any-race
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Pirate Captain"
---
# [Pirate Captain](3-Mechanics/CLI/bestiary/humanoid/pirate-captain-gos.md)
*Source: Ghosts of Saltmarsh p. 247*  

Pirate captains spend their lives at sea, earning and keeping command through blood and daring. A captain's impressive sword work and biting words inspire both confidence and fear in a ship's crew. Sigurd "Snake Eyes" is the pirate captain who leads a gang of smugglers in The Sinister Secret of Saltmarsh.

```statblock
"name": "Pirate Captain (GoS)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Any alignment"
"ac": !!int "14"
"ac_class": "studded leather"
"hp": !!int "45"
"hit_dice": "7d8 + 14"
"modifier": !!int "2"
"stats":
  - !!int "16"
  - !!int "14"
  - !!int "14"
  - !!int "11"
  - !!int "10"
  - !!int "14"
"speed": "30 ft."
"skillsaves":
  - "name": "Athletics"
    "desc": "+5"
  - "name": "Intimidation"
    "desc": "+4"
"gear":
  - "hand crossbow"
  - "longsword"
"senses": "passive Perception 10"
"languages": "any one language (usually Common)"
"cr": "2"
"traits":
  - "desc": "The captain adds its Charisma modifier to the damage roll for its longsword\
      \ attacks (included in the attack)."
    "name": "Flourish"
  - "desc": "The captain has advantage on ability checks and saving throws to resist\
      \ being knocked prone."
    "name": "Sea Legs"
"actions":
  - "desc": "The captain makes two attacks: one with its hand crossbow and one with\
      \ its longsword."
    "name": "Multiattack"
  - "desc": "*Ranged Weapon Attack:* +4 to hit, range 30/120 ft., one target. *Hit:*\
      \ 5 (1d6 + 2) piercing damage."
    "name": "Hand Crossbow"
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one target. *Hit:* 9\
      \ (1d8 + 5) slashing damage, or 10 (1d10 + 5) slashing damage if used with\
      \ two hands."
    "name": "Longsword"
"reactions":
  - "desc": "Whenever a friendly creature within 30 feet of the captain that can hear\
      \ it misses with an attack, the captain can yell perilous threats to allow that\
      \ creature to reroll the attack roll."
    "name": "Shape Up, Ye Dog (2/Day)"
"source":
  - "GoS"
"image": "3-Mechanics/CLI/bestiary/humanoid/token/pirate-captain-gos.webp"
```
^statblock