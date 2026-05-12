---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mpp
- ttrpg-cli/monster/cr/12
- ttrpg-cli/monster/size/small-or-medium
- ttrpg-cli/monster/type/humanoid
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Doomguard Doom Lord"
---
# [Doomguard Doom Lord](3-Mechanics/CLI/bestiary/humanoid/doomguard-doom-lord-mpp.md)
*Source: Morte's Planar Parade p. 54*  

Doom lords are the highest-ranking members of the Doomguard, embodying the multiverse's inevitable collapse into dust. Doom lords' mere presence snuffs the life from weaker foes, and the stoutest walls crumble before them.

```statblock
"name": "Doomguard Doom Lord (MPP)"
"size": "Small or Medium"
"type": "humanoid"
"alignment": "Any alignment"
"ac": !!int "18"
"ac_class": "[plate armor](3-Mechanics/CLI/items/plate-armor.md)"
"hp": !!int "202"
"hit_dice": "27d8 + 81"
"modifier": !!int "1"
"stats":
  - !!int "20"
  - !!int "12"
  - !!int "16"
  - !!int "15"
  - !!int "14"
  - !!int "18"
"speed": "30 ft."
"saves":
  - "strength": !!int "9"
  - "constitution": !!int "7"
"skillsaves":
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+6"
"damage_immunities": "necrotic"
"senses": "passive Perception 16"
"languages": "Common plus three more languages"
"cr": "12"
"traits":
  - "desc": "Any creature that starts its turn within 10 feet of the doom lord must\
      \ make a DC 16 Constitution saving throw, taking 18 (4d8) necrotic damage\
      \ on a failed save, or half as much damage on a successful one. If the doom\
      \ lord doesn't have the [incapacitated](3-Mechanics/CLI/rules/conditions.md#Incapacitated)\
      \ condition, it can suppress or resume this aura at the start of its turn (no\
      \ action required)."
    "name": "Aura of Doom"
  - "desc": "The doom lord deals double damage to objects and structures."
    "name": "Siege Monster"
"actions":
  - "desc": "The doom lord makes two Entropic Greatsword or Entropic Javelin attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +9 to hit, reach 5 ft., one target. *Hit:* 12\
      \ (2d6 + 5) slashing damage plus 10 (3d6) necrotic damage. A creature killed\
      \ by this attack has its body and everything it is wearing or carrying, except\
      \ for magic items, reduced to ash."
    "name": "Entropic Greatsword"
  - "desc": "*Melee  or Ranged Weapon Attack:* +9 to hit, reach 5 ft. or range 30/120\
      \ ft., one target. *Hit:* 8 (1d6 + 5) piercing damage plus 14 (4d6) necrotic\
      \ damage. A creature killed by this attack has its body and everything it is\
      \ wearing or carrying, except for magic items, reduced to ash."
    "name": "Entropic Javelin"
"source":
  - "MPP"
"image": "3-Mechanics/CLI/bestiary/humanoid/token/doomguard-doom-lord-mpp.webp"
```
^statblock