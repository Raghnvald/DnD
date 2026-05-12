---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/bam
- ttrpg-cli/monster/cr/1-4
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/ooze
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Plasmoid Explorer"
---
# [Plasmoid Explorer](3-Mechanics/CLI/bestiary/ooze/plasmoid-explorer-bam.md)
*Source: Boo's Astral Menagerie p. 43*  

Wanderlust compels some plasmoids to explore the Astral Plane and visit different worlds of the Material Plane. Such an explorer usually travels light, keeping its possessions in a backpack or similar container.

```statblock
"name": "Plasmoid Explorer (BAM)"
"size": "Medium"
"type": "ooze"
"alignment": "Any alignment"
"ac": !!int "11"
"hp": !!int "16"
"hit_dice": "3d8 + 3"
"modifier": !!int "1"
"stats":
  - !!int "13"
  - !!int "12"
  - !!int "12"
  - !!int "10"
  - !!int "14"
  - !!int "10"
"speed": "30 ft."
"skillsaves":
  - "name": "Perception"
    "desc": "+4"
  - "name": "Survival"
    "desc": "+4"
"damage_resistances": "acid, poison"
"gear":
  - "javelin"
"senses": "darkvision 60 ft., passive Perception 14"
"languages": "Common"
"cr": "1/4"
"traits":
  - "desc": "The plasmoid can squeeze through a space as narrow as 1 inch wide, provided\
      \ it is wearing and carrying nothing. It has advantage on ability checks it\
      \ makes to initiate or escape a grapple."
    "name": "Amorphous"
  - "desc": "The plasmoid can hold its breath for 1 hour."
    "name": "Hold Breath"
"actions":
  - "desc": "The plasmoid makes two Pseudopod attacks. It can replace one of those\
      \ attacks with a Javelin attack."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +3 to hit, reach 5 ft., one target. *Hit:* 3\
      \ (1d4 + 1) bludgeoning damage."
    "name": "Pseudopod"
  - "desc": "*Melee  or Ranged Weapon Attack:* +3 to hit, reach 5 ft. or range 30/120\
      \ ft., one target. *Hit:* 4 (1d6 + 1) piercing damage."
    "name": "Javelin"
"source":
  - "BAM"
"image": "3-Mechanics/CLI/bestiary/ooze/token/plasmoid-explorer-bam.webp"
```
^statblock