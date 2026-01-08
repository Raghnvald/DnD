---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mcv4ec
- ttrpg-cli/monster/cr/11
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/elemental
statblock: inline
statblock-link: "#^statblock"
aliases:
- Tempest Hart
---
# [Tempest Hart](3-Mechanics\CLI\bestiary\elemental/tempest-hart-mcv4ec.md)
*Source: Monstrous Compendium Volume 4: Eldraine Creatures*  

Storm giants live high above Eldraine in a cloudy landscape known as Stormkeld. Massive cottages, keeps, and towers dot this magical realm, scattered between expanses of cloudy wilderness marked by tangles of giant beanstalks and raging storms. Various enormous creatures dwell in these wilds, with the tempest hart being among the most majestic.

A colossal elk with antlers made of living lightning, a tempest hart has a long mane of fine hair that waves as if tossed by a strong wind. Its patterned hide resembles the twisting beanstalks that also coil around its legs, shoulders, and haunches.

Storm giant hunters consider tempest harts to be the worthiest prey, desirable for their meat and the raw lightning of their antlers. However, these creatures wield mighty elemental power to defend themselves.

```statblock
"name": "Tempest Hart (MCV4EC)"
"size": "Huge"
"type": "elemental"
"alignment": "Unaligned"
"ac": !!int "13"
"hp": !!int "147"
"hit_dice": "14d12 + 56"
"modifier": !!int "3"
"stats":
  - !!int "21"
  - !!int "17"
  - !!int "18"
  - !!int "3"
  - !!int "18"
  - !!int "14"
"speed": "50 ft., fly 50 ft."
"saves":
  - "dexterity": !!int "7"
  - "wisdom": !!int "8"
"skillsaves":
  - "name": "Perception"
    "desc": "+12"
"damage_resistances": "bludgeoning, piercing, slashing from nonmagical attacks"
"damage_immunities": "lightning, thunder"
"condition_immunities": "exhaustion"
"senses": "passive Perception 22"
"languages": ""
"cr": "11"
"traits":
  - "desc": "If the hart fails a saving throw, it can choose to succeed instead."
    "name": "Legendary Resistance (3/Day)"
"actions":
  - "desc": "The hart makes a Lightning Antlers attack and a Thunder Hooves attack."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +9 to hit, reach 15 ft., one target. *Hit:* 16\
      \ (2d10 + 5) lightning damage. If the target is a creature, it must succeed\
      \ on a DC 16 Constitution saving throw or have the stunned condition until the\
      \ start of the hart's next turn."
    "name": "Lightning Antlers"
  - "desc": "*Melee Weapon Attack:* +9 to hit, reach 5 ft., one target. *Hit:* 14\
      \ (2d8 + 5) thunder damage."
    "name": "Thunder Hooves"
"reactions":
  - "desc": "Immediately after a creature the hart can see within 120 feet of itself\
      \ hits it with an attack roll, the hart reduces the damage to itself by half.\
      \ The attacker must immediately make a DC 16 Strength saving throw as beanstalks\
      \ coil around it in its space. On a failed save, the creature has the grappled\
      \ condition (escape DC 16) and has the restrained condition as long as it is\
      \ grappled. The beanstalks vanish after 1 minute, if the hart has the incapacitated\
      \ condition, or when the hart dies."
    "name": "Entangling Growth"
  - "desc": "In response to making a saving throw, the hart calls down a bolt of lightning\
      \ that targets a creature it can see within 120 feet of itself. The target must\
      \ make a DC 16 Dexterity saving throw, taking 19 (3d12) lightning damage on\
      \ a failed save, or half as much damage on a successful one."
    "name": "Lightning Call"
"source":
  - "MCV4EC"
"image": "/3-Mechanics/CLI/bestiary/elemental/token/tempest-hart-mcv4ec.webp"
```
^statblock