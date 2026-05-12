---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/psk
- ttrpg-cli/monster/cr/8
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/monstrosity
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Hydra"
---
# [Hydra](3-Mechanics/CLI/bestiary/monstrosity/hydra-psk.md)
*Source: Plane Shift: Kaladesh p. 30*  

Hydras are giant lizards resembling iguanas, with multiple heads set atop long, snakelike necks. Aether traces whorling patterns through their scales, shapes the crests running down their necks and tails, and glows blue within the skin under their chins. Most hydras have five or six heads, but small hydras with as few as three heads—as well as enormous specimens with eight or more—have been seen in the deep forests far from Ghirapur.

Hydras are fierce predators, favoring prey that has absorbed large quantities of aether from the environment. This taste for aether also leads them to devour aether-powered machines whenever they encounter such devices, from thopters to automatons. In the remote wilderness near Peema where hydras are plentiful, such altercations are rarely an issue. But in the rare event of a hydra coming too close to civilization—or even wandering into one of Ghirapur's greenbelts—they can cause widespread destruction in their hunt for aether.

Use the [hydra](3-Mechanics/CLI/bestiary/monstrosity/hydra.md) statistics in the "Monster Manual".

```statblock
"name": "Hydra (PSK)"
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
      \ 10 (1d10 + 5) piercing damage."
    "name": "Bite"
"source":
  - "PSK"
"image": "3-Mechanics/CLI/bestiary/monstrosity/token/hydra-psk.webp"
```
^statblock