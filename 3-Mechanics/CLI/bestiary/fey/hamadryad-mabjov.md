---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mabjov
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/fey
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Hamadryad"
---
# [Hamadryad](3-Mechanics/CLI/bestiary/fey/hamadryad-mabjov.md)
*Source: Minsc and Boo's Journal of Villainy p. 143*  

> [!quote] A quote from Hamadryad  
> 
> I cannot drink the water. My roots grow black and rotten. I cannot drink the water. My leaves wither and die. I cannot drink...

> [!quote] A quote from Volo  
> 
> It is a sad thing when one of nature's most beautiful fey is corrupted into a hamadryad. Be careful about feeling too much sympathy for them, for they are fearsome when someone trespasses into their territory.

These fey come into being when the home tree of a dryad is destroyed or becomes corrupted by foul magic. If the dryad isn't killed she slowly wastes away and over the course of several months becomes a hamadryad. Hamadryads are mad creatures that seek vengeance against any non-fey that wanders into the deep places of the wood that is their home.

## Beauty Lost

Hamadryads do not retain the beauty that they had before whatever tragedy befell them. Their mouths have vanished and their laughter is forever gone. The beautiful feminine forms dryads are famed for have become twisted. Their emerald skin is grey and sickly and their very touch is corrupt and poisonous.

## Madness

Hamadryads rarely behave in a manner that seems rational. They might viciously attack an intruder and then vanish, only to return later when their mood changes. Sometimes they might help a group of adventurers against evil creatures only to turn on the adventurers once their mutual foe is vanquished.

```statblock
"name": "Hamadryad (MaBJoV)"
"size": "Medium"
"type": "fey"
"alignment": "Chaotic Neutral"
"ac": !!int "13"
"ac_class": "16 with [barkskin](3-Mechanics/CLI/spells/barkskin.md)"
"hp": !!int "32"
"hit_dice": "5d8 + 10"
"modifier": !!int "3"
"stats":
  - !!int "10"
  - !!int "16"
  - !!int "14"
  - !!int "14"
  - !!int "10"
  - !!int "15"
"speed": "30 ft."
"skillsaves":
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+2"
  - "name": "[Stealth](3-Mechanics/CLI/rules/skills.md#Stealth)"
    "desc": "+6"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 60ft., passive\
  \ Perception 12"
"languages": "Sylvan"
"cr": "2"
"traits":
  - "desc": "The hamadryad has advantage on saving throws against spells and other\
      \ magical effects."
    "name": "Magic Resistance"
  - "desc": "The hamadryad can communicate with Beasts and Plants as if they shared\
      \ a language."
    "name": "Speak with Beasts and Plants"
  - "desc": "Once on her turn, the hamadryad can use 10 feet of her movement to step\
      \ magically into one living tree within her reach and emerge from a second living\
      \ tree within 60 feet of the first tree, appearing in an unoccupied space within\
      \ 5 feet of the second tree. Both trees must be Large in size or bigger."
    "name": "Tree Stride"
"actions":
  - "desc": "The hamadryad makes two Claw attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +5 to hit, range 5 ft., one target. *Hit:* 5\
      \ (1d4 + 3) plus 10 (3d6) poison damage."
    "name": "Claw"
  - "desc": "The hamadryad casts one of the following spells, requiring no material\
      \ components and using Charisma as the spellcasting ability (spell save DC 12):\n\
      \n**2/day:** [entangle](3-Mechanics/CLI/spells/entangle.md)\n\n**1/day each:**\
      \ [barkskin](3-Mechanics/CLI/spells/barkskin.md), [grasping vine](3-Mechanics/CLI/spells/grasping-vine.md),\
      \ [pass without trace](3-Mechanics/CLI/spells/pass-without-trace.md)"
    "name": "Spellcasting"
"source":
  - "MaBJoV"
"image": "3-Mechanics/CLI/bestiary/fey/token/hamadryad-mabjov.webp"
```
^statblock