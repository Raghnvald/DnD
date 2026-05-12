---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/psd
- ttrpg-cli/monster/cr/16
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/celestial
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Lyra"
---
# [Lyra](3-Mechanics/CLI/bestiary/npc/lyra-psd.md)
*Source: Plane Shift: Dominaria p. 9*  

The most visible and recognized symbols of the Church of Serra are her angels—both those that were personally created by Serra and those that appeared spontaneously in the Cathedral at Sursi. Some angels live contemplative lives within the cathedrals, but most are active defenders of the faith, protecting Serra's people across the world. Powerful angels often take responsibility for large regions of the world. Lyra, for example, stands as the protector of Benalia, and Shalai plays a similar role in Llanowar. Serra's angels are believed to hear prayers addressed to Serra, and they have an uncanny tendency to arrive exactly when they are needed.

Any of the angels in the "Monster Manual" can serve as [Serra angels](3-Mechanics/CLI/bestiary/celestial/serra-angel-psd.md). The [deva](3-Mechanics/CLI/bestiary/celestial/deva.md) represents the most common angels, while the [planetar](3-Mechanics/CLI/bestiary/celestial/planetar.md) and [solar](3-Mechanics/CLI/bestiary/celestial/solar.md) are appropriate for powerful angels such as [Lyra](3-Mechanics/CLI/bestiary/npc/lyra-psd.md) and [Shalai](3-Mechanics/CLI/bestiary/npc/shalai-psd.md).

```statblock
"name": "Lyra (PSD)"
"size": "Large"
"type": "celestial"
"alignment": "Lawful Good"
"ac": !!int "19"
"ac_class": "natural armor"
"hp": !!int "200"
"hit_dice": "16d10 + 112"
"modifier": !!int "5"
"stats":
  - !!int "24"
  - !!int "20"
  - !!int "24"
  - !!int "19"
  - !!int "22"
  - !!int "25"
"speed": "40 ft., fly 120 ft."
"saves":
  - "constitution": !!int "12"
  - "wisdom": !!int "11"
  - "charisma": !!int "12"
"skillsaves":
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+11"
"damage_resistances": "radiant; bludgeoning, piercing, slashing from nonmagical attacks"
"condition_immunities": "[charmed](3-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](3-Mechanics/CLI/rules/conditions.md#Exhaustion),\
  \ [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened)"
"gear":
  - "[greatsword](3-Mechanics/CLI/items/greatsword.md)"
"senses": "[truesight](3-Mechanics/CLI/rules/senses.md#Truesight) 120 ft., passive\
  \ Perception 21"
"languages": "all, telepathy 120 ft."
"cr": "16"
"traits":
  - "desc": "Lyra's spellcasting ability is Charisma (spell save DC 20). Lyra can\
      \ innately cast the following spells, requiring no material components:\n\n\
      **At will:** [detect evil and good](3-Mechanics/CLI/spells/detect-evil-and-good.md),\
      \ [invisibility](3-Mechanics/CLI/spells/invisibility.md) (self only)\n\n**3/day\
      \ each:** [blade barrier](3-Mechanics/CLI/spells/blade-barrier.md), [dispel\
      \ evil and good](3-Mechanics/CLI/spells/dispel-evil-and-good.md), [flame strike](3-Mechanics/CLI/spells/flame-strike.md),\
      \ [raise dead](3-Mechanics/CLI/spells/raise-dead.md)\n\n**1/day each:** [commune](3-Mechanics/CLI/spells/commune.md),\
      \ [control weather](3-Mechanics/CLI/spells/control-weather.md), [insect plague](3-Mechanics/CLI/spells/insect-plague.md)"
    "name": "Innate Spellcasting"
  - "desc": "Lyra's weapon attacks are magical. When Lyra hits with any weapon, the\
      \ weapon deals an extra 5d8 radiant damage (included in the attack)."
    "name": "Angelic Weapons"
  - "desc": "Lyra knows if it hears a lie."
    "name": "Divine Awareness"
  - "desc": "Lyra has advantage on saving throws against spells and other magical\
      \ effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "Lyra makes two melee attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +12 to hit, reach 5 ft., one target. *Hit:*\
      \ 21 (4d6 + 7) slashing damage plus 22 (5d8) radiant damage."
    "name": "Greatsword"
  - "desc": "Lyra touches another creature. The target magically regains 30 (6d8\
      \ + 3) hit points and is freed from any curse, disease, poison, blindness,\
      \ or deafness."
    "name": "Healing Touch (4/Day)"
"source":
  - "PSD"
"image": "3-Mechanics/CLI/bestiary/npc/token/lyra-psd.webp"
```
^statblock