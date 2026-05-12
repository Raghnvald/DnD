---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/qftis
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/any-race
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Isabela Folcarae"
---
# [Isabela Folcarae](3-Mechanics/CLI/bestiary/npc/isabela-folcarae-qftis.md)
*Source: Quests from the Infinite Staircase p. 79*  

```statblock
"name": "Isabela Folcarae (QftIS)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Lawful Good"
"ac": !!int "15"
"ac_class": "[studded leather](3-Mechanics/CLI/items/studded-leather-armor.md)"
"hp": !!int "65"
"hit_dice": "10d8 + 20"
"modifier": !!int "3"
"stats":
  - !!int "15"
  - !!int "16"
  - !!int "14"
  - !!int "14"
  - !!int "11"
  - !!int "14"
"speed": "30 ft."
"saves":
  - "strength": !!int "4"
  - "dexterity": !!int "5"
  - "wisdom": !!int "2"
"skillsaves":
  - "name": "[Athletics](3-Mechanics/CLI/rules/skills.md#Athletics)"
    "desc": "+4"
  - "name": "[Deception](3-Mechanics/CLI/rules/skills.md#Deception)"
    "desc": "+4"
"gear":
  - "[dagger](3-Mechanics/CLI/items/dagger.md)"
  - "[scimitar](3-Mechanics/CLI/items/scimitar.md)"
"senses": "passive Perception 10"
"languages": "any two languages"
"cr": "2"
"actions":
  - "desc": "Isabela makes three melee attacks: two with its scimitar and one with\
      \ its dagger. Or Isabela makes two ranged attacks with its daggers."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one target. *Hit:* 6\
      \ (1d6 + 3) slashing damage."
    "name": "Scimitar"
  - "desc": "*Melee  or Ranged Weapon Attack:* +5 to hit, reach 5 ft. or range 20/60\
      \ ft., one target. *Hit:* 5 (1d4 + 3) piercing damage."
    "name": "Dagger"
"reactions":
  - "desc": "Isabela adds 2 to its AC against one melee attack that would hit it.\
      \ To do so, Isabela must see the attacker and be wielding a melee weapon."
    "name": "Parry"
"source":
  - "QftIS"
"image": "3-Mechanics/CLI/bestiary/npc/token/isabela-folcarae-qftis.webp"
```
^statblock