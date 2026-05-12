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
- "Skyweaver"
---
# [Skyweaver](3-Mechanics/CLI/bestiary/humanoid/skyweaver-pota.md)
*Source: Princes of the Apocalypse p. 191*  

Skyweavers brim with rage and desire, which makes them perfect vessels for the wildly destructive magic of the Cult of the Howling Hatred. In contrast to their hurricane counterparts in the air cult, skyweavers embrace the worship of Elemental Evil for a quick path to power. With little experience wielding the might of the elements, skyweavers thrill with the rush of releasing raw elemental energy.

```statblock
"name": "Skyweaver (PotA)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Chaotic Evil"
"ac": !!int "12"
"ac_class": "15 with [mage armor](3-Mechanics/CLI/spells/mage-armor.md)"
"hp": !!int "44"
"hit_dice": "8d8 + 8"
"modifier": !!int "2"
"stats":
  - !!int "8"
  - !!int "14"
  - !!int "12"
  - !!int "11"
  - !!int "10"
  - !!int "16"
"speed": "30 ft."
"skillsaves":
  - "name": "[Deception](3-Mechanics/CLI/rules/skills.md#Deception)"
    "desc": "+5"
  - "name": "[Persuasion](3-Mechanics/CLI/rules/skills.md#Persuasion)"
    "desc": "+5"
"gear":
  - "[dagger](3-Mechanics/CLI/items/dagger.md)"
"senses": "passive Perception 10"
"languages": "Auran, Common"
"cr": "3"
"traits":
  - "desc": "The Skyweaver is a 6th-level spellcaster. Its spellcasting ability is\
      \ Charisma (spell save DC 13, +5 to hit with spell attacks). It knows the\
      \ following sorcerer spells:\n\n**Cantrips (at will):** [blade ward](3-Mechanics/CLI/spells/blade-ward.md),\
      \ [light](3-Mechanics/CLI/spells/light.md), [message](3-Mechanics/CLI/spells/message.md),\
      \ [ray of frost](3-Mechanics/CLI/spells/ray-of-frost.md), [shocking grasp](3-Mechanics/CLI/spells/shocking-grasp.md)\n\
      \n**1st level (4 slots):** [feather fall](3-Mechanics/CLI/spells/feather-fall.md),\
      \ [mage armor](3-Mechanics/CLI/spells/mage-armor.md), [witch bolt](3-Mechanics/CLI/spells/witch-bolt.md)\n\
      \n**2nd level (3 slots):** [gust of wind](3-Mechanics/CLI/spells/gust-of-wind.md),\
      \ [invisibility](3-Mechanics/CLI/spells/invisibility.md)\n\n**3rd level (3 slots):**\
      \ [fly](3-Mechanics/CLI/spells/fly.md), [lightning bolt](3-Mechanics/CLI/spells/lightning-bolt.md)"
    "name": "Spellcasting"
"actions":
  - "desc": "*Melee  or Ranged Weapon Attack:* +4 to hit, reach 5 ft. or range 20/60\
      \ ft., one target. *Hit:* 3 (1d4 + 1) piercing damage."
    "name": "Dagger"
"source":
  - "PotA"
"image": "3-Mechanics/CLI/bestiary/humanoid/token/skyweaver-pota.webp"
```
^statblock