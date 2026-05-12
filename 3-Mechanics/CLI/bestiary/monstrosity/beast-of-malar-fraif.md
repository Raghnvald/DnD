---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fraif
- ttrpg-cli/monster/cr/11
- ttrpg-cli/monster/environment/coastal
- ttrpg-cli/monster/environment/forest
- ttrpg-cli/monster/environment/hill
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/monstrosity
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Beast of Malar"
---
# [Beast of Malar](3-Mechanics/CLI/bestiary/monstrosity/beast-of-malar-fraif.md)
*Source: Forgotten Realms: Adventures in Faerûn p. 251*  

## Beast of Malar

*Ferocious, Shape-Changing Predator*

Malar, god of the bestial hunt, sometimes manifests a spark of primal predation in physical form: the beast of Malar. The beast of Malar can take three types of forms—a land form, a sea form, and a sky form—to pursue prey across land, seas, and skies. In each form, its short fur is glossy black with red fur around its jaws and claws as though stained by the blood it has spilled.

The beast of Malar has a muscular and unnatural appearance no matter its form; whether it resembles a bat, wolverine, or shark, there's no mistaking the beast of Malar for a mundane animal. The beast shifts easily between its forms to pursue its prey, using whichever shape suits it best to catch and kill its quarry.

Normally only one beast of Malar exists at a time. However, Malar might create multiple beasts to pursue legendary prey or simply display his extraordinary ferocity.

```statblock
"name": "Beast of Malar (FRAiF)"
"size": "Medium"
"type": "monstrosity"
"alignment": "Chaotic Evil"
"ac": !!int "17"
"hp": !!int "168"
"hit_dice": "16d8 + 96"
"modifier": !!int "7"
"stats":
  - !!int "21"
  - !!int "16"
  - !!int "23"
  - !!int "10"
  - !!int "14"
  - !!int "12"
"speed": "50 ft., burrow 40 ft. (land form only), fly 60 ft. (sky form only), swim\
  \ 40 ft. (sea form only)"
"saves":
  - "strength": !!int "9"
"skillsaves":
  - "name": "Perception"
    "desc": "+10"
  - "name": "Stealth"
    "desc": "+7"
"condition_immunities": "charmed, frightened"
"senses": "Darkvision 60 ft., passive Perception 20"
"languages": "understands Common but can't speak"
"cr": "11"
"traits":
  - "desc": "The beast breathes air and water."
    "name": "Amphibious (Sea Form Only)"
  - "desc": "If the beast dies, its body dissolves into black goo, and it gains a\
      \ new body after 1d10 days, reviving with all its <span title=\"Player's Handbook\
      \ (2024)\">Hit Points</span> in a place of Malar's choosing."
    "name": "Divine Immortality"
  - "desc": "If the beast fails a saving throw, it can choose to succeed instead."
    "name": "Legendary Resistance (3/Day)"
  - "desc": "The beast has <span title=\"Player's Handbook (2024)\">Advantage</span>\
      \ on saving throws against spells and other magical effects."
    "name": "Magic Resistance"
  - "desc": "The beast regains 20 <span title=\"Player's Handbook (2024)\">Hit Points</span>\
      \ at the start of its turn. If the beast takes Radiant damage or damage from\
      \ a <span title=\"Player's Handbook (2024)\">Critical Hit</span>, this trait\
      \ doesn't function at the start of the beast's next turn. The beast dies only\
      \ if it starts its turn with 0 <span title=\"Player's Handbook (2024)\">Hit\
      \ Points</span> and doesn't regenerate."
    "name": "Regeneration"
"actions":
  - "desc": "The beast makes three attacks, using Bite or Claws in any combination."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +9, reach 5 ft. *Hit:* 23 (4d8 + 5) Piercing\
      \ damage."
    "name": "Bite"
  - "desc": "*Melee Attack Roll:* +9, reach 5 ft. *Hit:* 18 (3d8 + 5) Slashing\
      \ damage. If the target is Large or smaller, it has the Prone condition."
    "name": "Claws (Land or Sky Form Only)"
"bonus_actions":
  - "desc": "The beast shape-shifts into its land form, sea form, or sky form and\
      \ regains 9 (2d8) <span title=\"Player's Handbook (2024)\">Hit Points</span>.\
      \ Its game statistics are the same in each form, except where noted. Any equipment\
      \ it is wearing or carrying isn't transformed."
    "name": "Recuperative Shape-Shift"
"source":
  - "FRAiF"
"image": "3-Mechanics/CLI/bestiary/monstrosity/token/beast-of-malar-fraif.webp"
```
^statblock

## Environment

coastal, forest, hill