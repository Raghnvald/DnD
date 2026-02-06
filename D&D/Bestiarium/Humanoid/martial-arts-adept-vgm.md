---
cssclasses:
  - json5e-monster
tags:
  - Quelle/5e/vgm
  - Monster/HG/3
  - Monster/Habitat/Stadt
  - Monster/Größe/Mittelgroß
  - Monster/Typ/Humanoid/any-race
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Martial Arts Adept
---
# [Martial Arts Adept](3-Mechanics\CLI\bestiary\humanoid/martial-arts-adept-vgm.md)
*Source: Volo's Guide to Monsters p. 216, Tales from the Yawning Portal, Tomb of Annihilation*  

Martial arts adepts are disciplined monks with extensive training in hand-to-hand combat. Some protect monasteries; others travel the world seeking enlightenment or new forms of combat to master. A few become bodyguards, trading their combat prowess and loyalty for food and lodging.

```statblock
"name": "Martial Arts Adept (VGM)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Any alignment"
"ac": !!int "16"
"hp": !!int "60"
"hit_dice": "11d8 + 11"
"modifier": !!int "3"
"stats":
  - !!int "11"
  - !!int "17"
  - !!int "13"
  - !!int "11"
  - !!int "16"
  - !!int "10"
"speed": "40 ft."
"skillsaves":
  - "name": "Acrobatics"
    "desc": "+5"
  - "name": "Insight"
    "desc": "+5"
  - "name": "Stealth"
    "desc": "+5"
"senses": "passive Perception 13"
"languages": "any one language (usually Common)"
"cr": "3"
"traits":
  - "desc": "While the adept is wearing no armor and wielding no shield, its AC includes\
      \ its Wisdom modifier."
    "name": "Unarmored Defense"
"actions":
  - "desc": "The adept makes three unarmed strikes or three dart attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one target. *Hit:* 7 (1d8\
      \ + 3) bludgeoning damage. If the target is a creature, the adept can choose\
      \ one of the following additional effects:\n\n- The target must succeed on a\
      \ DC 13 Strength saving throw or drop one item it is holding (adept's choice).\
      \  \n- The target must succeed on a DC 13 Dexterity saving throw or be knocked\
      \ prone.  \n- The target must succeed on a DC 13 Constitution saving throw or\
      \ be stunned until the end of the adept's next turn.  "
    "name": "Unarmed Strike"
  - "desc": "*Ranged Weapon Attack:* +5 to hit, range 20/60 ft., one target. *Hit:*\
      \ 5 (1d4 + 3) piercing damage."
    "name": "Dart"
"reactions":
  - "desc": "In response to being hit by a ranged weapon attack, the adept deflects\
      \ the missile. The damage it takes from the attack is reduced by 1d10 + 3. If\
      \ the damage is reduced to 0, the adept catches the missile if it's small enough\
      \ to hold in one hand and the adept has a hand free."
    "name": "Deflect Missile"
"source":
  - "VGM"
  - "TftYP"
  - "ToA"
"image": "/3-Mechanics/CLI/bestiary/humanoid/token/martial-arts-adept-vgm.webp"
```
^statblock

## Environment

urban