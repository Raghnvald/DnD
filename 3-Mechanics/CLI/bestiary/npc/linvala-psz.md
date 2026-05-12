---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/psz
- ttrpg-cli/monster/cr/16
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/celestial
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Linvala"
---
# [Linvala](3-Mechanics/CLI/bestiary/npc/linvala-psz.md)
*Source: Plane Shift: Zendikar p. 21*  

The angels of Zendikar are living manifestations of white mana, and they embody its inherent tendencies toward morality and order. Peace and harmony are their goals, though they are more concerned with reestablishing the natural order of the plane than with interfering in disputes between the lowly mortal races. Angels appear similar to female humans possessing two, four, or six feathered wings. Their eyes glow with inner light, and glowing golden rings surround their heads—usually positioned to cover their eyes.

Zendikar's people consider the angels to be aloof but benevolent. Their resistance to the Eldrazi broods in the ancient past is vaguely remembered in the myths of the humans, kor, and merfolk. Humans in particular venerate angels as divine protectors because of those myths.

You can represent most angels in Zendikar using the [deva](3-Mechanics/CLI/bestiary/celestial/deva.md) in the Monster Manual. For unique or more powerful angels, you can use the [planetar](3-Mechanics/CLI/bestiary/celestial/planetar.md) or [solar](3-Mechanics/CLI/bestiary/celestial/solar.md) instead. Perhaps [Linvala](3-Mechanics/CLI/bestiary/npc/linvala-psz.md) is a [planetar](3-Mechanics/CLI/bestiary/celestial/planetar.md) and [Iona](3-Mechanics/CLI/bestiary/npc/iona-psz.md) is a [solar](3-Mechanics/CLI/bestiary/celestial/solar.md).

```statblock
"name": "Linvala (PSZ)"
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
  - "desc": "Linvala's spellcasting ability is Charisma (spell save DC 20). Linvala\
      \ can innately cast the following spells, requiring no material components:\n\
      \n**At will:** [detect evil and good](3-Mechanics/CLI/spells/detect-evil-and-good.md),\
      \ [invisibility](3-Mechanics/CLI/spells/invisibility.md) (self only)\n\n**3/day\
      \ each:** [blade barrier](3-Mechanics/CLI/spells/blade-barrier.md), [dispel\
      \ evil and good](3-Mechanics/CLI/spells/dispel-evil-and-good.md), [flame strike](3-Mechanics/CLI/spells/flame-strike.md),\
      \ [raise dead](3-Mechanics/CLI/spells/raise-dead.md)\n\n**1/day each:** [commune](3-Mechanics/CLI/spells/commune.md),\
      \ [control weather](3-Mechanics/CLI/spells/control-weather.md), [insect plague](3-Mechanics/CLI/spells/insect-plague.md)"
    "name": "Innate Spellcasting"
  - "desc": "Linvala's weapon attacks are magical. When Linvala hits with any weapon,\
      \ the weapon deals an extra 5d8 radiant damage (included in the attack)."
    "name": "Angelic Weapons"
  - "desc": "Linvala knows if it hears a lie."
    "name": "Divine Awareness"
  - "desc": "Linvala has advantage on saving throws against spells and other magical\
      \ effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "Linvala makes two melee attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +12 to hit, reach 5 ft., one target. *Hit:*\
      \ 21 (4d6 + 7) slashing damage plus 22 (5d8) radiant damage."
    "name": "Greatsword"
  - "desc": "Linvala touches another creature. The target magically regains 30 (6d8\
      \ + 3) hit points and is freed from any curse, disease, poison, blindness,\
      \ or deafness."
    "name": "Healing Touch (4/Day)"
"source":
  - "PSZ"
"image": "3-Mechanics/CLI/bestiary/npc/token/linvala-psz.webp"
```
^statblock