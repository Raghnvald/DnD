---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/oota
- ttrpg-cli/monster/cr/4
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/fiend/gnoll
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Kurr"
---
# [Kurr](3-Mechanics/CLI/bestiary/npc/kurr-oota.md)
*Source: Out of the Abyss p. 179*  

```statblock
"name": "Kurr (OotA)"
"size": "Medium"
"type": "fiend"
"subtype": "gnoll"
"alignment": "Chaotic Evil"
"ac": !!int "14"
"ac_class": "[hide armor](3-Mechanics/CLI/items/hide-armor.md)"
"hp": !!int "65"
"hit_dice": "10d8 + 20"
"modifier": !!int "2"
"stats":
  - !!int "17"
  - !!int "15"
  - !!int "15"
  - !!int "10"
  - !!int "11"
  - !!int "13"
"speed": "30 ft."
"saves":
  - "constitution": !!int "4"
  - "wisdom": !!int "2"
  - "charisma": !!int "3"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., passive\
  \ Perception 10"
"languages": "Abyssal, Gnoll"
"cr": "4"
"traits":
  - "desc": "When Kurr reduces a creature to 0 hit points with a melee attack on its\
      \ turn, Kurr can take a bonus action to move up to half its speed and make a\
      \ bite attack."
    "name": "Rampage"
"actions":
  - "desc": "Kurr makes three attacks: one with its bite and two with its claws."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one creature. *Hit:*\
      \ 6 (1d6 + 3) piercing damage, and the target must succeed on a DC 12 Constitution\
      \ saving throw or take 7 (2d6) poison damage."
    "name": "Bite"
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one target. *Hit:* 7\
      \ (1d8 + 3) slashing damage."
    "name": "Claw"
"source":
  - "OotA"
"image": "3-Mechanics/CLI/bestiary/npc/token/kurr-oota.webp"
```
^statblock