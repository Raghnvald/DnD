---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/psx
- ttrpg-cli/monster/cr/8
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/beast
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Tyrant"
---
# [Tyrant](3-Mechanics/CLI/bestiary/beast/tyrant-psx.md)
*Source: Plane Shift: Ixalan p. 31*  

## Dinosaur Tyrants

Ixalan's largest predators comprise a family of dinosaurs with large heads, blade-like teeth, and short, almost vestigial front legs. These terrifying creatures bear names like monstrosaurs, dreadmaws, swordtooths, regisaurs, and tyrants, and their roars inspire terror in those who hear them. Most of these dinosaurs are solitary hunters, but regisaurs in particular are known for hunting in small packs. Use the [tyrannosaurus rex](3-Mechanics/CLI/bestiary/beast/tyrannosaurus-rex.md) statistics in the "Monster Manual" for all these giant predators.

## Dinosaurs

Dinosaurs are the dominant form of animal life in Ixalan—the absolute rulers of the coastal lands held by the Sun Empire, and a force to be reckoned with in the interior jungles. A number of dinosaurs appear in the "Monster Manual", with even more to be found in "Volo's Guide to Monsters", making that a particularly worthwhile resource for an Ixalan campaign. (Many of the dinosaurs in "Volo's Guide" also appear in Tomb of Annihilation.)

```statblock
"name": "Tyrant (PSX)"
"size": "Huge"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "13"
"ac_class": "natural armor"
"hp": !!int "136"
"hit_dice": "13d12 + 52"
"modifier": !!int "0"
"stats":
  - !!int "25"
  - !!int "10"
  - !!int "19"
  - !!int "2"
  - !!int "12"
  - !!int "9"
"speed": "50 ft."
"skillsaves":
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+4"
"senses": "passive Perception 14"
"languages": ""
"cr": "8"
"actions":
  - "desc": "The tyrant makes two attacks: one with its bite and one with its tail.\
      \ It can't make both attacks against the same target."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +10 to hit, reach 10 ft., one target. *Hit:*\
      \ 33 (4d12 + 7) piercing damage. If the target is a Medium or smaller creature,\
      \ it is [grappled](3-Mechanics/CLI/rules/conditions.md#Grappled) (escape DC\
      \ 17). Until this grapple ends, the target is [restrained](3-Mechanics/CLI/rules/conditions.md#Restrained),\
      \ and the tyrant can't bite another target."
    "name": "Bite"
  - "desc": "*Melee Weapon Attack:* +10 to hit, reach 10 ft., one target. *Hit:*\
      \ 20 (3d8 + 7) bludgeoning damage."
    "name": "Tail"
"source":
  - "PSX"
"image": "3-Mechanics/CLI/bestiary/beast/token/tyrant-psx.webp"
```
^statblock