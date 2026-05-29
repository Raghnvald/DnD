---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: White Maw
linter-yaml-title-alias: White Maw
tags:
  - Monster/Größe/Gigantisch
  - Monster/HG/10
  - Monster/Typ/Schleim
  - Quelle/5e/tftyp
aliases:
  - White Maw
---
# [White Maw](3-Mechanics\CLI\bestiary\npc/white-maw-tftyp.md)
*Source: Tales from the Yawning Portal p. 248*  

```statblock
"name": "White Maw (TftYP)"
"size": "Gargantuan"
"type": "ooze"
"alignment": "Chaotic Neutral"
"ac": !!int "5"
"hp": !!int "217"
"hit_dice": "14d20 + 70"
"modifier": !!int "-5"
"stats":
  - !!int "18"
  - !!int "1"
  - !!int "20"
  - !!int "12"
  - !!int "10"
  - !!int "3"
"speed": "10 ft."
"damage_resistances": "acid, cold, fire"
"damage_immunities": "poison"
"condition_immunities": "blinded, charmed, deafened, exhaustion, frightened, poisoned,\
  \ prone"
"senses": "blindsight 60 ft. (blind beyond this radius), passive Perception 10"
"languages": "telepathy 50 ft."
"cr": "10"
"traits":
  - "desc": "White Maw can occupy another creature's space and vice versa."
    "name": "Amorphous Form"
  - "desc": "Any nonmagical weapon made of metal that hits White Maw corrodes. After\
      \ dealing damage, the weapon takes a permanent and cumulative −1 penalty to\
      \ damage rolls. if its penalty drops to −5, the weapon is destroyed. Nonmagical\
      \ ammunition made of metal that hits White Maw is destroyed after dealing damage.\n\
      \nWhite Maw can eat through 2-inch-thick, nonmagical metal in 1 round."
    "name": "Corrode Metal"
  - "desc": "While White Maw remains motionless, it is indistinguishable from white\
      \ stone."
    "name": "False Appearance"
  - "desc": "Any creature that starts its turn in White Maw's space is targeted by\
      \ a pseudopod attack if White Maw isn't incapacitated."
    "name": "Killer Response"
"actions":
  - "desc": "*Melee Weapon Attack:* +8 to hit, reach 10 ft., one target. *Hit:* 22\
      \ (4d8 + 4) bludgeoning damage plus 9 (2d8) acid damage. If the target is wearing\
      \ nonmagical metal armor, its armor is partly corroded and takes a permanent\
      \ and cumulative −1 penalty to the AC it offers. The armor is destroyed if the\
      \ penalty reduces its AC to 10."
    "name": "Pseudopod"
"source":
  - "TftYP"
"image": "/3-Mechanics/CLI/bestiary/npc/token/white-maw-tftyp.webp"
```
^statblock