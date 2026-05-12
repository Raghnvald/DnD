---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mcv4ec
- ttrpg-cli/monster/cr/3
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/giant/druid
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Ogre Chitterlord"
---
# [Ogre Chitterlord](3-Mechanics/CLI/bestiary/giant/ogre-chitterlord-mcv4ec.md)
*Source: Monstrous Compendium Volume 4: Eldraine Creatures*  

When ogres first moved into the wilds of Eldraine, they encountered all manner of unfamiliar creatures: spellcasting witches, tricksy faeries, and talking beasts. Over generations, these ogres adapted to their new environs, passing down a spellcasting tradition of their own to help their kin wreak havoc in the wilds and beyond.

An ogre chitterlord exercises control over the rats that infest Dunbarrow and countless other regions in the wilds of Eldraine. When ogres venture from the wilds to raid nearby settlements, an ogre chitterlord often leads the way, calling rats from the alleys and sewers to harry townsfolk from within the city while the ogres lay siege to the outer walls. Should their rodent allies fail them, chitterlords can also turn the tide of any battle with their prodigious strength and druidic magic.

```statblock
"name": "Ogre Chitterlord (MCV4EC)"
"size": "Large"
"type": "giant"
"subtype": "druid"
"alignment": "Any alignment"
"ac": !!int "12"
"ac_class": "[hide armor](3-Mechanics/CLI/items/hide-armor.md)"
"hp": !!int "52"
"hit_dice": "7d10 + 14"
"modifier": !!int "0"
"stats":
  - !!int "19"
  - !!int "10"
  - !!int "15"
  - !!int "5"
  - !!int "12"
  - !!int "9"
"speed": "40 ft."
"saves":
  - "wisdom": !!int "3"
"skillsaves":
  - "name": "[Animal Handling](3-Mechanics/CLI/rules/skills.md#Animal%20Handling)"
    "desc": "+3"
  - "name": "[Nature](3-Mechanics/CLI/rules/skills.md#Nature)"
    "desc": "+1"
"gear":
  - "[club](3-Mechanics/CLI/items/club.md)"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., passive\
  \ Perception 11"
"languages": "Common, Giant"
"cr": "3"
"traits":
  - "desc": "The ogre can verbally communicate simple concepts to ordinary rats and\
      \ giant rats."
    "name": "Speak with Rats"
"actions":
  - "desc": "The ogre makes two Club attacks, two Rat-Tail Whip attacks, or one of\
      \ each."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +6 to hit, reach 5 ft., one target. *Hit:* 15\
      \ (2d10 + 4) bludgeoning damage."
    "name": "Club"
  - "desc": "*Melee Weapon Attack:* +6 to hit, reach 10 ft., one target. *Hit:*\
      \ 13 (2d8 + 4) slashing damage, and if the target is Large or smaller, it\
      \ is pulled 5 feet toward the ogre."
    "name": "Rat-Tail Whip"
  - "desc": "The ogre casts one of the following spells, requiring no material components\
      \ and using Wisdom as the spellcasting ability (spell save DC 11):\n\n**At will:**\
      \ [beast sense](3-Mechanics/CLI/spells/beast-sense.md) (rats only), [druidcraft](3-Mechanics/CLI/spells/druidcraft.md),\
      \ [entangle](3-Mechanics/CLI/spells/entangle.md)\n\n**1/day each:** [animal\
      \ messenger](3-Mechanics/CLI/spells/animal-messenger.md) (rats only), [stinking\
      \ cloud](3-Mechanics/CLI/spells/stinking-cloud.md)"
    "name": "Spellcasting"
"bonus_actions":
  - "desc": "The ogre magically calls 1d4 giant rats. Each rat appears in an unoccupied\
      \ space within 30 feet of the ogre that the ogre can see. The rats act as the\
      \ ogre's allies, obey its spoken commands, and take their turns immediately\
      \ after the ogre's turn on the same initiative count. The rats remain for 1\
      \ hour, until the ogre dies, or until the ogre dismisses them as a bonus action."
    "name": "Call Rats (1/Day)"
"source":
  - "MCV4EC"
"image": "3-Mechanics/CLI/bestiary/giant/token/ogre-chitterlord-mcv4ec.webp"
```
^statblock