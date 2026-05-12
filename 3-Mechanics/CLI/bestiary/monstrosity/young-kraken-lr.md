---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/lr
- ttrpg-cli/monster/cr/14
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/monstrosity/titan
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Young Kraken"
---
# [Young Kraken](3-Mechanics/CLI/bestiary/monstrosity/young-kraken-lr.md)
*Source: Locathah Rising p. 21*  

```statblock
"name": "Young Kraken (LR)"
"size": "Huge"
"type": "monstrosity"
"subtype": "titan"
"alignment": "Chaotic Evil"
"ac": !!int "16"
"ac_class": "natural armor"
"hp": !!int "207"
"hit_dice": "18d12 + 90"
"modifier": !!int "0"
"stats":
  - !!int "24"
  - !!int "11"
  - !!int "20"
  - !!int "19"
  - !!int "15"
  - !!int "17"
"speed": "20 ft., swim 50 ft."
"saves":
  - "strength": !!int "12"
  - "dexterity": !!int "5"
  - "constitution": !!int "10"
  - "intelligence": !!int "9"
  - "wisdom": !!int "7"
"damage_immunities": "lightning; bludgeoning, piercing, slashing from nonmagical attacks"
"condition_immunities": "[frightened](3-Mechanics/CLI/rules/conditions.md#Frightened),\
  \ [paralyzed](3-Mechanics/CLI/rules/conditions.md#Paralyzed)"
"senses": "[truesight](3-Mechanics/CLI/rules/senses.md#Truesight) 120 ft., passive\
  \ Perception 14"
"languages": "Abyssal, Celestial, Infernal, Primordial, telepathy 60 ft. but can't\
  \ speak"
"cr": "14"
"traits":
  - "desc": "The kraken can breathe air and water."
    "name": "Amphibious"
"actions":
  - "desc": "The kraken makes two tentacle attacks, each of which it can replace with\
      \ one use of Fling."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +12 to hit, reach 5 ft., one target. *Hit:*\
      \ 20 (3d8 + 7) piercing damage.\n\nIf the target is a Medium or smaller creature\
      \ [grappled](3-Mechanics/CLI/rules/conditions.md#Grappled) by the kraken, that\
      \ creature is swallowed and the grapple ends. While swallowed, the creature\
      \ is [blinded](3-Mechanics/CLI/rules/conditions.md#Blinded) and [restrained](3-Mechanics/CLI/rules/conditions.md#Restrained),\
      \ it has total cover against attacks and other effects outside the kraken, and\
      \ it takes 21 (6d6) acid damage at the start of each of the kraken's turns.\
      \ One Medium or two smaller creatures can be swallowed at the same time.\n\n\
      If the kraken takes 35 damage or more on a single turn from a creature inside\
      \ it, the kraken must succeed on a DC 23 Constitution saving throw at the end\
      \ of that turn or regurgitate all swallowed creatures, which fall [prone](3-Mechanics/CLI/rules/conditions.md#Prone)\
      \ in spaces within 10 feet of the kraken. If the kraken dies, a swallowed creature\
      \ is no longer [restrained](3-Mechanics/CLI/rules/conditions.md#Restrained)\
      \ by it and can escape from the corpse using 10 feet of movement, exiting [prone](3-Mechanics/CLI/rules/conditions.md#Prone)."
    "name": "Bite"
  - "desc": "*Melee Weapon Attack:* +12 to hit, reach 20 ft., one target. *Hit:*\
      \ 17 (3d6 + 7) bludgeoning damage, and the target is [grappled](3-Mechanics/CLI/rules/conditions.md#Grappled)\
      \ (escape DC 20). Until the grapple ends, the target is [restrained](3-Mechanics/CLI/rules/conditions.md#Restrained).\
      \ The kraken has ten tentacles, each of which can grapple one target."
    "name": "Tentacle"
  - "desc": "One Medium or smaller object held or creature [grappled](3-Mechanics/CLI/rules/conditions.md#Grappled)\
      \ by the kraken is thrown up to 40 feet in a random direction and knocked [prone](3-Mechanics/CLI/rules/conditions.md#Prone).\
      \ If a thrown target strikes a solid surface, the target takes 3 (1d6) bludgeoning\
      \ damage for every 10 feet it was thrown. If the target is thrown at another\
      \ creature, that creature must succeed on a DC 13 Dexterity saving throw or\
      \ take the same damage and be knocked [prone](3-Mechanics/CLI/rules/conditions.md#Prone)."
    "name": "Fling"
  - "desc": "The kraken magically create a bolt of lightning, which can strike a target\
      \ the kraken can see within 90 feet of it. The target must make a DC 18 Dexterity\
      \ saving throw, taking 22 (4d10) lightning damage on a failed save, or half\
      \ as much damage on a successful one."
    "name": "Lightning Strike"
"source":
  - "LR"
"image": "3-Mechanics/CLI/bestiary/monstrosity/token/young-kraken-lr.webp"
```
^statblock