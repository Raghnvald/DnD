---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/psz
- ttrpg-cli/monster/cr/10
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/celestial
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Angel"
---
# [Angel](3-Mechanics/CLI/bestiary/celestial/angel-psz.md)
*Source: Plane Shift: Zendikar p. 21*  

The angels of Zendikar are living manifestations of white mana, and they embody its inherent tendencies toward morality and order. Peace and harmony are their goals, though they are more concerned with reestablishing the natural order of the plane than with interfering in disputes between the lowly mortal races. Angels appear similar to female humans possessing two, four, or six feathered wings. Their eyes glow with inner light, and glowing golden rings surround their heads—usually positioned to cover their eyes.

Zendikar's people consider the angels to be aloof but benevolent. Their resistance to the Eldrazi broods in the ancient past is vaguely remembered in the myths of the humans, kor, and merfolk. Humans in particular venerate angels as divine protectors because of those myths.

You can represent most angels in Zendikar using the [deva](3-Mechanics/CLI/bestiary/celestial/deva.md) in the Monster Manual. For unique or more powerful angels, you can use the [planetar](3-Mechanics/CLI/bestiary/celestial/planetar.md) or [solar](3-Mechanics/CLI/bestiary/celestial/solar.md) instead. Perhaps [Linvala](3-Mechanics/CLI/bestiary/npc/linvala-psz.md) is a [planetar](3-Mechanics/CLI/bestiary/celestial/planetar.md) and [Iona](3-Mechanics/CLI/bestiary/npc/iona-psz.md) is a [solar](3-Mechanics/CLI/bestiary/celestial/solar.md).

```statblock
"name": "Angel (PSZ)"
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
  - "PSZ"
"image": "3-Mechanics/CLI/bestiary/celestial/token/angel-psz.webp"
```
^statblock