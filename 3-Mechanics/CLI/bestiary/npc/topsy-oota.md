---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/oota
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/human
- ttrpg-cli/monster/type/humanoid/shapechanger
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Topsy"
---
# [Topsy](3-Mechanics/CLI/bestiary/npc/topsy-oota.md)
*Source: Out of the Abyss p. 8*  

```statblock
"name": "Topsy (OotA)"
"size": "Medium"
"type": "humanoid"
"subtype": "human, shapechanger"
"alignment": "Lawful Evil"
"ac": !!int "12"
"hp": !!int "33"
"hit_dice": "6d8 + 6"
"modifier": !!int "2"
"stats":
  - !!int "10"
  - !!int "15"
  - !!int "12"
  - !!int "11"
  - !!int "10"
  - !!int "8"
"speed": "30 ft."
"skillsaves":
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+2"
  - "name": "[Stealth](3-Mechanics/CLI/rules/skills.md#Stealth)"
    "desc": "+4"
"damage_immunities": "bludgeoning, piercing, slashing from nonmagical attacks that\
  \ aren't silvered"
"gear":
  - "[hand crossbow](3-Mechanics/CLI/items/hand-crossbow.md)"
  - "[shortsword](3-Mechanics/CLI/items/shortsword.md)"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 60 ft. (rat form\
  \ only), [darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 120 ft., passive\
  \ Perception 12"
"languages": "Gnomish, Terran, Undercommon"
"cr": "2"
"traits":
  - "desc": "Topsy\n\n**At will:** [nondetection](3-Mechanics/CLI/spells/nondetection.md)\
      \ (self only)\n\n**1/day each:** [blindness/deafness](3-Mechanics/CLI/spells/blindness-deafness.md),\
      \ [blur](3-Mechanics/CLI/spells/blur.md), [disguise self](3-Mechanics/CLI/spells/disguise-self.md)"
    "name": "Innate Spellcasting"
  - "desc": "Topsy can use its action to polymorph into a rat-humanoid hybrid or into\
      \ a giant rat, or back into its true form, which is humanoid. Its statistics,\
      \ other than its size, are the same in each form. Any equipment it is wearing\
      \ or carrying isn't transformed. It reverts to its true form if it dies."
    "name": "Shapechanger"
  - "desc": "Topsy has advantage on Wisdom ([Perception](3-Mechanics/CLI/rules/skills.md#Perception))\
      \ checks that rely on smell."
    "name": "Keen Smell"
  - "desc": "Topsy"
    "name": "Gnome Cunning"
  - "desc": "Topsy"
    "name": "Stone Camouflage"
"actions":
  - "desc": "Topsy makes two attacks, only one of which can be a bite."
    "name": "Multiattack (Humanoid or Hybrid Form Only)"
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one target. *Hit:* 4\
      \ (1d4 + 2) piercing damage. If the target is a humanoid, it must succeed\
      \ on a DC 11 Constitution saving throw or be cursed with wererat lycanthropy."
    "name": "Bite (Rat or Hybrid Form Only)"
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one target. *Hit:* 5\
      \ (1d6 + 2) piercing damage."
    "name": "Shortsword (Humanoid or Hybrid Form Only)"
  - "desc": "*Ranged Weapon Attack:* +4 to hit, range 30/120 ft., one target. *Hit:*\
      \ 5 (1d6 + 2) piercing damage."
    "name": "Hand Crossbow (Humanoid or Hybrid Form Only)"
"source":
  - "OotA"
"image": "3-Mechanics/CLI/bestiary/npc/token/topsy-oota.webp"
```
^statblock