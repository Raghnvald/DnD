---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mot
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/monstrosity
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Two-Headed Cerberus"
---
# [Two-Headed Cerberus](3-Mechanics/CLI/bestiary/monstrosity/two-headed-cerberus-mot.md)
*Source: Mythic Odysseys of Theros p. 215*  

Thought to be a lesser breed of cerberi that have interbred with mortal wolves, two-headed cerberi typically roam the mortal side of the Tartyx River. There they generally ignore—or only modestly menace—the souls of the dead. Such isn't the case for mortals, though, and they eagerly set upon those who tread too close to the Underworld's borders.

Feared by the living and the dead, cerberi patrol both banks of the Tartyx River. These multiheaded hounds of the Underworld breathe gouts of molten rock that sear and imprison those who trespass upon the borders of life and death. Most cerberi have a boundless hunger for fresh meat, especially the flesh of humanoids. Villains have been known to exploit that hunger by luring cerberi away from the river and setting them loose on mortal settlements.

```statblock
"name": "Two-Headed Cerberus (MOT)"
"size": "Medium"
"type": "monstrosity"
"alignment": "Lawful Evil"
"ac": !!int "12"
"hp": !!int "39"
"hit_dice": "6d8 + 12"
"modifier": !!int "2"
"stats":
  - !!int "15"
  - !!int "14"
  - !!int "14"
  - !!int "3"
  - !!int "13"
  - !!int "6"
"speed": "40 ft."
"skillsaves":
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+5"
  - "name": "[Stealth](3-Mechanics/CLI/rules/skills.md#Stealth)"
    "desc": "+4"
"damage_immunities": "fire, necrotic"
"condition_immunities": "[blinded](3-Mechanics/CLI/rules/conditions.md#Blinded), [charmed](3-Mechanics/CLI/rules/conditions.md#Charmed),\
  \ [deafened](3-Mechanics/CLI/rules/conditions.md#Deafened), [exhaustion](3-Mechanics/CLI/rules/conditions.md#Exhaustion),\
  \ [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened), [stunned](3-Mechanics/CLI/rules/conditions.md#Stunned)"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., passive\
  \ Perception 15"
"languages": ""
"cr": "2"
"traits":
  - "desc": "As a bonus action, the cerberus can move up to its speed toward a hostile\
      \ creature that it can see."
    "name": "Aggressive"
  - "desc": "The cerberus can't be [surprised](3-Mechanics/CLI/rules/conditions.md#Surprised),\
      \ and it has advantage on saving throws against being knocked [unconscious](3-Mechanics/CLI/rules/conditions.md#Unconscious)."
    "name": "Multiheaded"
  - "desc": "The cerberus has advantage on an attack roll against a creature if at\
      \ least one of the cerberus's allies is within 5 feet of the creature and the\
      \ ally isn't [incapacitated](3-Mechanics/CLI/rules/conditions.md#Incapacitated)."
    "name": "Pack Tactics"
"actions":
  - "desc": "The cerberus makes two bite attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one target. *Hit:* 5\
      \ (1d6 + 2) piercing damage plus 2 (1d4) fire damage."
    "name": "Bite"
  - "desc": "The cerberus exhales a 15-foot cone of molten rock. Each creature in\
      \ the cone must make a DC 12 Dexterity saving throw, taking 10 (3d6) fire\
      \ damage on a failed save, or half as much damage on a successful one. On a\
      \ failed save, a creature is also [restrained](3-Mechanics/CLI/rules/conditions.md#Restrained)\
      \ by the hardening rock. A creature can make a DC 12 Strength ([Athletics](3-Mechanics/CLI/rules/skills.md#Athletics))\
      \ check as an action, freeing itself or a creature within reach from the rock\
      \ on a success. The rock has AC 17 and 10 hit points, and it is immune to fire,\
      \ poison, and psychic damage."
    "name": "Breath Weapon (Recharge 5-6)"
"source":
  - "MOT"
"image": "3-Mechanics/CLI/bestiary/monstrosity/token/two-headed-cerberus-mot.webp"
```
^statblock