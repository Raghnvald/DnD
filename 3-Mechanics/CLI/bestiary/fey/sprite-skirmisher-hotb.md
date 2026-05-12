---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/hotb
- ttrpg-cli/monster/cr/1-4
- ttrpg-cli/monster/size/tiny
- ttrpg-cli/monster/type/fey
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Sprite Skirmisher"
---
# [Sprite Skirmisher](3-Mechanics/CLI/bestiary/fey/sprite-skirmisher-hotb.md)
*Source: Heroes of the Borderlands p. 9*  

Sprites are wee spirits of nature that can see the innate goodness or wickedness of other creatures. Those that enter their realms with good intentions might be treated with tiny feasts and celebrations. The wicked face nasty tricks and bold ambushes at the hands of invisible sprite defenders.

```statblock
"name": "Sprite Skirmisher (HotB)"
"size": "Tiny"
"type": "fey"
"alignment": "Neutral Good"
"ac": !!int "15"
"hp": !!int "10"
"hit_dice": "4d4"
"modifier": !!int "4"
"stats":
  - !!int "3"
  - !!int "18"
  - !!int "10"
  - !!int "14"
  - !!int "13"
  - !!int "11"
"speed": "10 ft., fly 40 ft."
"skillsaves":
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+3"
  - "name": "[Stealth](3-Mechanics/CLI/rules/skills.md#Stealth)"
    "desc": "+8"
"senses": "passive Perception 13"
"languages": "Common, Elvish, Sylvan"
"cr": "1/4"
"actions":
  - "desc": "*Melee Attack Roll:* +6, reach 5 ft. *Hit:* 6 (1d4 + 4) Piercing\
      \ damage."
    "name": "Needle Sword"
  - "desc": "*Ranged Attack Roll:* +6, range 40/160 ft. *Hit:* 1 Piercing damage,\
      \ and the target has the Charmed condition until the start of the sprite's next\
      \ turn."
    "name": "Enchanting Bow"
  - "desc": "*Charisma Saving Throw:* DC 10, one creature within 5 feet the sprite\
      \ can see (Celestials, Fiends, Undead automatically fail the save). *Failure:*\
      \ The sprite knows the target's emotions."
    "name": "Heart Sight"
  - "desc": "The sprite has the Invisible condition for 1 minute. This effect ends\
      \ early immediately after the sprite makes an attack roll or deals damage, or\
      \ if the sprite has the Incapacitated condition."
    "name": "Invisibility"
"source":
  - "HotB"
"image": "3-Mechanics/CLI/bestiary/fey/token/sprite-skirmisher-hotb.webp"
```
^statblock