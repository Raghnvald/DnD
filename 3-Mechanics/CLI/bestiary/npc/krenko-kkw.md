---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/kkw
- ttrpg-cli/monster/cr/1
- ttrpg-cli/monster/size/small
- ttrpg-cli/monster/type/humanoid/goblinoid
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Krenko"
---
# [Krenko](3-Mechanics/CLI/bestiary/npc/krenko-kkw.md)
*Source: Krenko's Way p. 168*  

```statblock
"name": "Krenko (KKW)"
"size": "Small"
"type": "humanoid"
"subtype": "goblinoid"
"alignment": "Neutral Evil"
"ac": !!int "17"
"ac_class": "[chain shirt](3-Mechanics/CLI/items/chain-shirt.md), [shield](3-Mechanics/CLI/items/shield.md)"
"hp": !!int "21"
"hit_dice": "6d6"
"modifier": !!int "2"
"stats":
  - !!int "10"
  - !!int "14"
  - !!int "10"
  - !!int "10"
  - !!int "8"
  - !!int "14"
"speed": "30 ft."
"skillsaves":
  - "name": "[Stealth](3-Mechanics/CLI/rules/skills.md#Stealth)"
    "desc": "+6"
  - "name": "[Deception](3-Mechanics/CLI/rules/skills.md#Deception)"
    "desc": "+4"
  - "name": "[Persuasion](3-Mechanics/CLI/rules/skills.md#Persuasion)"
    "desc": "+4"
"gear":
  - "[light crossbow](3-Mechanics/CLI/items/light-crossbow.md)"
  - "[scimitar](3-Mechanics/CLI/items/scimitar.md)"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., passive\
  \ Perception 9"
"languages": "Common, Goblin"
"cr": "1"
"traits":
  - "desc": "Krenko can take the [Disengage](3-Mechanics/CLI/rules/actions.md#Disengage)\
      \ or [Hide](3-Mechanics/CLI/rules/actions.md#Hide) action as a bonus action\
      \ on each of his turns."
    "name": "Nimble Escape"
"actions":
  - "desc": "Krenko makes two attacks with his scimitar."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one target. *Hit:* 5\
      \ (1d6 + 2) slashing damage plus 2 (1d4) poison damage.."
    "name": "Scimitar"
  - "desc": "*Ranged Weapon Attack:* +4 to hit, range 80/320 ft., one target. *Hit:*\
      \ 6 (1d8 + 2) piercing damage."
    "name": "Light Crossbow"
"reactions":
  - "desc": "When a creature Krenko can see targets him with an attack, Krenko chooses\
      \ another goblin within 5 feet of him. The two goblins swap places, and the\
      \ chosen goblin becomes the target instead."
    "name": "Redirect Attack"
"source":
  - "KKW"
"image": "3-Mechanics/CLI/bestiary/npc/token/krenko-kkw.webp"
```
^statblock