---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/bam
- ttrpg-cli/monster/cr/1-4
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/beast
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Space Swine"
---
# [Space Swine](3-Mechanics/CLI/bestiary/beast/space-swine-bam.md)
*Source: Boo's Astral Menagerie p. 57*  

Space swine are a species of winged boar bred by dohwars for a variety of uses. They can serve as mounts for Small creatures, and they also make fine trackers and capable beasts of burden. Space swine that are trained for battle are typically outfitted with half-plate barding and are referred to as death squealers.

A fully grown specimen stands 3 feet high at the shoulder and is 5 to 6 feet long. Space swine eat just about anything, but they prefer truffles. A space swine also tastes delicious when roasted and served with applesauce.

```statblock
"name": "Space Swine (BAM)"
"size": "Medium"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "11"
"hp": !!int "22"
"hit_dice": "4d8 + 4"
"modifier": !!int "1"
"stats":
  - !!int "12"
  - !!int "12"
  - !!int "12"
  - !!int "4"
  - !!int "10"
  - !!int "3"
"speed": "40 ft., fly 40 ft."
"skillsaves":
  - "name": "Perception"
    "desc": "+4"
  - "name": "Survival"
    "desc": "+4"
"senses": "passive Perception 14"
"languages": ""
"cr": "1/4"
"actions":
  - "desc": "*Melee Weapon Attack:* +3 to hit, reach 5 ft., one target. *Hit:* 4\
      \ (1d6 + 1) piercing damage."
    "name": "Bite"
"source":
  - "BAM"
"image": "3-Mechanics/CLI/bestiary/beast/token/space-swine-bam.webp"
```
^statblock