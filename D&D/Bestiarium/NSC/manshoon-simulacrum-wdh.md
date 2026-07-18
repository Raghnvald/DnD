---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Manshoon Simulacrum
Status: WIP
linter-yaml-title-alias: Manshoon Simulacrum
tags:
  - Monster/Größe/Mittelgroß
  - Monster/HG/8
  - Monster/Typ/Humanoid/Mensch
  - Quelle/5e/wdh
aliases:
  - Manshoon Simulacrum
---
# [Manshoon Simulacrum](3-Mechanics\CLI\bestiary\npc/manshoon-simulacrum-wdh.md)
*Source: Waterdeep: Dragon Heist p. 208*  

Manshoon uses the simulacrum spell to create a magical duplicate of himself as needed. He has customized the spell to increase his simulacrum's hit points at the expense of its spellcasting ability.

Manshoon can have only one simulacrum at any given time, and he uses it as a subordinate to command his Zhentarim minions in the field. If his simulacrum is destroyed, Manshoon creates another. Each simulacrum has the statistics of Manshoon, with these changes:

- The simulacrum has no special equipment. Consequently, it has AC 12 and lacks the Magic Resistance trait and the Staff of Power action option.  
- It loses all spell slots of 6th level and higher.  
- It has a challenge rating of 8 (3,900 XP).  

```statblock
"name": "Manshoon Simulacrum (WDH)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Lawful Evil"
"ac": !!int "12"
"hp": !!int "126"
"hit_dice": "23d8 + 23"
"modifier": !!int "2"
"stats":
  - !!int "10"
  - !!int "14"
  - !!int "12"
  - !!int "23"
  - !!int "15"
  - !!int "16"
"speed": "30 ft."
"saves":
  - "intelligence": !!int "11"
  - "wisdom": !!int "7"
"skillsaves":
  - "name": "Arcana"
    "desc": "+12"
  - "name": "History"
    "desc": "+12"
"senses": "darkvision 60 ft., passive Perception 12"
"languages": "Common, Draconic, Goblin, Infernal, Orc, Undercommon"
"cr": "8"
"traits":
  - "desc": "Manshoon is an 18th-level spellcaster. His spellcasting ability is Intelligence\
      \ (spell save DC 19, +11 to hit with spell attacks). He has the following wizard\
      \ spells prepared:\n\n**Cantrips (at will):** fire bolt, light, mage hand, prestidigitation,\
      \ shocking grasp\n\n**1st level (4 slots):** detect magic, mage armor, magic\
      \ missile, shield\n\n**2nd level (3 slots):** detect thoughts, mirror image,\
      \ misty step\n\n**3rd level (3 slots):** counterspell, lightning bolt, sending\n\
      \n**4th level (3 slots):** fire shield, greater invisibility, polymorph\n\n\
      **5th level (3 slots):** Bigby's hand, scrying, wall of force"
    "name": "Spellcasting"
"actions":
  - "desc": "*Melee Weapon Attack:* +6 to hit, reach 5 ft., one target. *Hit:* 4 (1d4\
      \ + 2) bludgeoning damage."
    "name": "Metal Fist"
"source":
  - "WDH"
"image": "/3-Mechanics/CLI/bestiary/npc/token/manshoon-simulacrum-wdh.webp"
```
^statblock