---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/egw
- ttrpg-cli/monster/cr/1
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/construct
statblock: inline
statblock-link: "#^statblock"
aliases:
- Damaged Flesh Golem
---
# [Damaged Flesh Golem](3-Mechanics\CLI\bestiary\construct/damaged-flesh-golem-egw.md)
*Source: Explorer's Guide to Wildemount p. 248*  

```statblock
"name": "Damaged Flesh Golem (EGW)"
"size": "Medium"
"type": "construct"
"alignment": "Neutral"
"ac": !!int "9"
"hp": !!int "5"
"hit_dice": "11d8 + 44"
"modifier": !!int "-1"
"stats":
  - !!int "19"
  - !!int "9"
  - !!int "18"
  - !!int "6"
  - !!int "10"
  - !!int "5"
"speed": "30 ft."
"damage_immunities": "lightning; poison; bludgeoning, piercing, slashing from nonmagical\
  \ attacks that aren't adamantine"
"condition_immunities": "[charmed](/3-Mechanics/CLI/conditions.md#Charmed), [exhaustion](/3-Mechanics/CLI/conditions.md#Exhaustion),\
  \ [frightened](/3-Mechanics/CLI/conditions.md#Frightened), [paralyzed](/3-Mechanics/CLI/conditions.md#Paralyzed),\
  \ [petrified](/3-Mechanics/CLI/conditions.md#Petrified), [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)"
"senses": "[darkvision](/3-Mechanics/CLI/senses.md#Darkvision) 60 ft., passive Perception\
  \ 10"
"languages": "understands the languages of its creator but can't speak"
"cr": "1"
"traits":
  - "desc": "Whenever the golem starts its turn with 40 hit points or fewer, roll\
      \ a d6. On a 6, the golem goes berserk. On each of its turns while berserk,\
      \ the golem attacks the nearest creature it can see. If no creature is near\
      \ enough to move to and attack, the golem attacks an object, with preference\
      \ for an object smaller than itself. Once the golem goes berserk, it continues\
      \ to do so until it is destroyed or regains all its hit points.\n\nThe golem's\
      \ creator, if within 60 feet of the berserk golem, can try to calm it by speaking\
      \ firmly and persuasively. The golem must be able to hear its creator, who must\
      \ take an action to make a DC 15 Charisma ([Persuasion](/3-Mechanics/CLI/skills.md#Persuasion))\
      \ check. If the check succeeds, the golem ceases being berserk. If it takes\
      \ damage while still at 40 hit points or fewer, the golem might go berserk again."
    "name": "Berserk"
  - "desc": "If the golem takes fire damage, it has disadvantage on attack rolls and\
      \ ability checks until the end of its next turn."
    "name": "Aversion of Fire"
  - "desc": "The golem is immune to any spell or effect that would alter its form."
    "name": "Immutable Form"
  - "desc": "Whenever the golem is subjected to lightning damage, it takes no damage\
      \ and instead regains a number of hit points equal to the lightning damage dealt."
    "name": "Lightning Absorption"
  - "desc": "The golem has advantage on saving throws against spells and other magical\
      \ effects."
    "name": "Magic Resistance"
  - "desc": "The golem's weapon attacks are magical."
    "name": "Magic Weapons"
"actions":
  - "desc": "*Melee Weapon Attack:* +7 to hit, reach 5 ft., one target. *Hit:* 13\
      \ (2d8 + 4) bludgeoning damage."
    "name": "Slam"
"source":
  - "EGW"
"image": "/3-Mechanics/CLI/bestiary/construct/token/damaged-flesh-golem-egw.webp"
```
^statblock