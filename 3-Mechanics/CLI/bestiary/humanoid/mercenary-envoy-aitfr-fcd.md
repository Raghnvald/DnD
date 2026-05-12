---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/aitfr-fcd
- ttrpg-cli/monster/cr/1
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Mercenary Envoy"
---
# [Mercenary Envoy](3-Mechanics/CLI/bestiary/humanoid/mercenary-envoy-aitfr-fcd.md)
*Source: Adventures in the Forgotten Realms: From Cyan Depths p. 10*  

These mercenaries stand for the Banner of Blades and the Iron Lions at Tyreus's fortress, but they might not be representative of those armies. These are rank-and-file warriors capable of demonstrating coordinated attacks and formations. They are neither the most capable lieutenants nor the rough-and-tumble masses of these small armies.

For the purposes of their Inspired Courage feature, the mercenaries of both companies consider each other allies while at the fortress—unless the adventurers do something to drive them apart.

```statblock
"name": "Mercenary Envoy (AitFR-FCD)"
"size": "Medium"
"type": "humanoid"
"alignment": "Unaligned"
"ac": !!int "15"
"ac_class": "chain shirt"
"hp": !!int "26"
"hit_dice": "4d8 + 8"
"modifier": !!int "2"
"stats":
  - !!int "15"
  - !!int "15"
  - !!int "15"
  - !!int "10"
  - !!int "12"
  - !!int "9"
"speed": "30 ft."
"saves":
  - "strength": !!int "4"
  - "constitution": !!int "4"
"skillsaves":
  - "name": "Athletics"
    "desc": "+4"
  - "name": "Perception"
    "desc": "+3"
"gear":
  - "heavy crossbow"
  - "longsword"
"senses": "passive Perception 13"
"languages": "Common"
"cr": "1"
"traits":
  - "desc": "The mercenary has advantage on savings throws against being charmed,\
      \ frightened, grappled, or restrained while within 5 feet of at least one ally."
    "name": "Inspired Courage"
  - "desc": "Once per turn, the mercenary can deal an extra 7 (2d6) damage to a\
      \ creature it hits with a weapon attack if that creature is within 5 feet of\
      \ an ally of the mercenary that isn't incapacitated."
    "name": "Martial Advantage"
"actions":
  - "desc": "The mercenary makes two longsword attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one target. *Hit:* 6\
      \ (1d8 + 2) slashing damage."
    "name": "Longsword"
  - "desc": "*Ranged Weapon Attack:* +4 to hit, range\n\n100/400 ft., one target.\
      \ *Hit:* 7 (1d10 + 2) piercing damage."
    "name": "Heavy Crossbow"
"source":
  - "AitFR-FCD"
"image": "3-Mechanics/CLI/bestiary/humanoid/token/mercenary-envoy-aitfr-fcd.webp"
```
^statblock