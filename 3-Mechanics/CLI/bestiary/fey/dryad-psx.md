---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/psx
- ttrpg-cli/monster/cr/1
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/fey
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Dryad"
---
# [Dryad](3-Mechanics/CLI/bestiary/fey/dryad-psx.md)
*Source: Plane Shift: Ixalan p. 38*  

It is said that the only force on Ixalan not interested in finding the golden city is Ixalan itself. Dryads, as incarnations of the land and its will, prove the saying true. Their only concern is the health of the forest: when the trees and ferns are healthy, the dryads flourish. But when the vampires' dusk fog or a demon's unwholesome influence cause the jungle to wither, the dryads suffer. As a result, they are generally friendly with the River Heralds, who live in harmony with nature, and hostile to the Legion of Dusk.

The dryads otherwise have no stake in the conflict between the people of Ixalan and the invaders, but as creatures of life and growth, they hate to see any living being suffer. Thus, they have been known to tend to wounded people left in the jungle to die, sharing their own abundant life energy with those in their care.

Ixalan's dryads are identical to the [dryads](3-Mechanics/CLI/bestiary/fey/dryad.md) in the "Monster Manual".

```statblock
"name": "Dryad (PSX)"
"size": "Medium"
"type": "fey"
"alignment": "Neutral"
"ac": !!int "11"
"ac_class": "16 with [barkskin](3-Mechanics/CLI/spells/barkskin.md)"
"hp": !!int "22"
"hit_dice": "5d8"
"modifier": !!int "1"
"stats":
  - !!int "10"
  - !!int "12"
  - !!int "11"
  - !!int "14"
  - !!int "15"
  - !!int "18"
"speed": "30 ft."
"skillsaves":
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+4"
  - "name": "[Stealth](3-Mechanics/CLI/rules/skills.md#Stealth)"
    "desc": "+5"
"gear":
  - "[club](3-Mechanics/CLI/items/club.md)"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., passive\
  \ Perception 14"
"languages": "Elvish, Sylvan"
"cr": "1"
"traits":
  - "desc": "The dryad's innate spellcasting ability is Charisma (spell save DC 14).\
      \ The dryad can innately cast the following spells, requiring no material components:\n\
      \n**At will:** [druidcraft](3-Mechanics/CLI/spells/druidcraft.md)\n\n**3/day\
      \ each:** [entangle](3-Mechanics/CLI/spells/entangle.md), [goodberry](3-Mechanics/CLI/spells/goodberry.md)\n\
      \n**1/day each:** [barkskin](3-Mechanics/CLI/spells/barkskin.md), [pass without\
      \ trace](3-Mechanics/CLI/spells/pass-without-trace.md), [shillelagh](3-Mechanics/CLI/spells/shillelagh.md)"
    "name": "Innate Spellcasting"
  - "desc": "The dryad has advantage on saving throws against spells and other magical\
      \ effects."
    "name": "Magic Resistance"
  - "desc": "The dryad can communicate with beasts and plants as if they shared a\
      \ language."
    "name": "Speak with Beasts and Plants"
  - "desc": "Once on her turn, the dryad can use 10 feet of her movement to step magically\
      \ into one living tree within her reach and emerge from a second living tree\
      \ within 60 feet of the first tree, appearing in an unoccupied space within\
      \ 5 feet of the second tree. Both trees must be large or bigger."
    "name": "Tree Stride"
"actions":
  - "desc": "*Melee Weapon Attack:* +2 to hit (+6 to hit with shillelagh), reach\
      \ 5 ft., one target. *Hit:* 2 (1d4) bludgeoning damage, or 8 (1d8 + 4) bludgeoning\
      \ damage with shillelagh."
    "name": "Club"
  - "desc": "The dryad targets one humanoid or beast that she can see within 30 feet\
      \ of her. If the target can see the dryad, it must succeed on a DC 14 Wisdom\
      \ saving throw or be magically [charmed](3-Mechanics/CLI/rules/conditions.md#Charmed).\
      \ The [charmed](3-Mechanics/CLI/rules/conditions.md#Charmed) creature regards\
      \ the dryad as a trusted friend to be heeded and protected. Although the target\
      \ isn't under the dryad's control, it takes the dryad's requests or actions\
      \ in the most favorable way it can.\n\nEach time the dryad or its allies do\
      \ anything harmful to the target, it can repeat the saving throw, ending the\
      \ effect on itself on a success. Otherwise, the effect lasts 24 hours or until\
      \ the dryad dies, is on a different plane of existence from the target, or ends\
      \ the effect as a bonus action. If a target's saving throw is successful, the\
      \ target is immune to the dryad's Fey Charm for the next 24 hours.\n\nThe dryad\
      \ can have no more than one humanoid and up to three beasts [charmed](3-Mechanics/CLI/rules/conditions.md#Charmed)\
      \ at a time."
    "name": "Fey Charm"
"source":
  - "PSX"
"image": "3-Mechanics/CLI/bestiary/fey/token/dryad-psx.webp"
```
^statblock