---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/psa
- ttrpg-cli/monster/cr/6
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/beast
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Cerodon"
---
# [Cerodon](3-Mechanics/CLI/bestiary/beast/cerodon-psa.md)
*Source: Plane Shift: Amonkhet p. 37*  

Cerodons are sometimes mistaken for herbivores because of their resemblance to bulls, but they are never mistaken for harmless. They stand over thirty feet tall at the shoulder, and their heads are crowned with enormous horns that jut forward from the nose, then extend backward almost the entire length of their bodies. The horn structure resembles a sandstone cliff, and a cerodon can use it to ruin buildings or monuments with a minimum of effort. Cerodons are extremely aggressive, and often mistake the shimmering Hekma for an intruder into their territory. Use the statistics of a [mammoth](3-Mechanics/CLI/bestiary/beast/mammoth.md) for these creatures, with the following additional trait:

## Siege Monster

The cerodon deals double damage to objects and structures.

## The Desert Lands

The desolate wilderness beyond the protection of the Hekma is largely uncharted. Immediately beyond the protective veil is a chaotic dune sea called Shefet, the Scouring Sands. The desert wears away at the edges of the fertile lands surrounding Naktamun, serving as a constant reminder that only the bounty and protection of the God-Pharaoh stand between the people of the city-state and a grisly death in the sands beyond. Beyond Shefet are parched, cracked expanses called Ramunap, the Broken Lands. The ruins of ancient civilizations are said to lie in the Broken Lands, though no one has ever explored such ruins and returned to Naktamun to tell of them.

```statblock
"name": "Cerodon (PSA)"
"size": "Huge"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "13"
"ac_class": "natural armor"
"hp": !!int "126"
"hit_dice": "11d12 + 55"
"modifier": !!int "-1"
"stats":
  - !!int "24"
  - !!int "9"
  - !!int "21"
  - !!int "3"
  - !!int "11"
  - !!int "6"
"speed": "40 ft."
"senses": "passive Perception 10"
"languages": ""
"cr": "6"
"traits":
  - "desc": "If the cerodon moves at least 20 feet straight toward a creature and\
      \ then hits it with a gore attack on the same turn, that target must succeed\
      \ on a DC 18 Strength saving throw or be knocked [prone](3-Mechanics/CLI/rules/conditions.md#Prone).\
      \ If the target is [prone](3-Mechanics/CLI/rules/conditions.md#Prone), the cerodon\
      \ can make one stomp attack against it as a bonus action."
    "name": "Trampling Charge"
  - "desc": "The cerodon deals double damage to objects and structures."
    "name": "Siege Monster"
"actions":
  - "desc": "*Melee Weapon Attack:* +10 to hit, reach 10 ft., one target. *Hit:*\
      \ 25 (4d8 + 7) piercing damage."
    "name": "Gore"
  - "desc": "*Melee Weapon Attack:* +10 to hit, reach 5 ft., one [prone](3-Mechanics/CLI/rules/conditions.md#Prone)\
      \ creature. *Hit:* 29 (4d10 + 7) bludgeoning damage."
    "name": "Stomp"
"source":
  - "PSA"
"image": "3-Mechanics/CLI/bestiary/beast/token/cerodon-psa.webp"
```
^statblock