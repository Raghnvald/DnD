---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mpp
- ttrpg-cli/monster/cr/11
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/fiend
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Farastu Demodand"
---
# [Farastu Demodand](3-Mechanics/CLI/bestiary/fiend/farastu-demodand-mpp.md)
*Source: Morte's Planar Parade p. 26*  

Farastus, also known as tarry demodands, are the least of the demodands. These violent Fiends ooze thick, sticky tar that sticks to anything it touches. Arrogant and cruel, farastus delight in tormenting those weaker than themselves. Due to their sharp senses and vicious streaks, farastus sometimes work as hunters that track down those who escape Carceri.

## Demodands

Demodands, also called gehreleths, are Fiends from the Tarterian Depths of Carceri. Cast into the prison plane long ago for forgotten transgressions, these bitter, wicked creatures have appointed themselves the jailers of the plane. Demodands viciously defend the few known portals that lead out of Carceri and ruthlessly torment other creatures trapped there.

Demodands that manage to leave Carceri know they're doomed to return; a demodand that dies outside Carceri re-forms there in a torturous process that takes `2d20` days. Even those who survive on other planes find themselves eventually dragged back, pulled by some planar tether.

```statblock
"name": "Farastu Demodand (MPP)"
"size": "Medium"
"type": "fiend"
"alignment": "typically  Neutral Evil"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "195"
"hit_dice": "26d8 + 78"
"modifier": !!int "1"
"stats":
  - !!int "20"
  - !!int "13"
  - !!int "16"
  - !!int "8"
  - !!int "12"
  - !!int "16"
"speed": "40 ft., climb 40 ft."
"saves":
  - "dexterity": !!int "5"
  - "wisdom": !!int "5"
"skillsaves":
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+9"
  - "name": "[Stealth](3-Mechanics/CLI/rules/skills.md#Stealth)"
    "desc": "+5"
  - "name": "[Survival](3-Mechanics/CLI/rules/skills.md#Survival)"
    "desc": "+5"
"damage_resistances": "cold, fire"
"damage_immunities": "acid, poison"
"condition_immunities": "[paralyzed](3-Mechanics/CLI/rules/conditions.md#Paralyzed),\
  \ [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned), [restrained](3-Mechanics/CLI/rules/conditions.md#Restrained)"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 120 ft., passive\
  \ Perception 19"
"languages": "Abyssal, Demodand, telepathy 120 ft."
"cr": "11"
"traits":
  - "desc": "The farastu ignores difficult terrain, and magical effects can't reduce\
      \ its speed. It can spend 5 feet of movement to automatically remove the [grappled](3-Mechanics/CLI/rules/conditions.md#Grappled)\
      \ condition from itself."
    "name": "Boundless Movement"
  - "desc": "The farastu has advantage on saving throws against spells and other magical\
      \ effects."
    "name": "Magic Resistance"
  - "desc": "The farastu can climb difficult surfaces, including upside down on ceilings,\
      \ without an ability check."
    "name": "Spider Climb"
"actions":
  - "desc": "The farastu makes two Claw attacks and one Bite attack."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +9 to hit, reach 5 ft., one target. *Hit:* 16\
      \ (2d10 + 5) slashing damage. If the target is a Large or smaller creature,\
      \ it has the [grappled](3-Mechanics/CLI/rules/conditions.md#Grappled) condition\
      \ (escape DC 15, with disadvantage). The farastu has two claws, each of which\
      \ can grapple one creature."
    "name": "Claw"
  - "desc": "*Melee Weapon Attack:* +9 to hit (with advantage against a creature\
      \ the farastu is grappling), reach 5 ft., one target. *Hit:* 12 (2d6 + 5)\
      \ piercing damage plus 24 (7d6) acid damage."
    "name": "Bite"
  - "desc": "The farastu has a 40 percent chance of summoning 1 farastu demodand.\
      \ A summoned demodand appears in an unoccupied space within 60 feet of the farastu,\
      \ acts as an ally of the farastu, and can't summon other demodands. It remains\
      \ for 1 minute, until it or the farastu dies, or until the farastu dismisses\
      \ it as an action."
    "name": "Summon Demodand (1/Day)"
  - "desc": "The farastu casts one of the following spells, requiring no material\
      \ components and using Charisma as the spellcasting ability:\n\n**At will:**\
      \ [invisibility](3-Mechanics/CLI/spells/invisibility.md) (self only)\n\n**1/day\
      \ each:** [dispel magic](3-Mechanics/CLI/spells/dispel-magic.md), [fog cloud](3-Mechanics/CLI/spells/fog-cloud.md)"
    "name": "Spellcasting"
"source":
  - "MPP"
"image": "3-Mechanics/CLI/bestiary/fiend/token/farastu-demodand-mpp.webp"
```
^statblock