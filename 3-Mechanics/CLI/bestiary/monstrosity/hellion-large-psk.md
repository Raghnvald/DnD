---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/psk
- ttrpg-cli/monster/cr/5
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/monstrosity
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Hellion (Large)"
---
# [Hellion (Large)](3-Mechanics/CLI/bestiary/monstrosity/hellion-large-psk.md)
*Source: Plane Shift: Kaladesh p. 31*  

Hellions appear similar to wurms, though the two creatures are unrelated. A hellion has a long, segmented body like that of a centipede, with innumerable short legs that propel it above or below ground. Its huge, toothy maw is surrounded by anywhere from six to twelve long appendages resembling clawed fingers, which it uses to grasp and pull prey to its mouth. Hellions are found in mountainous areas, where they burst up from the rocky ground to ambush their prey.

The [remorhaz](3-Mechanics/CLI/bestiary/monstrosity/remorhaz.md) statistics in the "Monster Manual" work well for hellions of different sizes.

```statblock
"name": "Hellion (Large) (PSK)"
"size": "Large"
"type": "monstrosity"
"alignment": "Unaligned"
"ac": !!int "14"
"ac_class": "natural armor"
"hp": !!int "93"
"hit_dice": "11d10 + 33"
"modifier": !!int "1"
"stats":
  - !!int "18"
  - !!int "13"
  - !!int "17"
  - !!int "3"
  - !!int "10"
  - !!int "4"
"speed": "30 ft., burrow 30 ft."
"damage_immunities": "cold, fire"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., tremorsense\
  \ 60 ft., passive Perception 10"
"languages": ""
"cr": "5"
"traits":
  - "desc": "A creature that touches the hellion or hits it with a melee attack while\
      \ within 5 feet of it takes 7 (2d6) fire damage."
    "name": "Heated Body"
"actions":
  - "desc": "*Melee Weapon Attack:* +6 to hit, reach 5 ft., one target. *Hit:* 20\
      \ (3d10 + 4) piercing damage plus 7 (2d6) fire damage."
    "name": "Bite"
"source":
  - "PSK"
"image": "3-Mechanics/CLI/bestiary/monstrosity/token/hellion-large-psk.webp"
```
^statblock