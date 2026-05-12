---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/psx
- ttrpg-cli/monster/cr/1
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/construct
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Stone Guardian (Animated Armor)"
---
# [Stone Guardian (Animated Armor)](3-Mechanics/CLI/bestiary/construct/stone-guardian-animated-armor-psx.md)
*Source: Plane Shift: Ixalan p. 40*  

Through the years in which the Sun Empire was ruled from Orazca, its priests crafted huge stone guardians to protect the empire's cities and temples. The incredible magic of the Immortal Sun gave a semblance of life to these artificial creatures, endowing them with the ability to move their stone bodies, a keen awareness of their surroundings, and a limited ability to think and reason in order to help them carry out their orders. These stone guardians were tasked with standing watch—constantly alert, vigilant to any danger, never sleeping, and unswerving in their duty.

Most stone guardians are inactive now. In ancient ruins lying far from the old capital, the magic that gave them life has faded over the centuries. Even within the golden city, many of them have become inert, and those who seek to explore Orazca or other ancient ruins must be on constant guard. Any carved figure or statue might well be a stone guardian whose magic has failed. But it might also be a guardian that is simply waiting for a threat before it activates and drives that threat away.

Constructs such as [animated armor](3-Mechanics/CLI/bestiary/construct/animated-armor.md), [helmed horrors](3-Mechanics/CLI/bestiary/construct/helmed-horror.md), [shield guardians](3-Mechanics/CLI/bestiary/construct/shield-guardian.md), and [stone golems](3-Mechanics/CLI/bestiary/construct/stone-golem.md) can represent these guardians.

```statblock
"name": "Stone Guardian (Animated Armor) (PSX)"
"size": "Medium"
"type": "construct"
"alignment": "Unaligned"
"ac": !!int "18"
"ac_class": "natural armor"
"hp": !!int "33"
"hit_dice": "6d8 + 6"
"modifier": !!int "0"
"stats":
  - !!int "14"
  - !!int "11"
  - !!int "13"
  - !!int "1"
  - !!int "3"
  - !!int "1"
"speed": "25 ft."
"damage_immunities": "poison, psychic"
"condition_immunities": "[blinded](3-Mechanics/CLI/rules/conditions.md#Blinded), [charmed](3-Mechanics/CLI/rules/conditions.md#Charmed),\
  \ [deafened](3-Mechanics/CLI/rules/conditions.md#Deafened), [exhaustion](3-Mechanics/CLI/rules/conditions.md#Exhaustion),\
  \ [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened), [paralyzed](3-Mechanics/CLI/rules/conditions.md#Paralyzed),\
  \ [petrified](3-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)"
"senses": "[blindsight](3-Mechanics/CLI/rules/senses.md#Blindsight) 60 ft. (blind\
  \ beyond this radius), passive Perception 6"
"languages": ""
"cr": "1"
"traits":
  - "desc": "The stone guardian is [incapacitated](3-Mechanics/CLI/rules/conditions.md#Incapacitated)\
      \ while in the area of an [antimagic field](3-Mechanics/CLI/spells/antimagic-field.md).\
      \ If targeted by [dispel magic](3-Mechanics/CLI/spells/dispel-magic.md), the\
      \ stone guardian must succeed on a Constitution saving throw against the caster's\
      \ spell save DC or fall [unconscious](3-Mechanics/CLI/rules/conditions.md#Unconscious)\
      \ for 1 minute."
    "name": "Antimagic Susceptibility"
  - "desc": "While the stone guardian remains motionless, it is indistinguishable\
      \ from a normal suit of stone guardian."
    "name": "False Appearance"
"actions":
  - "desc": "The stone guardian makes two melee attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one target. *Hit:* 5\
      \ (1d6 + 2) bludgeoning damage."
    "name": "Slam"
"source":
  - "PSX"
"image": "3-Mechanics/CLI/bestiary/construct/token/stone-guardian-animated-armor-psx.webp"
```
^statblock