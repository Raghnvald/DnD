---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Oracs the Enduring
linter-yaml-title-alias: Oracs the Enduring
tags:
  - Monster/Größe/Gigantisch
  - Monster/HG/21
  - Monster/Typ/Drache
  - Quelle/5e/egw
aliases:
  - Oracs the Enduring
---
# [Oracs the Enduring](3-Mechanics\CLI\bestiary\npc/oracs-the-enduring-egw.md)
*Source: Explorer's Guide to Wildemount p. 154*  

```statblock
"name": "Oracs the Enduring (EGW)"
"size": "Gargantuan"
"type": "dragon"
"alignment": "Chaotic Evil"
"ac": !!int "22"
"ac_class": "natural armor"
"hp": !!int "367"
"hit_dice": "21d20 + 147"
"modifier": !!int "2"
"stats":
  - !!int "27"
  - !!int "14"
  - !!int "25"
  - !!int "16"
  - !!int "15"
  - !!int "19"
"speed": "40 ft., fly 80 ft., swim 40 ft."
"saves":
  - "dexterity": !!int "9"
  - "constitution": !!int "14"
  - "wisdom": !!int "9"
  - "charisma": !!int "11"
"skillsaves":
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+16"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+9"
"damage_resistances": "necrotic"
"damage_immunities": "acid, poison"
"condition_immunities": "[charmed](/3-Mechanics/CLI/conditions.md#Charmed), [frightened](/3-Mechanics/CLI/conditions.md#Frightened),\
  \ [paralyzed](/3-Mechanics/CLI/conditions.md#Paralyzed), [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned),\
  \ [exhaustion](/3-Mechanics/CLI/conditions.md#Exhaustion)"
"senses": "[blindsight](/3-Mechanics/CLI/senses.md#Blindsight) 60 ft., [darkvision](/3-Mechanics/CLI/senses.md#Darkvision)\
  \ 120 ft., passive Perception 26"
"languages": "Common, Draconic"
"cr": "21"
"traits":
  - "desc": "If the dracolich fails a saving throw, it can choose to succeed instead."
    "name": "Legendary Resistance (3/Day)"
  - "desc": "The dracolich has advantage on saving throws against spells and other\
      \ magical effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "The dracolich can use its Frightful Presence. It then makes three attacks:\
      \ one with its bite and two with its claws."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +15 to hit, reach 15 ft., one target. *Hit:* 19\
      \ (2d10 + 8) piercing damage plus 9 (2d8) acid damage."
    "name": "Bite"
  - "desc": "*Melee Weapon Attack:* +15 to hit, reach 10 ft., one target. *Hit:* 15\
      \ (2d6 + 8) slashing damage."
    "name": "Claw"
  - "desc": "*Melee Weapon Attack:* +15 to hit, reach 20 ft., one target. *Hit:* 17\
      \ (2d8 + 8) bludgeoning damage."
    "name": "Tail"
  - "desc": "Each creature of the dracolich's choice that is within 120 feet of the\
      \ dracolich and aware of it must succeed on a DC 19 Wisdom saving throw or become\
      \ [frightened](/3-Mechanics/CLI/conditions.md#Frightened) for 1 minute. A creature\
      \ can repeat the saving throw at the end of each of its turns, ending the effect\
      \ on itself on a success. If a creature's saving throw is successful or the\
      \ effect ends for it, the creature is immune to the dracolich's Frightful Presence\
      \ for the next 24 hours."
    "name": "Frightful Presence"
  - "desc": "The dracolich exhales acid in a 90-foot line that is 10 feet wide. Each\
      \ creature in that line must make a DC 22 Dexterity saving throw, taking 67\
      \ (15d8) acid damage on a failed save, or half as much damage on a successful\
      \ one."
    "name": "Acid Breath (Recharge 5-6)"
"legendary_description": "Legendary Action Uses: 3. Immediately after another creature's\
  \ turn, Oracs can expend a use to take one of the following actions. Oracs regains\
  \ all expended uses at the start of each of their turns."
"legendary_actions":
  - "desc": "The dracolich makes a Wisdom ([Perception](/3-Mechanics/CLI/skills.md#Perception))\
      \ check."
    "name": "Detect"
  - "desc": "The dracolich makes a tail attack."
    "name": "Tail Attack"
  - "desc": "The dracolich beats its wings. Each creature within 15 feet of the dracolich\
      \ must succeed on a DC 23 Dexterity saving throw or take 15 (2d6 + 8) bludgeoning\
      \ damage and be knocked [prone](/3-Mechanics/CLI/conditions.md#Prone). The dracolich\
      \ can then fly up to half its flying speed."
    "name": "Wing Attack (Costs 2 Actions)"
"source":
  - "EGW"
"image": "/3-Mechanics/CLI/bestiary/npc/token/oracs-the-enduring-egw.webp"
```
^statblock