---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/aitfr-isf
- ttrpg-cli/monster/cr/11
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/elemental
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Exul"
---
# [Exul](3-Mechanics/CLI/bestiary/npc/exul-aitfr-isf.md)
*Source: Adventures in the Forgotten Realms: In Scarlet Flames p. 12*  

With his skin aglow like searing coal, a beard like sheafs of burnt paper, and hair billowing like smoke, Exul's physical form does nothing to hide his elemental nature. He was born as a spirit of earth and flame. This physical manifestation is a dalliance of mere decades, he hopes.

Exul serves Tyreus not out of loyalty, but due to a geas. Exul bears Tyreus only a little ill will, however, as occasional "arrangements" with mortal wizards are no great hassle. Exul resents and avoids the pain of the geas, ideally, but has no intention of dying for Tyreus's petty, mortal ambitions.

```statblock
"name": "Exul (AitFR-ISF)"
"size": "Large"
"type": "elemental"
"alignment": "Neutral Evil"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "200"
"hit_dice": "16d10 + 112"
"modifier": !!int "1"
"stats":
  - !!int "22"
  - !!int "12"
  - !!int "24"
  - !!int "16"
  - !!int "15"
  - !!int "16"
"speed": "40 ft., fly 60 ft."
"saves":
  - "intelligence": !!int "7"
  - "charisma": !!int "7"
"damage_immunities": "fire"
"gear":
  - "handaxe"
"senses": "darkvision 120 ft., passive Perception 12"
"languages": "Common, Ignan, Terran"
"cr": "11"
"traits":
  - "desc": "Exul's innate spellcasting ability is Charisma (spell save DC 15, +7\
      \ to hit with spell attacks). He can innately cast the following spells, requiring\
      \ no material components:\n\n**At will:** detect magic\n\n**3/day each:** comprehend\
      \ languages, tongues\n\n**1/day each:** conjure elemental (earth or fire elemental\
      \ only), invisibility, major image, plane shift, wall of fire"
    "name": "Innate Spellcasting"
  - "desc": "If Exul dies, his body disintegrates in a flash of fire and puff of smoke,\
      \ leaving behind only the equipment he was wearing or carrying."
    "name": "Elemental Demise"
"actions":
  - "desc": "Exul makes two handaxe attacks or uses his Hurl Flame twice."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +10 to hit, reach 5 ft., one target. *Hit:*\
      \ 13 (2d6 + 6) slashing damage plus 3 (1d6) fire damage."
    "name": "Handaxe"
  - "desc": "*Ranged Spell Attack:* +7 to hit, range 120 ft., one target. *Hit:*\
      \ 17 (5d6) fire damage."
    "name": "Hurl Flame"
"source":
  - "AitFR-ISF"
"image": "3-Mechanics/CLI/bestiary/npc/token/exul-aitfr-isf.webp"
```
^statblock