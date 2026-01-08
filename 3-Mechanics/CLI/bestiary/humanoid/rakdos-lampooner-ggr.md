---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/ggr
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/any-race
statblock: inline
statblock-link: "#^statblock"
aliases:
- Rakdos Lampooner
---
# [Rakdos Lampooner](3-Mechanics\CLI\bestiary\humanoid/rakdos-lampooner-ggr.md)
*Source: Guildmasters' Guide to Ravnica p. 248*  

One of the most effective weapons in the Rakdos cult's arsenal is satire, and a Rakdos lampooner is a virtuoso of that art. Lampooners generally reserve their mockery for people and guilds that have seized an outsized measure of power, those who need to be taken down a peg, rather than piling further humiliation onto those who are already struggling. They use masks, marionettes, or effigies to caricature public figures, or sometimes play pranks on those individuals directly in the streets.

```statblock
"name": "Rakdos Lampooner (GGR)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Chaotic Evil"
"ac": !!int "12"
"ac_class": "[leather armor](/3-Mechanics/CLI/items/leather-armor-xphb.md)"
"hp": !!int "27"
"hit_dice": "5d8 + 5"
"modifier": !!int "1"
"stats":
  - !!int "11"
  - !!int "12"
  - !!int "13"
  - !!int "12"
  - !!int "9"
  - !!int "18"
"speed": "30 ft."
"skillsaves":
  - "name": "[Deception](/3-Mechanics/CLI/skills.md#Deception)"
    "desc": "+6"
  - "name": "[Performance](/3-Mechanics/CLI/skills.md#Performance)"
    "desc": "+6"
"senses": "passive Perception 9"
"languages": "Common plus any one language"
"cr": "2"
"traits":
  - "desc": "The lampooner is a 4th-level Rakdos spellcaster. Its spellcasting ability\
      \ is Charisma (spell save DC 14, +6 to hit with spell attacks). It knows the\
      \ following bard spells:\n\n**Cantrips (at will):** [dancing lights](/3-Mechanics/CLI/spells/dancing-lights-xphb.md),\
      \ [minor illusion](/3-Mechanics/CLI/spells/minor-illusion-xphb.md), [vicious\
      \ mockery](/3-Mechanics/CLI/spells/vicious-mockery-xphb.md)\n\n**1st level (4\
      \ slots):** [bane](/3-Mechanics/CLI/spells/bane-xphb.md), [dissonant whispers](/3-Mechanics/CLI/spells/dissonant-whispers-xphb.md),\
      \ [silent image](/3-Mechanics/CLI/spells/silent-image-xphb.md), [Tasha's hideous\
      \ laughter](/3-Mechanics/CLI/spells/tashas-hideous-laughter-xphb.md), [thunderwave](/3-Mechanics/CLI/spells/thunderwave-xphb.md)\n\
      \n**2nd level (3 slots):** [crown of madness](/3-Mechanics/CLI/spells/crown-of-madness-xphb.md),\
      \ [enthrall](/3-Mechanics/CLI/spells/enthrall-xphb.md), [suggestion](/3-Mechanics/CLI/spells/suggestion-xphb.md)"
    "name": "Spellcasting"
"actions":
  - "desc": "*Melee Weapon Attack:* +2 to hit, reach 5 ft., one target. *Hit:* 2 (1d4)\
      \ bludgeoning damage."
    "name": "Club"
"source":
  - "GGR"
"image": "/3-Mechanics/CLI/bestiary/humanoid/token/rakdos-lampooner-ggr.webp"
```
^statblock