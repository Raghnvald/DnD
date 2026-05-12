---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/ai
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/half-elf
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Auspicia Dran"
---
# [Auspicia Dran](3-Mechanics/CLI/bestiary/npc/auspicia-dran-ai.md)
*Source: Acquisitions Incorporated p. 208*  

The youngest sister of Omin Dran, the half-elf Auspicia Dran had her life torn apart as a child when she was seized by a mysterious creature called the Wandering Crypt. Having spent long years in a kind of dark dream within the crypt, she was saved in the end by her brother Omin's tireless efforts and the valor of his handpicked "C" Team. Now returned safely to the world-and with the false Auspicia of the crypt's creation slain-she focuses on trying to discover her own identity and to work through the ongoing complications arising from her ordeal.

When Auspicia emerged from the Wandering Crypt, she carried within her a growing level of psionic power. She can't help but read others' minds, but finds that wearing a diamond earring helps tamp that unwitting ability down. This magic has also left her connected to the crypt in a way she doesn't understand, even as it grants her occasional memories of others still trapped there and an awareness of faraway places. In combat, she manifests an instinctive knowledge of events before they happen, often making use of this ability to bring a fight to a standstill that encourages parley. But she has only just begun to explore her full precognitive potential.

```statblock
"name": "Auspicia Dran (AI)"
"size": "Medium"
"type": "humanoid"
"subtype": "half-elf"
"alignment": "Neutral Good"
"ac": !!int "15"
"ac_class": "chain shirt"
"hp": !!int "52"
"hit_dice": "8d8 + 16"
"modifier": !!int "2"
"stats":
  - !!int "16"
  - !!int "14"
  - !!int "14"
  - !!int "15"
  - !!int "12"
  - !!int "10"
"speed": "30 ft."
"skillsaves":
  - "name": "Athletics"
    "desc": "+5"
  - "name": "Perception"
    "desc": "+3"
"gear":
  - "light crossbow"
  - "longsword"
"senses": "passive Perception 13"
"languages": "Common, Elvish"
"cr": "2"
"traits":
  - "desc": "Auspicia's innate spellcasting ability is Intelligence. She can innately\
      \ cast the following spells, requiring no components:\n\n**At will:** detect\
      \ thoughts\n\n**1/day each:** augury"
    "name": "Innate Spellcasting (Psionics)"
"actions":
  - "desc": "Auspicia makes two attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one target. *Hit:* 7\
      \ (1d8 + 3) slashing damage, or 8 (1d10 + 3) slashing damage if used with\
      \ two hands."
    "name": "Longsword"
  - "desc": "*Ranged Weapon Attack:* +4 to hit, range 80/320 ft., one target. *Hit:*\
      \ 6 (1d8 + 2) piercing damage."
    "name": "Light Crossbow"
"source":
  - "AI"
"image": "3-Mechanics/CLI/bestiary/npc/token/auspicia-dran-ai.webp"
```
^statblock