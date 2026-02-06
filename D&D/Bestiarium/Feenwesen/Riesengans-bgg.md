---
cssclasses:
  - json5e-monster
tags:
  - Quelle/5e/bgg
  - Monster/HG/3
  - Monster/Größe/Groß
  - Monster/Typ/Fee
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Giant Goose
---
# [Giant Goose](3-Mechanics\CLI\bestiary\fey/giant-goose-bgg.md)
*Source: Bigby Presents: Glory of the Giants p. 150*  

Giants keep geese as livestock for eggs and because geese make excellent sentries, protecting the giants' property with their keen senses and loud voices. Not only are giant geese from fey stock significantly larger than ordinary geese, but they also have two magical properties that make them even more valuable: their honk is a powerful defense against intruders, and they can lay eggs with shells of pure gold.

When commanded by its keeper, a giant goose lays a golden egg—a hollow shell of gold, 1 foot long and weighing 2 pounds. The shell is worth 100 gp. Sometimes, the egg inexplicably contains some kind of small trinket or minor magic item. Once it lays a golden egg, a giant goose can't do so again for a year and a day.

You can use the [Goose Egg Trinket](/3-Mechanics/CLI/items/goose-egg-trinket-bgg.md) table to determine the contents of a golden egg. A giant goose's egg can be a great way to give characters an item that's important to the story of an adventure or your campaign.

```statblock
"name": "Giant Goose (BGG)"
"size": "Large"
"type": "fey"
"alignment": "typically  Neutral"
"ac": !!int "13"
"hp": !!int "60"
"hit_dice": "8d10 + 16"
"modifier": !!int "3"
"stats":
  - !!int "14"
  - !!int "16"
  - !!int "15"
  - !!int "6"
  - !!int "14"
  - !!int "11"
"speed": "30 ft., fly 30 ft."
"skillsaves":
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+6"
"senses": "[darkvision](/3-Mechanics/CLI/senses.md#Darkvision) 60 ft., passive Perception\
  \ 16"
"languages": "understands Giant and Sylvan but can't speak"
"cr": "3"
"actions":
  - "desc": "The goose makes one Beak attack and two Wing attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 10 ft., one target. *Hit:* 9\
      \ (2d6 + 2) bludgeoning damage."
    "name": "Beak"
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one target. *Hit:* 7 (1d10\
      \ + 2) bludgeoning damage, and the target must succeed on a DC 12 Strength saving\
      \ throw or have the [prone](/3-Mechanics/CLI/conditions.md#Prone) condition."
    "name": "Wing"
  - "desc": "The goose honks with ear-splitting volume. Each other creature within\
      \ 30 feet of the goose must make a DC 12 Constitution saving throw. On a failed\
      \ save, a creature takes 16 (3d10) thunder damage and has the [deafened](/3-Mechanics/CLI/conditions.md#Deafened)\
      \ condition until the start of the goose's next turn. On a successful save,\
      \ a creature takes half as much damage only. The honk can be heard within 300\
      \ feet."
    "name": "Thunderous Honk (Recharge 5-6)"
"source":
  - "BGG"
"image": "/3-Mechanics/CLI/bestiary/fey/token/giant-goose-bgg.webp"
```
^statblock