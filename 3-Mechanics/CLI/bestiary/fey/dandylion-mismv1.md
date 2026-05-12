---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mismv1
- ttrpg-cli/monster/cr/6
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/fey
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Dandylion"
---
# [Dandylion](3-Mechanics/CLI/bestiary/fey/dandylion-mismv1.md)
*Source: Misplaced Monsters: Volume 1 p. 6*  

> [!note]
> Created by Jones D.-D.

Dandylions are herbivorous farmers who cultivate beautiful gardens of flowers and fields of crops in the Feywild. If treated with respect, dandylions are glad to share their wealth of knowledge about farming with those who show interest in the subject. They give great gardening advice, and their fruits and vegetables are healthy and delicious. Some of their crops also have magical properties, making them valuable as potion ingredients and spell components. Dandylions protect their farms ferociously, and anyone who tramples on or steals from a dandylion's bounty is likely to incur the creature's fury. The surest way to entice a dandylion to give up some of its beloved produce or flowers is to flatter it.

A dandylion has soft green fur woven with small leaves. A small, fluffy seed head at the end of the dandylion's tail contains seed pods. These seed pods enrich soil, giving rise to healthy plants and bountiful harvests. Often, dandylions weave necklaces with petals from their flower gardens and brag about the fertility of their soil. Dandylions love to boast about the fullness of their sunny yellow manes.

```statblock
"name": "Dandylion (MisMV1)"
"size": "Large"
"type": "fey"
"alignment": "typically  Chaotic Neutral"
"ac": !!int "14"
"hp": !!int "90"
"hit_dice": "12d10 + 24"
"modifier": !!int "4"
"stats":
  - !!int "22"
  - !!int "19"
  - !!int "14"
  - !!int "16"
  - !!int "17"
  - !!int "18"
"speed": "50 ft."
"saves":
  - "strength": !!int "9"
  - "charisma": !!int "7"
"skillsaves":
  - "name": "[Nature](3-Mechanics/CLI/rules/skills.md#Nature)"
    "desc": "+9"
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+6"
  - "name": "[Survival](3-Mechanics/CLI/rules/skills.md#Survival)"
    "desc": "+6"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., passive\
  \ Perception 16"
"languages": "Common, Sylvan"
"cr": "6"
"traits":
  - "desc": "The dandylion has advantage on saving throws against spells and other\
      \ magical effects."
    "name": "Magic Resistance"
  - "desc": "The dandylion has advantage on an attack roll against a creature if at\
      \ least one of the dandylion's allies is within 5 feet of the creature and the\
      \ ally doesn't have the [incapacitated](3-Mechanics/CLI/rules/conditions.md#Incapacitated)\
      \ condition."
    "name": "Pack Tactics"
"actions":
  - "desc": "The dandylion makes one Bite attack and one Claws attack."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +9 to hit, reach 5 ft., one target. *Hit:* 13\
      \ (2d6 + 6) piercing damage."
    "name": "Bite"
  - "desc": "*Melee Weapon Attack:* +9 to hit, reach 5 ft., one target. *Hit:* 20\
      \ (4d6 + 6) slashing damage. If the dandylion moved at least 20 feet straight\
      \ toward the target immediately before the hit, the target must succeed on a\
      \ DC 17 Strength saving throw or have the [prone](3-Mechanics/CLI/rules/conditions.md#Prone)\
      \ condition. If the target has the [prone](3-Mechanics/CLI/rules/conditions.md#Prone)\
      \ condition, the dandylion can make one Bite attack against it as a bonus action."
    "name": "Claws"
  - "desc": "The dandylion releases a burst of seedpods from its tail, filling a 10-foot-radius\
      \ sphere centered on itself. Each creature of the dandylion's choice in the\
      \ sphere can immediately end one of the following conditions on itself (creature's\
      \ choice): [blinded](3-Mechanics/CLI/rules/conditions.md#Blinded), [deafened](3-Mechanics/CLI/rules/conditions.md#Deafened),\
      \ [paralyzed](3-Mechanics/CLI/rules/conditions.md#Paralyzed), or [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned).\
      \ In addition, all soil in the sphere's area is enriched, restoring withered\
      \ vegetation in the area to full health and causing all crops in the area to\
      \ produce twice the normal harvest for the next year."
    "name": "Rejuvenating Seedpods (2/Day)"
  - "desc": "The dandylion casts one of the following spells, requiring no material\
      \ components and using Charisma as the spellcasting ability (spell save DC 15):\n\
      \n**At will:** [druidcraft](3-Mechanics/CLI/spells/druidcraft.md), [guidance](3-Mechanics/CLI/spells/guidance.md),\
      \ [purify food and drink](3-Mechanics/CLI/spells/purify-food-and-drink.md)\n\
      \n**2/day each:** [entangle](3-Mechanics/CLI/spells/entangle.md), [goodberry](3-Mechanics/CLI/spells/goodberry.md)\n\
      \n**1/day:** [speak with plants](3-Mechanics/CLI/spells/speak-with-plants.md)"
    "name": "Spellcasting"
"reactions":
  - "desc": "When a creature within 60 feet of the dandylion hits it with an attack\
      \ roll, the dandylion can unleash a furious roar. The creature that triggered\
      \ this reaction must succeed on a DC 15 Wisdom saving throw or have the [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened)\
      \ condition until the end of the dandylion's next turn."
    "name": "Roar of Pride"
"source":
  - "MisMV1"
"image": "3-Mechanics/CLI/bestiary/fey/token/dandylion-mismv1.webp"
```
^statblock