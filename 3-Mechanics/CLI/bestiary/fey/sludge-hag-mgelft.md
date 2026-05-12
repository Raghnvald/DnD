---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mgelft
- ttrpg-cli/monster/cr/3
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/fey
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Sludge Hag"
---
# [Sludge Hag](3-Mechanics/CLI/bestiary/fey/sludge-hag-mgelft.md)
*Source: Muk's Guide To Everything He Learned From Tasha p. 33*  

You can smell a sludge hag long before you see one. A super stinky smell like rotten eggs mixed with old flower water lingers whenever a sludge hag is around. Sludge hags also tend to leave oily, dark trails of goop around the locations they inhabit. Small critters who venture too close will become covered in the oily goop and require the help of another creature to get clean.

There are rumors that sludge hags were once pristine, fey creatures who became encased in gooey sludge after mistreating their environment. Another rumor is that sludge hags just have really itchy skin and the goop makes them feel relaxed.

```statblock
"name": "Sludge Hag (MGELFT)"
"size": "Medium"
"type": "fey"
"alignment": "neutral oozy"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "82"
"hit_dice": "11d8 + 33"
"modifier": !!int "1"
"stats":
  - !!int "18"
  - !!int "12"
  - !!int "16"
  - !!int "13"
  - !!int "14"
  - !!int "14"
"speed": "30 ft."
"skillsaves":
  - "name": "[Arcana](3-Mechanics/CLI/rules/skills.md#Arcana)"
    "desc": "+3"
  - "name": "[Deception](3-Mechanics/CLI/rules/skills.md#Deception)"
    "desc": "+4"
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+4"
  - "name": "[Stealth](3-Mechanics/CLI/rules/skills.md#Stealth)"
    "desc": "+3"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., passive\
  \ Perception 14"
"languages": "Common, Draconic, Sylvan"
"cr": "3"
"traits":
  - "desc": "**At will:** [acid splash](3-Mechanics/CLI/spells/acid-splash.md), [dancing\
      \ lights](3-Mechanics/CLI/spells/dancing-lights.md), [minor illusion](3-Mechanics/CLI/spells/minor-illusion.md)\n\
      \nThe hag's innate spellcasting ability is Charisma (spell save DC 12). She\
      \ can innately cast the following spells, requiring no material components. "
    "name": "Innate Spellcasting"
  - "desc": "The sludge hag can move through a space as narrow as 1 inch wide without\
      \ squeezing."
    "name": "Amorphous"
  - "desc": "The sludge hag can breathe air and water."
    "name": "Amphibious"
"actions":
  - "desc": "The sludge hag collapses into a oily pool of sludge. While motionless,\
      \ the sludge hag is indistinguishable from any other oily pool of oozy drippiness."
    "name": "False Appearance"
  - "desc": "*Melee Weapon Attack:* +6 to hit, reach 5 ft., one target. *Hit:* 12\
      \ (1d8 + 8) bludgeoning damage, plus 4 (1d8) acid damage. Sludge Slap does\
      \ both bludgeoning and acid damage."
    "name": "Sludge Slap"
"source":
  - "MGELFT"
"image": "3-Mechanics/CLI/bestiary/fey/token/sludge-hag-mgelft.webp"
```
^statblock