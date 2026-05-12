---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mff
- ttrpg-cli/monster/cr/1
- ttrpg-cli/monster/size/small
- ttrpg-cli/monster/type/fey
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Screaming Devilkin"
---
# [Screaming Devilkin](3-Mechanics/CLI/bestiary/fey/screaming-devilkin-mff.md)
*Source: Mordenkainen's Fiendish Folio p. 19*  

The ferocious screaming devilkin are bizarre fey creatures spawned by overwhelming moments of panic. Despite their diabolic appearance and name, are denizens of the Feywild. Sages believe that their appearance derives from the primal fear inspired by fiendish creatures, while bards assert that panic, being such a repulsive emotion, is embodied by an equally ugly creature.

## Screaming Terrors

A screaming devilkin sometimes arises when a creature in the Feywild is overcome with panic to the point that it screams, babbles, and otherwise loses control of its faculties. When such an event occurs, the creature's scream echoes through the Feywild. If it echoes at just the right angle between a rocky outcropping in the dead of night, the scream gains intensity and volume until it reaches a piercing crescendo. At that moment, the stone of the outcropping shatters as a small flock of screaming devilkins erupts from the earth and take to the air.

## Wicked Tormentors

As befits creatures born from a moment of panic, screaming devilkins love to spread fear and confusion across the world. They gather in small flocks, lurking along lonely forest roads and mountain passes. When their victims approach, the devilkins swoop down upon them to lash them with their long, barbed tails. Their horrid shrieking overwhelms a creature's senses, inspiring a combination of panic, sensory overload, and confusion that leaves creatures reeling. Despite their evil nature, screaming devilkins rarely attack to kill. They much prefer to leave their victims badly injured and shorn of all hope. The devilkin steal treasures, weapons, and supplies, dooming an expedition to a slow death. The devilkin fly near their victims, taunting them with the items they stole. Predators in the area learn that the devilkin's screeching is a sure sign that easy prey draws near.

## Opportunistic Alliances

A flock of screaming devilkins can appreciate vicious cruelty in other creatures. If they see signs of an evil presence in the land, such as a cruel overlord or a vicious necromancer, they may offer an alliance if the villain offers plenty of opportunities for them to engage in wanton destruction and torment. These creatures serve as horrid mascots of a sort, capering about their new master and following orders to torment those who displease their leader with glee.

```statblock
"name": "Screaming Devilkin (MFF)"
"size": "Small"
"type": "fey"
"alignment": "Lawful Evil"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "18"
"hit_dice": "4d6 + 4"
"modifier": !!int "3"
"stats":
  - !!int "4"
  - !!int "16"
  - !!int "13"
  - !!int "5"
  - !!int "8"
  - !!int "11"
"speed": "0 ft., fly 40 ft."
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 30 ft., passive\
  \ Perception 9"
"languages": "Sylvan"
"cr": "1"
"traits":
  - "desc": "Opportunity attacks against the screaming devilkin have disadvantage\
      \ while it is flying."
    "name": "Agile Flier"
  - "desc": "Any creature other than a screaming devilkin that starts its turn within\
      \ 30 feet of one or more screaming devilkins and can hear it must make a DC\
      \ 10\n\nWisdom saving throw. On a failure the creature is [incapacitated](3-Mechanics/CLI/rules/conditions.md#Incapacitated)\
      \ until the start of its next turn. On a success, the creature suffers no effect."
    "name": "Ceaseless Screaming"
  - "desc": "The screaming devilkin has disadvantage on attack rolls and all attack\
      \ rolls made against it gain advantage while the devilkin isn't flying."
    "name": "Stunted Legs"
"actions":
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one target. *Hit:* 5\
      \ (1d4 + 3) piercing damage."
    "name": "Barbed Tail"
"source":
  - "MFF"
"image": "3-Mechanics/CLI/bestiary/fey/token/screaming-devilkin-mff.webp"
```
^statblock