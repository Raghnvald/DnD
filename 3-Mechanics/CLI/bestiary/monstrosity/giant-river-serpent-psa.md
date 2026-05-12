---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/psa
- ttrpg-cli/monster/cr/11
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/monstrosity
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Giant River Serpent"
---
# [Giant River Serpent](3-Mechanics/CLI/bestiary/monstrosity/giant-river-serpent-psa.md)
*Source: Plane Shift: Amonkhet p. 38*  

The Luxa river is an abundant source of life, fertilizing the lush valley around Naktamun and providing water to humanoids and animals alike. It is also a vibrant habitat for countless creatures, including many species of birds, fish, and frogs. [Crocodiles](3-Mechanics/CLI/bestiary/beast/crocodile.md) and [hippopotamuses](3-Mechanics/CLI/bestiary/beast/hippopotamus-psa.md) can be a danger to boats and barges, but perhaps the most feared denizens of the river are the [giant serpents](3-Mechanics/CLI/bestiary/monstrosity/giant-river-serpent-psa.md) known to lurk near its bottom. When roused to anger, they can sink fishing boats by the dozens and flood the shore.

Monsters found in the river include fish such as [quippers](3-Mechanics/CLI/bestiary/beast/quipper.md), [giant frogs](3-Mechanics/CLI/bestiary/beast/giant-frog.md), and [crocodiles](3-Mechanics/CLI/bestiary/beast/crocodile.md).

River serpents range from fairly mundane specimens that resemble [giant constrictor snakes](3-Mechanics/CLI/bestiary/beast/giant-constrictor-snake.md) to more monstrous versions with the statistics of a [behir](3-Mechanics/CLI/bestiary/monstrosity/behir.md) (but without lightning immunity or lightning breath).

```statblock
"name": "Giant River Serpent (PSA)"
"size": "Huge"
"type": "monstrosity"
"alignment": "Neutral Evil"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "168"
"hit_dice": "16d12 + 64"
"modifier": !!int "3"
"stats":
  - !!int "23"
  - !!int "16"
  - !!int "18"
  - !!int "7"
  - !!int "14"
  - !!int "12"
"speed": "50 ft., climb 40 ft."
"skillsaves":
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+6"
  - "name": "[Stealth](3-Mechanics/CLI/rules/skills.md#Stealth)"
    "desc": "+7"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 90 ft., passive\
  \ Perception 16"
"languages": "Draconic"
"cr": "11"
"actions":
  - "desc": "The serpent makes two attacks: one with its bite and one to constrict."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +10 to hit, reach 10 ft., one target. *Hit:*\
      \ 22 (3d10 + 6) piercing damage."
    "name": "Bite"
  - "desc": "*Melee Weapon Attack:* +10 to hit, reach 5 ft., one Large or smaller\
      \ creature. *Hit:* 17 (2d10 + 6) bludgeoning damage plus 17 (2d10 + 6) slashing\
      \ damage. The target is [grappled](3-Mechanics/CLI/rules/conditions.md#Grappled)\
      \ (escape DC 16) if the serpent isn't already constricting a creature, and the\
      \ target is [restrained](3-Mechanics/CLI/rules/conditions.md#Restrained) until\
      \ this grapple ends."
    "name": "Constrict"
  - "desc": "The serpent makes one bite attack against a Medium or smaller target\
      \ it is grappling. If the attack hits, the target is also swallowed, and the\
      \ grapple ends. While swallowed, the target is [blinded](3-Mechanics/CLI/rules/conditions.md#Blinded)\
      \ and [restrained](3-Mechanics/CLI/rules/conditions.md#Restrained), it has total\
      \ cover against attacks and other effects outside the serpent, and it takes\
      \ 21 (6d6) acid damage at the start of each of the serpent's turns. A serpent\
      \ can have only one creature swallowed at a time.\n\nIf the serpent takes 30\
      \ damage or more on a single turn from the swallowed creature, the serpent must\
      \ succeed on a DC 14 Constitution saving throw at the end of that turn or regurgitate\
      \ the creature, which falls [prone](3-Mechanics/CLI/rules/conditions.md#Prone)\
      \ in a space within 10 feet of the serpent. If the serpent dies, a swallowed\
      \ creature is no longer [restrained](3-Mechanics/CLI/rules/conditions.md#Restrained)\
      \ by it and can escape from the corpse by using 15 feet of movement, exiting\
      \ [prone](3-Mechanics/CLI/rules/conditions.md#Prone)."
    "name": "Swallow"
"source":
  - "PSA"
"image": "3-Mechanics/CLI/bestiary/monstrosity/token/giant-river-serpent-psa.webp"
```
^statblock