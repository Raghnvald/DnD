---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/wdmm
- ttrpg-cli/monster/cr/
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/construct
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Iron Spider"
---
# [Iron Spider](3-Mechanics/CLI/bestiary/npc/iron-spider-wdmm.md)
*Source: Waterdeep: Dungeon of the Mad Mage p. 165*  

The iron spider exists solely to produce web cables. It has no attacks and no instinct for self-preservation.

```statblock
"name": "Iron Spider (WDMM)"
"size": "Large"
"type": "construct"
"alignment": "Unaligned"
"ac": !!int "19"
"hp": !!int "80"
"modifier": !!int "0"
"stats":
  - !!int "18"
  - !!int "10"
  - !!int "10"
  - !!int "3"
  - !!int "3"
  - !!int "1"
"speed": "30 ft., climb 30 ft."
"damage_immunities": "poison, psychic"
"senses": "[blindsight](3-Mechanics/CLI/rules/senses.md#Blindsight) 60 ft. (blind\
  \ beyond this radius), passive Perception 6"
"languages": ""
"traits":
  - "desc": "The iron spider can climb difficult surfaces, including upside down on\
      \ ceilings, without needing to make an ability check."
    "name": "Spider Climb"
  - "desc": "The iron spider is [incapacitated](3-Mechanics/CLI/rules/conditions.md#Incapacitated)\
      \ while in the area of an [antimagic field](3-Mechanics/CLI/spells/antimagic-field-xphb.md).\
      \ If targeted by [dispel magic](3-Mechanics/CLI/spells/dispel-magic-xphb.md),\
      \ the iron spider must succeed on a Constitution saving throw against the caster's\
      \ spell save DC or fall [unconscious](3-Mechanics/CLI/rules/conditions.md#Unconscious)\
      \ for 1 minute."
    "name": "Antimagic Susceptibility"
"actions":
  - "desc": "The iron spider shoots out a 6-inch-thick web cable up to 50 feet long,\
      \ attaching the far end of the cable to a solid surface up to 50 feet away from\
      \ it. As a bonus action, it can detach the other end of the cable from itself\
      \ and attach it to a solid surface within 10 feet of it. Once it creates 200\
      \ feet of web cable, the spider can't produce any more cable until the next\
      \ dawn."
    "name": "Web Cable"
"source":
  - "WDMM"
"image": "3-Mechanics/CLI/bestiary/npc/token/iron-spider-wdmm.webp"
```
^statblock