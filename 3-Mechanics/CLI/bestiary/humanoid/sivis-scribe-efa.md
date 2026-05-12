---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/efa
- ttrpg-cli/monster/cr/3
- ttrpg-cli/monster/size/small
- ttrpg-cli/monster/type/humanoid/gnome
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Sivis Scribe"
---
# [Sivis Scribe](3-Mechanics/CLI/bestiary/humanoid/sivis-scribe-efa.md)
*Source: Eberron: Forge of the Artificer p. 84*  

The dragonmarked heirs of House Sivis are typically accomplished gnome scholars of magic. In addition to the might that comes with their marks, they favor magical sigils and words of power.

```statblock
"name": "Sivis Scribe (EFA)"
"size": "Small"
"type": "humanoid"
"subtype": "gnome"
"alignment": "Neutral"
"ac": !!int "15"
"hp": !!int "56"
"hit_dice": "16d6"
"modifier": !!int "2"
"stats":
  - !!int "11"
  - !!int "15"
  - !!int "10"
  - !!int "16"
  - !!int "12"
  - !!int "11"
"speed": "30 ft."
"saves":
  - "wisdom": !!int "3"
"skillsaves":
  - "name": "Arcana"
    "desc": "+5"
  - "name": "Sleight of Hand"
    "desc": "+4"
"senses": "Darkvision 60 ft., passive Perception 11"
"languages": "Common, Gnomish plus three other languages"
"cr": "3"
"traits":
  - "desc": "Allies in a 10-foot <span title=\"Player's Handbook (2024)\">Emanation</span>\
      \ originating from the scribe have <span title=\"Player's Handbook (2024)\"\
      >Advantage</span> on saving throws to avoid or end the Charmed or Frightened\
      \ condition. This trait doesn't function if the scribe has the Incapacitated\
      \ condition."
    "name": "Words of Reason"
"actions":
  - "desc": "The scribe makes two Bursting Sigil attacks."
    "name": "Multiattack"
  - "desc": "*Melee  or Ranged Attack Roll:* +5, reach 5 ft. or range 60 ft. *Hit:*\
      \ 13 (3d6 + 3) Radiant damage."
    "name": "Bursting Sigil"
  - "desc": "The scribe casts one of the following spells, requiring no Material components\
      \ and using Intelligence as the spellcasting ability (DC 13):\n\n**At will:**\
      \ Comprehend Languages, Mage Armor (included in AC), Message\n\n1/Da y: Sending"
    "name": "Spellcasting"
"reactions":
  - "desc": "*Constitution Saving Throw:* DC 13, each creature in a 20-foot-radius\
      \ <span title=\"Player's Handbook (2024)\">Sphere</span> centered on a point\
      \ the scribe can see within 60 feet. *Failure:* The target has the Incapacitated\
      \ condition until the start of the scribe's next turn. While the target is Incapacitated,\
      \ its <span title=\"Player's Handbook (2024)\">Speed</span> is 0 and can't increase."
    "name": "Word of Stasis (Recharge 5-6)"
"source":
  - "EFA"
"image": "3-Mechanics/CLI/bestiary/humanoid/token/sivis-scribe-efa.webp"
```
^statblock