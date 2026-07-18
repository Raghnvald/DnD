---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Bag Jelly
Status: WIP
linter-yaml-title-alias: Bag Jelly
tags:
  - Monster/Größe/Mittelgroß
  - Monster/HG/1
  - Monster/Typ/Schleim
  - Quelle/5e/bgg
aliases:
  - Bag Jelly
---
# [Bag Jelly](3-Mechanics\CLI\bestiary\ooze/bag-jelly-bgg.md)
*Source: Bigby Presents: Glory of the Giants p. 120*  

> [!quote] A quote from Bigby  
> 
> A Dwarvish saga claims bag jellies are the result of a curse laid by Durgrid Bladeforge, who was beaten to death while hiding inside a giant's bag.

Bag jellies are olive-hued oozes similar to the dungeon scavengers described in the *Monster Manual*. As their name suggests, though, these creatures are most often found in the bags carried by giants, where they feed on whatever organic material they find. Bag jellies are resistant to squishing, which helps them survive when a giant throws the bag, sits on it, or uses it as a makeshift bludgeon.

Some giants keep their bags scrupulously clean to avoid attracting bag jellies, but others actually use these scavengers to hinder thieves. Many would-be thieves who rummage through a sleeping giant's bag find themselves stuck to a bag jelly's adhesive surface and unable to flee as the sound of their struggle wakes the giant.

> [!quote] A quote from Diancastra  
> 
> I'm not one to discount Dwarvish sagas as a rule, but everyone knows that food left in a bag too long sometimes comes alive. "Eat it before it eats you." That's my motto.

```statblock
"name": "Bag Jelly (BGG)"
"size": "Medium"
"type": "ooze"
"alignment": "Unaligned"
"ac": !!int "8"
"hp": !!int "42"
"hit_dice": "5d8 + 20"
"modifier": !!int "-2"
"stats":
  - !!int "13"
  - !!int "6"
  - !!int "19"
  - !!int "2"
  - !!int "7"
  - !!int "2"
"speed": "10 ft., climb 10 ft."
"damage_resistances": "acid, bludgeoning"
"condition_immunities": "[exhaustion](/3-Mechanics/CLI/conditions.md#Exhaustion)"
"senses": "[blindsight](/3-Mechanics/CLI/senses.md#Blindsight) 60 ft. (can't see beyond\
  \ this radius), passive Perception 8"
"languages": ""
"cr": "1"
"traits":
  - "desc": "The bag jelly can move through a space as narrow as 1 inch without squeezing."
    "name": "Amorphous"
"actions":
  - "desc": "The bag jelly makes two Pseudopod attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +3 to hit, reach 5 ft., one target. *Hit:* 8 (2d6\
      \ + 1) acid damage. If the target is a Medium or smaller creature, it has the\
      \ [grappled](/3-Mechanics/CLI/conditions.md#Grappled) condition (escape DC 11).\
      \ Ability checks made to escape this grapple have disadvantage."
    "name": "Pseudopod"
"source":
  - "BGG"
"image": "/3-Mechanics/CLI/bestiary/ooze/token/bag-jelly-bgg.webp"
```
^statblock