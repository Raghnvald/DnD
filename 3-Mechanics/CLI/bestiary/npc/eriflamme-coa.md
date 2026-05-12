---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/coa
- ttrpg-cli/monster/cr/28
- ttrpg-cli/monster/size/gargantuan
- ttrpg-cli/monster/type/elemental
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Eriflamme"
---
# [Eriflamme](3-Mechanics/CLI/bestiary/npc/eriflamme-coa.md)
*Source: Chains of Asmodeus p. 121*  

```statblock
"name": "Eriflamme (CoA)"
"size": "Gargantuan"
"type": "elemental"
"alignment": "Unaligned"
"ac": !!int "19"
"ac_class": "natural armor"
"hp": !!int "518"
"hit_dice": "28d20 + 224"
"modifier": !!int "0"
"stats":
  - !!int "30"
  - !!int "11"
  - !!int "26"
  - !!int "5"
  - !!int "10"
  - !!int "10"
"speed": "40 ft."
"saves":
  - "intelligence": !!int "5"
  - "wisdom": !!int "8"
  - "charisma": !!int "8"
"skillsaves":
  - "name": "Arcana"
    "desc": "+5"
  - "name": "Athletics"
    "desc": "+18"
"damage_immunities": "fire; poison; bludgeoning, piercing, slashing from nonmagical\
  \ attacks"
"condition_immunities": "charmed, frightened, paralyzed, poisoned"
"senses": "blindsight 120 ft., passive Perception 10"
"languages": ""
"cr": "28"
"traits":
  - "desc": "If the Eriflamme fails a saving throw, it can choose to succeed instead."
    "name": "Legendary Resistance (3/Day)"
  - "desc": "The Eriflamme has advantage on saving throws against spells and other\
      \ magical effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "The Eriflamme makes four Claw attacks. It can replace one of the attacks\
      \ with a Bite attack."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +18 to hit, reach 15 ft., one target. *Hit:*\
      \ 20 (3d6 + 10) slashing damage plus 7 (2d6) fire damage."
    "name": "Claw"
  - "desc": "*Melee Weapon Attack:* +18 to hit, reach 10 ft., one target. *Hit:*\
      \ 24 (4d6 + 10) piercing damage plus 33 (6d10) fire damage."
    "name": "Bite"
  - "desc": "All the Eriflamme's fire elementals vanish and the Eriflamme reappears\
      \ in one of their spaces. The Eriflamme's hit points are equivalent to the combined\
      \ hit points of the fire elementals."
    "name": "Reform"
"reactions":
  - "desc": "As a reaction to taking damage, the Eriflamme can split into fire elementals\
      \ and reduce the damage to 0. The Eriflamme can form up to 10 fire elementals,\
      \ splitting its remaining hit points between them. The fire elementals appear\
      \ in spaces adjacent to or within the Eriflamme's old location, and all act\
      \ on the Eriflamme's initiative. They gain a +5 bonus to attack rolls and have\
      \ the Eriflamme's Reform action."
    "name": "Split (2/Day)"
"legendary_description": "Legendary Action Uses: 3. Immediately after another creature's\
  \ turn, the eriflamme can expend a use to take one of the following actions. The\
  \ eriflamme regains all expended uses at the start of each of its turns."
"legendary_actions":
  - "desc": "The Eriflamme makes a Claw attack, which deals force damage instead of\
      \ slashing damage if it hits."
    "name": "Slam"
  - "desc": "The Eriflamme moves up to half its speed. It can fly during this movement."
    "name": "Fireglide"
  - "desc": "The Eriflamme makes a Bite attack with advantage."
    "name": "Chomp (Costs 2 Actions)"
"source":
  - "CoA"
"image": "3-Mechanics/CLI/bestiary/npc/token/eriflamme-coa.webp"
```
^statblock