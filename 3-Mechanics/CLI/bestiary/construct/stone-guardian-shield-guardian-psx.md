---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/psx
- ttrpg-cli/monster/cr/7
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/construct
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Stone Guardian (Shield Guardian)"
---
# [Stone Guardian (Shield Guardian)](3-Mechanics/CLI/bestiary/construct/stone-guardian-shield-guardian-psx.md)
*Source: Plane Shift: Ixalan p. 40*  

Through the years in which the Sun Empire was ruled from Orazca, its priests crafted huge stone guardians to protect the empire's cities and temples. The incredible magic of the Immortal Sun gave a semblance of life to these artificial creatures, endowing them with the ability to move their stone bodies, a keen awareness of their surroundings, and a limited ability to think and reason in order to help them carry out their orders. These stone guardians were tasked with standing watch—constantly alert, vigilant to any danger, never sleeping, and unswerving in their duty.

Most stone guardians are inactive now. In ancient ruins lying far from the old capital, the magic that gave them life has faded over the centuries. Even within the golden city, many of them have become inert, and those who seek to explore Orazca or other ancient ruins must be on constant guard. Any carved figure or statue might well be a stone guardian whose magic has failed. But it might also be a guardian that is simply waiting for a threat before it activates and drives that threat away.

Constructs such as [animated armor](3-Mechanics/CLI/bestiary/construct/animated-armor.md), [helmed horrors](3-Mechanics/CLI/bestiary/construct/helmed-horror.md), [shield guardians](3-Mechanics/CLI/bestiary/construct/shield-guardian.md), and [stone golems](3-Mechanics/CLI/bestiary/construct/stone-golem.md) can represent these guardians.

```statblock
"name": "Stone Guardian (Shield Guardian) (PSX)"
"size": "Large"
"type": "construct"
"alignment": "Unaligned"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "142"
"hit_dice": "15d10 + 60"
"modifier": !!int "-1"
"stats":
  - !!int "18"
  - !!int "8"
  - !!int "18"
  - !!int "7"
  - !!int "10"
  - !!int "3"
"speed": "30 ft."
"damage_immunities": "poison"
"condition_immunities": "[charmed](3-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](3-Mechanics/CLI/rules/conditions.md#Exhaustion),\
  \ [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened), [paralyzed](3-Mechanics/CLI/rules/conditions.md#Paralyzed),\
  \ [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)"
"senses": "[blindsight](3-Mechanics/CLI/rules/senses.md#Blindsight) 10 ft., [darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision)\
  \ 60 ft., passive Perception 10"
"languages": "understands commands given in any language but can't speak"
"cr": "7"
"traits":
  - "desc": "The stone guardian is magically bound to an amulet. As long as the guardian\
      \ and its amulet are on the same plane of existence, the amulet's wearer can\
      \ telepathically call the guardian to travel to it, and the guardian knows the\
      \ distance and direction to the amulet. If the guardian is within 60 feet of\
      \ the amulet's wearer, half of any damage the wearer takes (rounded up) is transferred\
      \ to the guardian."
    "name": "Bound"
  - "desc": "The stone guardian regains 10 hit points at the start of its turn if\
      \ it has at least 1 hit point."
    "name": "Regeneration"
  - "desc": "A spellcaster who wears the stone guardian's amulet can cause the guardian\
      \ to store one spell of 4th level or lower. To do so, the wearer must cast the\
      \ spell on the guardian. The spell has no effect but is stored within the guardian.\
      \ When commanded to do so by the wearer or when a situation arises that was\
      \ predefined by the spellcaster, the guardian casts the stored spell with any\
      \ parameters set by the original caster, requiring no components. When the spell\
      \ is cast or a new spell is stored, any previously stored spell is lost."
    "name": "Spell Storing"
"actions":
  - "desc": "The guardian makes two fist attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +7 to hit, reach 5 ft., one target. *Hit:* 11\
      \ (2d6 + 4) bludgeoning damage."
    "name": "Fist"
"reactions":
  - "desc": "When a creature makes an attack against the wearer of the guardian's\
      \ amulet, the guardian grants a +2 bonus to the wearer's AC if the guardian\
      \ is within 5 feet of the wearer."
    "name": "Shield"
"source":
  - "PSX"
"image": "3-Mechanics/CLI/bestiary/construct/token/stone-guardian-shield-guardian-psx.webp"
```
^statblock