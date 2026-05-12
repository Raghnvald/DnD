---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mpp
- ttrpg-cli/monster/cr/8
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/celestial
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Warden Archon"
---
# [Warden Archon](3-Mechanics/CLI/bestiary/celestial/warden-archon-mpp.md)
*Source: Morte's Planar Parade p. 18*  

Warden archons are vigilant, ursine guardians of portals and paths connected to goodly realms. They have powerfully built, bipedal bodies with the heads of great bears and eyes like pools of silvery light. When warden archons speak, glimmering radiance shines from within their mouths, punctuating their deep, resonant voices.

A warden archon knows when a creature uses a portal the archon is tasked to guard, and it moves swiftly to interrogate any who cross that planar boundary. If an invader enters the archon's plane, the warden strikes with claw and tooth, using its powerful bite to magically mark the intruder, which the archon pursues relentlessly.

## Archons

Archons are denizens of the Seven Heavens of Mount Celestia. Created by the powers of order and benevolence, archons defend their home from fiendish incursions and safeguard those threatened by wicked forces. Archons are skilled communicators, able to speak all the languages of the multiverse. When pushed into combat, they prefer to subdue foes. However, against Fiends, archons are wrathful combatants, manifesting the righteous vengeance of Mount Celestia to strike down the wicked.

Each archon's form corresponds to its place within the Celestial hierarchy. When faced in battle, archons radiate the full fury of the Upper Planes, bolstering their allies and cowing their foes.

```statblock
"name": "Warden Archon (MPP)"
"size": "Large"
"type": "celestial"
"alignment": "typically  Lawful Good"
"ac": !!int "18"
"ac_class": "[plate armor](3-Mechanics/CLI/items/plate-armor.md)"
"hp": !!int "136"
"hit_dice": "16d10 + 48"
"modifier": !!int "0"
"stats":
  - !!int "20"
  - !!int "10"
  - !!int "17"
  - !!int "15"
  - !!int "18"
  - !!int "18"
"speed": "30 ft., climb 30 ft."
"saves":
  - "constitution": !!int "6"
  - "wisdom": !!int "7"
"skillsaves":
  - "name": "[Arcana](3-Mechanics/CLI/rules/skills.md#Arcana)"
    "desc": "+5"
  - "name": "[Athletics](3-Mechanics/CLI/rules/skills.md#Athletics)"
    "desc": "+8"
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+10"
"damage_immunities": "lightning"
"condition_immunities": "[charmed](3-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](3-Mechanics/CLI/rules/conditions.md#Exhaustion),\
  \ [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened), [paralyzed](3-Mechanics/CLI/rules/conditions.md#Paralyzed)"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 120 ft., [truesight](3-Mechanics/CLI/rules/senses.md#Truesight)\
  \ 30 ft., passive Perception 20"
"languages": "all"
"cr": "8"
"traits":
  - "desc": "As long as the archon doesn't have the [incapacitated](3-Mechanics/CLI/rules/conditions.md#Incapacitated)\
      \ condition, each creature of the archon's choice that starts its turn within\
      \ 20 feet of the archon must make a DC 15 Wisdom saving throw. On a failed save,\
      \ the creature has the [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened)\
      \ condition until the start of its next turn. On a successful save, the creature\
      \ is immune to all archons' Aura of Menace for 24 hours."
    "name": "Aura of Menace"
  - "desc": "The archon can't be surprised. Moreover, it knows when any creature uses\
      \ a portal it is assigned to guard."
    "name": "Eternal Vigil"
"actions":
  - "desc": "The archon makes two Claw attacks and one Tracker's Bite attack."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +8 to hit, reach 10 ft., one target. *Hit:*\
      \ 12 (2d6 + 5) slashing damage. If the target is a Medium or smaller creature,\
      \ the target has the [grappled](3-Mechanics/CLI/rules/conditions.md#Grappled)\
      \ condition (escape DC 18). The archon can have only one creature [grappled](3-Mechanics/CLI/rules/conditions.md#Grappled)\
      \ in this way at a time."
    "name": "Claw"
  - "desc": "*Melee Weapon Attack:* +8 to hit, reach 5 ft., one target. *Hit:* 15\
      \ (3d6 + 5) piercing damage. If the target is a creature, for the next 24\
      \ hours, the archon knows the distance and direction to the target while they\
      \ are both on the same plane of existence."
    "name": "Tracker's Bite"
  - "desc": "The archon teleports, along with any equipment it is wearing or carrying,\
      \ to an unoccupied space it can see within 120 feet of itself."
    "name": "Teleport"
  - "desc": "The archon casts one of the following spells, requiring no material components\
      \ and using Charisma as the spellcasting ability (spell save DC 15):\n\n**At\
      \ will:** [detect evil and good](3-Mechanics/CLI/spells/detect-evil-and-good.md)\n\
      \n**1/day each:** [aid](3-Mechanics/CLI/spells/aid.md), [continual flame](3-Mechanics/CLI/spells/continual-flame.md),\
      \ [protection from evil and good](3-Mechanics/CLI/spells/protection-from-evil-and-good.md),\
      \ [scrying](3-Mechanics/CLI/spells/scrying.md) (as an action)"
    "name": "Spellcasting"
"source":
  - "MPP"
"image": "3-Mechanics/CLI/bestiary/celestial/token/warden-archon-mpp.webp"
```
^statblock