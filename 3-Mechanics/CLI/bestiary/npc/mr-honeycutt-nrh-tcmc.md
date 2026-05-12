---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/nrh-tcmc
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/human
- ttrpg-cli/monster/type/humanoid/shapechanger
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Mr. Honeycutt"
---
# [Mr. Honeycutt](3-Mechanics/CLI/bestiary/npc/mr-honeycutt-nrh-tcmc.md)
*Source: NERDS Restoring Harmony: The Candy Mountain Caper p. 10, NERDS Restoring Harmony: A Voice in the Wilderness p. 9, NERDS Restoring Harmony: A Sticky Situation p. 9, NERDS Restoring Harmony: Circus of Illusions p. 10, NERDS Restoring Harmony: The Lost Tomb p. 9, NERDS Restoring Harmony: A Web of Lies p. 7, NERDS Restoring Harmony: Adventure Together p. 12*  

```statblock
"name": "Mr. Honeycutt (NRH-TCMC)"
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
  \ only), passive Perception 12"
"languages": "Common (can't speak in rat form)"
"cr": "2"
"traits":
  - "desc": "Mr. Honeycutt can use its action to polymorph into a rat-humanoid hybrid\
      \ or into a giant rat, or back into its true form, which is humanoid. Its statistics,\
      \ other than its size, are the same in each form. Any equipment it is wearing\
      \ or carrying isn't transformed. It reverts to its true form if it dies."
    "name": "Shapechanger"
  - "desc": "Mr. Honeycutt has advantage on Wisdom ([Perception](3-Mechanics/CLI/rules/skills.md#Perception))\
      \ checks that rely on smell."
    "name": "Keen Smell"
"actions":
  - "desc": "Mr. Honeycutt makes two attacks, only one of which can be a bite."
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
  - "NRH-TCMC"
  - "NRH-AVitW"
  - "NRH-ASS"
  - "NRH-CoI"
  - "NRH-TLT"
  - "NRH-AWoL"
  - "NRH-AT"
"image": "3-Mechanics/CLI/bestiary/npc/token/mr-honeycutt-nrh-tcmc.webp"
```
^statblock