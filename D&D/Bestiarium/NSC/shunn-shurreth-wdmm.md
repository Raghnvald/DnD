---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Shunn Shurreth
linter-yaml-title-alias: Shunn Shurreth
tags:
  - Monster/Größe/Mittelgroß
  - Monster/HG/5
  - Monster/Typ/Humanoid/elf
  - Quelle/5e/wdmm
aliases:
  - Shunn Shurreth
---
# [Shunn Shurreth](3-Mechanics\CLI\bestiary\npc/shunn-shurreth-wdmm.md)
*Source: Waterdeep: Dungeon of the Mad Mage p. 33*  

A drow priestess of Lolth placed a curse on Shunn and forced him into exile after he displeased her. The curse partially transformed him into a spider, giving him eight red arachnid eyes, a mouth full of fangs, and black bristles sprouting from his slender limbs. A remove curse or greater restoration spell restores Shunn's natural form, but Shunn doesn't want the curse lifted. His horrific appearance strikes fear into the hearts of his comrades-in-arms and has earned him favor with Xanathar. Shunn believes that returning to his normal form might weaken his influence over his gang and diminish his status in the Xanathar Guild.

```statblock
"name": "Shunn Shurreth (WDMM)"
"size": "Medium"
"type": "humanoid"
"subtype": "elf"
"alignment": "Lawful Evil"
"ac": !!int "18"
"ac_class": "studded leather, shield"
"hp": !!int "71"
"hit_dice": "11d8 + 22"
"modifier": !!int "4"
"stats":
  - !!int "13"
  - !!int "18"
  - !!int "14"
  - !!int "11"
  - !!int "13"
  - !!int "12"
"speed": "30 ft."
"saves":
  - "dexterity": !!int "7"
  - "constitution": !!int "5"
  - "wisdom": !!int "4"
"skillsaves":
  - "name": "Perception"
    "desc": "+4"
  - "name": "Stealth"
    "desc": "+10"
"senses": "darkvision 120 ft., passive Perception 14"
"languages": "Elvish, Undercommon"
"cr": "5"
"traits":
  - "desc": "Shunn's spellcasting ability is Charisma (spell save DC 12). It can innately\
      \ cast the following spells, requiring no material components:\n\n**At will:**\
      \ dancing lights\n\n**1/day each:** darkness, faerie fire, levitate (self only)"
    "name": "Innate Spellcasting"
  - "desc": "While cursed with spider features, Shunn can climb difficult surfaces,\
      \ even across ceilings, without needing to make an ability check."
    "name": "Spider Features"
  - "desc": "Shunn has advantage on saving throws against being charmed, and magic\
      \ can't put Shunn to sleep."
    "name": "Fey Ancestry"
  - "desc": "While in sunlight, Shunn has disadvantage on attack rolls, as well as\
      \ on Wisdom (Perception) checks that rely on sight."
    "name": "Sunlight Sensitivity"
"actions":
  - "desc": "Shunn makes two shortsword attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +7 to hit, reach 5 ft., one target. *Hit:* 7 (1d6\
      \ + 4) piercing damage plus 10 (3d6) poison damage."
    "name": "Shortsword"
  - "desc": "*Ranged Weapon Attack:* +7 to hit, range 30/120 ft., one target. *Hit:*\
      \ 7 (1d6 + 4) piercing damage, and the target must succeed on a DC 13 Constitution\
      \ saving throw or be poisoned for 1 hour. If the saving throw fails by 5 or\
      \ more, the target is also unconscious while poisoned in this way. The target\
      \ wakes up if it takes damage or if another creature takes an action to shake\
      \ it awake."
    "name": "Hand Crossbow"
"reactions":
  - "desc": "Shunn adds 3 to its AC against one melee attack that would hit it. To\
      \ do so, Shunn must see the attacker and be wielding a melee weapon."
    "name": "Parry"
"source":
  - "WDMM"
"image": "/3-Mechanics/CLI/bestiary/npc/token/shunn-shurreth-wdmm.webp"
```
^statblock