---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/wdh
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/human
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Barnibus Blastwind"
---
# [Barnibus Blastwind](3-Mechanics/CLI/bestiary/npc/barnibus-blastwind-wdh.md)
*Source: Waterdeep: Dragon Heist p. 195*  

Barnibus works for the Watchful Order of Magists and Protectors, investigating crimes that involve the use of magic. He comes across as prickly and secretive, confiding only in Saeth Cromley, a retired sergeant of the City Watch who assists in many of his investigations.

A lifelong bachelor, Barnibus has a small, tidy estate in the Sea Ward that he inherited from his grandmother. When not serving the Watchful Order, he spends his days reading and writing books in his library.

Barnibus uses spells that help him investigate crimes, pry secrets from the minds of suspects, and locate missing persons. He finds violence appalling and would never use his magic to inflict harm on others-even those who harm him.

```statblock
"name": "Barnibus Blastwind (WDH)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Lawful Good"
"ac": !!int "10"
"ac_class": "13 with [mage armor](3-Mechanics/CLI/spells/mage-armor-xphb.md)"
"hp": !!int "24"
"hit_dice": "7d8 - 7"
"modifier": !!int "0"
"stats":
  - !!int "9"
  - !!int "10"
  - !!int "9"
  - !!int "17"
  - !!int "15"
  - !!int "11"
"speed": "30 ft."
"saves":
  - "intelligence": !!int "5"
  - "wisdom": !!int "4"
"skillsaves":
  - "name": "[Arcana](3-Mechanics/CLI/rules/skills.md#Arcana)"
    "desc": "+5"
  - "name": "[Insight](3-Mechanics/CLI/rules/skills.md#Insight)"
    "desc": "+6"
  - "name": "[Investigation](3-Mechanics/CLI/rules/skills.md#Investigation)"
    "desc": "+7"
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+4"
"gear":
  - "[dagger](3-Mechanics/CLI/items/dagger-xphb.md)"
"senses": "passive Perception 14"
"languages": "Common, Draconic, Dwarvish, Halfling"
"cr": "2"
"traits":
  - "desc": "Barnibus is a 7th-level spellcaster. His spellcasting ability is Intelligence\
      \ (spell save DC 13, +5 to hit with spell attacks) He has the following wizard\
      \ spells prepared:\n\n**Cantrips (at will):** [blade ward](3-Mechanics/CLI/spells/blade-ward-xphb.md),\
      \ [light](3-Mechanics/CLI/spells/light-xphb.md), [mage hand](3-Mechanics/CLI/spells/mage-hand-xphb.md),\
      \ [message](3-Mechanics/CLI/spells/message-xphb.md)\n\n**1st level (4 slots):**\
      \ [comprehend languages](3-Mechanics/CLI/spells/comprehend-languages-xphb.md),\
      \ [identify](3-Mechanics/CLI/spells/identify-xphb.md), [detect magic](3-Mechanics/CLI/spells/detect-magic-xphb.md),\
      \ [mage armor](3-Mechanics/CLI/spells/mage-armor-xphb.md), [shield](3-Mechanics/CLI/spells/shield-xphb.md)\n\
      \n**2nd level (3 slots):** [detect thoughts](3-Mechanics/CLI/spells/detect-thoughts-xphb.md),\
      \ [suggestion](3-Mechanics/CLI/spells/suggestion-xphb.md)\n\n**3rd level (3\
      \ slots):** [clairvoyance](3-Mechanics/CLI/spells/clairvoyance-xphb.md), [sending](3-Mechanics/CLI/spells/sending-xphb.md)\n\
      \n**4th level (1 slots):** [locate creature](3-Mechanics/CLI/spells/locate-creature-xphb.md),\
      \ [Otiluke's resilient sphere](3-Mechanics/CLI/spells/otilukes-resilient-sphere-xphb.md)"
    "name": "Spellcasting"
  - "desc": "Barnibus carries a [wand of magic detection](3-Mechanics/CLI/items/wand-of-magic-detection-xdmg.md).\
      \ (spell included in spell list below but does not use a slot when cast from\
      \ the wand)"
    "name": "Special Equipment"
"actions":
  - "desc": "*Melee  or Ranged Weapon Attack:* +2 to hit, reach 5 ft. or range 20/60\
      \ ft., one target. *Hit:* 2 (1d4) piercing damage."
    "name": "Dagger"
"source":
  - "WDH"
"image": "3-Mechanics/CLI/bestiary/npc/token/barnibus-blastwind-wdh.webp"
```
^statblock