---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/wbtw
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/orc
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Zarak"
---
# [Zarak](3-Mechanics/CLI/bestiary/npc/zarak-wbtw.md)
*Source: The Wild Beyond the Witchlight p. 222*  

Zarak is an assassin without honor or conscience. Unusually short of stature for someone of orcish heritage, he might pass for an ugly, beardless dwarf were it not for his rotting tusks and grayish pallor. The only thing he loves is money, and he wouldn't hesitate to stab allies in the back if they came between him and the riches he covets.

```statblock
"name": "Zarak (WBtW)"
"size": "Medium"
"type": "humanoid"
"subtype": "orc"
"alignment": "Chaotic Evil"
"ac": !!int "14"
"ac_class": "[leather armor](3-Mechanics/CLI/items/leather-armor-xphb.md)"
"hp": !!int "37"
"hit_dice": "5d8 + 15"
"modifier": !!int "3"
"stats":
  - !!int "13"
  - !!int "16"
  - !!int "16"
  - !!int "11"
  - !!int "15"
  - !!int "6"
"speed": "30 ft."
"saves":
  - "dexterity": !!int "5"
  - "intelligence": !!int "2"
"skillsaves":
  - "name": "[Acrobatics](3-Mechanics/CLI/rules/skills.md#Acrobatics)"
    "desc": "+7"
  - "name": "[Insight](3-Mechanics/CLI/rules/skills.md#Insight)"
    "desc": "+6"
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+6"
  - "name": "[Stealth](3-Mechanics/CLI/rules/skills.md#Stealth)"
    "desc": "+7"
"gear":
  - "[dagger](3-Mechanics/CLI/items/dagger-xphb.md)"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 60, passive Perception\
  \ 16"
"languages": "Common, Orc"
"cr": "2"
"traits":
  - "desc": "Zarak carries a [potion of invisibility](3-Mechanics/CLI/items/potion-of-invisibility-xdmg.md)."
    "name": "Special Equipment"
"actions":
  - "desc": "Zarak makes two Dagger attacks."
    "name": "Multiattack"
  - "desc": "*Melee  or Ranged Weapon Attack:* +5 to hit, reach 5 ft. or range 20/60\
      \ ft., one target. *Hit:* 5 (1d4 + 3) piercing damage, plus an extra 5 (2d4)\
      \ piercing damage if the target is a creature and Zarak has at least 18 hit\
      \ points."
    "name": "Dagger"
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one Humanoid. *Hit:*\
      \ 8 (2d4 + 3) slashing damage, and the target is [grappled](3-Mechanics/CLI/rules/conditions.md#Grappled)\
      \ (escape DC 11). Until this grapple ends, the target takes 8 (2d4 + 3) slashing\
      \ damage at the start of each of its turns, and Zarak can't grapple another\
      \ creature or use Assassin's Whim."
    "name": "Garrote"
"bonus_actions":
  - "desc": "Zarak takes the [Dash](3-Mechanics/CLI/rules/actions.md#Dash), [Disengage](3-Mechanics/CLI/rules/actions.md#Disengage),\
      \ or [Hide](3-Mechanics/CLI/rules/actions.md#Hide) action."
    "name": "Assassin's Whim"
"reactions":
  - "desc": "Zarak halves the damage he takes from an attack made against him, provided\
      \ he can see the attacker."
    "name": "Uncanny Dodge"
"source":
  - "WBtW"
"image": "3-Mechanics/CLI/bestiary/npc/token/zarak-wbtw.webp"
```
^statblock