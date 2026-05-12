---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mtf
- ttrpg-cli/monster/cr/10
- ttrpg-cli/monster/environment/desert
- ttrpg-cli/monster/environment/mountain
- ttrpg-cli/monster/environment/urban
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/gith
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Githyanki Gish"
---
# [Githyanki Gish](3-Mechanics/CLI/bestiary/humanoid/githyanki-gish-mtf.md)
*Source: Mordenkainen's Tome of Foes p. 205, Waterdeep: Dungeon of the Mad Mage p. 312*  

## Githyanki Gish

Their keen minds and psionic gifts allow the githyanki to master magic. Gish blend their magical abilities with swordplay to become dangerous foes in battle. Their specialized capabilities make them well suited for assassination, raiding, and espionage.

## Gith

> [!quote] A quote from Mordenkainen  
> 
> What would become of this multiverse if githyanki didn't guard the Astral Plane from the illithid menace? What would reality become if beings of thought ruled the plane of thought?

The descendants of an ancient people—so old their original name has been lost—have turned against each other, becoming vicious enemies divided over mortality, purpose, and the machinations of their leaders. The bellicose githyanki terrorize the Astral Plane, raiding into other worlds to plunder the multiverse of its magic and riches. The githzerai live apart from the rest of the cosmos, content within the confines of their fortresses floating through the chaos of Limbo. Although the two groups of gith despise each other, their hatred for the mind flayers from whom they escaped endures, and both githyanki and githzerai are dedicated to hunting their ancestral foes.

```statblock
"name": "Githyanki Gish (MTF)"
"size": "Medium"
"type": "humanoid"
"subtype": "gith"
"alignment": "Lawful Evil"
"ac": !!int "17"
"ac_class": "[half plate armor](3-Mechanics/CLI/items/half-plate-armor-xphb.md)"
"hp": !!int "123"
"hit_dice": "19d8 + 38"
"modifier": !!int "2"
"stats":
  - !!int "17"
  - !!int "15"
  - !!int "14"
  - !!int "16"
  - !!int "15"
  - !!int "16"
"speed": "30 ft."
"saves":
  - "constitution": !!int "6"
  - "intelligence": !!int "7"
  - "wisdom": !!int "6"
"skillsaves":
  - "name": "[Insight](3-Mechanics/CLI/rules/skills.md#Insight)"
    "desc": "+6"
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+6"
  - "name": "[Stealth](3-Mechanics/CLI/rules/skills.md#Stealth)"
    "desc": "+6"
"gear":
  - "[longsword](3-Mechanics/CLI/items/longsword-xphb.md)"
"senses": "passive Perception 16"
"languages": "Gith"
"cr": "10"
"traits":
  - "desc": "The githyanki is an 8th-level spellcaster. Its spellcasting ability is\
      \ Intelligence (spell save DC 15, +7 to hit with spell attacks). The githyanki\
      \ has the following wizard spells prepared:\n\n**Cantrips (at will):** [blade\
      \ ward](3-Mechanics/CLI/spells/blade-ward-xphb.md), [light](3-Mechanics/CLI/spells/light-xphb.md),\
      \ [message](3-Mechanics/CLI/spells/message-xphb.md), [true strike](3-Mechanics/CLI/spells/true-strike-xphb.md)\n\
      \n**1st level (4 slots):** [expeditious retreat](3-Mechanics/CLI/spells/expeditious-retreat-xphb.md),\
      \ [magic missile](3-Mechanics/CLI/spells/magic-missile-xphb.md), [sleep](3-Mechanics/CLI/spells/sleep-xphb.md),\
      \ [thunderwave](3-Mechanics/CLI/spells/thunderwave-xphb.md)\n\n**2nd level (3\
      \ slots):** [blur](3-Mechanics/CLI/spells/blur-xphb.md), [invisibility](3-Mechanics/CLI/spells/invisibility-xphb.md),\
      \ [levitate](3-Mechanics/CLI/spells/levitate-xphb.md)\n\n**3rd level (3 slots):**\
      \ [counterspell](3-Mechanics/CLI/spells/counterspell-xphb.md), [fireball](3-Mechanics/CLI/spells/fireball-xphb.md),\
      \ [haste](3-Mechanics/CLI/spells/haste-xphb.md)\n\n**4th level (2 slots):**\
      \ [dimension door](3-Mechanics/CLI/spells/dimension-door-xphb.md)"
    "name": "Spellcasting"
  - "desc": "The githyanki's innate spellcasting ability is Intelligence (spell save\
      \ DC 15, +7 to hit with spell attacks). It can innately cast the following\
      \ spells, requiring no components:\n\n**At will:** [mage hand](3-Mechanics/CLI/spells/mage-hand-xphb.md)\
      \ (the hand is invisible)\n\n**3/day each:** [jump](3-Mechanics/CLI/spells/jump-xphb.md),\
      \ [misty step](3-Mechanics/CLI/spells/misty-step-xphb.md), [nondetection](3-Mechanics/CLI/spells/nondetection-xphb.md)\
      \ (self only)\n\n**1/day each:** [plane shift](3-Mechanics/CLI/spells/plane-shift-xphb.md),\
      \ [telekinesis](3-Mechanics/CLI/spells/telekinesis-xphb.md)"
    "name": "Innate Spellcasting (Psionics)"
  - "desc": "When the githyanki uses its action to cast a spell, it can make one weapon\
      \ attack as a bonus action."
    "name": "War Magic"
"actions":
  - "desc": "The githyanki makes two longsword attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +7 to hit, reach 5 ft., one target. *Hit:* 7\
      \ (1d8 + 3) slashing damage plus 18 (4d8) psychic damage, or 8 (1d10 +\
      \ 3) slashing damage plus 18 (4d8) psychic damage if used with two hands."
    "name": "Longsword"
"source":
  - "MTF"
  - "WDMM"
"image": "3-Mechanics/CLI/bestiary/humanoid/token/githyanki-gish-mtf.webp"
```
^statblock

## Environment

desert, mountain, urban