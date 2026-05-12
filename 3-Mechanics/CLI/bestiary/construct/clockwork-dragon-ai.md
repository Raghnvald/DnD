---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/ai
- ttrpg-cli/monster/cr/1
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/construct
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Clockwork Dragon"
---
# [Clockwork Dragon](3-Mechanics/CLI/bestiary/construct/clockwork-dragon-ai.md)
*Source: Acquisitions Incorporated p. 209*  

These intricately crafted constructs are typically made to reflect the forms of the metallic dragons. Plated in brass, bronze, copper, or faux gold and silver, they are often taken for fine draconic statues at first glance. A clockwork dragon makes a formidable guardian or defender, with its advanced intellect allowing it to be programmed with a wide range of orders, as well as being capable of wholly independent reactions to potential threats.

Though most clockwork dragons have a breath weapon that deals fire damage, some might be constructed to deal acid, cold, or lightning damage, depending on their makers' whims.

```statblock
"name": "Clockwork Dragon (AI)"
"size": "Medium"
"type": "construct"
"alignment": "Neutral"
"ac": !!int "16"
"ac_class": "natural armor"
"hp": !!int "22"
"hit_dice": "4d8 + 4"
"modifier": !!int "0"
"stats":
  - !!int "14"
  - !!int "10"
  - !!int "12"
  - !!int "10"
  - !!int "11"
  - !!int "13"
"speed": "30 ft., fly 60 ft."
"skillsaves":
  - "name": "Acrobatics"
    "desc": "+2"
  - "name": "Perception"
    "desc": "+4"
"damage_immunities": "poison, psychic"
"condition_immunities": "blinded, charmed, deafened, exhaustion, frightened, paralyzed,\
  \ petrified, poisoned"
"senses": "blindsight 60 ft., darkvision 60 ft., passive Perception 14"
"languages": "Common, Draconic"
"cr": "1"
"traits":
  - "desc": "While the clockwork dragon remains motionless, it is indistinguishable\
      \ from a metal statue."
    "name": "False Appearance"
"actions":
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one target. *Hit:* 7\
      \ (1d10 + 2) piercing damage."
    "name": "Bite"
  - "desc": "The clockwork dragon exhales fire in a 15-foot cone. Each creature in\
      \ that area must make a DC 11 Dexterity saving throw, taking 14 (4d6) fire\
      \ damage on a failed save, or half as much damage on a successful one."
    "name": "Fire Breath (Recharge 5-6)"
"source":
  - "AI"
"image": "3-Mechanics/CLI/bestiary/construct/token/clockwork-dragon-ai.webp"
```
^statblock