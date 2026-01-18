---
obsidianUIMode: preview
cssclasses:
  - json5e-monster
tags:
  - Quelle/5e/mcv4ec
  - Monster/HG/7
  - Monster/Größe/Riesig
  - Monster/Typ/Fee
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Goose Mother
---
# [Goose Mother](3-Mechanics\CLI\bestiary\fey/goose-mother-mcv4ec.md)
*Source: Monstrous Compendium Volume 4: Eldraine Creatures*  

Astonishingly aggressive geese populate the marshes of Eldraine. Legends tell that these geese descend from a monstrous many-headed bird that dwells deep within the wilds. Though the knights of Eldraine consider its existence a myth, the folk of the wilds know that the Goose Mother is real.

Centuries ago, an enterprising witch created a frothy stew composed of hydra's blood and goose feathers. It is from this noxious slurry that the Goose Mother was born. Within days, the Goose Mother grew to prodigious size, and the witch grew fearful. One night, while the Goose Mother slept, the witch took to its neck with a cleaver, but to her horror, two more heads sprouted in place of the first. Enraged, the Goose Mother devoured the witch and rampaged deep into the wilds where it lives to this day.

The Goose Mother lays one golden egg every hour, precisely on the hour. Sometimes these eggs hatch into clutches of young geese that grow up to terrorize the marshes of Eldraine. Other times, the eggs contain trinkets or valuables. The fae folk of Eldraine's wilds have developed a symbiotic relationship with the Goose Mother, often bringing it fresh meat in exchange for the treasures inside its golden eggs.

If you have "Bigby Presents: Glory of the Giants", you can use the Goose Egg Trinket table to determine the contents of one of the Goose Mother's eggs that isn't destined to hatch into a goose or a giant goose (also described in that book).

```statblock
"name": "Goose Mother (MCV4EC)"
"size": "Huge"
"type": "fey"
"alignment": "Unaligned"
"ac": !!int "12"
"hp": !!int "114"
"hit_dice": "12d12 + 36"
"modifier": !!int "2"
"stats":
  - !!int "17"
  - !!int "15"
  - !!int "17"
  - !!int "12"
  - !!int "18"
  - !!int "15"
"speed": "40 ft., fly 40 ft."
"saves":
  - "strength": !!int "6"
  - "intelligence": !!int "4"
"skillsaves":
  - "name": "Insight"
    "desc": "+7"
  - "name": "Investigation"
    "desc": "+4"
  - "name": "Perception"
    "desc": "+10"
"condition_immunities": "blinded, charmed, deafened, frightened, stunned, unconscious"
"senses": "darkvision 60 ft., passive Perception 20"
"languages": ""
"cr": "7"
"traits":
  - "desc": "If the Goose Mother fails a saving throw, it can choose to succeed instead."
    "name": "Legendary Resistance (3/Day)"
  - "desc": "The Goose Mother has five heads. Whenever the Goose Mother takes 25 or\
      \ more damage in a single turn, one of its heads dies. If all its heads die,\
      \ the Goose Mother dies.\n\nAt the end of its turn, the Goose Mother grows two\
      \ heads for each of its heads that died since its last turn, unless it has taken\
      \ poison damage since its last turn. The Goose Mother regains 10 hit points\
      \ for each head when it regrows."
    "name": "Multiple Heads"
  - "desc": "For each head the Goose Mother has beyond one, it gets an extra reaction\
      \ that can be used only for opportunity attacks."
    "name": "Reactive Heads"
  - "desc": "While the Goose Mother sleeps, at least one of its heads is awake."
    "name": "Wakeful"
"actions":
  - "desc": "The Goose Mother makes as many Beak attacks as it has heads and one Wing\
      \ attack."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +6 to hit, reach 10 ft., one target. *Hit:* 6\
      \ (1d6 + 3) bludgeoning damage."
    "name": "Beak"
  - "desc": "*Melee Weapon Attack:* +6 to hit, reach 10 ft., one target. *Hit:* 9\
      \ (1d12 + 3) bludgeoning damage. If the target is a Large or smaller creature,\
      \ it must succeed on a DC 15 Strength saving throw or have the prone condition."
    "name": "Wing"
  - "desc": "The Goose Mother's heads honk a discordant lullaby. Each creature of\
      \ the Goose Mother's choice within 10 feet of it must make a DC 15 Constitution\
      \ saving throw. On a failed save, a creature takes 7 (2d6) thunder damage and\
      \ falls into a magical slumber. On a successful save, the target takes half\
      \ as much damage only. The honks can be heard up to 300 feet away.\n\nA creature\
      \ under magical slumber has the unconscious condition for 8 hours. This effect\
      \ ends early for a creature if it takes damage or another creature uses an action\
      \ to shake it awake."
    "name": "Lullaby of Honks (Recharge 5-6)"
"source":
  - "MCV4EC"
"image": "/3-Mechanics/CLI/bestiary/fey/token/goose-mother-mcv4ec.webp"
```
^statblock