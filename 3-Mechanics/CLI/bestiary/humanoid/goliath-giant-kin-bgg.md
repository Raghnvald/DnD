---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/bgg
- ttrpg-cli/monster/cr/3
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Goliath Giant-Kin"
---
# [Goliath Giant-Kin](3-Mechanics/CLI/bestiary/humanoid/goliath-giant-kin-bgg.md)
*Source: Bigby Presents: Glory of the Giants p. 155*  

Goliaths are Humanoids distantly related to giants. Infused with the supernatural essence of their ancestors' mountainous home, goliaths have the strength and fortitude to garner a giant's respect. Communities of goliaths who live in close relationship with giants emulate them and are recognized by the giants as kin. These goliath giant-kin often act as liaisons between giant clans and other Humanoids.

Though they rarely stand more than 8 feet tall, goliaths can hold their own in contests of strength with ogres. Goliath giant-kin can also channel the magic of their giant relatives into mighty melee attacks.

Though they are not part of the ordning, goliath giant-kin often revere the divine ancestors of the giants, with a particular affinity for Annam's daughters: Diancastra, Hiatea, and Iallanis. They also tend to extol the same virtues as the giants they live alongside, so goliath giant-kin dwelling near frost giants boast of their might, while those dwelling with stone giants cherish artistry.

> [!quote] A quote from Diancastra  
> 
> Few things bring me as much delight as goliaths who strive to celebrate their connection to the magnificent history of giants. When they sing me hymns, their voices are sweetest.


```statblock
"name": "Goliath Giant-Kin (BGG)"
"size": "Medium"
"type": "humanoid"
"alignment": "Any alignment"
"ac": !!int "18"
"ac_class": "half plate, shield"
"hp": !!int "67"
"hit_dice": "9d8 + 27"
"modifier": !!int "1"
"stats":
  - !!int "18"
  - !!int "13"
  - !!int "16"
  - !!int "10"
  - !!int "12"
  - !!int "12"
"speed": "30 ft."
"skillsaves":
  - "name": "Athletics"
    "desc": "+6"
  - "name": "Perception"
    "desc": "+3"
  - "name": "Survival"
    "desc": "+3"
"damage_resistances": "cold"
"gear":
  - "spear"
"senses": "passive Perception 13"
"languages": "Common, Giant"
"cr": "3"
"actions":
  - "desc": "The goliath makes two Spear attacks."
    "name": "Multiattack"
  - "desc": "*Melee  or Ranged Weapon Attack:* +6 to hit, reach 5 ft. or range 20/60\
      \ ft., one target. *Hit:* 7 (1d6 + 4) piercing damage, or 8 (1d8 + 4) piercing\
      \ damage if used with two hands to make a melee attack."
    "name": "Spear"
"bonus_actions":
  - "desc": "Until the end of its turn, the goliath's melee attacks each deal an extra\
      \ 7 (2d6) damage of a type determined by the goliath's giant community: cold\
      \ (frost giant), fire (fire giant), force (stone giant), lightning (storm giant),\
      \ piercing (hill giant), or thunder (cloud giant)."
    "name": "Giant's Strikes (Recharge 5-6)"
"source":
  - "BGG"
"image": "3-Mechanics/CLI/bestiary/humanoid/token/goliath-giant-kin-bgg.webp"
```
^statblock