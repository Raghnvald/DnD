---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/bgg
- ttrpg-cli/monster/cr/5
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/elemental
statblock: inline
statblock-link: "#^statblock"
aliases:
- Dust Hulk
---
# [Dust Hulk](3-Mechanics\CLI\bestiary\elemental/dust-hulk-bgg.md)
*Source: Bigby Presents: Glory of the Giants p. 131*  

Dust hulks are descended from enclaves of stone giants who lived in extreme environments, isolated from others. Elemental energy from the Plane of Air eroded their physical forms and slowly transformed them into Elementals. They are little more than clouds of gravel and dust, barely maintaining a cohesive form. When a dust hulk dies, it disperses into a cloud of dust.

Dust hulks retain their ancestors' passion for artistry, but instead of carving stone, they view their bodies as living works of art. As they fly, coursing along wind currents or blowing through underground tunnels like living sandstorms, they create mesmerizing dances with their ever-shifting forms.

> [!quote] A quote from Bigby  
> 
> It's tempting to view the various hulks as symbols of the long, slow decline of the giants as a people. But that's hardly fair to the giants who still survive and thrive in the world, heirs of tremendous glory.


```statblock
"name": "Dust Hulk (BGG)"
"size": "Large"
"type": "elemental"
"alignment": "typically  Chaotic Neutral"
"ac": !!int "16"
"ac_class": "natural armor"
"hp": !!int "68"
"hit_dice": "8d10 + 24"
"modifier": !!int "4"
"stats":
  - !!int "15"
  - !!int "19"
  - !!int "16"
  - !!int "10"
  - !!int "12"
  - !!int "8"
"speed": "0 ft., fly 30 ft. (hover)"
"damage_immunities": "poison"
"condition_immunities": "[exhaustion](/3-Mechanics/CLI/conditions.md#Exhaustion),\
  \ [grappled](/3-Mechanics/CLI/conditions.md#Grappled), [paralyzed](/3-Mechanics/CLI/conditions.md#Paralyzed),\
  \ [petrified](/3-Mechanics/CLI/conditions.md#Petrified), [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned),\
  \ [restrained](/3-Mechanics/CLI/conditions.md#Restrained)"
"senses": "[darkvision](/3-Mechanics/CLI/senses.md#Darkvision) 60 ft., passive Perception\
  \ 11"
"languages": "Giant, Terran"
"cr": "5"
"traits":
  - "desc": "The dust hulk can enter a hostile creature's space and stop there. It\
      \ can move through a space as narrow as 1 inch without squeezing."
    "name": "Air Form"
  - "desc": "When the dust hulk dies, it explodes in a burst of dust that fills a\
      \ 10-foot-radius sphere centered on itself. Each creature in that area must\
      \ succeed on a DC 14 Constitution saving throw or have the [blinded](/3-Mechanics/CLI/conditions.md#Blinded)\
      \ condition for 1 minute. An affected creature can repeat the saving throw at\
      \ the end of each of its turns, ending the effect on itself on a success."
    "name": "Death Burst"
"actions":
  - "desc": "The dust hulk makes three Slam attacks. It can replace one of these attacks\
      \ with Stinging Dust."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +7 to hit, reach 10 ft., one target. *Hit:* 13\
      \ (2d8 + 4) bludgeoning damage."
    "name": "Slam"
  - "desc": "One creature of the dust hulk's choice inside its space must make a DC\
      \ 14 Constitution saving throw. On a failed save, the creature takes 10 (3d6)\
      \ bludgeoning damage and has the [blinded](/3-Mechanics/CLI/conditions.md#Blinded)\
      \ condition until the end of its next turn. On a successful save, the creature\
      \ takes half as much damage only."
    "name": "Stinging Dust"
"source":
  - "BGG"
"image": "/3-Mechanics/CLI/bestiary/elemental/token/dust-hulk-bgg.webp"
```
^statblock