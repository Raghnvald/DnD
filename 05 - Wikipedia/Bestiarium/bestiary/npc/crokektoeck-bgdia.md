---
cssclasses:
  - json5e-monster
tags:
  - Quelle/5e/bgdia
  - Monster/cr/14
  - Monster/Größe/Gigantisch
  - Monster/Typ/Unhold/demon
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Crokek'toeck
---
# [Crokek'toeck](3-Mechanics\CLI\bestiary\npc/crokektoeck-bgdia.md)
*Source: Baldur's Gate: Descent Into Avernus p. 231*  

Crokek'toeck is Yeenoghu's demonic pet. Resembling a giant mudskipper with the teeth, fur, ears, and laugh of a hyena, this unique demon can hold smaller demons in its gullet and disgorge them anywhere Yeenoghu wishes. Immune to the mind-shattering effects of the River Styx, Crokek'toeck is often used to transport smaller demons (and sometimes Yeenoghu himself) through the Styx's terrible waters.

```statblock
"name": "Crokek'toeck (BGDIA)"
"size": "Gargantuan"
"type": "fiend"
"subtype": "demon"
"alignment": "Chaotic Evil"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "297"
"hit_dice": "17d20 + 119"
"modifier": !!int "0"
"stats":
  - !!int "28"
  - !!int "10"
  - !!int "24"
  - !!int "6"
  - !!int "10"
  - !!int "13"
"speed": "60 ft., swim 60 ft."
"saves":
  - "constitution": !!int "12"
  - "wisdom": !!int "5"
"damage_resistances": "cold; fire; lightning; bludgeoning, piercing, slashing from\
  \ nonmagical attacks"
"damage_immunities": "poison"
"condition_immunities": "[charmed](/3-Mechanics/CLI/conditions.md#Charmed), [frightened](/3-Mechanics/CLI/conditions.md#Frightened),\
  \ [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)"
"senses": "[darkvision](/3-Mechanics/CLI/senses.md#Darkvision) 120 ft., passive Perception\
  \ 10"
"languages": "understands Abyssal but can't speak"
"cr": "14"
"traits":
  - "desc": "Crokek'toeck can breathe air and water."
    "name": "Amphibious"
  - "desc": "Crokek'toeck has advantage on saving throws against spells and other\
      \ magical effects."
    "name": "Magic Resistance"
  - "desc": "Crokek'toeck's weapon attacks are magical."
    "name": "Magic Weapons"
  - "desc": "Crokek'toeck is immune to the waters of the River Styx as well as any\
      \ effect that would steal or modify its memories or detect or read its thoughts."
    "name": "Secure Memory"
  - "desc": "Crokek'toeck's long jump is up to 60 feet and its high jump is up to\
      \ 30 feet, with or without a running start."
    "name": "Standing Leap"
"actions":
  - "desc": "*Melee Weapon Attack:* +14 to hit, reach 15 ft., one target. *Hit:* 44\
      \ (10d6 + 9) piercing damage."
    "name": "Bite"
  - "desc": "Crokek'toeck opens its mouth and disgorges 1d4 [barlguras](/3-Mechanics/CLI/bestiary/fiend/barlgura-xmm.md),\
      \ 3d6 [gnolls](/3-Mechanics/CLI/bestiary/fiend/gnoll-warrior-xmm.md) led by\
      \ 1 [gnoll fang of Yeenoghu](/3-Mechanics/CLI/bestiary/fiend/gnoll-fang-of-yeenoghu-xmm.md),\
      \ 6d6 [dretches](/3-Mechanics/CLI/bestiary/fiend/dretch-xmm.md), or 1d3 [vrocks](/3-Mechanics/CLI/bestiary/fiend/vrock-xmm.md).\
      \ Each creature it disgorges appears in an unoccupied space within 30 feet of\
      \ Crokek'toeck's mouth, or the next closest unoccupied space."
    "name": "Disgorge Allies (Recharge 6)"
"source":
  - "BGDIA"
"image": "/3-Mechanics/CLI/bestiary/npc/token/crokektoeck-bgdia.webp"
```
^statblock