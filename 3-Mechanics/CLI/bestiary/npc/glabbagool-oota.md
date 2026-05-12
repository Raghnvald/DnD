---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/oota
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/ooze
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Glabbagool"
---
# [Glabbagool](3-Mechanics/CLI/bestiary/npc/glabbagool-oota.md)
*Source: Out of the Abyss p. 35*  

Juiblex's arrival in the Underdark has granted Glabbagool sentience and awareness. The ooze is genuinely curious about other creatures and wants to learn more about the world. It defends itself if attacked, but doesn't otherwise try to harm the characters, instead asking who they are, where they come from, and why they have come to the temple.

```statblock
"name": "Glabbagool (OotA)"
"size": "Large"
"type": "ooze"
"alignment": "Unaligned"
"ac": !!int "6"
"hp": !!int "84"
"hit_dice": "8d10 + 40"
"modifier": !!int "-4"
"stats":
  - !!int "14"
  - !!int "3"
  - !!int "20"
  - !!int "10"
  - !!int "6"
  - !!int "1"
"speed": "15 ft."
"condition_immunities": "[blinded](3-Mechanics/CLI/rules/conditions.md#Blinded), [charmed](3-Mechanics/CLI/rules/conditions.md#Charmed),\
  \ [deafened](3-Mechanics/CLI/rules/conditions.md#Deafened), [exhaustion](3-Mechanics/CLI/rules/conditions.md#Exhaustion),\
  \ [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened), [prone](3-Mechanics/CLI/rules/conditions.md#Prone)"
"senses": "[blindsight](3-Mechanics/CLI/rules/senses.md#Blindsight) 60 ft. (blind\
  \ beyond this radius), passive Perception 8"
"languages": "telepathy 60 ft."
"cr": "2"
"traits":
  - "desc": "Glabbagool takes up its entire space. Other creatures can enter the space,\
      \ but a creature that does so is subjected to Glabbagool's Engulf and has disadvantage\
      \ on the saving throw.\n\nCreatures inside Glabbagool can be seen but have total\
      \ cover.\n\nA creature within 5 feet of Glabbagool can take an action to pull\
      \ a creature or object out of Glabbagool. Doing so requires a successful DC\
      \ 12 Strength check, and the creature making the attempt takes 10 (3d6) acid\
      \ damage.\n\nGlabbagool can hold only one Large creature or up to four Medium\
      \ or smaller creatures inside it at a time."
    "name": "Ooze Cube"
  - "desc": "Even when Glabbagool is in plain sight, it takes a successful DC 15 Wisdom\
      \ ([Perception](3-Mechanics/CLI/rules/skills.md#Perception)) check to spot a\
      \ cube that has neither moved nor attacked. A creature that tries to enter Glabbagool's\
      \ space while unaware of Glabbagool is [surprised](3-Mechanics/CLI/rules/conditions.md#Surprised)\
      \ by Glabbagool."
    "name": "Transparent"
"actions":
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one creature. *Hit:*\
      \ 10 (3d6) acid damage."
    "name": "Pseudopod"
  - "desc": "Glabbagool moves up to its speed. While doing so, it can enter Large\
      \ or smaller creatures' spaces. Whenever Glabbagool enters a creature's space,\
      \ the creature must make a DC 12 Dexterity saving throw.\n\nOn a successful\
      \ save, the creature can choose to be pushed 5 feet back or to the side of Glabbagool.\
      \ A creature that chooses not to be pushed suffers the consequences of a failed\
      \ saving throw.\n\nOn a failed save, Glabbagool enters the creature's space,\
      \ and the creature takes 10 (3d6) acid damage and is engulfed. The engulfed\
      \ creature can't breathe, is [restrained](3-Mechanics/CLI/rules/conditions.md#Restrained),\
      \ and takes 21 (6d6) acid damage at the start of each of Glabbagool's turns.\
      \ When Glabbagool moves, the engulfed creature moves with it.\n\nAn engulfed\
      \ creature can try to escape by taking an action to make a DC 12 Strength check.\
      \ On a success, the creature escapes and enters a space of its choice within\
      \ 5 feet of Glabbagool."
    "name": "Engulf"
"source":
  - "OotA"
"image": "3-Mechanics/CLI/bestiary/npc/token/glabbagool-oota.webp"
```
^statblock