---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/nrh-at
- ttrpg-cli/monster/cr/5
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/human
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Mr. Greystone"
---
# [Mr. Greystone](3-Mechanics/CLI/bestiary/npc/mr-greystone-nrh-at.md)
*Source: NERDS Restoring Harmony: Adventure Together p. 13*  

```statblock
"name": "Mr. Greystone (NRH-AT)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Lawful Evil"
"ac": !!int "15"
"ac_class": "[studded leather](3-Mechanics/CLI/items/studded-leather-armor.md)"
"hp": !!int "112"
"hit_dice": "15d8 + 45"
"modifier": !!int "2"
"stats":
  - !!int "18"
  - !!int "15"
  - !!int "16"
  - !!int "10"
  - !!int "12"
  - !!int "15"
"speed": "30 ft."
"saves":
  - "strength": !!int "7"
  - "dexterity": !!int "5"
  - "constitution": !!int "6"
"skillsaves":
  - "name": "[Athletics](3-Mechanics/CLI/rules/skills.md#Athletics)"
    "desc": "+10"
  - "name": "[Intimidation](3-Mechanics/CLI/rules/skills.md#Intimidation)"
    "desc": "+5"
"gear":
  - "[club](3-Mechanics/CLI/items/club.md)"
  - "[hand crossbow](3-Mechanics/CLI/items/hand-crossbow.md)"
"senses": "passive Perception 11"
"languages": "Common, Goblin"
"cr": "5"
"traits":
  - "desc": "Mr. Greystone has advantage on saving throws against being [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened)."
    "name": "Brave"
  - "desc": "A melee weapon deals one extra die of its damage when Mr. Greystone hits\
      \ with it (included in the attack)."
    "name": "Brute"
"actions":
  - "desc": "Mr. Greystone makes two melee attacks or two ranged attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +7 to hit, reach 5 ft., one target. *Hit:* 11\
      \ (2d6 + 4) bludgeoning damage."
    "name": "Club"
  - "desc": "*Ranged Weapon Attack:* +5 to hit, range 30/120 ft., one target. *Hit:*\
      \ 5 (1d6 + 2) piercing damage."
    "name": "Hand Crossbow"
"source":
  - "NRH-AT"
"image": "3-Mechanics/CLI/bestiary/npc/token/mr-greystone-nrh-at.webp"
```
^statblock