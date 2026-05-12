---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/psk
- ttrpg-cli/monster/cr/1-4
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/beast
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Drake (Small)"
---
# [Drake (Small)](3-Mechanics/CLI/bestiary/beast/drake-small-psk.md)
*Source: Plane Shift: Kaladesh p. 29*  

Drakes are skittish, opportunistic predators that hunt the skies of Kaladesh in units called rushes, made up of as many as a dozen drakes. Though they prey mostly on birds, they can also be seen clinging to the hides of leviathans and whales, picking off winged leeches and other parasites and scavengers that attach themselves to the huge sky beasts. Occasionally, a rush of drakes will descend on a herd of mountain goats or other game found at high elevations.

Drakes have reptilian bodies and large, leathery wings. They use the sharp claws on their two legs to cling to rocky crags, whales, or leviathans, as well as to grasp and tear at larger prey. Drakes are highly territorial, and have been known to attack airships from time to time. A drake is intelligent enough to recognize specific airships that have killed other members of its rush, and drake harassment often forces such ships to find new routes to avoid a rush's territory.

A [pteranodon](3-Mechanics/CLI/bestiary/beast/pteranodon.md) can represent a smaller drake, while a larger one is more like a [giant eagle](3-Mechanics/CLI/bestiary/beast/giant-eagle.md).

```statblock
"name": "Drake (Small) (PSK)"
"size": "Medium"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "13"
"ac_class": "natural armor"
"hp": !!int "13"
"hit_dice": "3d8"
"modifier": !!int "2"
"stats":
  - !!int "12"
  - !!int "15"
  - !!int "10"
  - !!int "2"
  - !!int "9"
  - !!int "5"
"speed": "10 ft., fly 60 ft."
"skillsaves":
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+1"
"senses": "passive Perception 11"
"languages": ""
"cr": "1/4"
"traits":
  - "desc": "The drake doesn't provoke opportunity attacks when it flies out of an\
      \ enemy's reach."
    "name": "Flyby"
"actions":
  - "desc": "*Melee Weapon Attack:* +3 to hit, reach 5 ft., one target. *Hit:* 6\
      \ (2d4 + 1) piercing damage."
    "name": "Bite"
"source":
  - "PSK"
"image": "3-Mechanics/CLI/bestiary/beast/token/drake-small-psk.webp"
```
^statblock