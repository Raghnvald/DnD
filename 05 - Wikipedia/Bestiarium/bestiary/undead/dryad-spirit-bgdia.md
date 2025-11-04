---
cssclasses:
  - json5e-monster
tags:
  - Quelle/5e/bgdia
  - Monster/cr/4
  - Monster/Größe/Mittelgroß
  - Monster/Typ/Untote
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Dryad Spirit
---
# [Dryad Spirit](3-Mechanics\CLI\bestiary\undead/dryad-spirit-bgdia.md)
*Source: Baldur's Gate: Descent Into Avernus p. 108*  

```statblock
"name": "Dryad Spirit (BGDIA)"
"size": "Medium"
"type": "undead"
"alignment": "Chaotic Evil"
"ac": !!int "12"
"hp": !!int "58"
"hit_dice": "13d8"
"modifier": !!int "2"
"stats":
  - !!int "1"
  - !!int "14"
  - !!int "10"
  - !!int "12"
  - !!int "11"
  - !!int "17"
"speed": "0 ft., fly 40 ft. (hover)"
"saves":
  - "wisdom": !!int "2"
  - "charisma": !!int "5"
"damage_resistances": "acid; fire; lightning; thunder; bludgeoning, piercing, slashing\
  \ from nonmagical attacks"
"damage_immunities": "cold, necrotic, poison"
"condition_immunities": "[charmed](/3-Mechanics/CLI/conditions.md#Charmed), [exhaustion](/3-Mechanics/CLI/conditions.md#Exhaustion),\
  \ [frightened](/3-Mechanics/CLI/conditions.md#Frightened), [grappled](/3-Mechanics/CLI/conditions.md#Grappled),\
  \ [paralyzed](/3-Mechanics/CLI/conditions.md#Paralyzed), [petrified](/3-Mechanics/CLI/conditions.md#Petrified),\
  \ [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned), [prone](/3-Mechanics/CLI/conditions.md#Prone),\
  \ [restrained](/3-Mechanics/CLI/conditions.md#Restrained)"
"senses": "[darkvision](/3-Mechanics/CLI/senses.md#Darkvision) 60 ft., passive Perception\
  \ 10"
"languages": "Common, Elvish"
"cr": "4"
"traits":
  - "desc": "The dryad can magically sense the presence of living creatures up to\
      \ 5 miles away that aren't undead or constructs. She knows the general direction\
      \ they're in but not their exact locations."
    "name": "Detect Life"
  - "desc": "The dryad can move through other creatures and objects as if they were\
      \ difficult terrain. She takes 5 (1d10) force damage if she ends her turn inside\
      \ an object."
    "name": "Incorporeal Movement"
"actions":
  - "desc": "*Melee Spell Attack:* +4 to hit, reach 5 ft., one target. *Hit:* 12 (3d6\
      \ + 2) necrotic damage."
    "name": "Corrupting Touch"
  - "desc": "Each non-undead creature within 60 feet of the dryad that can see her\
      \ must succeed on a DC 13 Wisdom saving throw or be [frightened](/3-Mechanics/CLI/conditions.md#Frightened)\
      \ for 1 minute. A [frightened](/3-Mechanics/CLI/conditions.md#Frightened) target\
      \ can repeat the saving throw at the end of each of its turns, with disadvantage\
      \ if the dryad is within line of sight, ending the effect on itself on a success.\
      \ If a target's saving throw is successful or the effect ends for it, the target\
      \ is immune to the dryad's Horrifying Visage for the next 24 hours."
    "name": "Horrifying Visage"
  - "desc": "The dryad releases a mournful wail, provided that she isn't in sunlight.\
      \ This wail has no effect on constructs and undead. All other creatures within\
      \ 30 feet of her that can hear her must make a DC 13 Constitution saving throw.\
      \ On a failure, a creature drops to 0 hit points. On a success, a creature takes\
      \ 10 (3d6) psychic damage."
    "name": "Wail (1/Day)"
"source":
  - "BGDIA"
"image": "/3-Mechanics/CLI/bestiary/undead/token/dryad-spirit-bgdia.webp"
```
^statblock