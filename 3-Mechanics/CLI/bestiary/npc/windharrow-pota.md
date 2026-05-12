---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/pota
- ttrpg-cli/monster/cr/3
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/half-elf
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Windharrow"
---
# [Windharrow](3-Mechanics/CLI/bestiary/npc/windharrow-pota.md)
*Source: Princes of the Apocalypse p. 192*  

An opportunistic half-moon elf rake and bandit formerly known as Harald Grayspear, Windharrow was given his new name by Aerisi Kalinoth. When Aerisi was still with her family, Harald charmed and flattered his way into her favor. When Aerisi ran away from home to become the air prophet, she took Windharrow with her.

At Aerisi's insistence, Windharrow recruited a band of flutists from the ranks of new converts to the air cult, calling them the Windwyrds. Most have no musical talent whatsoever, and their music is often a shrill cacophony. Of all the air cultists, the Windwyrds are the least fanatical and the most fearful for their lives. Aerisi disposes of these minstrels on a whim, replacing them with other initiates. Those that master some skill with their instruments survive the longest, but the cost of failure creates a highly competitive environment among the minstrels.

Windharrow is loyal to Aerisi Kalinoth as long as he fears her power. If his life is threatened or a richer offer presents itself, Windharrow betrays the air cult without a backward glance.

```statblock
"name": "Windharrow (PotA)"
"size": "Medium"
"type": "humanoid"
"subtype": "half-elf"
"alignment": "Neutral Evil"
"ac": !!int "15"
"ac_class": "[studded leather](3-Mechanics/CLI/items/studded-leather-armor.md)"
"hp": !!int "55"
"hit_dice": "10d8 + 10"
"modifier": !!int "3"
"stats":
  - !!int "10"
  - !!int "16"
  - !!int "12"
  - !!int "14"
  - !!int "10"
  - !!int "17"
"speed": "30 ft."
"skillsaves":
  - "name": "[Acrobatics](3-Mechanics/CLI/rules/skills.md#Acrobatics)"
    "desc": "+5"
  - "name": "[Deception](3-Mechanics/CLI/rules/skills.md#Deception)"
    "desc": "+7"
  - "name": "[Persuasion](3-Mechanics/CLI/rules/skills.md#Persuasion)"
    "desc": "+5"
  - "name": "[Performance](3-Mechanics/CLI/rules/skills.md#Performance)"
    "desc": "+7"
  - "name": "[Stealth](3-Mechanics/CLI/rules/skills.md#Stealth)"
    "desc": "+5"
"gear":
  - "[rapier](3-Mechanics/CLI/items/rapier.md)"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., passive\
  \ Perception 10"
"languages": "Auran, Common, Elvish"
"cr": "3"
"traits":
  - "desc": "Windharrow is an 8th-level spellcaster. His spellcasting ability is Charisma\
      \ (spell save DC 13, +5 to hit with spell attacks). Windharrow knows the following\
      \ bard spells:\n\n**Cantrips (at will):** [friends](3-Mechanics/CLI/spells/friends.md),\
      \ [prestidigitation](3-Mechanics/CLI/spells/prestidigitation.md), [vicious mockery](3-Mechanics/CLI/spells/vicious-mockery.md)\n\
      \n**1st level (4 slots):** [disguise self](3-Mechanics/CLI/spells/disguise-self.md),\
      \ [dissonant whispers](3-Mechanics/CLI/spells/dissonant-whispers.md), [thunderwave](3-Mechanics/CLI/spells/thunderwave.md)\n\
      \n**2nd level (3 slots):** [invisibility](3-Mechanics/CLI/spells/invisibility.md),\
      \ [shatter](3-Mechanics/CLI/spells/shatter.md), [silence](3-Mechanics/CLI/spells/silence.md)\n\
      \n**3rd level (3 slots):** [nondetection](3-Mechanics/CLI/spells/nondetection.md),\
      \ [sending](3-Mechanics/CLI/spells/sending.md), [tongues](3-Mechanics/CLI/spells/tongues.md)\n\
      \n**4th level (2 slots):** [confusion](3-Mechanics/CLI/spells/confusion.md),\
      \ [dimension door](3-Mechanics/CLI/spells/dimension-door.md)"
    "name": "Spellcasting"
  - "desc": "Windharrow has advantage on saving throws against being [charmed](3-Mechanics/CLI/rules/conditions.md#Charmed),\
      \ and magic can't put him to sleep."
    "name": "Fey Ancestry"
"actions":
  - "desc": "Windharrow makes two melee attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one creature. *Hit:*\
      \ 7 (1d8 + 3) piercing damage."
    "name": "Rapier"
"source":
  - "PotA"
"image": "3-Mechanics/CLI/bestiary/npc/token/windharrow-pota.webp"
```
^statblock