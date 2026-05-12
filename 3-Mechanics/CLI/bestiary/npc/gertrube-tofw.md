---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/tofw
- ttrpg-cli/monster/cr/1-2
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/human
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Gertrube"
---
# [Gertrube](3-Mechanics/CLI/bestiary/npc/gertrube-tofw.md)
*Source: Turn of Fortune's Wheel p. 18*  

```statblock
"name": "Gertrube (ToFW)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Chaotic Evil"
"ac": !!int "11"
"ac_class": "[leather armor](3-Mechanics/CLI/items/leather-armor-xphb.md)"
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
  - "[heavy crossbow](3-Mechanics/CLI/items/heavy-crossbow-xphb.md)"
  - "[mace](3-Mechanics/CLI/items/mace-xphb.md)"
"senses": "passive Perception 10"
"languages": "any one language (usually Common)"
"cr": "1/2"
"traits":
  - "desc": "Gertrube has advantage on an attack roll against a creature if at least\
      \ one of Gertrube's allies is within 5 feet of the creature and the ally isn't\
      \ [incapacitated](3-Mechanics/CLI/rules/conditions.md#Incapacitated)."
    "name": "Pack Tactics"
"actions":
  - "desc": "Gertrube makes two melee attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one creature. *Hit:*\
      \ 5 (1d6 + 2) bludgeoning damage."
    "name": "Mace"
  - "desc": "*Ranged Weapon Attack:* +2 to hit, range 100/400 ft., one target. *Hit:*\
      \ 5 (1d10) piercing damage."
    "name": "Heavy Crossbow"
"source":
  - "ToFW"
"image": "3-Mechanics/CLI/bestiary/npc/token/gertrube-tofw.webp"
```
^statblock