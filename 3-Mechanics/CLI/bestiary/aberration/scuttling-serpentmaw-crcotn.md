---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/crcotn
- ttrpg-cli/monster/cr/4
- ttrpg-cli/monster/size/small
- ttrpg-cli/monster/type/aberration
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Scuttling Serpentmaw"
---
# [Scuttling Serpentmaw](3-Mechanics/CLI/bestiary/aberration/scuttling-serpentmaw-crcotn.md)
*Source: Critical Role: Call of the Netherdeep p. 208*  

A scuttling serpentmaw looks like an unusually large crab with a sleek black shell. It lurks in crevasses and deep underwater canyons. Once spotted, it scuttles toward its prey and reveals its most formidable feature: an armored maw concealed on the back of its shell. This serpentine appendage can extend out from the shell to tear into prey.

Though they inhabit water, serpentmaws can't swim. They move along the sea floor in small mobs, working together to tear apart much larger creatures they come across.

```statblock
"name": "Scuttling Serpentmaw (CRCotN)"
"size": "Small"
"type": "aberration"
"alignment": "Unaligned"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "65"
"hit_dice": "10d6 + 30"
"modifier": !!int "2"
"stats":
  - !!int "16"
  - !!int "14"
  - !!int "16"
  - !!int "3"
  - !!int "11"
  - !!int "3"
"speed": "30 ft."
"skillsaves":
  - "name": "Stealth"
    "desc": "+6"
"senses": "blindsight 60 ft. (blind beyond this radius), passive Perception 10"
"languages": ""
"cr": "4"
"traits":
  - "desc": "The serpentmaw can breathe air and water."
    "name": "Amphibious"
  - "desc": "The serpentmaw has advantage on an attack roll against a creature if\
      \ at least one of the serpentmaw's allies is within 5 feet of the creature and\
      \ the ally isn't incapacitated."
    "name": "Pack Tactics"
"actions":
  - "desc": "The serpentmaw makes one Bite attack and two Claw attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 15 ft., one target. *Hit:*\
      \ 10 (2d6 + 3) piercing damage, or 17 (4d6 + 3) piercing damage if the serpentmaw\
      \ had advantage on the attack roll."
    "name": "Bite"
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one target. *Hit:* 7\
      \ (1d8 + 3) slashing damage."
    "name": "Claw"
"source":
  - "CRCotN"
"image": "3-Mechanics/CLI/bestiary/aberration/token/scuttling-serpentmaw-crcotn.webp"
```
^statblock