---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/awm
- ttrpg-cli/monster/cr/1-8
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/merfolk
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Crystal Cave Merfolk"
---
# [Crystal Cave Merfolk](3-Mechanics/CLI/bestiary/humanoid/crystal-cave-merfolk-awm.md)
*Source: Adventure with Muk p. 31*  

The Crystal Cave merfolk have long, flowing fins and silvery scales. They have lovely, melodic voices that are enhanced by the vibrating crystals of the cave in which they dwell.

They love anything silver and are willing to trade pearls and bits of gold treasure that they have found on their hunts under the waters. They also have [magical potions](3-Mechanics/CLI/items/potion-of-water-breathing.md) that can help a surface dweller breathe underwater.

```statblock
"name": "Crystal Cave Merfolk (AWM)"
"size": "Medium"
"type": "humanoid"
"subtype": "merfolk"
"alignment": "Neutral"
"ac": !!int "11"
"hp": !!int "11"
"modifier": !!int "1"
"stats":
  - !!int "10"
  - !!int "13"
  - !!int "12"
  - !!int "11"
  - !!int "11"
  - !!int "12"
"speed": "10 ft., swim 40 ft."
"senses": "passive Perception 0"
"languages": ""
"cr": "1/8"
"traits":
  - "desc": "The merfolk can breathe air and water."
    "name": "Amphibious"
  - "desc": "Lovely singing voices charm every humanoid or giant within 300 feet.\
      \ The targets must succeed on a DC 11 Wisdom saving throw or be charmed until\
      \ the song ends."
    "name": "Siren Song"
"actions":
  - "desc": "*Melee Weapon Attack:* +2 to hit, one target. *Hit:* 3 (1d6) piercing\
      \ damage."
    "name": "Bite"
"source":
  - "AWM"
"image": "3-Mechanics/CLI/bestiary/humanoid/token/crystal-cave-merfolk-awm.webp"
```
^statblock