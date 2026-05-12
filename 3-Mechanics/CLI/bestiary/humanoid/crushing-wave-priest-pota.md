---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/pota
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/human
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Crushing Wave Priest"
---
# [Crushing Wave Priest](3-Mechanics/CLI/bestiary/humanoid/crushing-wave-priest-pota.md)
*Source: Princes of the Apocalypse p. 205*  

Crushing Wave priests are the fanatical core of the cult. Gathering in secretive cabals, they perform dark rituals to glorify Olhydra as the embodiment of water's destructiveness. They believe that using water to kill their enemies, such as through ritual drowning, earns them Olhydra's favor.

```statblock
"name": "Crushing Wave Priest (PotA)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Neutral Evil"
"ac": !!int "13"
"ac_class": "[chain shirt](3-Mechanics/CLI/items/chain-shirt.md)"
"hp": !!int "52"
"hit_dice": "8d8 + 16"
"modifier": !!int "0"
"stats":
  - !!int "15"
  - !!int "11"
  - !!int "14"
  - !!int "10"
  - !!int "11"
  - !!int "16"
"speed": "30 ft."
"skillsaves":
  - "name": "[Deception](3-Mechanics/CLI/rules/skills.md#Deception)"
    "desc": "+5"
  - "name": "[Religion](3-Mechanics/CLI/rules/skills.md#Religion)"
    "desc": "+2"
  - "name": "[Stealth](3-Mechanics/CLI/rules/skills.md#Stealth)"
    "desc": "+2"
"gear":
  - "[quarterstaff](3-Mechanics/CLI/items/quarterstaff.md)"
"senses": "passive Perception 10"
"languages": "Aquan, Common"
"cr": "2"
"traits":
  - "desc": "The priest is a 5th-level spellcaster. Its spellcasting ability is Charisma\
      \ (spell save DC 13, +5 to hit with spell attacks). It knows the following\
      \ sorcerer spells:\n\n**Cantrips (at will):** [chill touch](3-Mechanics/CLI/spells/chill-touch.md),\
      \ [mage hand](3-Mechanics/CLI/spells/mage-hand.md), [minor illusion](3-Mechanics/CLI/spells/minor-illusion.md),\
      \ [prestidigitation](3-Mechanics/CLI/spells/prestidigitation.md), [ray of frost](3-Mechanics/CLI/spells/ray-of-frost.md)\n\
      \n**1st level (4 slots):** [expeditious retreat](3-Mechanics/CLI/spells/expeditious-retreat.md),\
      \ ice knife, [magic missile](3-Mechanics/CLI/spells/magic-missile.md), [shield](3-Mechanics/CLI/spells/shield.md)\n\
      \n**2nd level (3 slots):** [blur](3-Mechanics/CLI/spells/blur.md), [hold person](3-Mechanics/CLI/spells/hold-person.md)\n\
      \n**3rd level (2 slots):** [sleet storm](3-Mechanics/CLI/spells/sleet-storm.md)"
    "name": "Spellcasting"
"actions":
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one target. *Hit:* 6\
      \ (1d8 + 2) bludgeoning damage."
    "name": "Quarterstaff"
"source":
  - "PotA"
"image": "3-Mechanics/CLI/bestiary/humanoid/token/crushing-wave-priest-pota.webp"
```
^statblock