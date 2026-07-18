---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: "K'Tulah"
Status: WIP
linter-yaml-title-alias: "K'Tulah"
tags:
  - Monster/Größe/Mittelgroß
  - Monster/HG/2
  - Monster/Typ/Humanoid/tabaxi
  - Quelle/5e/cm
aliases:
  - "K'Tulah"
---
# [K'Tulah](3-Mechanics\CLI\bestiary\npc/ktulah-cm.md)
*Source: Candlekeep Mysteries p. 64*  

K'Tulah is a gregarious tabaxi, a catlike humanoid. She arrived at Candlekeep six days ago and received permission to use the library to conduct her research on regional forms of folk magic.

She is an animated talker whose exaggerated gesticulations while chatting annoy Varnyr, but the elf appreciates her academic expertise.

```statblock
"name": "K'Tulah (CM)"
"size": "Medium"
"type": "humanoid"
"subtype": "tabaxi"
"alignment": "Neutral Good"
"ac": !!int "11"
"hp": !!int "27"
"hit_dice": "5d8 + 5"
"modifier": !!int "1"
"stats":
  - !!int "10"
  - !!int "12"
  - !!int "13"
  - !!int "12"
  - !!int "15"
  - !!int "11"
"speed": "30 ft."
"skillsaves":
  - "name": "Medicine"
    "desc": "+4"
  - "name": "Nature"
    "desc": "+3"
  - "name": "Perception"
    "desc": "+4"
"senses": "darkvision 60 ft., passive Perception 14"
"languages": "Common, Druidic"
"cr": "2"
"traits":
  - "desc": "K'Tulah is a 4th-level spellcaster. K'Tulah's spellcasting ability is\
      \ Wisdom (spell save DC 12, +4 to hit with spell attacks). K'Tulah has the following\
      \ druid spells prepared:\n\n**Cantrips (at will):** druidcraft, produce flame,\
      \ shillelagh\n\n**1st level (4 slots):** entangle, longstrider, speak with animals,\
      \ thunderwave\n\n**2nd level (3 slots):** animal messenger, barkskin"
    "name": "Spellcasting"
  - "desc": "When K'Tulah moves on her turn in combat, she can double her speed until\
      \ the end of the turn. Once she uses this ability, K'Tulah can't use it again\
      \ until she moves 0 feet on one of her turns."
    "name": "Feline Agility"
"actions":
  - "desc": "*Melee Weapon Attack:* +2 to hit (+4 to hit with shillelagh), reach 5\
      \ ft., one target. *Hit:* 3 (1d6) bludgeoning damage, 4 (1d8) bludgeoning damage\
      \ if wielded with two hands, or 6 (1d8 + 2) bludgeoning damage with shillelagh."
    "name": "Quarterstaff"
  - "desc": "*Melee Weapon Attack:* +2 to hit, reach 5 ft., one target. *Hit:* 2 (1d4)\
      \ slashing damage."
    "name": "Claws"
"source":
  - "CM"
"image": "/3-Mechanics/CLI/bestiary/npc/token/ktulah-cm.webp"
```
^statblock