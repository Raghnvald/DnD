---
cssclasses:
  - json5e-monster
tags:
  - Quelle/5e/bgdia
  - Monster/HG/8
  - Monster/Größe/Groß
  - Monster/Typ/Konstrukt
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Fiendish Flesh Golem
---
# [Fiendish Flesh Golem](3-Mechanics\CLI\bestiary\construct/fiendish-flesh-golem-bgdia.md)
*Source: Baldur's Gate: Descent Into Avernus p. 236*  

A fiendish flesh golem is a particularly big flesh golem made of stitched-together body parts from devils, demons, yugoloths, and other fiends. As these parts can come from different creatures and be combined in different ways, no two fiendish flesh golems look exactly alike. Night hags guard the secret to making such golems, rarely sharing it with anyone else.

Some fiendish flesh golems have wings. However, the magic used to create these golems allows them to fly and hover even without wings.

```statblock
"name": "Fiendish Flesh Golem (BGDIA)"
"size": "Large"
"type": "construct"
"alignment": "Unaligned"
"ac": !!int "12"
"ac_class": "natural armor"
"hp": !!int "210"
"hit_dice": "20d10 + 100"
"modifier": !!int "-1"
"stats":
  - !!int "20"
  - !!int "9"
  - !!int "20"
  - !!int "7"
  - !!int "10"
  - !!int "5"
"speed": "30 ft., fly 30 ft. (hover)"
"damage_resistances": "cold, fire"
"damage_immunities": "lightning; poison; bludgeoning, piercing, slashing from nonmagical\
  \ attacks that aren't adamantine or silvered"
"condition_immunities": "[charmed](/3-Mechanics/CLI/conditions.md#Charmed), [exhaustion](/3-Mechanics/CLI/conditions.md#Exhaustion),\
  \ [frightened](/3-Mechanics/CLI/conditions.md#Frightened), [paralyzed](/3-Mechanics/CLI/conditions.md#Paralyzed),\
  \ [petrified](/3-Mechanics/CLI/conditions.md#Petrified), [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)"
"senses": "[darkvision](/3-Mechanics/CLI/senses.md#Darkvision) 60 ft., passive Perception\
  \ 10"
"languages": "understands the languages of its creator but can't speak"
"cr": "8"
"traits":
  - "desc": "Whenever the golem starts its turn with 100 hit points or fewer, roll\
      \ a d6. On a 6, the golem goes berserk. On each of its turns while berserk,\
      \ the golem attacks the nearest creature it can see. If no creature is near\
      \ enough to move to and attack, the golem attacks an object, with preference\
      \ for an object smaller than itself. Once the golem goes berserk, it continues\
      \ to do so until it is destroyed or regains all its hit points. If the golem's\
      \ creator is within 60 feet of the berserk golem, the creator can try to calm\
      \ it by speaking firmly and persuasively. The golem must be able to hear its\
      \ creator, who must take an action to make a DC 15 Charisma ([Persuasion](/3-Mechanics/CLI/skills.md#Persuasion))\
      \ check. If the check succeeds, the golem ceases being berserk. If it takes\
      \ damage while still at 100 hit points or fewer, the golem might go berserk\
      \ again."
    "name": "Berserk"
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
  - "desc": "The golem makes two slam attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +8 to hit, reach 5 ft., one target. *Hit:* 16\
      \ (2d10 + 5) bludgeoning damage."
    "name": "Slam"
"source":
  - "BGDIA"
"image": "/3-Mechanics/CLI/bestiary/construct/token/fiendish-flesh-golem-bgdia.webp"
```
^statblock