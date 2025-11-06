---
cssclasses:
  - json5e-monster
tags:
  - Quelle/5e/pabtso
  - Monster/HG/1
  - Monster/Größe/Winzig
  - Monster/Typ/Unhold/demon
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Zeond
---
# [Zeond](3-Mechanics\CLI\bestiary\npc/zeond-pabtso.md)
*Source: Phandelver and Below: The Shattered Obelisk p. 43*  

```statblock
"name": "Zeond (PaBTSO)"
"size": "Tiny"
"type": "fiend"
"subtype": "demon"
"alignment": "Chaotic Evil"
"ac": !!int "13"
"hp": !!int "7"
"hit_dice": "3d4"
"modifier": !!int "3"
"stats":
  - !!int "5"
  - !!int "17"
  - !!int "10"
  - !!int "7"
  - !!int "10"
  - !!int "10"
"speed": "40 ft."
"skillsaves":
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+5"
"damage_resistances": "cold; fire; lightning; bludgeoning, piercing, slashing from\
  \ nonmagical attacks"
"damage_immunities": "poison"
"condition_immunities": "[poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)"
"senses": "[darkvision](/3-Mechanics/CLI/senses.md#Darkvision) 120 ft., passive Perception\
  \ 10"
"languages": "Abyssal, Common"
"cr": "1"
"traits":
  - "desc": "Zeond can use its action to polymorph into a beast form that resembles\
      \ a bat (speed 10 feet fly 40 ft.), a centipede (40 ft., climb 40 ft.), or a\
      \ toad (40 ft., swim 40 ft.), or back into its true form. Its statistics are\
      \ the same in each form, except for the speed changes noted. Any equipment it\
      \ is wearing or carrying isn't transformed. It reverts to its true form if it\
      \ dies."
    "name": "Shapechanger"
  - "desc": "Zeond has advantage on saving throws against spells and other magical\
      \ effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one target. *Hit:* 5 (1d4\
      \ + 3) piercing damage, and the target must succeed on a DC 10 Constitution\
      \ saving throw or take 5 (2d4) poison damage and become [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)\
      \ for 1 minute. The target can repeat the saving throw at the end of each of\
      \ its turns, ending the effect on itself on a success."
    "name": "Claw (Bite in Beast Form)"
  - "desc": "One creature of Zeond's choice within 20 feet of it must succeed on a\
      \ DC 10 Wisdom saving throw or be [frightened](/3-Mechanics/CLI/conditions.md#Frightened)\
      \ for 1 minute. The target can repeat the saving throw at the end of each of\
      \ its turns, with disadvantage if Zeond is within line of sight, ending the\
      \ effect on itself on a success."
    "name": "Scare (1/Day)"
  - "desc": "Zeond magically turns [invisible](/3-Mechanics/CLI/conditions.md#Invisible)\
      \ until it attacks or uses Scare, or until its [concentration](/3-Mechanics/CLI/conditions.md#Concentration)\
      \ ends (as if [concentrating](/3-Mechanics/CLI/conditions.md#Concentration)\
      \ on a spell). Any equipment Zeond wears or carries is [invisible](/3-Mechanics/CLI/conditions.md#Invisible)\
      \ with it."
    "name": "Invisibility"
"source":
  - "PaBTSO"
"image": "/3-Mechanics/CLI/bestiary/npc/token/zeond-pabtso.webp"
```
^statblock