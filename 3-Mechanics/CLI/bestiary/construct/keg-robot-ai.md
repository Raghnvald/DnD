---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/ai
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/construct
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Keg Robot"
---
# [Keg Robot](3-Mechanics/CLI/bestiary/construct/keg-robot-ai.md)
*Source: Acquisitions Incorporated p. 212*  

> [!quote]  
> 
> This beer is delicious. But did the spigot really have to be placed in that spot?

A keg robot is a stout wood-and-metal construct, vaguely reminiscent of a dwarf wearing a horned helm and possessing a barrel for a body. These constructs are another achievement of the Heuristic Arcane Research and Development (HARD) department of Acquisitions Incorporated. These devices have a number of practical purposes, including the ability to be filled with a variety of substances of use to an adventuring party. Specific models are nominally named for their primary function, including "ambulatory fermenter," "mobile alchemical dispensary," and so forth. But their prominent use as portable beer dispensers has placed the name "keg robot" firmly into public consciousness.

A keg robot can hold up to three different kinds of liquid in its body cavity, from water and other potables to alchemical substances and lamp oil. Its individual storage compartments can leak, providing drinkable liquids with a unique but mostly safe flavor. These constructs have a rudimentary intellect that allows them to operate independently and discern friend from foe-and which sometimes causes them to operate with a crass sense of humor that has never been fully explained.

```statblock
"name": "Keg Robot (AI)"
"size": "Medium"
"type": "construct"
"alignment": "Unaligned"
"ac": !!int "14"
"ac_class": "natural armor"
"hp": !!int "39"
"hit_dice": "6d8 + 12"
"modifier": !!int "3"
"stats":
  - !!int "16"
  - !!int "16"
  - !!int "15"
  - !!int "6"
  - !!int "8"
  - !!int "5"
"speed": "30 ft."
"skillsaves":
  - "name": "Perception"
    "desc": "+1"
"damage_resistances": "bludgeoning, piercing, slashing from nonmagical attacks"
"damage_immunities": "poison, psychic"
"condition_immunities": "charmed, exhaustion, frightened, paralyzed, petrified, poisoned"
"senses": "darkvision 60 ft., passive Perception 11"
"languages": "understands Common but can't speak"
"cr": "2"
"traits":
  - "desc": "A keg robot can hold up to three types of liquid payload totaling 12\
      \ gallons within its hollow, barrel-shaped body. A full keg robot can make one\
      \ liquid attack per gallon before the liquid must be refilled. Filling a keg\
      \ robot takes 2 rounds per gallon. Differing payloads can alter the keg robot's\
      \ attacks from those presented here."
    "name": "Customizable Storage"
"actions":
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one target. *Hit:* 7\
      \ (1d8 + 3) bludgeoning damage."
    "name": "Fist"
  - "desc": "*Ranged Weapon Attack:* +5 to hit, range 20/40 ft., one target. *Hit:*\
      \ 7 (1d8 + 3) acid damage."
    "name": "Acid Squirt"
  - "desc": "The keg robot spews an unnaturally potent beer in a 15-foot cone or in\
      \ a 30-foot line that is 5 feet wide. Each creature in the area must succeed\
      \ on a DC 13 Constitution saving throw or be poisoned. While poisoned in this\
      \ way, a creature has its speed halved by exposure to the potent brew. An affected\
      \ creature can repeat the saving throw at the end of each of its turns, ending\
      \ the effect on itself on a success.\n\nAdditionally, the beer shower extinguishes\
      \ any fires or open flames in its area."
    "name": "Beer Shower"
  - "desc": "The keg robot sprays hot oil in a 15-foot cone or in a 30-foot line that\
      \ is 5 feet wide. Each creature in the area must make a DC 13 Dexterity saving\
      \ throw. On a failed save, a creature takes 7 (1d8 + 3) fire damage and falls\
      \ prone. On a successful save, a creature takes half as much damage and doesn't\
      \ fall prone.\n\nAny creature affected by the hot oil spray that takes fire\
      \ damage before the oil dries (after 1 minute) takes an additional 3 (1d6)\
      \ fire damage, and the oil burns away.\n\nIf the oil that remains in the area\
      \ of the spray is lit, it burns for 1d4 rounds and deals 3 (1d6) fire damage\
      \ to any creature that enters the area for the first time on a turn or ends\
      \ its turn there."
    "name": "Hot Oil Spray (Recharge 5-6)"
"source":
  - "AI"
"image": "3-Mechanics/CLI/bestiary/construct/token/keg-robot-ai.webp"
```
^statblock