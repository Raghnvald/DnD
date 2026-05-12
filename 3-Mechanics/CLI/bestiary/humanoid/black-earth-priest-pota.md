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
- "Black Earth Priest"
---
# [Black Earth Priest](3-Mechanics/CLI/bestiary/humanoid/black-earth-priest-pota.md)
*Source: Princes of the Apocalypse p. 195*  

The priests of the Black Earth are the drivers and organizers of Ogrémoch's cult. They are the true believers, seeing Ogrémoch as a divine force, and they have developed a twisted dogma to explain how the evil of elemental earth is destined to remake the world and rule over all. The Black Earth priests form a cabal of leaders whose fanaticism and magical power serve as the backbone of the cult. Individuals of unusual power hold higher rank in the cult, but the priests provide the cult leader with his or her authority over the rest of Ogrémoch's followers.

```statblock
"name": "Black Earth Priest (PotA)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Neutral Evil"
"ac": !!int "17"
"ac_class": "[splint armor](3-Mechanics/CLI/items/splint-armor.md)"
"hp": !!int "45"
"hit_dice": "7d8 + 14"
"modifier": !!int "0"
"stats":
  - !!int "15"
  - !!int "11"
  - !!int "14"
  - !!int "12"
  - !!int "10"
  - !!int "16"
"speed": "30 ft."
"skillsaves":
  - "name": "[Intimidation](3-Mechanics/CLI/rules/skills.md#Intimidation)"
    "desc": "+5"
  - "name": "[Religion](3-Mechanics/CLI/rules/skills.md#Religion)"
    "desc": "+3"
  - "name": "[Persuasion](3-Mechanics/CLI/rules/skills.md#Persuasion)"
    "desc": "+5"
"gear":
  - "[glaive](3-Mechanics/CLI/items/glaive.md)"
"senses": "passive Perception 10"
"languages": "Common, Terran"
"cr": "3"
"traits":
  - "desc": "The priest is a 5th-level spellcaster. Its spellcasting ability is Charisma\
      \ (spell save DC 13, +5 to hit with spell attacks). It knows the following\
      \ sorcerer spells:\n\n**Cantrips (at will):** [acid splash](3-Mechanics/CLI/spells/acid-splash.md),\
      \ [blade ward](3-Mechanics/CLI/spells/blade-ward.md), [light](3-Mechanics/CLI/spells/light.md),\
      \ [mending](3-Mechanics/CLI/spells/mending.md), mold earth\n\n**1st level (4\
      \ slots):** earth tremor, [expeditious retreat](3-Mechanics/CLI/spells/expeditious-retreat.md),\
      \ [shield](3-Mechanics/CLI/spells/shield.md)\n\n**2nd level (3 slots):** [shatter](3-Mechanics/CLI/spells/shatter.md),\
      \ [spider climb](3-Mechanics/CLI/spells/spider-climb.md)\n\n**3rd level (2 slots):**\
      \ [slow](3-Mechanics/CLI/spells/slow.md)"
    "name": "Spellcasting"
"actions":
  - "desc": "The priest makes two melee attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 10 ft., one target. *Hit:*\
      \ 7 (1d10 + 2) slashing damage."
    "name": "Glaive"
"reactions":
  - "desc": "When the priest is subjected to an effect that would move it, knock it\
      \ [prone](3-Mechanics/CLI/rules/conditions.md#Prone), or both, it can use its\
      \ reaction to be neither moved nor knocked [prone](3-Mechanics/CLI/rules/conditions.md#Prone)."
    "name": "Unyielding"
"source":
  - "PotA"
"image": "3-Mechanics/CLI/bestiary/humanoid/token/black-earth-priest-pota.webp"
```
^statblock