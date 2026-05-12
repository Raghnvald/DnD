---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/qftis
- ttrpg-cli/monster/cr/1-8
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Guardian of Gorm"
---
# [Guardian of Gorm](3-Mechanics/CLI/bestiary/humanoid/guardian-of-gorm-qftis.md)
*Source: Quests from the Infinite Staircase p. 203*  

Guardians are the fearless rank and file of their faction.

## Guardians of Gorm

The Guardians of Gorm are stalwart Cynidiceans who worship Gorm, an ancient god of justice, storms, and war. Members of the order wear brass masks bearing the face of their god, who is depicted as a long-haired, bearded man with a stern gaze. Each fully initiated guardian has a small blue lightning bolt tattooed on their right shoulder. Guardians follow a strict code of decorum that values bravery, honesty, and justice tempered with mercy. Still, they are quick to chastise blasphemers, criminals, and cultists who oppose their cause, buffeting these foes with their shocking implements.

```statblock
"name": "Guardian of Gorm (QftIS)"
"size": "Medium"
"type": "humanoid"
"alignment": "typically  Lawful Good"
"ac": !!int "16"
"ac_class": "[chain mail](3-Mechanics/CLI/items/chain-mail.md)"
"hp": !!int "9"
"hit_dice": "2d8"
"modifier": !!int "0"
"stats":
  - !!int "15"
  - !!int "10"
  - !!int "10"
  - !!int "10"
  - !!int "13"
  - !!int "12"
"speed": "30 ft."
"skillsaves":
  - "name": "[Athletics](3-Mechanics/CLI/rules/skills.md#Athletics)"
    "desc": "+4"
  - "name": "[Insight](3-Mechanics/CLI/rules/skills.md#Insight)"
    "desc": "+3"
  - "name": "[Religion](3-Mechanics/CLI/rules/skills.md#Religion)"
    "desc": "+2"
"gear":
  - "[handaxe](3-Mechanics/CLI/items/handaxe.md)"
"senses": "passive Perception 11"
"languages": "Common"
"cr": "1/8"
"traits":
  - "desc": "The guardian has advantage on saving throws against the [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened)\
      \ condition."
    "name": "Brave"
"actions":
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one target. *Hit:* 5\
      \ (1d6 + 2) piercing damage plus 2 (1d4) lightning damage."
    "name": "Lightning Mace"
  - "desc": "*Melee  or Ranged Weapon Attack:* +4 to hit, reach 5 ft. or range 20/60\
      \ ft., one target. *Hit:* 5 (1d6 + 2) slashing damage."
    "name": "Handaxe"
"source":
  - "QftIS"
"image": "3-Mechanics/CLI/bestiary/humanoid/token/guardian-of-gorm-qftis.webp"
```
^statblock