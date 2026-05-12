---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/psi
- ttrpg-cli/monster/cr/3
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/human
- ttrpg-cli/monster/type/humanoid/shapechanger
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Werewolf (Leeraug)"
---
# [Werewolf (Leeraug)](3-Mechanics/CLI/bestiary/humanoid/werewolf-leeraug-psi.md)
*Source: Plane Shift: Innistrad p. 15*  

```statblock
"name": "Werewolf (Leeraug) (PSI)"
"size": "Medium"
"type": "humanoid"
"subtype": "human, shapechanger"
"alignment": "Chaotic Evil"
"ac": !!int "11"
"ac_class": "12 natural armor in canid form"
"hp": !!int "58"
"hit_dice": "9d8 + 18"
"modifier": !!int "1"
"stats":
  - !!int "15"
  - !!int "13"
  - !!int "14"
  - !!int "10"
  - !!int "11"
  - !!int "10"
"speed": "30 ft. (40 ft. in canid form)"
"skillsaves":
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+4"
  - "name": "[Stealth](3-Mechanics/CLI/rules/skills.md#Stealth)"
    "desc": "+3"
"damage_immunities": "bludgeoning, piercing, slashing from nonmagical attacks not\
  \ made with silvered weapons"
"gear":
  - "[spear](3-Mechanics/CLI/items/spear.md)"
"senses": "passive Perception 14"
"languages": "Common (can't speak in canid form)"
"cr": "3"
"traits":
  - "desc": "The werewolf polymorphs into a wolf-humanoid canid form, or back into\
      \ its true human form. This change is dictated by the moon, but can also be\
      \ induced by trauma or strong emotion. Its statistics, other than its AC, are\
      \ the same in each form. Any equipment it is wearing or carrying isn't transformed.\
      \ It reverts to its true form if it dies."
    "name": "Shapechanger"
  - "desc": "The werewolf has advantage on Wisdom ([Perception](3-Mechanics/CLI/rules/skills.md#Perception))\
      \ checks that rely on hearing or smell."
    "name": "Keen Hearing and Smell"
  - "desc": "Vildin Rampage (Canid Form Only). When the werewolf reduces a creature\
      \ to 0 hit points with a melee attack on its turn, it can take a bonus action\
      \ to move up to half its speed and make a bite attack."
    "name": "Howlpack: Vildin"
  - "desc": "The werewolf has advantage on melee attack rolls against any creature\
      \ that doesn't have all its hit points."
    "name": "Leeraug Blood Frenzy"
"actions":
  - "desc": "The werewolf makes two attacks: one with its bite and one with its claws\
      \ or spear."
    "name": "Multiattack (Canid Form Only)"
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one target. *Hit:* 6\
      \ (1d8 + 2) piercing damage."
    "name": "Bite (Canid Form Only)"
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one target. *Hit:* 7\
      \ (2d4 + 2) slashing damage."
    "name": "Claws (Canid Form Only)"
  - "desc": "*Melee  or Ranged Weapon Attack:* +4 to hit, reach 5 ft. or range 20/60\
      \ ft., one target. *Hit:* 5 (1d6 + 2) piercing damage, or 6 (1d8 + 2) piercing\
      \ damage if used with two hands to make a melee attack."
    "name": "Spear (Human Form Only)"
"source":
  - "PSI"
```
^statblock