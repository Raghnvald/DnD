---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/imr
- ttrpg-cli/monster/cr/5
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/celestial
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Banrion"
---
# [Banrion](3-Mechanics/CLI/bestiary/npc/banrion-imr.md)
*Source: Infernal Machine Rebuild p. 91*  

Unrelated to the horses it resembles, a unicorn is a celestial creature that wanders sylvan realms, its white form glimmering like starlight. They allow good-hearted creatures to enter their woods to hunt or gather food, but they hold evil ever at bay.

```statblock
"name": "Banrion (IMR)"
"size": "Large"
"type": "celestial"
"alignment": "Lawful Good"
"ac": !!int "12"
"hp": !!int "67"
"hit_dice": "9d10 + 18"
"modifier": !!int "2"
"stats":
  - !!int "18"
  - !!int "14"
  - !!int "15"
  - !!int "11"
  - !!int "17"
  - !!int "16"
"speed": "50 ft."
"damage_immunities": "poison"
"condition_immunities": "[charmed](3-Mechanics/CLI/rules/conditions.md#Charmed), [paralyzed](3-Mechanics/CLI/rules/conditions.md#Paralyzed),\
  \ [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., passive\
  \ Perception 13"
"languages": "Celestial, Elvish, Sylvan, telepathy 60 ft."
"cr": "5"
"traits":
  - "desc": "Banrion's innate spellcasting ability is Charisma (spell save DC 14).\
      \ Banrion can innately cast the following spells, requiring no components:\n\
      \n**At will:** [detect evil and good](3-Mechanics/CLI/spells/detect-evil-and-good.md),\
      \ [druidcraft](3-Mechanics/CLI/spells/druidcraft.md), [pass without trace](3-Mechanics/CLI/spells/pass-without-trace.md)\n\
      \n**1/day each:** [calm emotions](3-Mechanics/CLI/spells/calm-emotions.md),\
      \ [dispel evil and good](3-Mechanics/CLI/spells/dispel-evil-and-good.md), [entangle](3-Mechanics/CLI/spells/entangle.md)"
    "name": "Innate Spellcasting"
  - "desc": "If Banrion moves at least 20 feet straight toward a target and then hits\
      \ it with a horn attack on the same turn, the target takes an extra 9 (2d8)\
      \ piercing damage. If the target is a creature, it must succeed on a DC 15 Strength\
      \ saving throw or be knocked [prone](3-Mechanics/CLI/rules/conditions.md#Prone)."
    "name": "Charge"
  - "desc": "Banrion has advantage on saving throws against spells and other magical\
      \ effects."
    "name": "Magic Resistance"
  - "desc": "Banrion's weapon attacks are magical."
    "name": "Magic Weapons"
"actions":
  - "desc": "Banrion makes two attacks: one with its hooves and one with its horn."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +7 to hit, reach 5 ft., one target. *Hit:* 11\
      \ (2d6 + 4) bludgeoning damage."
    "name": "Hooves"
  - "desc": "*Melee Weapon Attack:* +7 to hit, reach 5 ft., one target. *Hit:* 8\
      \ (1d8 + 4) piercing damage."
    "name": "Horn"
  - "desc": "Banrion touches another creature with its horn. The target magically\
      \ regains 11 (2d8 + 2) hit points. In addition, the touch removes all diseases\
      \ and neutralizes all poisons afflicting the target."
    "name": "Healing Touch (3/Day)"
  - "desc": "Banrion magically teleports itself and up to three willing creatures\
      \ it can see within 5 feet of it, along with any equipment they are wearing\
      \ or carrying, to a location Banrion is familiar with, up to 1 mile away."
    "name": "Teleport (1/Day)"
"legendary_description": "Legendary Action Uses: 3. Immediately after another creature's\
  \ turn, Banrion can expend a use to take one of the following actions. Banrion regains\
  \ all expended uses at the start of each of their turns."
"legendary_actions":
  - "desc": "Banrion makes one attack with its hooves."
    "name": "Hooves"
  - "desc": "Banrion creates a shimmering, magical field around itself or another\
      \ creature it can see within 60 feet of it. The target gains a +2 bonus to AC\
      \ until the end of Banrion's next turn."
    "name": "Shimmering Shield (Costs 2 Actions)"
  - "desc": "Banrion magically regains 11 (2d8 + 2) hit points."
    "name": "Heal Self (Costs 3 Actions)"
"source":
  - "IMR"
"image": "3-Mechanics/CLI/bestiary/npc/token/banrion-imr.webp"
```
^statblock