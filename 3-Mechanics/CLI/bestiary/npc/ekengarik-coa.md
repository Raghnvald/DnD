---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/coa
- ttrpg-cli/monster/cr/16
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/fiend
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Ekengarik"
---
# [Ekengarik](3-Mechanics/CLI/bestiary/npc/ekengarik-coa.md)
*Source: Chains of Asmodeus p. 141*  

```statblock
"name": "Ekengarik (CoA)"
"size": "Large"
"type": "fiend"
"alignment": "Lawful Evil"
"ac": !!int "16"
"ac_class": "natural armor"
"hp": !!int "231"
"hit_dice": "22d10 + 110"
"modifier": !!int "3"
"stats":
  - !!int "23"
  - !!int "16"
  - !!int "21"
  - !!int "14"
  - !!int "17"
  - !!int "21"
"speed": "30 ft."
"saves":
  - "constitution": !!int "10"
  - "charisma": !!int "10"
"skillsaves":
  - "name": "Deception"
    "desc": "+10"
  - "name": "Insight"
    "desc": "+8"
  - "name": "Persuasion"
    "desc": "+10"
"damage_resistances": "acid; lightning; bludgeoning, piercing, slashing from nonmagical\
  \ attacks"
"damage_immunities": "cold, fire, poison"
"condition_immunities": "charmed, poisoned"
"senses": "blindsight 30 ft., darkvision 120 ft., passive Perception 13"
"languages": "Common, Formian, telepathy 120 ft."
"cr": "16"
"traits":
  - "desc": "All fiendish formians within 1 mile of Ekengarik can telepathically communicate\
      \ with each other and Ekengarik."
    "name": "Hive Mind"
  - "desc": "Ekengarik regenerates 10 hit points at the start of her turn, unless\
      \ she took radiant damage in the last round."
    "name": "Regeneration"
"actions":
  - "desc": "Ekengarik makes three Bite attacks. She can replace one of the attacks\
      \ with an Acid Spray (if available) attack or a use of Spellcasting."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +11 to hit, reach 5 ft., one target. *Hit:*\
      \ 15 (2d8 + 6) piercing damage and the target must make a DC 19 Constitution\
      \ saving throw. On a failed save, the target's Strength score is reduced by\
      \ 2 (1d4). The target dies if this reduces its Strength to 0. Otherwise, the\
      \ reduction lasts until the target finishes a short or long rest."
    "name": "Bite"
  - "desc": "Ekengarik spits acid at one creature within 60 feet of her, or two creatures\
      \ within 60 feet of her and 5 feet of each other. Targets must make a DC 18\
      \ Dexterity saving throw, taking 33 (6d10) acid damage on a failed saving\
      \ throw, or half as much on a successful one."
    "name": "Acid Spray (Recharge 5-6)"
  - "desc": "Ekengarik casts one of the following spells, requiring no material components\
      \ and using Charisma as the spellcasting ability (spell save DC 18):\n\n**At\
      \ will:** Detect Magic, Dispel Magic, Heroism, Magic Missile\n\n**1/day each:**\
      \ Evard's Black Tentacles, Cone of Cold, Confusion, Dimension Door, Geas, Invisibility,\
      \ Prismatic Wall, Slow"
    "name": "Spellcasting"
"reactions":
  - "desc": "When hit with an attack, Ekengarik temporarily hardens her carapace,\
      \ reducing her speed to 0 and increasing her AC by 5 until the start of her\
      \ next turn."
    "name": "Hardened Carapace (Recharge 4-6)"
"source":
  - "CoA"
"image": "3-Mechanics/CLI/bestiary/npc/token/ekengarik-coa.webp"
```
^statblock