---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/psa
- ttrpg-cli/monster/cr/3
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/undead
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Eternal"
---
# [Eternal](3-Mechanics/CLI/bestiary/undead/eternal-psa.md)
*Source: Plane Shift: Amonkhet p. 34*  

## An Eternal Army

A being as mighty and magnificent as Nicol Bolas demands a fighting force of the highest caliber, so that an ordinary army of zombies could never be worthy of the God-Pharaoh. The Eternals are elite soldiers with all the skill and prowess of living soldiers, but none of the disadvantages that arise in living beings, such as emotions, hesitation, or disloyalty. Bolas has personally crafted all of Amonkhet to create just such an army.

Eternals have the statistics of [wights](3-Mechanics/CLI/bestiary/undead/wight.md)—individually fearsome, and terrifying as they march in endless ranks.

```statblock
"name": "Eternal (PSA)"
"size": "Medium"
"type": "undead"
"alignment": "Neutral Evil"
"ac": !!int "14"
"ac_class": "[studded leather](3-Mechanics/CLI/items/studded-leather-armor.md)"
"hp": !!int "45"
"hit_dice": "6d8 + 18"
"modifier": !!int "2"
"stats":
  - !!int "15"
  - !!int "14"
  - !!int "16"
  - !!int "10"
  - !!int "13"
  - !!int "15"
"speed": "30 ft."
"skillsaves":
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+3"
  - "name": "[Stealth](3-Mechanics/CLI/rules/skills.md#Stealth)"
    "desc": "+4"
"damage_resistances": "necrotic; bludgeoning, piercing, slashing from nonmagical attacks\
  \ that aren't silvered"
"damage_immunities": "poison"
"condition_immunities": "[exhaustion](3-Mechanics/CLI/rules/conditions.md#Exhaustion),\
  \ [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)"
"gear":
  - "[longbow](3-Mechanics/CLI/items/longbow.md)"
  - "[longsword](3-Mechanics/CLI/items/longsword.md)"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., passive\
  \ Perception 13"
"languages": "the languages it knew in life"
"cr": "3"
"traits":
  - "desc": "While in sunlight, the eternal has disadvantage on attack rolls, as well\
      \ as on Wisdom ([Perception](3-Mechanics/CLI/rules/skills.md#Perception)) checks\
      \ that rely on sight."
    "name": "Sunlight Sensitivity"
"actions":
  - "desc": "The eternal makes two longsword attacks or two longbow attacks. It can\
      \ use its Life Drain in place of one longsword attack."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one creature. *Hit:*\
      \ 5 (1d6 + 2) necrotic damage. The target must succeed on a DC 13 Constitution\
      \ saving throw or its hit point maximum is reduced by an amount equal to the\
      \ damage taken. This reduction lasts until the target finishes a long rest.\
      \ The target dies if this effect reduces its hit point maximum to 0.\n\nA humanoid\
      \ slain by this attack rises 24 hours later as a [zombie](3-Mechanics/CLI/bestiary/undead/zombie.md)\
      \ under the eternal's control, unless the humanoid is restored to life or its\
      \ body is destroyed. The eternal can have no more than twelve zombies under\
      \ its control at one time."
    "name": "Life Drain"
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one target. *Hit:* 6\
      \ (1d8 + 2) slashing damage, or 7 (1d10 + 2) slashing damage if used with\
      \ two hands."
    "name": "Longsword"
  - "desc": "*Ranged Weapon Attack:* +4 to hit, range 150/600 ft., one target. *Hit:*\
      \ 6 (1d8 + 2) piercing damage."
    "name": "Longbow"
"source":
  - "PSA"
"image": "3-Mechanics/CLI/bestiary/undead/token/eternal-psa.webp"
```
^statblock