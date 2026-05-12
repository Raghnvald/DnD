---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/oota
- ttrpg-cli/monster/cr/1-4
- ttrpg-cli/monster/size/small
- ttrpg-cli/monster/type/humanoid/goblinoid
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Spiderbait"
---
# [Spiderbait](3-Mechanics/CLI/bestiary/npc/spiderbait-oota.md)
*Source: Out of the Abyss p. 31*  

```statblock
"name": "Spiderbait (OotA)"
"size": "Small"
"type": "humanoid"
"subtype": "goblinoid"
"alignment": "Neutral"
"ac": !!int "15"
"ac_class": "[leather armor](3-Mechanics/CLI/items/leather-armor.md), [shield](3-Mechanics/CLI/items/shield.md)"
"hp": !!int "7"
"hit_dice": "2d6"
"modifier": !!int "2"
"stats":
  - !!int "8"
  - !!int "14"
  - !!int "10"
  - !!int "10"
  - !!int "8"
  - !!int "8"
"speed": "30 ft."
"skillsaves":
  - "name": "[Acrobatics](3-Mechanics/CLI/rules/skills.md#Acrobatics)"
    "desc": "+6"
  - "name": "[Athletics](3-Mechanics/CLI/rules/skills.md#Athletics)"
    "desc": "+3"
  - "name": "[Stealth](3-Mechanics/CLI/rules/skills.md#Stealth)"
    "desc": "+6"
"gear":
  - "[scimitar](3-Mechanics/CLI/items/scimitar.md)"
  - "[shortbow](3-Mechanics/CLI/items/shortbow.md)"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., passive\
  \ Perception 9"
"languages": "Common, Goblin"
"cr": "1/4"
"traits":
  - "desc": "Spiderbait can take the [Disengage](3-Mechanics/CLI/rules/actions.md#Disengage)\
      \ or [Hide](3-Mechanics/CLI/rules/actions.md#Hide) action as a bonus action\
      \ on each of its turns."
    "name": "Nimble Escape"
  - "desc": "Spiderbait has advantage on checks made to avoid being [surprised](3-Mechanics/CLI/rules/conditions.md#Surprised)."
    "name": "Thrill-Seeker"
"actions":
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one target. *Hit:* 5\
      \ (1d6 + 2) slashing damage."
    "name": "Scimitar"
  - "desc": "*Ranged Weapon Attack:* +4 to hit, range 80/320 ft., one target. *Hit:*\
      \ 5 (1d6 + 2) piercing damage."
    "name": "Shortbow"
"source":
  - "OotA"
"image": "3-Mechanics/CLI/bestiary/npc/token/spiderbait-oota.webp"
```
^statblock