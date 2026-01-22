---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Turlang
tags:
  - Monster/Größe/Riesig
  - Monster/HG/9
  - Monster/Typ/Pflanze
  - Quelle/5e/skt
aliases:
  - Turlang
linter-yaml-title-alias: Turlang
---
# [Turlang](3-Mechanics\CLI\bestiary\npc/turlang-skt.md)
*Source: Storm King's Thunder p. 107*  

```statblock
"name": "Turlang (SKT)"
"size": "Huge"
"type": "plant"
"alignment": "Chaotic Good"
"ac": !!int "16"
"ac_class": "natural armor"
"hp": !!int "200"
"hit_dice": "12d12 + 60"
"modifier": !!int "-1"
"stats":
  - !!int "23"
  - !!int "8"
  - !!int "21"
  - !!int "12"
  - !!int "16"
  - !!int "12"
"speed": "30 ft."
"damage_vulnerabilities": "fire"
"damage_resistances": "bludgeoning, piercing"
"senses": "passive Perception 13"
"languages": "Common, Druidic, Elvish, Sylvan"
"cr": "9"
"traits":
  - "desc": "While Turlang remains motionless, it is indistinguishable from a normal\
      \ tree."
    "name": "False Appearance"
  - "desc": "The treant deals double damage to objects and structures."
    "name": "Siege Monster"
"actions":
  - "desc": "The treant makes two slam attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +10 to hit, reach 5 ft., one target. *Hit:* 16\
      \ (3d6 + 6) bludgeoning damage."
    "name": "Slam"
  - "desc": "*Ranged Weapon Attack:* +10 to hit, range 60/180 ft., one target. *Hit:*\
      \ 28 (4d10 + 6) bludgeoning damage."
    "name": "Rock"
  - "desc": "The treant magically animates one or two trees it can see within 60 feet\
      \ of it. These trees have the same statistics as a [treant](/3-Mechanics/CLI/bestiary/plant/treant.md),\
      \ except they have Intelligence and Charisma scores of 1, they can't speak,\
      \ and they have only the Slam action option. An animated tree acts as an ally\
      \ of Turlang. The tree remains animate for 1 day or until it dies; until Turlang\
      \ dies or is more than 120 feet from the tree; or until Turlang takes a bonus\
      \ action to turn it back into an inanimate tree. The tree then takes root if\
      \ possible."
    "name": "Animate Trees (1/Day)"
  - "desc": "Turlang casts one of the following spells, requiring no material spell\
      \ components and using Wisdom as the spellcasting ability (spell save DC 15):\n\
      \n**At will:** druidcraft, guidance, resistance, speak with plants\n\n**2/day\
      \ each:** animal messenger, detect magic, entangle, goodberry, gust of wind,\
      \ pass without trace, speak with animals\n\n**1/day each:** commune with nature\
      \ (cast as 1 action), conjure woodland beings, hallucinatory terrain (cast as\
      \ 1 action)"
    "name": "Spellcasting"
"source":
  - "SKT"
"image": "/3-Mechanics/CLI/bestiary/npc/token/turlang-skt.webp"
```
^statblock