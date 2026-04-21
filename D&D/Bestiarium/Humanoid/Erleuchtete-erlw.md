---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Inspired
tags:
  - Monster/Größe/Mittelgroß
  - Monster/HG/2
  - Monster/Typ/Humanoid/human
  - Quelle/5e/erlw
aliases:
  - Inspired
---
# [Inspired](3-Mechanics\CLI\bestiary\humanoid/inspired-erlw.md)
*Source: Eberron: Rising from the Last War p. 294*  

The rulers of distant Sarlona are known as the Inspired. These noble families are said to be bound to celestial spirits that guide and empower them, but the truth is far darker. The Inspired are the mortal hosts of the nightmare spirits of Dal Quor, and they carry out the foul agenda of the Dreaming Dark.

Any humanoid who can dream can volunteer to serve as a quori vessel. But the Inspired of Sarlona are humans bred to be such vessels. They have no choice in this destiny, since they can't resist quori possession. Physically, Inspired resemble the kalashtar, possessing an almost supernatural beauty.

Most of the people of the Five Nations have heard of the Inspired lords in Riedra—never realizing that Inspired are spread throughout Khorvaire as well. Beggars and generals, mayors and merchants might all be secret servants of the Dreaming Dark. Such Inspired have to willingly accept quori possession, but the Dreaming Dark has long experience in weaving dreams that can convince mortals to surrender their bodies.

```statblock
"name": "Inspired (ERLW)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Lawful Evil"
"ac": !!int "12"
"ac_class": "15 with mage armor"
"hp": !!int "40"
"hit_dice": "9d8"
"modifier": !!int "2"
"stats":
  - !!int "11"
  - !!int "14"
  - !!int "10"
  - !!int "16"
  - !!int "10"
  - !!int "16"
"speed": "30 ft."
"saves":
  - "intelligence": !!int "5"
  - "wisdom": !!int "2"
"skillsaves":
  - "name": "Deception"
    "desc": "+7"
  - "name": "Insight"
    "desc": "+2"
  - "name": "Persuasion"
    "desc": "+7"
"damage_resistances": "psychic"
"condition_immunities": "charmed, frightened"
"senses": "passive Perception 10"
"languages": "Common, Quori"
"cr": "2"
"traits":
  - "desc": "The Inspired's spellcasting ability is Intelligence (spell save DC 13).\
      \ It can innately cast the following spells, requiring no material components:\n\
      \n**At will:** mage hand, vicious mockery (see \"Actions\" below)\n\n**1/day\
      \ each:** charm person, dissonant whispers, hex, hold person, mage armor"
    "name": "Innate Spellcasting (Psionics)"
  - "desc": "The Inspired has advantage on Wisdom saving throws."
    "name": "Dual Mind"
"actions":
  - "desc": "The Inspired makes two crysteel dagger attacks. It can replace one attack\
      \ with vicious mockery."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one target. *Hit:* 4 (1d4\
      \ + 2) piercing damage plus 10 (3d6) force damage."
    "name": "Crysteel Dagger"
  - "desc": "The Inspired unleashes a string of insults laced with subtle enchantments\
      \ at one creature it can see within 60 feet of it. If the target can hear the\
      \ Inspired, the target must succeed on a DC 13 Wisdom saving throw or take 2\
      \ (1d4) psychic damage and have disadvantage on the next attack roll it makes\
      \ before the end of its next turn."
    "name": "Vicious Mockery (Cantrip)"
"source":
  - "ERLW"
"image": "/3-Mechanics/CLI/bestiary/humanoid/token/inspired-erlw.webp"
```
^statblock