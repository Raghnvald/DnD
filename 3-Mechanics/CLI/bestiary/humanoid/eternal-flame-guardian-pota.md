---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/pota
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/human
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Eternal Flame Guardian"
---
# [Eternal Flame Guardian](3-Mechanics/CLI/bestiary/humanoid/eternal-flame-guardian-pota.md)
*Source: Princes of the Apocalypse p. 200*  

Eternal Flame guardians are dullards fascinated by the power of fire and eager to show the cult's enemies firsthand what it feels like to burn. They light things aflame to honor elemental fire and just for entertainment, but they don't always think ahead about what else nearby might catch fire.

```statblock
"name": "Eternal Flame Guardian (PotA)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Chaotic Evil"
"ac": !!int "17"
"ac_class": "[breastplate](3-Mechanics/CLI/items/breastplate.md), [shield](3-Mechanics/CLI/items/shield.md);\
  \ 15 while using a crossbow"
"hp": !!int "45"
"hit_dice": "7d8 + 14"
"modifier": !!int "1"
"stats":
  - !!int "15"
  - !!int "13"
  - !!int "14"
  - !!int "8"
  - !!int "11"
  - !!int "13"
"speed": "30 ft."
"skillsaves":
  - "name": "[Intimidation](3-Mechanics/CLI/rules/skills.md#Intimidation)"
    "desc": "+3"
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+2"
"damage_resistances": "fire"
"gear":
  - "[heavy crossbow](3-Mechanics/CLI/items/heavy-crossbow.md)"
  - "[longsword](3-Mechanics/CLI/items/longsword.md)"
"senses": "passive Perception 12"
"languages": "Common"
"cr": "2"
"traits":
  - "desc": "As a bonus action, the guard can wreath one melee weapon it is wielding\
      \ in flame. The guard is unharmed by this fire, which lasts until the end of\
      \ the guard's next turn. While wreathed in flame, the weapon deals an extra\
      \ 3 (1d6) fire damage on a hit."
    "name": "Flaming Weapon (Recharges after a Short or Long Rest)"
"actions":
  - "desc": "The guard makes two melee attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one target. *Hit:* 6\
      \ (1d8 + 2) slashing damage."
    "name": "Longsword"
  - "desc": "*Ranged Weapon Attack:* +3 to hit, range 100/400 ft., one target. *Hit:*\
      \ 6 (1d10 + 1) piercing damage."
    "name": "Heavy Crossbow"
"source":
  - "PotA"
"image": "3-Mechanics/CLI/bestiary/humanoid/token/eternal-flame-guardian-pota.webp"
```
^statblock