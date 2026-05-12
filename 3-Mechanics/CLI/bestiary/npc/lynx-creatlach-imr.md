---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/imr
- ttrpg-cli/monster/cr/5
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/undead/tiefling
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Lynx Creatlach"
---
# [Lynx Creatlach](3-Mechanics/CLI/bestiary/npc/lynx-creatlach-imr.md)
*Source: Infernal Machine Rebuild p. 54*  

> [!note] Out on Loan
> 
> The powerful relics possessed by Lynx Creatlach and Sir Ursas (see the "Special Equipment" section of their stat blocks) have been granted to them by their diabolical masters, and are not meant to be claimed as treasure. If either agent is killed in the course of the adventure, their special equipment vanishes, returning to Bel or Zariel.
^out-on-loan

```statblock
"name": "Lynx Creatlach (IMR)"
"size": "Medium"
"type": "undead"
"subtype": "tiefling"
"alignment": "Lawful Evil"
"ac": !!int "13"
"ac_class": "[leather armor](3-Mechanics/CLI/items/leather-armor.md)"
"hp": !!int "136"
"hit_dice": "16d8 + 64"
"modifier": !!int "2"
"stats":
  - !!int "18"
  - !!int "14"
  - !!int "18"
  - !!int "13"
  - !!int "16"
  - !!int "18"
"speed": "30 ft."
"saves":
  - "strength": !!int "7"
  - "constitution": !!int "7"
  - "wisdom": !!int "6"
  - "charisma": !!int "7"
"damage_resistances": "necrotic, psychic"
"damage_immunities": "poison"
"condition_immunities": "[charmed](3-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](3-Mechanics/CLI/rules/conditions.md#Exhaustion),\
  \ [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened), [paralyzed](3-Mechanics/CLI/rules/conditions.md#Paralyzed),\
  \ [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned), [stunned](3-Mechanics/CLI/rules/conditions.md#Stunned)"
"gear":
  - "[shortsword](3-Mechanics/CLI/items/shortsword.md)"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., passive\
  \ Perception 13"
"languages": "Common, Infernal"
"cr": "5"
"traits":
  - "desc": "Lynx's crystal eye is a magically shrunken crystal ball of true seeing.\
      \ One of her teeth is a refashioned ring of mind shielding, while another has\
      \ been magicked to place her under a permanent [Nystul's magic aura](3-Mechanics/CLI/spells/nystuls-magic-aura.md)\
      \ spell, concealing the magic of these items and hiding her true nature from\
      \ magic or features that can detect undead."
    "name": "Special Equipment"
  - "desc": "If Lynx takes fire damage, she has disadvantage on attack rolls and ability\
      \ checks until the end of her next turn."
    "name": "Aversion of Fire"
  - "desc": "Lynx is immune to any spell or effect that would alter her form."
    "name": "Immutable Form"
  - "desc": "Whenever Lynx is subjected to lightning damage, she takes no damage and\
      \ instead regains a number of hit points equal to the lightning damage dealt."
    "name": "Lightning Absorption"
  - "desc": "Lynx has advantage on saving throws against spells and other magical\
      \ effects."
    "name": "Magic Resistance"
  - "desc": "Lynx regains 10 hit points at the start of her turn. If she takes fire\
      \ or radiant damage, this trait doesn't function at the start of her next turn.\
      \ Lynx's body is destroyed only if she starts her turn with 0 hit points and\
      \ doesn't regenerate."
    "name": "Regeneration"
  - "desc": "Lynx is immune to effects that turn undead."
    "name": "Turn Immunity"
"actions":
  - "desc": "Lynx makes two shortsword attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +7 to hit, reach 5 ft., one target. *Hit:* 7\
      \ (1d6 + 4) piercing damage."
    "name": "Shortsword"
"source":
  - "IMR"
"image": "3-Mechanics/CLI/bestiary/npc/token/lynx-creatlach-imr.webp"
```
^statblock