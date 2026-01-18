---
obsidianUIMode: preview
cssclasses:
  - json5e-monster
tags:
  - Quelle/5e/bgg
  - Monster/HG/7
  - Monster/Größe/Riesig
  - Monster/Typ/Untote
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Barrowghast
---
# [Barrowghast](3-Mechanics\CLI\bestiary\undead/barrowghast-bgg.md)
*Source: Bigby Presents: Glory of the Giants p. 121*  

A hill giant who dies with an empty stomach, full of rage and regret, might become suffused with energy from the Negative Plane and rise as a barrowghast. Though it looks like little more than an animated corpse, a barrowghast is filled with necrotic energy and driven by spite and malice. Its blood is a thick and toxic ichor that gives the barrowghast a noxious stench.

Barrowghasts no longer hunger for physical food and instead crave life energy drained from living creatures. They often target former family members and allies, but they feast indiscriminately on any creatures they encounter. When barrowghasts drain Humanoids' life energy, those Humanoids rise as zombies.

```statblock
"name": "Barrowghast (BGG)"
"size": "Huge"
"type": "undead"
"alignment": "typically  Chaotic Evil"
"ac": !!int "12"
"ac_class": "natural armor"
"hp": !!int "138"
"hit_dice": "12d12 + 60"
"modifier": !!int "-1"
"stats":
  - !!int "21"
  - !!int "8"
  - !!int "20"
  - !!int "5"
  - !!int "9"
  - !!int "6"
"speed": "40 ft."
"damage_resistances": "necrotic, poison"
"condition_immunities": "[exhaustion](/3-Mechanics/CLI/conditions.md#Exhaustion),\
  \ [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)"
"senses": "[darkvision](/3-Mechanics/CLI/senses.md#Darkvision) 60 ft., passive Perception\
  \ 9"
"languages": "Giant"
"cr": "7"
"traits":
  - "desc": "Any creature that starts its turn within 10 feet of the barrowghast must\
      \ make a DC 16 Constitution saving throw. On a failed save, the creature has\
      \ the [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned) condition for 1 minute.\
      \ While [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned) this way, the creature\
      \ can't regain hit points. On a successful save, the creature is immune to the\
      \ Stench of all barrowghasts for 24 hours."
    "name": "Stench"
"actions":
  - "desc": "The barrowghast makes two Slam attacks. It can replace one Slam attack\
      \ with a Life Drain attack."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +8 to hit, reach 10 ft., one target. *Hit:* 18\
      \ (2d12 + 5) bludgeoning damage."
    "name": "Slam"
  - "desc": "*Melee Weapon Attack:* +8 to hit, reach 10 ft., one creature. *Hit:*\
      \ 9 (1d8 + 5) necrotic damage, and the target must succeed on a DC 16 Constitution\
      \ saving throw or its hit point maximum is reduced by an amount equal to the\
      \ damage taken. This reduction lasts until the target finishes a long rest.\
      \ The target dies if this effect reduces its hit point maximum to 0.\n\nA Humanoid\
      \ slain by this attack immediately rises as a zombie (see the Monster Manual).\
      \ The zombie acts as an ally of the barrowghast but isn't under its control."
    "name": "Life Drain"
"reactions":
  - "desc": "Immediately after the barrowghast takes piercing or slashing damage,\
      \ poisonous ichor sprays from the wound. Each creature within 5 feet of the\
      \ barrowghast must make a DC 16 Dexterity saving throw, taking 10 (3d6) poison\
      \ damage on a failed save, or half as much damage on a successful one."
    "name": "Noxious Wound"
"source":
  - "BGG"
"image": "/3-Mechanics/CLI/bestiary/undead/token/barrowghast-bgg.webp"
```
^statblock