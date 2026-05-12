---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/psz
- ttrpg-cli/monster/cr/13
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/monstrosity
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Kraken"
---
# [Kraken](3-Mechanics/CLI/bestiary/monstrosity/kraken-psz.md)
*Source: Plane Shift: Zendikar p. 25*  

Lurking in the deepest reaches of Zendikar's seas, krakens are mysterious monsters of unpredictable wrath and terrible destruction. Though they take the form of rampaging brutes when they appear on the surface, the truth of their existence is more complex. Krakens embody force of will and the drive for self-determination shared by all thinking beings. When their will is turned to destruction, they are capable of wreaking terrible havoc upon ships at sea or coastal settlements. But they live most of their adult lives in utter isolation in the deeps, focused on their own probing of the seas' mysteries.

A kraken has a roughly humanoid shape, with two strong arms and a broad chest. Its head is encased in a rough shell that sprouts two large horns, and one of its hands is a bony claw. It has dozens of tentacles—a writhing mass below its toothy mouth, another mass at the end of one arm, and several long tentacles in place of legs. On its back is a huge conch-like shell.

Though the Monster Manual has its own version of the kraken, Zendikar's krakens are actually more similar to storm giants.

```statblock
"name": "Kraken (PSZ)"
"size": "Huge"
"type": "monstrosity"
"alignment": "Chaotic Evil"
"ac": !!int "16"
"ac_class": "natural armor"
"hp": !!int "230"
"hit_dice": "20d12 + 100"
"modifier": !!int "2"
"stats":
  - !!int "29"
  - !!int "14"
  - !!int "20"
  - !!int "16"
  - !!int "18"
  - !!int "18"
"speed": "30 ft., swim 50 ft."
"skillsaves":
  - "name": "[Athletics](3-Mechanics/CLI/rules/skills.md#Athletics)"
    "desc": "+14"
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+9"
"damage_resistances": "cold"
"damage_immunities": "lightning, thunder"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 120 ft., passive\
  \ Perception 19"
"languages": "Common"
"cr": "13"
"traits":
  - "desc": "The kraken's innate spellcasting ability is Charisma (spell save DC 17).\
      \ The kraken can innately cast the following spells, requiring no components:\n\
      \n**3/day each:** [control weather](3-Mechanics/CLI/spells/control-weather.md),\
      \ [water breathing](3-Mechanics/CLI/spells/water-breathing.md)"
    "name": "Innate Spellcasting"
  - "desc": "The kraken can breathe air and water."
    "name": "Amphibious"
"actions":
  - "desc": "The kraken makes two attacks: one with its claw and one with its tentacles."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +14 to hit, reach 10 ft., one target. *Hit:*\
      \ 30 (6d6 + 9) slashing damage."
    "name": "Claw"
  - "desc": "*Melee Weapon Attack:* +14 to hit, reach 20 ft., one target. *Hit:*\
      \ 30 (6d6 + 9) bludgeoning damage, and the target is [grappled](3-Mechanics/CLI/rules/conditions.md#Grappled)\
      \ (escape DC 17). Until this grapple ends, the target is [restrained](3-Mechanics/CLI/rules/conditions.md#Restrained)."
    "name": "Tentacles"
  - "desc": "The kraken hurls a magical lightning bolt at a point it can see within\
      \ 500 feet of it. Each creature within 10 feet of that point must make a DC\
      \ 17 Dexterity saving throw, taking 54 (12d8) lightning damage on a failed\
      \ save, or half as much damage on a successful one."
    "name": "Lightning Strike (Recharge 5-6)"
"source":
  - "PSZ"
"image": "3-Mechanics/CLI/bestiary/monstrosity/token/kraken-psz.webp"
```
^statblock