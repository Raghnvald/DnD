---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/bam
- ttrpg-cli/monster/cr/1-2
- ttrpg-cli/monster/size/small
- ttrpg-cli/monster/type/beast
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Space Eel"
---
# [Space Eel](3-Mechanics/CLI/bestiary/beast/space-eel-bam.md)
*Source: Boo's Astral Menagerie p. 55*  

Space eels avoid confrontations with larger creatures unless the eels are starving. These 5-foot-long scavengers might trail a spelljamming ship and feed on barnacles they detach from the ship's hull. Wildspace hunters try to catch and kill the eels for their meat—a task easier to describe than to accomplish.

```statblock
"name": "Space Eel (BAM)"
"size": "Small"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "14"
"hp": !!int "7"
"hit_dice": "2d6"
"modifier": !!int "4"
"stats":
  - !!int "12"
  - !!int "18"
  - !!int "11"
  - !!int "1"
  - !!int "10"
  - !!int "1"
"speed": "10 ft., fly 30 ft."
"senses": "darkvision 60 ft., passive Perception 10"
"languages": ""
"cr": "1/2"
"traits":
  - "desc": "The eel doesn't require air."
    "name": "Unusual Nature"
"actions":
  - "desc": "If it isn't attached to a creature, the eel makes one Bite attack and\
      \ one Tail Spine attack."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +3 to hit, reach 5 ft., one creature. *Hit:*\
      \ 4 (1d6 + 1) piercing damage, and the eel attaches to the target. While attached,\
      \ the eel can't make Bite attacks. Instead, the target takes 4 (1d6 + 1) piercing\
      \ damage at the start of each of the eel's turns. The eel can detach itself\
      \ as a bonus action. A creature, including the target, can use its action to\
      \ detach the eel."
    "name": "Bite"
  - "desc": "*Melee Weapon Attack:* +3 to hit, reach 5 ft., one creature. *Hit:*\
      \ 3 (1d4 + 1) piercing damage, and the target must succeed on a DC 10 Constitution\
      \ saving throw or be poisoned for 1 minute. Until this poison ends, the target\
      \ is paralyzed. The target can repeat the saving throw at the end of each of\
      \ its turns, ending the effect on itself on a success."
    "name": "Tail Spine"
"source":
  - "BAM"
"image": "3-Mechanics/CLI/bestiary/beast/token/space-eel-bam.webp"
```
^statblock