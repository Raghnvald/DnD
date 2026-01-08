---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/ggr
- ttrpg-cli/monster/cr/5
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/any-race
statblock: inline
statblock-link: "#^statblock"
aliases:
- Mind Mage
---
# [Mind Mage](3-Mechanics\CLI\bestiary\humanoid/mind-mage-ggr.md)
*Source: Guildmasters' Guide to Ravnica p. 233*  

Dimir mind mages are among the most feared spellcasters in Ravnica, thanks in large part to the aura of mystery that shrouds them and their work. Their ability to read and alter memories commands respect from the other members of House Dimir and makes them useful in the full spectrum of the guild's activities. Many mind mages lead cells of their own.

```statblock
"name": "Mind Mage (GGR)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Neutral Evil"
"ac": !!int "12"
"ac_class": "15 with [mage armor](/3-Mechanics/CLI/spells/mage-armor-xphb.md)"
"hp": !!int "49"
"hit_dice": "11d8"
"modifier": !!int "2"
"stats":
  - !!int "10"
  - !!int "14"
  - !!int "10"
  - !!int "20"
  - !!int "15"
  - !!int "16"
"speed": "30 ft."
"saves":
  - "intelligence": !!int "8"
  - "wisdom": !!int "5"
"skillsaves":
  - "name": "[Arcana](/3-Mechanics/CLI/skills.md#Arcana)"
    "desc": "+8"
  - "name": "[Deception](/3-Mechanics/CLI/skills.md#Deception)"
    "desc": "+6"
  - "name": "[Insight](/3-Mechanics/CLI/skills.md#Insight)"
    "desc": "+5"
  - "name": "[Persuasion](/3-Mechanics/CLI/skills.md#Persuasion)"
    "desc": "+6"
"senses": "passive Perception 12"
"languages": "Common plus any four languages"
"cr": "5"
"traits":
  - "desc": "The mage's spellcasting ability is Intelligence (spell save DC 16). It\
      \ can innately cast the following spells, requiring no components:\n\n**At will:**\
      \ [encode thoughts](/3-Mechanics/CLI/spells/encode-thoughts-ggr.md) (see chapter\
      \ 2), [friends](/3-Mechanics/CLI/spells/friends-xphb.md)\n\n**3/day each:**\
      \ [charm person](/3-Mechanics/CLI/spells/charm-person-xphb.md), [detect thoughts](/3-Mechanics/CLI/spells/detect-thoughts-xphb.md),\
      \ [mage armor](/3-Mechanics/CLI/spells/mage-armor-xphb.md), [sleep](/3-Mechanics/CLI/spells/sleep-xphb.md),\
      \ [suggestion](/3-Mechanics/CLI/spells/suggestion-xphb.md)\n\n**1/day each:**\
      \ [dominate person](/3-Mechanics/CLI/spells/dominate-person-xphb.md), [mass\
      \ suggestion](/3-Mechanics/CLI/spells/mass-suggestion-xphb.md), [modify memory](/3-Mechanics/CLI/spells/modify-memory-xphb.md)"
    "name": "Innate Spellcasting (Psionics)"
  - "desc": "The mage wears a [spies' murmur](/3-Mechanics/CLI/items/spies-murmur-ggr.md)\
      \ (see chapter 5)."
    "name": "Special Equipment"
"actions":
  - "desc": "*Melee  or Ranged Weapon Attack:* +5 to hit, reach 5 ft. or range 20/60\
      \ ft., one target. *Hit:* 4 (1d4 + 2) piercing damage."
    "name": "Dagger"
"source":
  - "GGR"
"image": "/3-Mechanics/CLI/bestiary/humanoid/token/mind-mage-ggr.webp"
```
^statblock