---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/egw
- ttrpg-cli/monster/cr/5
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/any-race
statblock: inline
statblock-link: "#^statblock"
aliases:
- Blood Hunter
---
# [Blood Hunter](3-Mechanics\CLI\bestiary\humanoid/blood-hunter-egw.md)
*Source: Explorer's Guide to Wildemount p. 284*  

To mortals and monsters alike, the blood hunter is a legendary figure—a humanoid stalker said to embrace monstrous power. Long years ago, a group of mortals undertook dark rituals and alchemical experiments to gain the power of the deadliest monsters, allowing them to better hunt those monsters.

Blood hunters are steely on the surface, but roiling emotion lies beneath that impassive mask. Bestial fury and fathomless sorrow drive every stroke of a blood hunter's blade. Humanoids who draw the ire of a blood hunter are often in league with monsters—or the victims of a terrible misunderstanding. Such misunderstandings are tough to clear up, for blood hunters are the kind of folk to slay first and ask questions later.

```statblock
"name": "Blood Hunter (EGW)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Any alignment"
"ac": !!int "16"
"ac_class": "[half plate](/3-Mechanics/CLI/items/half-plate-armor-xphb.md)"
"hp": !!int "65"
"hit_dice": "10d8 + 20"
"modifier": !!int "1"
"stats":
  - !!int "18"
  - !!int "12"
  - !!int "15"
  - !!int "9"
  - !!int "16"
  - !!int "11"
"speed": "30 ft."
"saves":
  - "strength": !!int "7"
  - "wisdom": !!int "6"
"skillsaves":
  - "name": "[Acrobatics](/3-Mechanics/CLI/skills.md#Acrobatics)"
    "desc": "+4"
  - "name": "[Insight](/3-Mechanics/CLI/skills.md#Insight)"
    "desc": "+6"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+6"
"senses": "[darkvision](/3-Mechanics/CLI/senses.md#Darkvision) 60 ft., passive Perception\
  \ 16"
"languages": "any one language (usually Common)"
"cr": "5"
"traits":
  - "desc": "The blood hunter can innately cast [hex](/3-Mechanics/CLI/spells/hex-xphb.md).\
      \ Its innate spellcasting ability is Intelligence.\n"
    "name": "Innate Spellcasting (1/Day)"
  - "desc": "As a bonus action, the blood hunter targets one creature it can see within\
      \ 30 feet of it. The target must succeed on a DC 14 Strength saving throw or\
      \ have its speed reduced to 0 and be unable to take reactions. The target can\
      \ repeat the saving throw at the end of each of its turns, ending the effect\
      \ on itself on a success."
    "name": "Blood Curse of Binding (1/Day)"
  - "desc": "The blood hunter has advantage on melee attack rolls against any creature\
      \ that doesn't have all its hit points."
    "name": "Blood Frenzy"
  - "desc": "The blood hunter has advantage on saving throws against spells and other\
      \ magical effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "The blood hunter attacks twice with a weapon."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +7 to hit, reach 5 ft., one target. *Hit:* 11\
      \ (2d6 + 4) slashing damage plus 3 (1d6) fire damage."
    "name": "Greatsword"
  - "desc": "*Ranged Weapon Attack:* +4 to hit, range 100/400 ft., one target. *Hit:*\
      \ 6 (1d10 + 1) piercing damage."
    "name": "Heavy Crossbow"
"source":
  - "EGW"
"image": "/3-Mechanics/CLI/bestiary/humanoid/token/blood-hunter-egw.webp"
```
^statblock