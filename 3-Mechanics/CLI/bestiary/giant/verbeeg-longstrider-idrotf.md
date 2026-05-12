---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/idrotf
- ttrpg-cli/monster/cr/5
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/giant
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Verbeeg Longstrider"
---
# [Verbeeg Longstrider](3-Mechanics/CLI/bestiary/giant/verbeeg-longstrider-idrotf.md)
*Source: Icewind Dale: Rime of the Frostmaiden p. 311*  

Verbeeg are giants that resemble oversized humans with gangly limbs and elongated faces. Some have other features that give them a fearsome aspect.

Verbeeg craft their own armor and weapons. They prefer thrown spears above all other weapons, and a verbeeg usually has several spears for that purpose.

## Longstriders

Some verbeeg worship gods of nature and help defend the natural world. These even-tempered verbeeg are called longstriders and are blessed with innate spellcasting abilities.

```statblock
"name": "Verbeeg Longstrider (IDRotF)"
"size": "Large"
"type": "giant"
"alignment": "Neutral"
"ac": !!int "14"
"ac_class": "[hide armor](3-Mechanics/CLI/items/hide-armor.md)"
"hp": !!int "119"
"hit_dice": "14d10 + 42"
"modifier": !!int "2"
"stats":
  - !!int "19"
  - !!int "15"
  - !!int "16"
  - !!int "13"
  - !!int "14"
  - !!int "10"
"speed": "50 ft."
"saves":
  - "dexterity": !!int "5"
  - "constitution": !!int "6"
  - "wisdom": !!int "5"
"skillsaves":
  - "name": "[Animal Handling](3-Mechanics/CLI/rules/skills.md#Animal%20Handling)"
    "desc": "+5"
  - "name": "[Athletics](3-Mechanics/CLI/rules/skills.md#Athletics)"
    "desc": "+7"
  - "name": "[Stealth](3-Mechanics/CLI/rules/skills.md#Stealth)"
    "desc": "+5"
"gear":
  - "[sling](3-Mechanics/CLI/items/sling.md)"
  - "[spear](3-Mechanics/CLI/items/spear.md)"
"senses": "passive Perception 12"
"languages": "Common, Giant"
"cr": "5"
"traits":
  - "desc": "The verbeeg's innate spellcasting ability is Wisdom. It can innately\
      \ cast the following spells, requiring no components:\n\n**1/day each:** [animal\
      \ messenger](3-Mechanics/CLI/spells/animal-messenger.md), [fog cloud](3-Mechanics/CLI/spells/fog-cloud.md),\
      \ [freedom of movement](3-Mechanics/CLI/spells/freedom-of-movement.md), [pass\
      \ without trace](3-Mechanics/CLI/spells/pass-without-trace.md), [silence](3-Mechanics/CLI/spells/silence.md),\
      \ [water walk](3-Mechanics/CLI/spells/water-walk.md)"
    "name": "Innate Spellcasting"
  - "desc": "A simple weapon deals one extra die of its damage when the verbeeg hits\
      \ with it (included in the attack)."
    "name": "Simple Weapon Wielder"
"actions":
  - "desc": "The verbeeg makes two melee attacks."
    "name": "Multiattack"
  - "desc": "*Melee  or Ranged Weapon Attack:* +7 to hit, reach 5 ft. or range 20/60\
      \ ft., one target. *Hit:* 14 (3d6 + 4) piercing damage, or 17 (3d8 + 4)\
      \ piercing damage if used to make a ranged attack or used with two hands to\
      \ make a melee attack."
    "name": "Spear"
  - "desc": "*Ranged Weapon Attack:* +5 to hit, range 30/120 ft., one target. *Hit:*\
      \ 9 (3d4 + 2) bludgeoning damage. If the target is a creature, it must succeed\
      \ on a DC 15 Constitution saving throw or be [stunned](3-Mechanics/CLI/rules/conditions.md#Stunned)\
      \ until the end of its next turn."
    "name": "Sling"
"source":
  - "IDRotF"
"image": "3-Mechanics/CLI/bestiary/giant/token/verbeeg-longstrider-idrotf.webp"
```
^statblock