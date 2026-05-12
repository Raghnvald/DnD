---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/psd
- ttrpg-cli/monster/cr/4
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/beast
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Steel Leaf Kavu"
---
# [Steel Leaf Kavu](3-Mechanics/CLI/bestiary/beast/steel-leaf-kavu-psd.md)
*Source: Plane Shift: Dominaria p. 24*  

## Deadly Chargers

Though the Basiphem dwell in the highest layer of the forest, they maintain extensive stables on the forest floor to house and train the largest ground-dwelling kavu. Members of the Order of the Steel Leaf often ride these creatures into battle, with the largest of the kavu sometimes reaching the size of elephants.

## Kavu

Kavu are reptilian creatures that are either very ancient or a relatively recent creation on Dominaria. Either awakening from a millennia-long hibernation or springing fully formed into being, they emerged from the ground to defend against the Phyrexian Invasion. The Llanowar elves now breed the kavu to fill a variety of roles, believing that these creatures were the goddess Gaea's means of intervening in Dominaria's defense. The close relationship between elves and kavu is a constant reminder of Gaea's beneficence. Every Kelfae bonds with an arboreal kavu companion, and some Kelfae and Basiphem warriors ride them into battle.

```statblock
"name": "Steel Leaf Kavu (PSD)"
"size": "Large"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "16"
"ac_class": "natural armor"
"hp": !!int "142"
"hit_dice": "15d10 + 60"
"modifier": !!int "1"
"stats":
  - !!int "20"
  - !!int "12"
  - !!int "18"
  - !!int "6"
  - !!int "14"
  - !!int "8"
"speed": "40 ft."
"skillsaves":
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+4"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., passive\
  \ Perception 14"
"languages": "understands Elvish"
"cr": "4"
"traits":
  - "desc": "If the kavu moves at least 20 feet straight toward a creature and then\
      \ hits it with a bite attack on the same turn, that target must succeed on a\
      \ DC 15 Strength saving throw or be knocked [prone](3-Mechanics/CLI/rules/conditions.md#Prone).\
      \ If the target is [prone](3-Mechanics/CLI/rules/conditions.md#Prone), the kavu\
      \ can make one rend attack against it as a bonus action."
    "name": "Raking Charge"
"actions":
  - "desc": "*Melee Weapon Attack:* +7 to hit, reach 5 ft., one target. *Hit:* 14\
      \ (2d8 + 5) piercing damage."
    "name": "Bite"
  - "desc": "*Melee Weapon Attack:* +7 to hit, reach 5 ft., one [prone](3-Mechanics/CLI/rules/conditions.md#Prone)\
      \ creature. *Hit:* 23 (4d8 + 5) slashing damage."
    "name": "Rend"
"source":
  - "PSD"
"image": "3-Mechanics/CLI/bestiary/beast/token/steel-leaf-kavu-psd.webp"
```
^statblock