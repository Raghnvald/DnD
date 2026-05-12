---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/wdh
- ttrpg-cli/monster/cr/8
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/human
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Manshoon Simulacrum"
---
# [Manshoon Simulacrum](3-Mechanics/CLI/bestiary/npc/manshoon-simulacrum-wdh.md)
*Source: Waterdeep: Dragon Heist p. 208*  

Manshoon uses the [simulacrum](3-Mechanics/CLI/spells/simulacrum-xphb.md) spell to create a magical duplicate of himself as needed. He has customized the spell to increase his simulacrum's hit points at the expense of its spellcasting ability.

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
  - "name": "[Arcana](3-Mechanics/CLI/rules/skills.md#Arcana)"
    "desc": "+12"
  - "name": "[History](3-Mechanics/CLI/rules/skills.md#History)"
    "desc": "+12"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., passive\
  \ Perception 12"
"languages": "Common, Draconic, Goblin, Infernal, Orc, Undercommon"
"cr": "8"
"traits":
  - "desc": "Manshoon is an 18th-level spellcaster. His spellcasting ability is Intelligence\
      \ (spell save DC 19, +11 to hit with spell attacks). He has the following\
      \ wizard spells prepared:\n\n**Cantrips (at will):** [fire bolt](3-Mechanics/CLI/spells/fire-bolt-xphb.md),\
      \ [light](3-Mechanics/CLI/spells/light-xphb.md), [mage hand](3-Mechanics/CLI/spells/mage-hand-xphb.md),\
      \ [prestidigitation](3-Mechanics/CLI/spells/prestidigitation-xphb.md), [shocking\
      \ grasp](3-Mechanics/CLI/spells/shocking-grasp-xphb.md)\n\n**1st level (4 slots):**\
      \ [detect magic](3-Mechanics/CLI/spells/detect-magic-xphb.md), [mage armor](3-Mechanics/CLI/spells/mage-armor-xphb.md),\
      \ [magic missile](3-Mechanics/CLI/spells/magic-missile-xphb.md), [shield](3-Mechanics/CLI/spells/shield-xphb.md)\n\
      \n**2nd level (3 slots):** [detect thoughts](3-Mechanics/CLI/spells/detect-thoughts-xphb.md),\
      \ [mirror image](3-Mechanics/CLI/spells/mirror-image-xphb.md), [misty step](3-Mechanics/CLI/spells/misty-step-xphb.md)\n\
      \n**3rd level (3 slots):** [counterspell](3-Mechanics/CLI/spells/counterspell-xphb.md),\
      \ [lightning bolt](3-Mechanics/CLI/spells/lightning-bolt-xphb.md), [sending](3-Mechanics/CLI/spells/sending-xphb.md)\n\
      \n**4th level (3 slots):** [fire shield](3-Mechanics/CLI/spells/fire-shield-xphb.md),\
      \ [greater invisibility](3-Mechanics/CLI/spells/greater-invisibility-xphb.md),\
      \ [polymorph](3-Mechanics/CLI/spells/polymorph-xphb.md)\n\n**5th level (3 slots):**\
      \ [Bigby's hand](3-Mechanics/CLI/spells/bigbys-hand-xphb.md), [scrying](3-Mechanics/CLI/spells/scrying-xphb.md),\
      \ [wall of force](3-Mechanics/CLI/spells/wall-of-force-xphb.md)"
    "name": "Spellcasting"
"actions":
  - "desc": "*Melee Weapon Attack:* +6 to hit, reach 5 ft., one target. *Hit:* 4\
      \ (1d4 + 2) bludgeoning damage."
    "name": "Metal Fist"
"source":
  - "WDH"
"image": "3-Mechanics/CLI/bestiary/npc/token/manshoon-simulacrum-wdh.webp"
```
^statblock