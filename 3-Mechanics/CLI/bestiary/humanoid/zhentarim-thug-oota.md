---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/oota
- ttrpg-cli/monster/cr/1-2
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/human
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Zhentarim Thug"
---
# [Zhentarim Thug](3-Mechanics/CLI/bestiary/humanoid/zhentarim-thug-oota.md)
*Source: Out of the Abyss p. 131*  

```statblock
"name": "Zhentarim Thug (OotA)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Neutral"
"ac": !!int "11"
"ac_class": "[leather armor](3-Mechanics/CLI/items/leather-armor.md)"
"hp": !!int "32"
"hit_dice": "5d8 + 10"
"modifier": !!int "0"
"stats":
  - !!int "15"
  - !!int "11"
  - !!int "14"
  - !!int "10"
  - !!int "10"
  - !!int "11"
"speed": "30 ft."
"skillsaves":
  - "name": "[Intimidation](3-Mechanics/CLI/rules/skills.md#Intimidation)"
    "desc": "+2"
"gear":
  - "[heavy crossbow](3-Mechanics/CLI/items/heavy-crossbow.md)"
  - "[mace](3-Mechanics/CLI/items/mace.md)"
"senses": "passive Perception 10"
"languages": "Common"
"cr": "1/2"
"traits":
  - "desc": "The thug has advantage on an attack roll against a creature if at least\
      \ one of the thug's allies is within 5 feet of the creature and the ally isn't\
      \ [incapacitated](3-Mechanics/CLI/rules/conditions.md#Incapacitated)."
    "name": "Pack Tactics"
"actions":
  - "desc": "The thug makes two melee attacks"
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one target. *Hit:* 5\
      \ (1d6 + 2) bludgeoning damage."
    "name": "Mace"
  - "desc": "*Ranged Weapon Attack:* +2 to hit, range 100/400 ft., one target. *Hit:*\
      \ 5 (1d10) piercing damage."
    "name": "Heavy Crossbow"
"source":
  - "OotA"
"image": "3-Mechanics/CLI/bestiary/humanoid/token/zhentarim-thug-oota.webp"
```
^statblock