---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/wdmm
- ttrpg-cli/monster/cr/6
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/human
statblock: inline
statblock-link: "#^statblock"
aliases:
- Preeta Kreepa
---
# [Preeta Kreepa](3-Mechanics\CLI\bestiary\npc/preeta-kreepa-wdmm.md)
*Source: Waterdeep: Dungeon of the Mad Mage p. 56*  

Mages spend their lives in the study and practice of magic. Good-aligned mages offer counsel to nobles and others in power, while evil mages dwell in isolated sites to perform unspeakable experiments without interference.

Preeta served as an assistant to Arcturia, one of Halaster's apprentices, until Arcturia transformed her into a monstrous horror. Preeta looks like an old woman with two beholder eyestalks sprouting from her eye sockets. Her mouth, twice as large as it should be, is filled with sharp, pointed teeth. She wears the flayed, slippery, translucent skin of a kuo-toa as a cloak.

```statblock
"name": "Preeta Kreepa (WDMM)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Chaotic Neutral"
"ac": !!int "12"
"ac_class": "15 with mage armor"
"hp": !!int "40"
"hit_dice": "9d8"
"modifier": !!int "2"
"stats":
  - !!int "9"
  - !!int "14"
  - !!int "11"
  - !!int "17"
  - !!int "12"
  - !!int "11"
"speed": "30 ft."
"saves":
  - "intelligence": !!int "6"
  - "wisdom": !!int "4"
"skillsaves":
  - "name": "Arcana"
    "desc": "+6"
  - "name": "History"
    "desc": "+6"
"senses": "darkvision 120 ft., passive Perception 11"
"languages": "Common, Dwarvish, Goblin, Undercommon"
"cr": "6"
"traits":
  - "desc": "Preeta is a 9th-level spellcaster. Its spellcasting ability is Intelligence\
      \ (spell save DC 14, +6 to hit with spell attacks). Preeta has the following\
      \ wizard spells prepared:\n\n**Cantrips (at will):** fire bolt, light, mage\
      \ hand, prestidigitation\n\n**1st level (4 slots):** detect magic, mage armor,\
      \ magic missile, shield\n\n**2nd level (3 slots):** misty step, suggestion\n\
      \n**3rd level (3 slots):** counterspell, fireball, fly\n\n**4th level (3 slots):**\
      \ greater invisibility, ice storm\n\n**5th level (1 slots):** cone of cold"
    "name": "Spellcasting"
"actions":
  - "desc": "*Melee  or Ranged Weapon Attack:* +5 to hit, reach 5 ft. or range 20/60\
      \ ft., one target. *Hit:* 4 (1d4 + 2) piercing damage."
    "name": "Dagger"
"reactions":
  - "desc": "As a bonus action or a reaction, Preeta can shoot one of the following\
      \ eye rays at one target she can see within 120 feet of her:\n\n- **Fear Ray.**\
      \ The target must succeed on a DC 15 Wisdom saving throw or be frightened for\
      \ 1 minute. The target can repeat the saving throw at the end of each of its\
      \ turns, ending the effect on itself on a success.  \n- **Paralyzing Ray.**\
      \ The target must succeed on a DC 15 Constitution saving throw or be paralyzed\
      \ for 1 minute. The target can repeat the saving throw at the end of each of\
      \ its turns, ending the effect on itself on a success.  "
    "name": "Eye Rays"
"source":
  - "WDMM"
"image": "/3-Mechanics/CLI/bestiary/npc/token/preeta-kreepa-wdmm.webp"
```
^statblock