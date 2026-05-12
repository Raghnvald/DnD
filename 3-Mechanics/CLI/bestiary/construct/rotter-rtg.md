---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/rtg
- ttrpg-cli/monster/cr/5
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/construct
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Rotter"
---
# [Rotter](3-Mechanics/CLI/bestiary/construct/rotter-rtg.md)
*Source: Return to Glory p. 34*  

```statblock
"name": "Rotter (RtG)"
"size": "Medium"
"type": "construct"
"alignment": "Unaligned"
"ac": !!int "18"
"ac_class": "natural armor, [shield](3-Mechanics/CLI/items/shield-xphb.md)"
"hp": !!int "75"
"hit_dice": "10d8 + 30"
"modifier": !!int "1"
"stats":
  - !!int "18"
  - !!int "12"
  - !!int "16"
  - !!int "10"
  - !!int "13"
  - !!int "8"
"speed": "30 ft., climb 30 ft."
"skillsaves":
  - "name": "[Athletics](3-Mechanics/CLI/rules/skills.md#Athletics)"
    "desc": "+7"
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+4"
  - "name": "[Stealth](3-Mechanics/CLI/rules/skills.md#Stealth)"
    "desc": "+4"
"damage_vulnerabilities": "fire"
"damage_resistances": "bludgeoning, piercing"
"damage_immunities": "poison"
"condition_immunities": "[charmed](3-Mechanics/CLI/rules/conditions.md#Charmed), [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened),\
  \ [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)"
"gear":
  - "[club](3-Mechanics/CLI/items/club-xphb.md)"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., passive\
  \ Perception 14"
"languages": "telepathy 60 ft."
"cr": "5"
"traits":
  - "desc": "In the rotter's hand, its club is magical and deals 7 (3d4) extra damage\
      \ (included in its attacks)."
    "name": "Magic Club"
  - "desc": "The rotter has advantage on Dexterity ([Stealth](3-Mechanics/CLI/rules/skills.md#Stealth))\
      \ checks it makes in terrain with ample obscuring plant life."
    "name": "Plant Camouflage"
  - "desc": "The rotter regains 10 hit points at the start of its turn if it is in\
      \ contact with the ground. If the rotter takes fire damage, this trait doesn't\
      \ function at the start of the rotter's next turn. The rotter dies only if it\
      \ starts its turn with 0 hit points and doesn't regenerate."
    "name": "Regeneration"
  - "desc": "The rotter can see and hear what any plant within 120 ft can see and\
      \ hear. In addition, the rotter can communicate telepathically with any plant\
      \ within this range."
    "name": "Shared Senses"
  - "desc": "Once on each of its turns, the rotter can use 10 feet of its movement\
      \ to step magically into one copse of mushrooms within 5 feet of it and emerge\
      \ from a second copse of mushrooms within 60 feet of it, appearing in an unoccupied\
      \ space within 5 feet of the second copse. Both copses of mushrooms must be\
      \ Large or bigger. The rotter doesn't need to be able to see the second copse\
      \ to use this ability."
    "name": "Tree Stride"
"actions":
  - "desc": "The rotter makes two attacks with its club."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +7 to hit, reach 5 ft., one target. *Hit:* 14\
      \ (4d4 + 4) bludgeoning damage."
    "name": "Club"
"source":
  - "RtG"
"image": "3-Mechanics/CLI/bestiary/construct/token/rotter-rtg.webp"
```
^statblock