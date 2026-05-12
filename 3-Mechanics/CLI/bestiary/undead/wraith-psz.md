---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/psz
- ttrpg-cli/monster/cr/5
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/undead
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Wraith"
---
# [Wraith](3-Mechanics/CLI/bestiary/undead/wraith-psz.md)
*Source: Plane Shift: Zendikar p. 28*  

Magic fueled by black mana can alter the natural cycle of life and death. Whether wielded by mortal wizards or demons, or simply an environmental manifestation of black mana's flow through the land, such magic can trap spirits between the realm of the living and the mysterious fate of the dead. These ghostly undead are as destructive and hateful as the magic that calls them into being. Zendikar's shades and wraiths can be represented by the [shadows](3-Mechanics/CLI/bestiary/undead/shadow.md) and [wraiths](3-Mechanics/CLI/bestiary/undead/wraith.md) in the Monster Manual.

Not all spirits are created with black mana, however, and not all are malevolent. The spirits of the dead sometimes linger in the world to protect their kin or communities, or to stand guard over sacred or important sites. These spirits can be dangerous, but they are not usually malicious. Both the kor and the Mul Daya elves remain in communion with the spirits of their dead kindred, entreating them for wisdom and protection. Such spirits are best described as the [ghosts](3-Mechanics/CLI/bestiary/undead/ghost.md) in the Monster Manual.

```statblock
"name": "Wraith (PSZ)"
"size": "Medium"
"type": "undead"
"alignment": "Neutral Evil"
"ac": !!int "13"
"hp": !!int "67"
"hit_dice": "9d8 + 27"
"modifier": !!int "3"
"stats":
  - !!int "6"
  - !!int "16"
  - !!int "16"
  - !!int "12"
  - !!int "14"
  - !!int "15"
"speed": "0 ft., fly 60 ft. (hover)"
"damage_resistances": "acid; cold; fire; lightning; thunder; bludgeoning, piercing,\
  \ slashing from nonmagical attacks that aren't silvered"
"damage_immunities": "necrotic, poison"
"condition_immunities": "[charmed](3-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](3-Mechanics/CLI/rules/conditions.md#Exhaustion),\
  \ [grappled](3-Mechanics/CLI/rules/conditions.md#Grappled), [paralyzed](3-Mechanics/CLI/rules/conditions.md#Paralyzed),\
  \ [petrified](3-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned),\
  \ [prone](3-Mechanics/CLI/rules/conditions.md#Prone), [restrained](3-Mechanics/CLI/rules/conditions.md#Restrained)"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., passive\
  \ Perception 12"
"languages": "the languages it knew in life"
"cr": "5"
"traits":
  - "desc": "The wraith can move through other creatures and objects as if they were\
      \ difficult terrain. It takes 5 (1d10) force damage if it ends its turn inside\
      \ an object."
    "name": "Incorporeal Movement"
  - "desc": "While in sunlight, the wraith has disadvantage on attack rolls, as well\
      \ as on Wisdom ([Perception](3-Mechanics/CLI/rules/skills.md#Perception)) checks\
      \ that rely on sight."
    "name": "Sunlight Sensitivity"
"actions":
  - "desc": "*Melee Weapon Attack:* +6 to hit, reach 5 ft., one creature. *Hit:*\
      \ 21 (4d8 + 3) necrotic damage. The target must succeed on a DC 14 Constitution\
      \ saving throw or its hit point maximum is reduced by an amount equal to the\
      \ damage taken. This reduction lasts until the target finishes a long rest.\
      \ The target dies if this effect reduces its hit point maximum to 0."
    "name": "Life Drain"
  - "desc": "The wraith targets a humanoid within 10 feet of it that has been dead\
      \ for no longer than 1 minute and died violently. The target's spirit rises\
      \ as a [specter](3-Mechanics/CLI/bestiary/undead/specter.md) in the space of\
      \ its corpse or in the nearest unoccupied space. The [specter](3-Mechanics/CLI/bestiary/undead/specter.md)\
      \ is under the wraith's control. The wraith can have no more than seven specters\
      \ under its control at one time."
    "name": "Create Specter"
"source":
  - "PSZ"
"image": "3-Mechanics/CLI/bestiary/undead/token/wraith-psz.webp"
```
^statblock