---
obsidianUIMode: preview
cssclasses:
  - json5e-monster
tags:
  - Quelle/5e/tftyp
  - Monster/HG/5
  - Monster/Größe/Groß
  - Monster/Typ/Monstrosität
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Xilonen
---
# [Xilonen](3-Mechanics\CLI\bestiary\npc/xilonen-tftyp.md)
*Source: Tales from the Yawning Portal p. 83*  

```statblock
"name": "Xilonen (TftYP)"
"size": "Large"
"type": "monstrosity"
"alignment": "Neutral Evil"
"ac": !!int "20"
"ac_class": "natural armor"
"hp": !!int "93"
"hit_dice": "11d10 + 33"
"modifier": !!int "-1"
"stats":
  - !!int "18"
  - !!int "8"
  - !!int "17"
  - !!int "2"
  - !!int "16"
  - !!int "6"
"speed": "10 ft., climb 10 ft."
"skillsaves":
  - "name": "Perception"
    "desc": "+6"
  - "name": "Stealth"
    "desc": "+5"
"senses": "darkvision 60 ft., passive Perception 16"
"languages": ""
"cr": "5"
"traits":
  - "desc": "While Xilonen remains motionless, it is indistinguishable from a normal\
      \ cave formation, such as a stalagmite."
    "name": "False Appearance"
  - "desc": "Xilonen can have up to six tendrils at a time. Each tendril can be attacked\
      \ (AC 20; 10 hit points; immunity to poison and psychic damage). Destroying\
      \ a tendril deals no damage to Xilonen, which can extrude a replacement tendril\
      \ on its next turn. A tendril can also be broken if a creature takes an action\
      \ and succeeds on a DC 15 Strength check against it."
    "name": "Grasping Tendrils"
  - "desc": "Xilonen can climb difficult surfaces, including upside down on ceilings,\
      \ without needing to make an ability check."
    "name": "Spider Climb"
"actions":
  - "desc": "Xilonen makes four attacks with its tendrils, uses Reel, and makes one\
      \ attack with its bite."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +7 to hit, reach 5 ft., one target. *Hit:* 22\
      \ (4d8 + 4) piercing damage."
    "name": "Bite"
  - "desc": "*Melee Weapon Attack:* +7 to hit, reach 50 ft., one creature. *Hit:*\
      \ The target is grappled (escape DC 15). Until the grapple ends, the target\
      \ is restrained and has disadvantage on Strength checks and Strength saving\
      \ throws, and Xilonen can't use the same tendril on another target."
    "name": "Tendril"
  - "desc": "Xilonen pulls each creature grappled by it up to 25 feet straight toward\
      \ it."
    "name": "Reel"
"source":
  - "TftYP"
"image": "/3-Mechanics/CLI/bestiary/npc/token/xilonen-tftyp.webp"
```
^statblock