---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/psd
- ttrpg-cli/monster/cr/10
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/celestial
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Serra Angel"
---
# [Serra Angel](3-Mechanics/CLI/bestiary/celestial/serra-angel-psd.md)
*Source: Plane Shift: Dominaria p. 9*  

The most visible and recognized symbols of the Church of Serra are her angels—both those that were personally created by Serra and those that appeared spontaneously in the Cathedral at Sursi. Some angels live contemplative lives within the cathedrals, but most are active defenders of the faith, protecting Serra's people across the world. Powerful angels often take responsibility for large regions of the world. Lyra, for example, stands as the protector of Benalia, and Shalai plays a similar role in Llanowar. Serra's angels are believed to hear prayers addressed to Serra, and they have an uncanny tendency to arrive exactly when they are needed.

Any of the angels in the "Monster Manual" can serve as [Serra angels](3-Mechanics/CLI/bestiary/celestial/serra-angel-psd.md). The [deva](3-Mechanics/CLI/bestiary/celestial/deva.md) represents the most common angels, while the [planetar](3-Mechanics/CLI/bestiary/celestial/planetar.md) and [solar](3-Mechanics/CLI/bestiary/celestial/solar.md) are appropriate for powerful angels such as [Lyra](3-Mechanics/CLI/bestiary/npc/lyra-psd.md) and [Shalai](3-Mechanics/CLI/bestiary/npc/shalai-psd.md).

```statblock
"name": "Serra Angel (PSD)"
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
  - "[mace](3-Mechanics/CLI/items/mace.md)"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 120 ft., passive\
  \ Perception 19"
"languages": "all, telepathy 120 ft."
"cr": "10"
"traits":
  - "desc": "The angel's spellcasting ability is Charisma (spell save DC 17). The\
      \ angel can innately cast the following spells, requiring only verbal components:\n\
      \n**At will:** [detect evil and good](3-Mechanics/CLI/spells/detect-evil-and-good.md)\n\
      \n**1/day each:** [commune](3-Mechanics/CLI/spells/commune.md), [raise dead](3-Mechanics/CLI/spells/raise-dead.md)"
    "name": "Innate Spellcasting"
  - "desc": "The angel's weapon attacks are magical. When the angel hits with any\
      \ weapon, the weapon deals an extra 4d8 radiant damage (included in the attack)."
    "name": "Angelic Weapons"
  - "desc": "The angel has advantage on saving throws against spells and other magical\
      \ effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "The angel makes two melee attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +8 to hit, reach 5 ft., one target. *Hit:* 7\
      \ (1d6 + 4) bludgeoning damage plus 18 (4d8) radiant damage."
    "name": "Mace"
  - "desc": "The angel touches another creature. The target magically regains 20 (4d8\
      \ + 2) hit points and is freed from any curse, disease, poison, blindness,\
      \ or deafness."
    "name": "Healing Touch (3/Day)"
  - "desc": "The angel magically polymorphs into a humanoid or beast that has a challenge\
      \ rating equal to or less than its own, or back into its true form. It reverts\
      \ to its true form if it dies. Any equipment it is wearing or carrying is absorbed\
      \ or borne by the new form (the angel's choice).\n\nIn a new form, the angel\
      \ retains its game statistics and ability to speak, but its AC, movement modes,\
      \ Strength, Dexterity, and special senses are replaced by those of the new form,\
      \ and it gains any statistics and capabilities (except class features, legendary\
      \ actions, and lair actions) that the new form has but that it lacks."
    "name": "Change Shape"
"source":
  - "PSD"
"image": "3-Mechanics/CLI/bestiary/celestial/token/serra-angel-psd.webp"
```
^statblock