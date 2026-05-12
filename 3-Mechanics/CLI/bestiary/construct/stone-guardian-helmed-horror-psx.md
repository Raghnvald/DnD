---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/psx
- ttrpg-cli/monster/cr/4
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/construct
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Stone Guardian (Helmed Horror)"
---
# [Stone Guardian (Helmed Horror)](3-Mechanics/CLI/bestiary/construct/stone-guardian-helmed-horror-psx.md)
*Source: Plane Shift: Ixalan p. 40*  

Through the years in which the Sun Empire was ruled from Orazca, its priests crafted huge stone guardians to protect the empire's cities and temples. The incredible magic of the Immortal Sun gave a semblance of life to these artificial creatures, endowing them with the ability to move their stone bodies, a keen awareness of their surroundings, and a limited ability to think and reason in order to help them carry out their orders. These stone guardians were tasked with standing watch—constantly alert, vigilant to any danger, never sleeping, and unswerving in their duty.

Most stone guardians are inactive now. In ancient ruins lying far from the old capital, the magic that gave them life has faded over the centuries. Even within the golden city, many of them have become inert, and those who seek to explore Orazca or other ancient ruins must be on constant guard. Any carved figure or statue might well be a stone guardian whose magic has failed. But it might also be a guardian that is simply waiting for a threat before it activates and drives that threat away.

Constructs such as [animated armor](3-Mechanics/CLI/bestiary/construct/animated-armor.md), [helmed horrors](3-Mechanics/CLI/bestiary/construct/helmed-horror.md), [shield guardians](3-Mechanics/CLI/bestiary/construct/shield-guardian.md), and [stone golems](3-Mechanics/CLI/bestiary/construct/stone-golem.md) can represent these guardians.

```statblock
"name": "Stone Guardian (Helmed Horror) (PSX)"
"size": "Medium"
"type": "construct"
"alignment": "Unaligned"
"ac": !!int "20"
"ac_class": "[plate armor](3-Mechanics/CLI/items/plate-armor.md), [shield](3-Mechanics/CLI/items/shield.md)"
"hp": !!int "60"
"hit_dice": "8d8 + 24"
"modifier": !!int "1"
"stats":
  - !!int "18"
  - !!int "13"
  - !!int "16"
  - !!int "10"
  - !!int "10"
  - !!int "10"
"speed": "30 ft., fly 30 ft."
"skillsaves":
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+4"
"damage_resistances": "bludgeoning, piercing, slashing from nonmagical attacks that\
  \ aren't adamantine"
"damage_immunities": "force, necrotic, poison"
"condition_immunities": "[blinded](3-Mechanics/CLI/rules/conditions.md#Blinded), [charmed](3-Mechanics/CLI/rules/conditions.md#Charmed),\
  \ [deafened](3-Mechanics/CLI/rules/conditions.md#Deafened), [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened),\
  \ [paralyzed](3-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](3-Mechanics/CLI/rules/conditions.md#Petrified),\
  \ [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned), [stunned](3-Mechanics/CLI/rules/conditions.md#Stunned)"
"gear":
  - "[longsword](3-Mechanics/CLI/items/longsword.md)"
"senses": "[blindsight](3-Mechanics/CLI/rules/senses.md#Blindsight) 60 ft. (blind\
  \ beyond this radius), passive Perception 14"
"languages": "understands the languages of its creator but can't speak"
"cr": "4"
"traits":
  - "desc": "The stone guardian has advantage on saving throws against spells and\
      \ other magical effects."
    "name": "Magic Resistance"
  - "desc": "The stone guardian is immune to three spells chosen by its creator. Typical\
      \ immunities include [fireball](3-Mechanics/CLI/spells/fireball.md), [heat metal](3-Mechanics/CLI/spells/heat-metal.md),\
      \ and [lightning bolt](3-Mechanics/CLI/spells/lightning-bolt.md)."
    "name": "Spell Immunity"
"actions":
  - "desc": "The stone guardian makes two longsword attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +6 to hit, reach 5 ft., one target. *Hit:* 8\
      \ (1d8 + 4) slashing damage, or 9 (1d10 + 4) slashing damage if used with\
      \ two hands."
    "name": "Longsword"
"source":
  - "PSX"
"image": "3-Mechanics/CLI/bestiary/construct/token/stone-guardian-helmed-horror-psx.webp"
```
^statblock