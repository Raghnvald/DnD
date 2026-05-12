---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fraif
- ttrpg-cli/monster/cr/4
- ttrpg-cli/monster/environment/any
- ttrpg-cli/monster/size/small-or-medium
- ttrpg-cli/monster/type/humanoid
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Zhentilar Paladin of Bane"
---
# [Zhentilar Paladin of Bane](3-Mechanics/CLI/bestiary/humanoid/zhentilar-paladin-of-bane-fraif.md)
*Source: Forgotten Realms: Adventures in Faerûn p. 285*  

The Zhentilar's most-respected commanders and sergeants tend to be spellswords or holy warriors who worship nefarious higher powers, such as Bane.

## Zhentilar

*Wardens of the Zhentarim*

The Zhentilar is the militant wing of the Zhentarim. Zhentilar forces occupy Zhentarim strongholds such as Zhentil Keep and Darkhold and defend these places from the Zhentarim's many enemies. If the Zhentarim is one big family, then the Zhentilar are the protective older siblings who look out for their kin.

Zhentilar also conduct other important organizational work such as safeguarding powerful magic items or escorting Zhentarim leaders.

```statblock
"name": "Zhentilar Paladin of Bane (FRAiF)"
"size": "Small or Medium"
"type": "humanoid"
"alignment": "Lawful Evil"
"ac": !!int "18"
"hp": !!int "58"
"hit_dice": "9d8 + 18"
"modifier": !!int "0"
"stats":
  - !!int "16"
  - !!int "11"
  - !!int "14"
  - !!int "12"
  - !!int "13"
  - !!int "17"
"speed": "30 ft."
"saves":
  - "strength": !!int "5"
  - "charisma": !!int "5"
"skillsaves":
  - "name": "Athletics"
    "desc": "+5"
  - "name": "Intimidation"
    "desc": "+5"
  - "name": "Religion"
    "desc": "+3"
"gear":
  - "plate armor"
"senses": "passive Perception 11"
"languages": "Common"
"cr": "4"
"traits":
  - "desc": "Creatures in a 10-foot <span title=\"Player's Handbook (2024)\">Emanation</span>\
      \ originating from the Zhentilar have their Speeds halved while in the <span\
      \ title=\"Player's Handbook (2024)\">Emanation</span>. The Zhentilar can designate\
      \ creatures to be unaffected by the aura."
    "name": "Aura of Dread"
"actions":
  - "desc": "The Zhentilar makes three attacks, using Dooming Blade or Oppressive\
      \ Ray in any combination. It can replace one attack with a use of Spellcasting."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +5, reach 5 ft. *Hit:* 7 (1d8 + 3) Bludgeoning\
      \ damage plus 7 (2d6) Necrotic damage."
    "name": "Dooming Blade"
  - "desc": "*Ranged Attack Roll:* +5, range 90 ft. *Hit:* 16 (3d10) Psychic damage."
    "name": "Oppressive Ray"
  - "desc": "The Zhentilar casts one of the following spells, using Charisma as the\
      \ spellcasting ability (spell save DC 13):\n\n**1/day each:** Command, Fear"
    "name": "Spellcasting"
"source":
  - "FRAiF"
"image": "3-Mechanics/CLI/bestiary/humanoid/token/zhentilar-paladin-of-bane-fraif.webp"
```
^statblock

## Environment

any