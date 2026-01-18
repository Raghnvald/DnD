---
obsidianUIMode: preview
cssclasses:
  - json5e-monster
tags:
  - Quelle/5e/bgg
  - Monster/HG/21
  - Monster/Größe/Gigantisch
  - Monster/Typ/Konstrukt
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Runic Colossus
---
# [Runic Colossus](3-Mechanics\CLI\bestiary\construct/runic-colossus-bgg.md)
*Source: Bigby Presents: Glory of the Giants p. 163*  

According to *The Saga of the Dragon Queller*, told by giants on some worlds, a disparate group of giants combined their efforts to protect their ancient empire from a particularly vicious dragon. Stone and hill giants hewed a mighty form from living stone. Cloud and frost giants gathered rare metals, and fire giants shaped them into flexible joints and plated armor. Storm giants inscribed runes into the inert form to give it the semblance of life. The fruit of these labors was an everlasting guardian: the first runic colossus.

A runic colossus stands 30 feet tall. It regards all non-giants as a threat, and unless it has other orders, it attacks such creatures on sight.

The art of crafting a runic colossus is lost to modern giants, but many tales suggest the instructions might be buried deep in ruins from ancient giants' empires.

```statblock
"name": "Runic Colossus (BGG)"
"size": "Gargantuan"
"type": "construct"
"alignment": "Unaligned"
"ac": !!int "20"
"ac_class": "natural armor"
"hp": !!int "315"
"hit_dice": "18d20 + 126"
"modifier": !!int "-1"
"stats":
  - !!int "25"
  - !!int "9"
  - !!int "24"
  - !!int "3"
  - !!int "11"
  - !!int "1"
"speed": "60 ft."
"damage_resistances": "acid, cold, fire, lightning"
"damage_immunities": "poison; psychic; bludgeoning, piercing, slashing from nonmagical\
  \ attacks"
"condition_immunities": "[charmed](/3-Mechanics/CLI/conditions.md#Charmed), [exhaustion](/3-Mechanics/CLI/conditions.md#Exhaustion),\
  \ [frightened](/3-Mechanics/CLI/conditions.md#Frightened), [paralyzed](/3-Mechanics/CLI/conditions.md#Paralyzed),\
  \ [petrified](/3-Mechanics/CLI/conditions.md#Petrified), [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)"
"senses": "[darkvision](/3-Mechanics/CLI/senses.md#Darkvision) 120 ft., passive Perception\
  \ 10"
"languages": "understands Giant but can't speak"
"cr": "21"
"traits":
  - "desc": "The colossus is immune to any spell or effect that would alter its form."
    "name": "Immutable Form"
  - "desc": "The colossus has advantage on saving throws against spells and other\
      \ magical effects."
    "name": "Magic Resistance"
  - "desc": "The colossus deals double damage to objects and structures."
    "name": "Siege Monster"
"actions":
  - "desc": "The colossus makes two Slam attacks and then uses Stomp."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +14 to hit, reach 20 ft., one target. *Hit:* 26\
      \ (3d12 + 7) bludgeoning damage."
    "name": "Slam"
  - "desc": "*Melee Weapon Attack:* +14 to hit, reach 20 ft., one target. *Hit:* 29\
      \ (4d10 + 7) bludgeoning damage. If the target is a Huge or smaller creature,\
      \ it must succeed on a DC 22 Dexterity saving throw or have the [prone](/3-Mechanics/CLI/conditions.md#Prone)\
      \ condition. Until the colossus uses its Stomp again or moves, the creature\
      \ has the [restrained](/3-Mechanics/CLI/conditions.md#Restrained) condition.\
      \ The [restrained](/3-Mechanics/CLI/conditions.md#Restrained) creature or another\
      \ creature within 5 feet of it can use its action to make a DC 22 Strength check.\
      \ On a successful check, the affected creature relocates to an unoccupied space\
      \ of its choice within 5 feet of the colossus and is no longer [restrained](/3-Mechanics/CLI/conditions.md#Restrained)."
    "name": "Stomp"
  - "desc": "The colossus fires a beam of magical force from its chest, hands, or\
      \ head in a 150-foot line that is 10 feet wide. Each creature in that area must\
      \ make a DC 22 Dexterity saving throw, taking 58 (9d12) force damage on a failed\
      \ save, or half as much damage on a successful one."
    "name": "Arcane Beam (Recharge 5-6)"
"reactions":
  - "desc": "*Ranged Spell Attack:* +14 to hit, range 120 ft., one creature casting\
      \ a spell of 5th level or lower. *Hit:* 26 (4d12) force damage, and the target\
      \ must succeed on a DC 15 Intelligence saving throw or the spell fails and has\
      \ no effect."
    "name": "Spell Reflection (2/Day)"
"source":
  - "BGG"
"image": "/3-Mechanics/CLI/bestiary/construct/token/runic-colossus-bgg.webp"
```
^statblock