---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Tempest Spirit
tags:
  - Monster/Größe/Riesig
  - Monster/HG/15
  - Monster/Typ/Untote
  - Quelle/5e/bgg
aliases:
  - Tempest Spirit
linter-yaml-title-alias: Tempest Spirit
---
# [Tempest Spirit](3-Mechanics\CLI\bestiary\undead/tempest-spirit-bgg.md)
*Source: Bigby Presents: Glory of the Giants p. 184*  

A storm giant can escape death through a mystical ritual that transforms the giant into a semiconscious storm. However, if the giant performs the ritual in a place where the barrier between the Material Plane and the Shadowfell is thin, the seeping negative energy drastically alters the ritual's outcome. The giant's soul becomes infused with negative energy and doesn't disperse into the elements. Rather, it absorbs the elemental energy around it, and its lower body becomes a storm cloud. The resulting tempest spirit is similar in appearance to a djinni and is sometimes mistaken for one by adventurers.

Some tempest spirits cannot accept their new form and seek to undo the transformation in solitude. Others are overcome with rage and hew a path of destruction. Massive hailstones and lightning infused with necrotic energy rain from tempest spirits on those that get too close to them.

```statblock
"name": "Tempest Spirit (BGG)"
"size": "Huge"
"type": "undead"
"alignment": "typically  Chaotic Evil"
"ac": !!int "12"
"hp": !!int "195"
"hit_dice": "17d12 + 85"
"modifier": !!int "2"
"stats":
  - !!int "24"
  - !!int "14"
  - !!int "20"
  - !!int "16"
  - !!int "18"
  - !!int "19"
"speed": "0 ft., fly 60 ft. (hover)"
"saves":
  - "constitution": !!int "10"
  - "intelligence": !!int "8"
  - "wisdom": !!int "9"
  - "charisma": !!int "9"
"skillsaves":
  - "name": "[Arcana](/3-Mechanics/CLI/skills.md#Arcana)"
    "desc": "+8"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+9"
"damage_resistances": "cold; necrotic; poison; bludgeoning, piercing, slashing from\
  \ nonmagical attacks"
"damage_immunities": "lightning, thunder"
"condition_immunities": "[charmed](/3-Mechanics/CLI/conditions.md#Charmed), [exhaustion](/3-Mechanics/CLI/conditions.md#Exhaustion),\
  \ [frightened](/3-Mechanics/CLI/conditions.md#Frightened), [grappled](/3-Mechanics/CLI/conditions.md#Grappled),\
  \ [paralyzed](/3-Mechanics/CLI/conditions.md#Paralyzed), [petrified](/3-Mechanics/CLI/conditions.md#Petrified),\
  \ [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned), [prone](/3-Mechanics/CLI/conditions.md#Prone),\
  \ [restrained](/3-Mechanics/CLI/conditions.md#Restrained)"
"senses": "passive Perception 19"
"languages": "Common, Giant"
"cr": "15"
"traits":
  - "desc": "The spirit can move through other creatures and objects as if they were\
      \ difficult terrain. The spirit takes 5 (1d10) force damage if it ends its turn\
      \ inside an object."
    "name": "Incorporeal Movement"
  - "desc": "If the spirit fails a saving throw, it can choose to succeed instead."
    "name": "Legendary Resistance (3/Day)"
"actions":
  - "desc": "The spirit makes two Lightning Fist or Hailstone attacks in any combination."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +12 to hit, reach 10 ft., one target. *Hit:* 25\
      \ (4d8 + 7) lightning damage."
    "name": "Lightning Fist"
  - "desc": "*Ranged Weapon Attack:* +12 to hit, range 90/180 ft., one target. *Hit:*\
      \ 17 (3d6 + 7) bludgeoning damage plus 7 (2d6) cold damage."
    "name": "Hailstone"
  - "desc": "The spirit hurls a magical lightning bolt in a 120-foot line that is\
      \ 10 feet wide. Each creature in that area must make a DC 18 Dexterity saving\
      \ throw, taking 27 (6d8) lightning damage plus 16 (3d10) necrotic damage on\
      \ a failed save, or half as much damage on a successful one. On a success or\
      \ failure, an affected creature's hit point maximum is reduced by an amount\
      \ equal to the necrotic damage taken. This reduction lasts until the creature\
      \ finishes a long rest. The creature dies if its hit point maximum is reduced\
      \ to 0."
    "name": "Death Bolt (Recharge 5-6)"
"bonus_actions":
  - "desc": "The spirit conjures a hailstorm in a 20-foot-radius, 40-foot-high cylinder\
      \ centered on a point it can see within 120 feet of itself. Each creature in\
      \ that area must make a DC 17 Dexterity saving throw. On a failed save, a creature\
      \ takes 10 (3d6) bludgeoning damage plus 10 (3d6) cold damage and has the [prone](/3-Mechanics/CLI/conditions.md#Prone)\
      \ condition. On a successful save, a creature takes half as much damage only."
    "name": "Hailstorm (Recharge 4-6)"
"source":
  - "BGG"
"image": "/3-Mechanics/CLI/bestiary/undead/token/tempest-spirit-bgg.webp"
```
^statblock