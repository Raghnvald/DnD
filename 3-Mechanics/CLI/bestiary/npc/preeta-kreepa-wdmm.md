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
- "Preeta Kreepa"
---
# [Preeta Kreepa](3-Mechanics/CLI/bestiary/npc/preeta-kreepa-wdmm.md)
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
"ac_class": "15 with [mage armor](3-Mechanics/CLI/spells/mage-armor-xphb.md)"
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
  - "name": "[Arcana](3-Mechanics/CLI/rules/skills.md#Arcana)"
    "desc": "+6"
  - "name": "[History](3-Mechanics/CLI/rules/skills.md#History)"
    "desc": "+6"
"gear":
  - "[dagger](3-Mechanics/CLI/items/dagger-xphb.md)"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 120 ft., passive\
  \ Perception 11"
"languages": "Common, Dwarvish, Goblin, Undercommon"
"cr": "6"
"traits":
  - "desc": "Preeta is a 9th-level spellcaster. Its spellcasting ability is Intelligence\
      \ (spell save DC 14, +6 to hit with spell attacks). Preeta has the following\
      \ wizard spells prepared:\n\n**Cantrips (at will):** [fire bolt](3-Mechanics/CLI/spells/fire-bolt-xphb.md),\
      \ [light](3-Mechanics/CLI/spells/light-xphb.md), [mage hand](3-Mechanics/CLI/spells/mage-hand-xphb.md),\
      \ [prestidigitation](3-Mechanics/CLI/spells/prestidigitation-xphb.md)\n\n**1st\
      \ level (4 slots):** [detect magic](3-Mechanics/CLI/spells/detect-magic-xphb.md),\
      \ [mage armor](3-Mechanics/CLI/spells/mage-armor-xphb.md), [magic missile](3-Mechanics/CLI/spells/magic-missile-xphb.md),\
      \ [shield](3-Mechanics/CLI/spells/shield-xphb.md)\n\n**2nd level (3 slots):**\
      \ [misty step](3-Mechanics/CLI/spells/misty-step-xphb.md), [suggestion](3-Mechanics/CLI/spells/suggestion-xphb.md)\n\
      \n**3rd level (3 slots):** [counterspell](3-Mechanics/CLI/spells/counterspell-xphb.md),\
      \ [fireball](3-Mechanics/CLI/spells/fireball-xphb.md), [fly](3-Mechanics/CLI/spells/fly-xphb.md)\n\
      \n**4th level (3 slots):** [greater invisibility](3-Mechanics/CLI/spells/greater-invisibility-xphb.md),\
      \ [ice storm](3-Mechanics/CLI/spells/ice-storm-xphb.md)\n\n**5th level (1 slots):**\
      \ [cone of cold](3-Mechanics/CLI/spells/cone-of-cold-xphb.md)"
    "name": "Spellcasting"
"actions":
  - "desc": "*Melee  or Ranged Weapon Attack:* +5 to hit, reach 5 ft. or range 20/60\
      \ ft., one target. *Hit:* 4 (1d4 + 2) piercing damage."
    "name": "Dagger"
"reactions":
  - "desc": "As a bonus action or a reaction, Preeta can shoot one of the following\
      \ eye rays at one target she can see within 120 feet of her:\n\n- **Fear Ray.**\
      \ The target must succeed on a DC 15 Wisdom saving throw or be [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened)\
      \ for 1 minute. The target can repeat the saving throw at the end of each of\
      \ its turns, ending the effect on itself on a success.  \n- **Paralyzing Ray.**\
      \ The target must succeed on a DC 15 Constitution saving throw or be [paralyzed](3-Mechanics/CLI/rules/conditions.md#Paralyzed)\
      \ for 1 minute. The target can repeat the saving throw at the end of each of\
      \ its turns, ending the effect on itself on a success.  "
    "name": "Eye Rays"
"source":
  - "WDMM"
"image": "3-Mechanics/CLI/bestiary/npc/token/preeta-kreepa-wdmm.webp"
```
^statblock