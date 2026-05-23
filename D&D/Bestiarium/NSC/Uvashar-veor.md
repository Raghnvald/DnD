---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Uvashar
status: WIP
tags:
  - Monster/Größe/Mittelgroß
  - Monster/HG/13
  - Monster/Typ/Unhold
  - Quelle/5e/veor
aliases:
  - Uvashar
IMAGE: token/uvashar-veor.webp
linter-yaml-title-alias: Uvashar
---
# [Uvashar](3-Mechanics\CLI\bestiary\npc/uvashar-veor.md)
*Source: Vecna: Eve of Ruin*  

```statblock
"name": "Uvashar (VEoR)"
"size": "Medium"
"type": "fiend"
"alignment": "Lawful Evil"
"ac": !!int "16"
"ac_class": "natural armor"
"hp": !!int "110"
"hit_dice": "13d8 + 52"
"modifier": !!int "3"
"stats":
  - !!int "14"
  - !!int "17"
  - !!int "18"
  - !!int "13"
  - !!int "16"
  - !!int "20"
"speed": "40 ft."
"skillsaves":
  - "name": "Deception"
    "desc": "+10"
  - "name": "Insight"
    "desc": "+8"
"damage_vulnerabilities": "piercing from magic weapons wielded by good creatures"
"damage_immunities": "bludgeoning, piercing, slashing from nonmagical attacks"
"senses": "darkvision 60 ft., passive Perception 13"
"languages": "Common, Infernal"
"cr": "13"
"traits":
  - "desc": "Uvashar can't be affected or detected by spells of 6th level or lower\
      \ unless it wishes to be. It has advantage on saving throws against all other\
      \ spells and magical effects."
    "name": "Limited Magic Immunity"
"actions":
  - "desc": "Uvashar makes two claw attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +7 to hit, reach 5 ft., one target. *Hit:* 9 (2d6\
      \ + 2) slashing damage, and the target is cursed if it is a creature. The magical\
      \ curse takes effect whenever the target takes a short or long rest, filling\
      \ the target's thoughts with horrible images and dreams. The cursed target gains\
      \ no benefit from finishing a short or long rest. The curse lasts until it is\
      \ lifted by a remove curse spell or similar magic."
    "name": "Claw"
"source":
  - "VEoR"
"image": "/3-Mechanics/CLI/bestiary/npc/token/uvashar-veor.webp"
```
^statblock