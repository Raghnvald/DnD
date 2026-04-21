---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Snapping Hydra
tags:
  - Monster/Größe/Riesig
  - Monster/HG/11
  - Monster/Typ/Monstrosität
  - Quelle/5e/mcv4ec
aliases:
  - Snapping Hydra
---
# [Snapping Hydra](3-Mechanics\CLI\bestiary\monstrosity/snapping-hydra-mcv4ec.md)
*Source: Monstrous Compendium Volume 4: Eldraine Creatures*  

A rare variety of hydra native to the wilds of Eldraine, snapping hydras resemble giant, many-headed turtles. Snapping hydras dwell at the bottom of the wild's largest lakes, or along shorelines where the wilds meet the ocean. These monstrous creatures are aptly named; their bites are known to snap giants' arms cleanly in half.

Snapping hydras have naturally long life spans and strong instincts of self-preservation. When a snapping hydra feels a battle's odds tipping out of its favor, the hydra lets out a raspy screech and retracts into its shell. In the wilds of Eldraine, it's never long before a hungry or curious creature arrives to investigate, leaping into battle with the hydra's foes while the hydra makes an opportune exit.

```statblock
"name": "Snapping Hydra (MCV4EC)"
"size": "Huge"
"type": "monstrosity"
"alignment": "Unaligned"
"ac": !!int "20"
"ac_class": "natural armor"
"hp": !!int "149"
"hit_dice": "13d12 + 65"
"modifier": !!int "-3"
"stats":
  - !!int "21"
  - !!int "5"
  - !!int "21"
  - !!int "2"
  - !!int "16"
  - !!int "7"
"speed": "30 ft., swim 40 ft."
"skillsaves":
  - "name": "Perception"
    "desc": "+11"
"condition_immunities": "blinded, charmed, deafened, frightened, stunned, unconscious"
"senses": "darkvision 60 ft., passive Perception 21"
"languages": ""
"cr": "11"
"traits":
  - "desc": "The hydra can breathe air and water."
    "name": "Amphibious"
  - "desc": "The hydra has five heads. Whenever the hydra takes 30 or more damage\
      \ in a single turn, one of its heads dies. If all its heads die, the hydra dies.\n\
      \nAt the end of its turn, the hydra grows two heads for each of its heads that\
      \ died since its last turn, unless it has taken cold damage since its last turn.\
      \ The hydra regains 10 hit points for each head regrown this way."
    "name": "Multiple Heads"
  - "desc": "For each head the hydra has beyond one, it gets an extra reaction that\
      \ can be used only for opportunity attacks."
    "name": "Reactive Heads"
  - "desc": "While the hydra sleeps, at least one of its heads is awake."
    "name": "Wakeful"
"actions":
  - "desc": "The hydra makes as many Bite attacks as it has heads."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +9 to hit, reach 10 ft., one target. *Hit:* 14\
      \ (2d8 + 5) piercing damage."
    "name": "Bite"
  - "desc": "The hydra withdraws its limbs and heads into its shell. Until it emerges\
      \ as a bonus action, it gains a +4 bonus to AC and has advantage on Strength\
      \ and Constitution saving throws. While in its shell, the hydra has the prone\
      \ condition, its speed is 0 and can't increase, its heads can't die, it has\
      \ disadvantage on Dexterity saving throws, and it can't take any other actions\
      \ or reactions."
    "name": "Shell Defense"
"source":
  - "MCV4EC"
"image": "/3-Mechanics/CLI/bestiary/monstrosity/token/snapping-hydra-mcv4ec.webp"
```
^statblock