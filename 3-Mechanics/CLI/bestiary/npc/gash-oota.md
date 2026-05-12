---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/oota
- ttrpg-cli/monster/cr/1-2
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/gnoll
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Gash"
---
# [Gash](3-Mechanics/CLI/bestiary/npc/gash-oota.md)
*Source: Out of the Abyss p. 181*  

```statblock
"name": "Gash (OotA)"
"size": "Medium"
"type": "humanoid"
"subtype": "gnoll"
"alignment": "Chaotic Evil"
"ac": !!int "15"
"ac_class": "[hide armor](3-Mechanics/CLI/items/hide-armor.md), [shield](3-Mechanics/CLI/items/shield.md)"
"hp": !!int "11"
"hit_dice": "5d8"
"modifier": !!int "1"
"stats":
  - !!int "14"
  - !!int "12"
  - !!int "11"
  - !!int "6"
  - !!int "10"
  - !!int "7"
"speed": "25 ft."
"gear":
  - "[longbow](3-Mechanics/CLI/items/longbow.md)"
  - "[spear](3-Mechanics/CLI/items/spear.md)"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., passive\
  \ Perception 10"
"languages": "Gnoll, Abyssal"
"cr": "1/2"
"traits":
  - "desc": "When Gash reduces a creature to 0 hit points with a melee attack on its\
      \ turn, Gash can take a bonus action to move up to half its speed and make a\
      \ bite attack."
    "name": "Rampage"
  - "desc": "Gash has disadvantage on Wisdom checks and Wisdom saving throws because\
      \ of the physical and mental abuse he has suffered. A [lesser restoration](3-Mechanics/CLI/spells/lesser-restoration.md)\
      \ spell rids him of these effects."
    "name": "Wretched"
"actions":
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one creature. *Hit:*\
      \ 4 (1d4 + 2) piercing damage."
    "name": "Bite"
  - "desc": "*Melee  or Ranged Weapon Attack:* +4 to hit, reach 5 ft. or range 20/60\
      \ ft., one target. *Hit:* 5 (1d6 + 2) piercing damage, or 6 (1d8 + 2) piercing\
      \ damage if used with two hands to make a melee attack."
    "name": "Spear"
  - "desc": "*Ranged Weapon Attack:* +3 to hit, range 150/600 ft., one target. *Hit:*\
      \ 5 (1d8 + 1) piercing damage."
    "name": "Longbow"
"source":
  - "OotA"
"image": "3-Mechanics/CLI/bestiary/npc/token/gash-oota.webp"
```
^statblock