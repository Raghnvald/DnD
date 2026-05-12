---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mpp
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/size/small
- ttrpg-cli/monster/type/celestial
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Lantern Archon"
---
# [Lantern Archon](3-Mechanics/CLI/bestiary/celestial/lantern-archon-mpp.md)
*Source: Morte's Planar Parade p. 17*  

The lowest-ranked archons, lantern archons greet newly arrived souls to Mount Celestia and light the path for those who traverse the plane with reverence and respect. They appear as glowing, winged balls of vaporous light wrapped in a gleaming metal lattice, although they have no more physical substance than smoke.

When confronting those who approach with ill intentions, lantern archons strike with searing bolts of focused light, flitting from place to place between blasts to confound their foes.

## Archons

Archons are denizens of the Seven Heavens of Mount Celestia. Created by the powers of order and benevolence, archons defend their home from fiendish incursions and safeguard those threatened by wicked forces. Archons are skilled communicators, able to speak all the languages of the multiverse. When pushed into combat, they prefer to subdue foes. However, against Fiends, archons are wrathful combatants, manifesting the righteous vengeance of Mount Celestia to strike down the wicked.

Each archon's form corresponds to its place within the Celestial hierarchy. When faced in battle, archons radiate the full fury of the Upper Planes, bolstering their allies and cowing their foes.

```statblock
"name": "Lantern Archon (MPP)"
"size": "Small"
"type": "celestial"
"alignment": "typically  Lawful Good"
"ac": !!int "13"
"hp": !!int "22"
"hit_dice": "5d6 + 5"
"modifier": !!int "3"
"stats":
  - !!int "1"
  - !!int "16"
  - !!int "12"
  - !!int "6"
  - !!int "12"
  - !!int "13"
"speed": "0 ft., fly 60 ft. (hover)"
"skillsaves":
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+3"
"damage_resistances": "bludgeoning, piercing, slashing from nonmagical attacks"
"damage_immunities": "lightning, radiant"
"condition_immunities": "[exhaustion](3-Mechanics/CLI/rules/conditions.md#Exhaustion),\
  \ [grappled](3-Mechanics/CLI/rules/conditions.md#Grappled), [paralyzed](3-Mechanics/CLI/rules/conditions.md#Paralyzed),\
  \ [prone](3-Mechanics/CLI/rules/conditions.md#Prone), [restrained](3-Mechanics/CLI/rules/conditions.md#Restrained)"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 120 ft., passive\
  \ Perception 13"
"languages": "all"
"cr": "2"
"traits":
  - "desc": "As long as the archon doesn't have the [incapacitated](3-Mechanics/CLI/rules/conditions.md#Incapacitated)\
      \ condition, each creature of the archon's choice that starts its turn within\
      \ 20 feet of the archon must make a DC 11 Wisdom saving throw. On a failed save,\
      \ the creature has the [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened)\
      \ condition until the start of its next turn. On a successful save, the creature\
      \ is immune to all archons' Aura of Menace for 24 hours."
    "name": "Aura of Menace"
  - "desc": "The archon sheds bright light in a 30-foot radius and dim light for an\
      \ additional 30 feet."
    "name": "Illumination"
  - "desc": "The archon can move through creatures and objects as if they were difficult\
      \ terrain. If it ends its turn inside an object, it takes 5 (1d10) force damage."
    "name": "Incorporeal Movement"
"actions":
  - "desc": "The archon makes two Radiant Strike attacks. It can replace one attack\
      \ with a use of Teleport."
    "name": "Multiattack"
  - "desc": "*Melee  or Ranged Weapon Attack:* +5 to hit, reach 5 ft. or range 60\
      \ ft., one target. *Hit:* 6 (1d6 + 3) radiant damage."
    "name": "Radiant Strike"
  - "desc": "The archon teleports, along with any equipment it is wearing or carrying,\
      \ to an unoccupied space it can see within 120 feet of itself."
    "name": "Teleport"
  - "desc": "The archon casts one of the following spells, requiring no material components\
      \ and using Charisma as the spellcasting ability:\n\n**At will:** [detect evil\
      \ and good](3-Mechanics/CLI/spells/detect-evil-and-good.md)\n\n**1/day:** [aid](3-Mechanics/CLI/spells/aid.md)"
    "name": "Spellcasting"
"bonus_actions":
  - "desc": "The archon reduces its Illumination to shed only dim light in a 5-foot\
      \ radius, or it returns the light to full intensity."
    "name": "Shift Radiance"
"source":
  - "MPP"
"image": "3-Mechanics/CLI/bestiary/celestial/token/lantern-archon-mpp.webp"
```
^statblock