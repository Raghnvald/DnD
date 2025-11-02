---
cssclasses:
  - json5e-monster
tags:
  - Quelle/5e/pabtso
  - monster/cr/5
  - monster/size/medium
  - monster/type/undead
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Feral Ashenwight
---
# [Feral Ashenwight](3-Mechanics\CLI\bestiary\undead/feral-ashenwight-pabtso.md)
*Source: Phandelver and Below: The Shattered Obelisk p. 204*  

Feral ashenwights retain a fragment of the spark they had in life. However, they are devoid of memories or thoughts beyond a compulsive desire to destroy all living creatures they encounter.

## Ashenwights

When a Humanoid consumed by cruelty and rage dies in an area corrupted by the Far Realm, the creature sometimes rises as an ashenwight. The skin of these Undead horrors is desiccated, and their eyes often glow with otherworldly power.

```statblock
"name": "Feral Ashenwight (PaBTSO)"
"size": "Medium"
"type": "undead"
"alignment": "typically  Neutral Evil"
"ac": !!int "16"
"ac_class": "natural armor"
"hp": !!int "65"
"hit_dice": "10d8 + 20"
"modifier": !!int "1"
"stats":
  - !!int "19"
  - !!int "13"
  - !!int "15"
  - !!int "4"
  - !!int "14"
  - !!int "6"
"speed": "25 ft."
"saves":
  - "strength": !!int "7"
  - "constitution": !!int "5"
"damage_resistances": "necrotic, poison"
"condition_immunities": "[charmed](/3-Mechanics/CLI/conditions.md#Charmed), [exhaustion](/3-Mechanics/CLI/conditions.md#Exhaustion),\
  \ [frightened](/3-Mechanics/CLI/conditions.md#Frightened), [paralyzed](/3-Mechanics/CLI/conditions.md#Paralyzed),\
  \ [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned), [unconscious](/3-Mechanics/CLI/conditions.md#Unconscious)"
"senses": "[darkvision](/3-Mechanics/CLI/senses.md#Darkvision) 120 ft., passive Perception\
  \ 12"
"languages": "understands the languages it knew in life but can't speak"
"cr": "5"
"actions":
  - "desc": "The ashenwight makes two Necrotic Shard attacks."
    "name": "Multiattack"
  - "desc": "*Melee  or Ranged Weapon Attack:* +7 to hit, reach 5 ft. or range 60\
      \ ft., one target. *Hit:* 7 (1d6 + 4) necrotic damage. If the target is a creature,\
      \ it has disadvantage on the next attack roll it makes before the end of its\
      \ next turn."
    "name": "Necrotic Shard"
"source":
  - "PaBTSO"
"image": "/3-Mechanics/CLI/bestiary/undead/token/feral-ashenwight-pabtso.webp"
```
^statblock