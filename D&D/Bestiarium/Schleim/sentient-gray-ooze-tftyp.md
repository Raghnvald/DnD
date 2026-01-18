---
obsidianUIMode: preview
cssclasses:
  - json5e-monster
tags:
  - Quelle/5e/tftyp
  - Monster/HG/1-2
  - Monster/Größe/Mittelgroß
  - Monster/Typ/Schleim
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Sentient Gray Ooze
---
# [Sentient Gray Ooze](3-Mechanics\CLI\bestiary\ooze/sentient-gray-ooze-tftyp.md)
*Source: Tales from the Yawning Portal p. 158*  

```statblock
"name": "Sentient Gray Ooze (TftYP)"
"size": "Medium"
"type": "ooze"
"alignment": "Unaligned"
"ac": !!int "8"
"hp": !!int "22"
"hit_dice": "3d8 + 9"
"modifier": !!int "-2"
"stats":
  - !!int "12"
  - !!int "6"
  - !!int "16"
  - !!int "5"
  - !!int "6"
  - !!int "2"
"speed": "10 ft., climb 10 ft."
"skillsaves":
  - "name": "Stealth"
    "desc": "+2"
"damage_resistances": "acid, cold, fire"
"condition_immunities": "blinded, charmed, deafened, exhaustion, frightened, prone"
"senses": "blindsight 60 ft. (blind beyond this radius), passive Perception 8"
"languages": "Common"
"cr": "1/2"
"traits":
  - "desc": "The ooze can move through a space as narrow as 1 inch wide without squeezing."
    "name": "Amorphous"
  - "desc": "Any nonmagical weapon made of metal that hits the ooze corrodes. After\
      \ dealing damage, the weapon takes a permanent and cumulative −1 penalty to\
      \ damage rolls. If its penalty drops to −5, the weapon is destroyed. Nonmagical\
      \ ammunition made of metal that hits the ooze is destroyed after dealing damage.\n\
      \nThe ooze can eat through 2-inch-thick, nonmagical metal in 1 round."
    "name": "Corrode Metal"
  - "desc": "While the ooze remains motionless, it is indistinguishable from an oily\
      \ pool or wet rock."
    "name": "False Appearance"
"actions":
  - "desc": "*Melee Weapon Attack:* +3 to hit, reach 5 ft., one target. *Hit:* 4 (1d6\
      \ + 1) bludgeoning damage plus 7 (2d6) acid damage, and if the target is wearing\
      \ nonmagical metal armor, its armor is partly corroded and takes a permanent\
      \ and cumulative −1 penalty to the AC it offers. The armor is destroyed if the\
      \ penalty reduces its AC to 10."
    "name": "Pseudopod"
"source":
  - "TftYP"
"image": "/3-Mechanics/CLI/bestiary/ooze/token/sentient-gray-ooze-tftyp.webp"
```
^statblock