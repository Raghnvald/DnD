---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/wtthc
- ttrpg-cli/monster/cr/1-2
- ttrpg-cli/monster/size/small
- ttrpg-cli/monster/type/monstrosity
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Giant Corrupted Rat"
---
# [Giant Corrupted Rat](3-Mechanics/CLI/bestiary/monstrosity/giant-corrupted-rat-wtthc.md)
*Source: Stranger Things: Welcome to the Hellfire Club*  

The rats of Elmshire sometimes grow to unusual proportions. Though frightening, these dog-size rodents were little more than a local nuisance until an ex-adventurer's magic transformed them into feral terrors. Caustic drool drips from their chattering incisors, and glowing pustules pockmark their bloated, ghastly hides.

```statblock
"name": "Giant Corrupted Rat (WttHC)"
"size": "Small"
"type": "monstrosity"
"alignment": "Unaligned"
"ac": !!int "13"
"hp": !!int "18"
"hit_dice": "4d6"
"modifier": !!int "3"
"stats":
  - !!int "7"
  - !!int "16"
  - !!int "12"
  - !!int "2"
  - !!int "10"
  - !!int "4"
"speed": "30 ft., climb 30 ft."
"skillsaves":
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+12"
  - "name": "[Stealth](3-Mechanics/CLI/rules/skills.md#Stealth)"
    "desc": "+5"
"senses": "[Darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., passive\
  \ Perception 12"
"languages": ""
"cr": "1/2"
"traits":
  - "desc": "The rat explodes when it dies. Constitution [Saving Throw](3-Mechanics/CLI/rules/variant-rules/saving-throw-xphb.md)\
      \ DC 11, each creature in a 5-foot [Emanation](3-Mechanics/CLI/rules/variant-rules/emanation-area-of-effect-xphb.md)\
      \ originating from the rat. *Failure:* 5 (2d4) Acid damage. *Success:* Half\
      \ damage."
    "name": "Death Burst"
"actions":
  - "desc": "*Melee Attack Roll:* +5, Reach 5 ft. *Hit:* 6 (1d6 + 3) Piercing\
      \ damage plus 5 (2d4) Acid damage."
    "name": "Bite"
"source":
  - "WttHC"
"image": "3-Mechanics/CLI/bestiary/monstrosity/token/giant-corrupted-rat-wtthc.webp"
```
^statblock