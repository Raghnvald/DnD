---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/pota
- ttrpg-cli/monster/cr/3
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/human
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Eternal Flame Priest"
---
# [Eternal Flame Priest](3-Mechanics/CLI/bestiary/humanoid/eternal-flame-priest-pota.md)
*Source: Princes of the Apocalypse p. 200*  

Eternal Flame priests see the world around them as impure and unworthy, and believe that only cleansing by fire can set it right. As a result, all fire is deemed holy, from the smallest candle flame to the greatest conflagrations. When traveling in the open, Eternal Flame priests are clever enough to hide their true beliefs, passing themselves off as druids or wizards with a knack for fire magic.

```statblock
"name": "Eternal Flame Priest (PotA)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Neutral Evil"
"ac": !!int "12"
"ac_class": "15 with [mage armor](3-Mechanics/CLI/spells/mage-armor.md)"
"hp": !!int "52"
"hit_dice": "8d8 + 16"
"modifier": !!int "2"
"stats":
  - !!int "12"
  - !!int "15"
  - !!int "14"
  - !!int "10"
  - !!int "11"
  - !!int "16"
"speed": "30 ft."
"skillsaves":
  - "name": "[Deception](3-Mechanics/CLI/rules/skills.md#Deception)"
    "desc": "+5"
  - "name": "[Intimidation](3-Mechanics/CLI/rules/skills.md#Intimidation)"
    "desc": "+5"
  - "name": "[Religion](3-Mechanics/CLI/rules/skills.md#Religion)"
    "desc": "+2"
"damage_resistances": "fire"
"gear":
  - "[dagger](3-Mechanics/CLI/items/dagger.md)"
"senses": "passive Perception 10"
"languages": "Common, Ignan"
"cr": "3"
"traits":
  - "desc": "The priest is a 5th-level spellcaster. Its spellcasting ability is Charisma\
      \ (spell save DC 13, +5 to hit with spell attacks). It knows the following\
      \ sorcerer spells:\n\n**Cantrips (at will):** control flames, create bonfire,\
      \ [fire bolt](3-Mechanics/CLI/spells/fire-bolt.md), [light](3-Mechanics/CLI/spells/light.md),\
      \ [minor illusion](3-Mechanics/CLI/spells/minor-illusion.md)\n\n**1st level\
      \ (4 slots):** [burning hands](3-Mechanics/CLI/spells/burning-hands.md), [expeditious\
      \ retreat](3-Mechanics/CLI/spells/expeditious-retreat.md), [mage armor](3-Mechanics/CLI/spells/mage-armor.md)\n\
      \n**2nd level (3 slots):** [blur](3-Mechanics/CLI/spells/blur.md), [scorching\
      \ ray](3-Mechanics/CLI/spells/scorching-ray.md)\n\n**3rd level (2 slots):**\
      \ [fireball](3-Mechanics/CLI/spells/fireball.md)"
    "name": "Spellcasting"
"actions":
  - "desc": "*Melee  or Ranged Weapon Attack:* +4 to hit, reach 5 ft. or range 20/60\
      \ ft., one target. *Hit:* 4 (1d4 + 2) piercing damage."
    "name": "Dagger"
"source":
  - "PotA"
"image": "3-Mechanics/CLI/bestiary/humanoid/token/eternal-flame-priest-pota.webp"
```
^statblock