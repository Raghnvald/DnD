---
cssclasses:
  - json5e-monster
tags:
  - Quelle/5e/pabtso
  - monster/cr/10
  - monster/size/large
  - monster/type/aberration
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Encephalon Cluster
---
# [Encephalon Cluster](3-Mechanics\CLI\bestiary\aberration/encephalon-cluster-pabtso.md)
*Source: Phandelver and Below: The Shattered Obelisk p. 205*  

An encephalon cluster pays no heed to an elder brain or its mind flayer progenitors. This grotesque creature shambles through dark and forgotten caverns, spewing warped progeny so it can multiply. As such, many mind flayers view encephalon clusters as insidious viruses. If left unchecked, a single encephalon cluster can quickly become a gorging menace that can overrun an entire mind flayer colony.

## Encephalons

When an illithid colony lays its eggs dangerously close to a Far Realm rift, an egg sac has a chance to mutate into what is known as an encephalon cluster—a ravenous, slimy, psionic, brain-shaped mass that spawns horrors called encephalon gemmules.

```statblock
"name": "Encephalon Cluster (PaBTSO)"
"size": "Large"
"type": "aberration"
"alignment": "Unaligned"
"ac": !!int "13"
"ac_class": "natural armor"
"hp": !!int "110"
"hit_dice": "17d10 + 17"
"modifier": !!int "0"
"stats":
  - !!int "23"
  - !!int "10"
  - !!int "13"
  - !!int "5"
  - !!int "17"
  - !!int "7"
"speed": "20 ft."
"damage_resistances": "psychic"
"condition_immunities": "[blinded](/3-Mechanics/CLI/conditions.md#Blinded)"
"senses": "[blindsight](/3-Mechanics/CLI/senses.md#Blindsight) 60 ft. (can't see beyond\
  \ this radius), passive Perception 13"
"languages": ""
"cr": "10"
"traits":
  - "desc": "If the cluster fails a saving throw, it can choose to succeed instead."
    "name": "Legendary Resistance (3/Day)"
  - "desc": "The cluster has advantage on saving throws against spells and other magical\
      \ effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "The cluster makes two Slam attacks. It can replace one of these attacks\
      \ with Spawn Progeny if available."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +10 to hit, reach 5 ft., one target. *Hit:* 17\
      \ (2d10 + 6) bludgeoning damage plus 10 (3d6) psychic damage, and if the target\
      \ is a creature, the target must succeed on a DC 18 Strength saving throw or\
      \ have the [prone](/3-Mechanics/CLI/conditions.md#Prone) condition. If this\
      \ attack reduces the target to 0 hit points, the target immediately dies and\
      \ is consumed by the cluster."
    "name": "Slam"
  - "desc": "The cluster bulges and spews 1d4 mature eggs. Each egg lands in an unoccupied\
      \ space of the cluster's choice within 30 feet of itself and immediately transforms\
      \ into an [encephalon gemmule](/3-Mechanics/CLI/bestiary/aberration/encephalon-gemmule-pabtso.md).\
      \ The gemmules obey the cluster's commands and take their turns immediately\
      \ after it."
    "name": "Spawn Progeny (Recharges after a Short or Long Rest)"
"reactions":
  - "desc": "Immediately after being hit by an attack, the cluster moves up to its\
      \ speed toward the attacker. This movement doesn't provoke opportunity attacks.\
      \ If the cluster ends this movement within 5 feet of the attacker, it then makes\
      \ one Slam attack against that attacker."
    "name": "Aggressive Hunger"
"source":
  - "PaBTSO"
"image": "/3-Mechanics/CLI/bestiary/aberration/token/encephalon-cluster-pabtso.webp"
```
^statblock