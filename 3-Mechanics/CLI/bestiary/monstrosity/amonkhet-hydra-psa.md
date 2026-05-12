---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/psa
- ttrpg-cli/monster/cr/8
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/monstrosity
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Amonkhet Hydra"
---
# [Amonkhet Hydra](3-Mechanics/CLI/bestiary/monstrosity/amonkhet-hydra-psa.md)
*Source: Plane Shift: Amonkhet p. 35*  

The hydras of Amonkhet have heads like those of a cobra. A successful bite attack from one of these heads deals 7 (`1d4 + 5`) piercing damage, and the target must make a DC 16 Constitution saving throw, taking 7 (`2d6`) poison damage on a failed save, or half as much damage on a successful one.

## The Desert Lands

The desolate wilderness beyond the protection of the Hekma is largely uncharted. Immediately beyond the protective veil is a chaotic dune sea called Shefet, the Scouring Sands. The desert wears away at the edges of the fertile lands surrounding Naktamun, serving as a constant reminder that only the bounty and protection of the God-Pharaoh stand between the people of the city-state and a grisly death in the sands beyond. Beyond Shefet are parched, cracked expanses called Ramunap, the Broken Lands. The ruins of ancient civilizations are said to lie in the Broken Lands, though no one has ever explored such ruins and returned to Naktamun to tell of them.

```statblock
"name": "Amonkhet Hydra (PSA)"
"size": "Huge"
"type": "monstrosity"
"alignment": "Unaligned"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "172"
"hit_dice": "15d12 + 75"
"modifier": !!int "1"
"stats":
  - !!int "20"
  - !!int "12"
  - !!int "20"
  - !!int "2"
  - !!int "10"
  - !!int "7"
"speed": "30 ft., swim 30 ft."
"skillsaves":
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+6"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., passive\
  \ Perception 16"
"languages": ""
"cr": "8"
"traits":
  - "desc": "The hydra can hold its breath for 1 hour."
    "name": "Hold Breath"
  - "desc": "The hydra has five heads. While it has more than one head, the hydra\
      \ has advantage on saving throws against being [blinded](3-Mechanics/CLI/rules/conditions.md#Blinded),\
      \ [charmed](3-Mechanics/CLI/rules/conditions.md#Charmed), [deafened](3-Mechanics/CLI/rules/conditions.md#Deafened),\
      \ [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened), [stunned](3-Mechanics/CLI/rules/conditions.md#Stunned),\
      \ and knocked [unconscious](3-Mechanics/CLI/rules/conditions.md#Unconscious).\n\
      \nWhenever the hydra takes 25 or more damage in a single turn, one of its heads\
      \ dies. If all its heads die, the hydra dies.\n\nAt the end of its turn, it\
      \ grows two heads for each of its heads that died since its last turn, unless\
      \ it has taken fire damage since its last turn. The hydra regains 10 hit points\
      \ for each head regrown in this way."
    "name": "Multiple Heads"
  - "desc": "For each head the hydra has beyond one, it gets an extra reaction that\
      \ can be used only for opportunity attacks."
    "name": "Reactive Heads"
  - "desc": "While the hydra sleeps, at least one of its heads is awake."
    "name": "Wakeful"
"actions":
  - "desc": "The hydra makes as many bite attacks as it has heads."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +8 to hit, reach 10 ft., one target. *Hit:*\
      \ 7 (1d4 + 5) piercing damage, and the target must make on a DC 16 Constitution\
      \ saving throw, taking 7 (2d6) poison damage on a failed save, or half as\
      \ much damage on a successful one."
    "name": "Bite"
"source":
  - "PSA"
"image": "3-Mechanics/CLI/bestiary/monstrosity/token/amonkhet-hydra-psa.webp"
```
^statblock