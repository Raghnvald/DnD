---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/qftis
- ttrpg-cli/monster/cr/4
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/plant
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Horrid Plant Purple Blossom"
---
# [Horrid Plant Purple Blossom](3-Mechanics/CLI/bestiary/plant/horrid-plant-purple-blossom-qftis.md)
*Source: Quests from the Infinite Staircase p. 204*  

```statblock
"name": "Horrid Plant Purple Blossom (QftIS)"
"size": "Large"
"type": "plant"
"alignment": "Unaligned"
"ac": !!int "6"
"hp": !!int "42"
"hit_dice": "5d10 + 15"
"modifier": !!int "-4"
"stats":
  - !!int "18"
  - !!int "3"
  - !!int "17"
  - !!int "1"
  - !!int "10"
  - !!int "1"
"speed": "5 ft."
"condition_immunities": "[blinded](3-Mechanics/CLI/rules/conditions.md#Blinded), [deafened](3-Mechanics/CLI/rules/conditions.md#Deafened)"
"senses": "[blindsight](3-Mechanics/CLI/rules/senses.md#Blindsight) 60 ft. (can't\
  \ see beyond this radius), passive Perception 10"
"languages": ""
"cr": "4"
"traits":
  - "desc": "If the horrid plant is motionless at the start of combat, it has advantage\
      \ on its initiative roll. Moreover, if a creature hasn't observed the horrid\
      \ plant move or act, that creature must succeed on a DC 18 Intelligence ([Nature](3-Mechanics/CLI/rules/skills.md#Nature))\
      \ check to discern that the horrid plant isn't an ordinary plant."
    "name": "False Appearance"
"actions":
  - "desc": "The horrid plant makes two Tendril attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +6 to hit, reach 30 ft., one target. *Hit:*\
      \ 7 (2d6) bludgeoning damage. If the target is a Huge or smaller creature,\
      \ it has the [grappled](3-Mechanics/CLI/rules/conditions.md#Grappled) condition\
      \ (escape DC 14), and the horrid plant can pull the target up to 25 feet closer\
      \ to itself. Until the grapple ends, the target has the [restrained](3-Mechanics/CLI/rules/conditions.md#Restrained)\
      \ condition, and the horrid plant can't use the same tendril on another target.\
      \ The horrid plant has two tendrils."
    "name": "Tendril"
"bonus_actions":
  - "desc": "The horrid plant targets one creature it can see within 15 feet of itself.\
      \ The target must succeed on a DC 14 Dexterity saving throw or take 28 (8d6)\
      \ acid damage and become covered in acidic sap. This sap lasts for 1 minute\
      \ or until a creature uses its action to scrape the sap off itself or another\
      \ creature it can reach. A creature covered in sap takes 14 (4d6) acid damage\
      \ at the start of each of its turns."
    "name": "Sap Squirt"
"source":
  - "QftIS"
```
^statblock