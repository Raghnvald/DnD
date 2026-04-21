---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Awakened White Moose
tags:
  - Monster/Größe/Groß
  - Monster/HG/3
  - Monster/Typ/Tier
  - Quelle/5e/idrotf
aliases:
  - Awakened White Moose
---
# [Awakened White Moose](3-Mechanics\CLI\bestiary\beast/awakened-white-moose-idrotf.md)
*Source: Icewind Dale: Rime of the Frostmaiden p. 82*  

A white moose is attacking loggers in the forest near Lonelywood. The town's logging industry is essential to the growth and survival of Ten-Towns, and Speaker Nimsy Huddle has assured the other speakers that Lonelywood's "moose problem" will be dealt with in short order. Hunters have been dispatched to kill the moose, but it has eluded them so far. From what the hunters have seen, their prey is smarter than the average moose, and its white hide makes it hard to spot in the snow. What they don't know is that the moose is using a magic mirror as a scrying device to show it where its enemies are.

```statblock
"name": "Awakened White Moose (IDRotF)"
"size": "Large"
"type": "beast"
"alignment": "Neutral Evil"
"ac": !!int "11"
"ac_class": "natural armor"
"hp": !!int "68"
"hit_dice": "8d10 + 24"
"modifier": !!int "0"
"stats":
  - !!int "19"
  - !!int "11"
  - !!int "16"
  - !!int "10"
  - !!int "12"
  - !!int "6"
"speed": "40 ft."
"senses": "passive Perception 11"
"languages": "Druidic"
"cr": "3"
"traits":
  - "desc": "If the moose moves at least 20 feet straight toward a target and then\
      \ hits it with an antlers attack on the same turn, the target takes an extra\
      \ 9 (2d8) bludgeoning damage. If the target is a creature, it must succeed on\
      \ a DC 14 Strength saving throw or be knocked prone."
    "name": "Charge"
  - "desc": "The moose has advantage on Strength and Dexterity saving throws made\
      \ against effects that would knock it prone."
    "name": "Sure-Footed"
"actions":
  - "desc": "The moose makes two attacks: one with its antlers and one with its hooves."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +6 to hit, reach 5 ft., one target. *Hit:* 13\
      \ (2d8 + 4) piercing damage."
    "name": "Antlers"
  - "desc": "*Melee Weapon Attack:* +6 to hit, reach 5 ft., one target. *Hit:* 9 (2d4\
      \ + 4) bludgeoning damage."
    "name": "Hooves"
"source":
  - "IDRotF"
"image": "/3-Mechanics/CLI/bestiary/beast/token/awakened-white-moose-idrotf.webp"
```
^statblock