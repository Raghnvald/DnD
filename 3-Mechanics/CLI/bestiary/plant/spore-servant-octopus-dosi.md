---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- new/compendium/src/5e/dosi
- new/monster/cr/1
- new/monster/size/large
- new/monster/type/plant
statblock: inline
statblock-link: "#^statblock"
aliases:
- Spore Servant Octopus
---
# [Spore Servant Octopus](3-Mechanics\CLI\bestiary\plant/spore-servant-octopus-dosi.md)
*Source: Dragons of Stormwreck Isle p. 46*  

Spore servants are dead creatures reanimated by the magical spores of a myconid leader. The final act of the myconid leader in Seagrow Caves before lapsing into its current comatose state was creating a spore servant from a dead giant octopus to protect the caves while the leader could not. Unlike a living octopus, this guardian has only basic control over its tentacles. Rather than coiling around intruders to immobilize them, the spore servant simply bludgeons them.

```statblock
"name": "Spore Servant Octopus (DoSI)"
"size": "Large"
"type": "plant"
"alignment": "Unaligned"
"ac": !!int "11"
"hp": !!int "52"
"hit_dice": "8d10 + 8"
"modifier": !!int "1"
"stats":
  - !!int "17"
  - !!int "13"
  - !!int "13"
  - !!int "2"
  - !!int "6"
  - !!int "1"
"speed": "5 ft., swim 50 ft."
"condition_immunities": "blinded, charmed, frightened, paralyzed"
"senses": "blindsight 30 ft. (blind beyond this radius), passive Perception 8"
"languages": ""
"cr": "1"
"traits":
  - "desc": "While out of water, the octopus can hold its breath for 1 hour."
    "name": "Hold Breath"
  - "desc": "The octopus can breathe only underwater."
    "name": "Water Breathing"
"actions":
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 15 ft., one target *Hit:* 7 (1d8\
      \ + 3) bludgeoning damage."
    "name": "Tentacles"
"source":
  - "DoSI"
"image": "/3-Mechanics/CLI/bestiary/plant/token/spore-servant-octopus-dosi.webp"
```
^statblock