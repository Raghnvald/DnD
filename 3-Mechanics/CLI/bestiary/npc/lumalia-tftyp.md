---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/tftyp
- ttrpg-cli/monster/cr/10
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/celestial
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Lumalia"
---
# [Lumalia](3-Mechanics/CLI/bestiary/npc/lumalia-tftyp.md)
*Source: Tales from the Yawning Portal p. 153*  

```statblock
"name": "Lumalia (TftYP)"
"size": "Medium"
"type": "celestial"
"alignment": "Lawful Good"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "136"
"hit_dice": "16d8 + 64"
"modifier": !!int "4"
"stats":
  - !!int "18"
  - !!int "18"
  - !!int "18"
  - !!int "17"
  - !!int "20"
  - !!int "20"
"speed": "30 ft., fly 90 ft."
"saves":
  - "wisdom": !!int "9"
  - "charisma": !!int "9"
"skillsaves":
  - "name": "[Insight](3-Mechanics/CLI/rules/skills.md#Insight)"
    "desc": "+9"
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+9"
"damage_resistances": "radiant; bludgeoning, piercing, slashing from nonmagical attacks"
"condition_immunities": "[charmed](3-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](3-Mechanics/CLI/rules/conditions.md#Exhaustion),\
  \ [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened)"
"gear":
  - "[mace](3-Mechanics/CLI/items/mace-xphb.md)"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 120 ft., passive\
  \ Perception 19"
"languages": "all, telepathy 120 ft."
"cr": "10"
"traits":
  - "desc": "Lumalia's spellcasting ability is Charisma (spell save DC 17). Lumalia\
      \ can innately cast the following spells, requiring only verbal components:\n\
      \n**At will:** [detect evil and good](3-Mechanics/CLI/spells/detect-evil-and-good-xphb.md)\n\
      \n**1/day each:** [commune](3-Mechanics/CLI/spells/commune-xphb.md), [raise\
      \ dead](3-Mechanics/CLI/spells/raise-dead-xphb.md)"
    "name": "Innate Spellcasting"
  - "desc": "Lumalia's weapon attacks are magical. When Lumalia hits with any weapon,\
      \ the weapon deals an extra 4d8 radiant damage (included in the attack)."
    "name": "Angelic Weapons"
  - "desc": "Lumalia has advantage on saving throws against spells and other magical\
      \ effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "Lumalia makes two melee attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +8 to hit, reach 5 ft., one target. *Hit:* 7\
      \ (1d6 + 4) bludgeoning damage plus 18 (4d8) radiant damage."
    "name": "Mace"
  - "desc": "Lumalia touches another creature. The target magically regains 20 (4d8\
      \ + 2) hit points and is freed from any curse, disease, poison, blindness,\
      \ or deafness."
    "name": "Healing Touch (3/Day)"
  - "desc": "Lumalia magically polymorphs into a humanoid or beast that has a challenge\
      \ rating equal to or less than its own, or back into its true form. It reverts\
      \ to its true form if it dies. Any equipment it is wearing or carrying is absorbed\
      \ or borne by the new form (Lumalia's choice).\n\nIn a new form, Lumalia retains\
      \ its game statistics and ability to speak, but its AC, movement modes, Strength,\
      \ Dexterity, and special senses are replaced by those of the new form, and it\
      \ gains any statistics and capabilities (except class features, legendary actions,\
      \ and lair actions) that the new form has but that it lacks."
    "name": "Change Shape"
"source":
  - "TftYP"
"image": "3-Mechanics/CLI/bestiary/npc/token/lumalia-tftyp.webp"
```
^statblock