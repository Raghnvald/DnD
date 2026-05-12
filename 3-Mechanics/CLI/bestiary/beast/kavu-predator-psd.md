---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/psd
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/beast
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Kavu Predator"
---
# [Kavu Predator](3-Mechanics/CLI/bestiary/beast/kavu-predator-psd.md)
*Source: Plane Shift: Dominaria p. 24*  

## Arboreal Foes

The arboreal kavu bred by the Kelfae are capable of climbing sheer surfaces at any angle, and of charging at astonishing speed at ground level. Kelfae warriors ride a large breed of kavu predators, using a series of cloth slings as safety restraints while sitting or dangling from the creature's back. The nimble and acrobatic Kelfae kavu riders are called arborealists.

## Kavu

Kavu are reptilian creatures that are either very ancient or a relatively recent creation on Dominaria. Either awakening from a millennia-long hibernation or springing fully formed into being, they emerged from the ground to defend against the Phyrexian Invasion. The Llanowar elves now breed the kavu to fill a variety of roles, believing that these creatures were the goddess Gaea's means of intervening in Dominaria's defense. The close relationship between elves and kavu is a constant reminder of Gaea's beneficence. Every Kelfae bonds with an arboreal kavu companion, and some Kelfae and Basiphem warriors ride them into battle.

```statblock
"name": "Kavu Predator (PSD)"
"size": "Large"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "75"
"hit_dice": "10d10 + 20"
"modifier": !!int "1"
"stats":
  - !!int "18"
  - !!int "12"
  - !!int "15"
  - !!int "6"
  - !!int "14"
  - !!int "8"
"speed": "30 ft., climb 30 ft."
"skillsaves":
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+4"
  - "name": "[Stealth](3-Mechanics/CLI/rules/skills.md#Stealth)"
    "desc": "+5"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., passive\
  \ Perception 14"
"languages": "understands Elvish"
"cr": "2"
"traits":
  - "desc": "If the kavu moves at least 20 feet straight toward a creature and then\
      \ hits it with a claw attack on the same turn, that target must succeed on a\
      \ DC 14 Strength saving throw or be knocked [prone](3-Mechanics/CLI/rules/conditions.md#Prone).\
      \ If the target is [prone](3-Mechanics/CLI/rules/conditions.md#Prone), the kavu\
      \ can make one bite attack against it as a bonus action."
    "name": "Pounce"
"actions":
  - "desc": "The kavu makes two claw attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +6 to hit, reach 5 ft., one target. *Hit:* 9\
      \ (1d10 + 4) piercing damage."
    "name": "Bite"
  - "desc": "*Melee Weapon Attack:* +6 to hit, reach 5 ft., one target. *Hit:* 7\
      \ (1d6 + 4) slashing damage."
    "name": "Claw"
"source":
  - "PSD"
"image": "3-Mechanics/CLI/bestiary/beast/token/kavu-predator-psd.webp"
```
^statblock