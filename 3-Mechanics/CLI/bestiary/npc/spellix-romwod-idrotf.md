---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/idrotf
- ttrpg-cli/monster/cr/1-2
- ttrpg-cli/monster/size/small
- ttrpg-cli/monster/type/humanoid/gnome
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Spellix Romwod"
---
# [Spellix Romwod](3-Mechanics/CLI/bestiary/npc/spellix-romwod-idrotf.md)
*Source: Icewind Dale: Rime of the Frostmaiden p. 144*  

```statblock
"name": "Spellix Romwod (IDRotF)"
"size": "Small"
"type": "humanoid"
"subtype": "gnome"
"alignment": "Chaotic Neutral"
"ac": !!int "14"
"ac_class": "[hide armor](3-Mechanics/CLI/items/hide-armor.md)"
"hp": !!int "33"
"hit_dice": "6d6 + 12"
"modifier": !!int "2"
"stats":
  - !!int "6"
  - !!int "15"
  - !!int "14"
  - !!int "15"
  - !!int "9"
  - !!int "16"
"speed": "25 ft."
"skillsaves":
  - "name": "[Arcana](3-Mechanics/CLI/rules/skills.md#Arcana)"
    "desc": "+4"
  - "name": "[Deception](3-Mechanics/CLI/rules/skills.md#Deception)"
    "desc": "+5"
  - "name": "[History](3-Mechanics/CLI/rules/skills.md#History)"
    "desc": "+4"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., passive\
  \ Perception 9"
"languages": "Common, Draconic, Elvish, Gnomish, Goblin"
"cr": "1/2"
"traits":
  - "desc": "Spellix's spellcasting ability is Charisma (spell save DC 13, +5 to\
      \ hit with spell attacks). He can innately cast the following spells, requiring\
      \ no material components:\n\n**At will:** [fire bolt](3-Mechanics/CLI/spells/fire-bolt.md)*,\
      \ [mage hand](3-Mechanics/CLI/spells/mage-hand.md), [shocking grasp](3-Mechanics/CLI/spells/shocking-grasp.md)*\n\
      \n**3/day:** [silent image](3-Mechanics/CLI/spells/silent-image.md)\n\n**1/day\
      \ each:** [chromatic orb](3-Mechanics/CLI/spells/chromatic-orb.md), [crown of\
      \ madness](3-Mechanics/CLI/spells/crown-of-madness.md), [shield](3-Mechanics/CLI/spells/shield.md)\n\
      \n*See \"Actions\" below."
    "name": "Innate Spellcasting"
  - "desc": "Spellix has advantage on all Intelligence, Wisdom, and Charisma saving\
      \ throws against magic."
    "name": "Gnome Cunning"
"actions":
  - "desc": "*Melee Spell Attack:* +5 to hit (with advantage on the attack roll\
      \ if the target is wearing armor made of metal), reach 5 ft., one creature.\
      \ *Hit:* 4 (1d8) lightning damage, and the target can't take reactions until\
      \ the start of its next turn."
    "name": "Shocking Grasp (Cantrip)"
  - "desc": "*Ranged Spell Attack:* +5 to hit, range 120 ft., one target. *Hit:*\
      \ 5 (1d10) fire damage. A flammable object hit by this spell ignites if it\
      \ isn't being worn or carried."
    "name": "Fire Bolt (Cantrip)"
"source":
  - "IDRotF"
"image": "3-Mechanics/CLI/bestiary/npc/token/spellix-romwod-idrotf.webp"
```
^statblock