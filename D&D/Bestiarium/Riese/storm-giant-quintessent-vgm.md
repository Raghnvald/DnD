---
obsidianUIMode: preview
cssclasses:
  - json5e-monster
tags:
  - Quelle/5e/vgm
  - Monster/HG/16
  - Monster/Habitat/arctic
  - Monster/Habitat/coastal
  - Monster/Habitat/desert
  - Monster/Habitat/mountain
  - Monster/Habitat/underwater
  - Monster/Größe/Riesig
  - Monster/Typ/giant/storm-giant
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Storm Giant Quintessent
---
# [Storm Giant Quintessent](3-Mechanics\CLI\bestiary\giant/storm-giant-quintessent-vgm.md)
*Source: Volo's Guide to Monsters p. 151, Ghosts of Saltmarsh*  

To forestall the inevitable, some storm giants approaching the end of their natural life spans seek an escape from death. They plumb the depths of their powerful connection to the elements and disperse themselves into nature, literally transforming into semiconscious storms. The blizzard that rages unendingly around a mountain peak, the vortex that swirls around a remote island, or the thunderstorm that howls ceaselessly up and down a rugged coastline could, in fact, be the undying form of a storm giant clinging to existence.

## Elemental Weapons

A storm giant quintessent sheds its armor and weapons, but gains the power to form makeshift weapons out of thin air. When the giant has no further use of them, or when the giant dies, its elemental weapons disappear.

## Forsaken Form

A storm giant quintessent can revert to its true giant form on a whim. The change is temporary but can be maintained long enough for the giant to communicate with a mortal, carry out a short task, or defend its home against aggressors.

> [!quote] A quote from Elminster  
> 
> Zhents claim the Black Road the safest path across the desert of Anauroch, but there's a stretch that passes near the sand-swallowed ruins of a once-great arch–a portal built by giants, some say. a sandstorm rages all around it, and in the storm some have seen a face: a giant scowling visage.

## A Quintessent's Lair

A storm giant quintessent has no need for castles or dungeon lairs. Its lair is usually a secluded region or prominent geographic feature, such as a mountain peak, a great waterfall, a remote island, a fog-shrouded loch, a beautiful coral reef, or a windswept desert bluff. As befits the environment, the storm in which the giant lives could be a blizzard, a typhoon, a thunderstorm, or a sandstorm.

```statblock
"name": "Storm Giant Quintessent (VGM)"
"size": "Huge"
"type": "giant"
"subtype": "storm giant"
"alignment": "Chaotic Good"
"ac": !!int "12"
"hp": !!int "230"
"hit_dice": "20d12 + 100"
"modifier": !!int "2"
"stats":
  - !!int "29"
  - !!int "14"
  - !!int "20"
  - !!int "17"
  - !!int "20"
  - !!int "19"
"speed": "50 ft., fly 50 ft. (hover), swim 50 ft."
"saves":
  - "strength": !!int "14"
  - "constitution": !!int "10"
  - "wisdom": !!int "10"
  - "charisma": !!int "9"
"skillsaves":
  - "name": "Arcana"
    "desc": "+8"
  - "name": "History"
    "desc": "+8"
"damage_resistances": "cold; bludgeoning, piercing, slashing from nonmagical attacks"
"damage_immunities": "lightning, thunder"
"senses": "truesight 60 ft., passive Perception 20"
"languages": "Common, Giant"
"cr": "16"
"traits":
  - "desc": "The giant can breathe air and water."
    "name": "Amphibious"
"actions":
  - "desc": "The giant makes two Lightning Sword attacks or uses Wind Javelin twice."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +14 to hit, reach 15 ft., one target. *Hit:* 40\
      \ (9d6 + 9) lightning damage."
    "name": "Lightning Sword"
  - "desc": "The giant coalesces wind into a javelin-like form and hurls it at a creature\
      \ it can see within 600 feet of it. The javelin is considered a magic weapon\
      \ and deals 19 (3d6 + 9) piercing damage to the target, striking unerringly.\
      \ The javelin disappears after it hits."
    "name": "Windjavelin"
"legendary_description": "Legendary Action Uses: 3. Immediately after another creature's\
  \ turn, the storm giant quintessent can expend a use to take one of the following\
  \ actions. The storm giant quintessent regains all expended uses at the start of\
  \ each of its turns."
"legendary_actions":
  - "desc": "The giant targets a creature it can see within 60 feet of it and creates\
      \ a magical gust of wind around it. The target must succeed on a DC 18 Strength\
      \ saving throw or be pushed up to 20 feet in any horizontal direction the giant\
      \ chooses."
    "name": "Gust"
  - "desc": "The giant hurls a thunderbolt at a creature it can see within 600 feet\
      \ of it. The target must make a DC 18 Dexterity saving throw, taking 22 (4d10)\
      \ thunder damage on a failed save, or half as much damage on a successful one."
    "name": "Thunderbolt (2 Actions)"
  - "desc": "The giant vanishes, dispersing itself into the storm surrounding its\
      \ lair. The giant can end this effect at the start of any of its turns, becoming\
      \ a giant once more and appearing in any location it chooses within its lair.\
      \ While dispersed, the giant can't take any actions other than lair actions,\
      \ and it can't be targeted by attacks, spells, or other effects. The giant can't\
      \ use this ability outside its lair, nor can it use this ability if another\
      \ creature is using a control weather spell or similar magic to quell the storm."
    "name": "One with the Storm (3 Actions)"
"source":
  - "VGM"
  - "GoS"
"image": "/3-Mechanics/CLI/bestiary/giant/token/storm-giant-quintessent-vgm.webp"
```
^statblock

## Environment

underwater, mountain, desert, coastal, arctic