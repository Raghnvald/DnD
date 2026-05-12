---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/coa
- ttrpg-cli/monster/cr/18
- ttrpg-cli/monster/size/gargantuan
- ttrpg-cli/monster/type/elemental
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Waeloquay"
---
# [Waeloquay](3-Mechanics/CLI/bestiary/npc/waeloquay-coa.md)
*Source: Chains of Asmodeus p. 175*  

```statblock
"name": "Waeloquay (CoA)"
"size": "Gargantuan"
"type": "elemental"
"alignment": "Neutral Evil"
"ac": !!int "14"
"ac_class": "natural armor"
"hp": !!int "290"
"hit_dice": "20d20 + 80"
"modifier": !!int "2"
"stats":
  - !!int "26"
  - !!int "14"
  - !!int "18"
  - !!int "8"
  - !!int "10"
  - !!int "12"
"speed": "30 ft., swim 90 ft."
"saves":
  - "wisdom": !!int "6"
  - "charisma": !!int "7"
"skillsaves":
  - "name": "Athletics"
    "desc": "+14"
  - "name": "Nature"
    "desc": "+5"
"damage_resistances": "acid; bludgeoning, piercing, slashing from nonmagical attacks"
"damage_immunities": "poison"
"condition_immunities": "exhaustion, grappled, paralyzed, petrified, poisoned, prone,\
  \ restrained, unconscious"
"senses": "darkvision 60 ft., passive Perception 10"
"languages": "Aquan, Common"
"cr": "18"
"traits":
  - "desc": "Waeloquay has advantage on saving throws against spells and other magical\
      \ effects."
    "name": "Magic Resistance"
  - "desc": "If Waeloquay fails a saving throw, he can choose to succeed instead."
    "name": "Legendary Resistance (3/Day)"
  - "desc": "Waeloquay can enter a hostile creature's space and stop there. It can\
      \ move through a space as narrow as 1 inch wide without squeezing."
    "name": "Water Form"
"actions":
  - "desc": "Waeloquay makes three Slam attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +14 to hit, reach 15 ft., one target. *Hit:*\
      \ 26 (4d8 + 8) bludgeoning damage."
    "name": "Slam"
  - "desc": "Each creature in Waeloquay's space must make a DC 22 Strength saving\
      \ throw. On a failed save, a target takes 21 (3d8 + 8) bludgeoning damage.\
      \ If it is Large or smaller, it also has the grappled condition (escape DC 20).\
      \ Until this grapple ends, the target is restrained and unable to breathe, unless\
      \ it can breathe water. If the save is successful, the target is pushed out\
      \ of Waeloquay's space. Waeloquay can grapple one Large creature or up to four\
      \ Medium or smaller creatures at one time. At the start of each of Waeloquay's\
      \ turns, each target grappled by it takes 21 (3d8 + 8) bludgeoning damage.\
      \ A creature within 5 feet of Waeloquay can pull a creature or object out of\
      \ it by taking an action to make a DC 22 Strength check and succeeding."
    "name": "Whelm (Recharge 4-6)"
"legendary_description": "Legendary Action Uses: 3. Immediately after another creature's\
  \ turn, Waeloquay can expend a use to take one of the following actions. Waeloquay\
  \ regains all expended uses at the start of each of their turns."
"legendary_actions":
  - "desc": "Waeloquay moves up to its speed."
    "name": "Flow"
  - "desc": "One creature that Waeloquay is grappling takes 44 (8d8 + 8) bludgeoning\
      \ damage."
    "name": "Crush (Costs 2 Actions)"
  - "desc": "Waeloquay makes a Slam attack with advantage."
    "name": "Pummel (Costs 2 Actions)"
"source":
  - "CoA"
"image": "3-Mechanics/CLI/bestiary/npc/token/waeloquay-coa.webp"
```
^statblock