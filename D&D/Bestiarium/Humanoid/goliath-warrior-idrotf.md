---
obsidianUIMode: preview
cssclasses:
  - json5e-monster
tags:
  - Quelle/5e/idrotf
  - Monster/HG/3
  - Monster/Größe/Mittelgroß
  - Monster/Typ/humanoid/goliath
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Goliath Warrior
---
# [Goliath Warrior](3-Mechanics\CLI\bestiary\humanoid/goliath-warrior-idrotf.md)
*Source: Icewind Dale: Rime of the Frostmaiden p. 292*  

Goliaths inhabit the Spine of the World, where their mettle is tested against orcs, ogres, frost giants, remorhazes, ice trolls, young white dragons, the treacherous mountain terrain, and the cruel indifference of nature.

```statblock
"name": "Goliath Warrior (IDRotF)"
"size": "Medium"
"type": "humanoid"
"subtype": "goliath"
"alignment": "Any alignment"
"ac": !!int "12"
"ac_class": "hide armor"
"hp": !!int "67"
"hit_dice": "9d8 + 27"
"modifier": !!int "0"
"stats":
  - !!int "18"
  - !!int "11"
  - !!int "16"
  - !!int "10"
  - !!int "15"
  - !!int "10"
"speed": "30 ft."
"skillsaves":
  - "name": "Athletics"
    "desc": "+6"
  - "name": "Perception"
    "desc": "+4"
  - "name": "Survival"
    "desc": "+4"
"damage_resistances": "cold"
"senses": "passive Perception 14"
"languages": "Common, Giant"
"cr": "3"
"traits":
  - "desc": "The goliath is acclimated to high altitude, including elevations above\
      \ 20,000 feet."
    "name": "Mountain Born"
  - "desc": "The goliath counts as one size larger when determining its carrying capacity\
      \ and the weight it can push, drag, or lift."
    "name": "Powerful Build"
"actions":
  - "desc": "The goliath makes two attacks with its greataxe or hurls two javelins."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +6 to hit, reach 5 ft., one target. *Hit:* 10\
      \ (1d12 + 4) slashing damage."
    "name": "Greataxe"
  - "desc": "*Melee  or Ranged Weapon Attack:* +6 to hit, reach 5 ft. or range 30/120\
      \ ft., one target. *Hit:* 7 (1d6 + 4) piercing damage."
    "name": "Javelin"
"reactions":
  - "desc": "When the goliath takes damage, it reduces the damage taken by 9 (1d12\
      \ + 3)."
    "name": "Stone's Endurance (Recharges after a Short or Long Rest)"
"source":
  - "IDRotF"
"image": "/3-Mechanics/CLI/bestiary/humanoid/token/goliath-warrior-idrotf.webp"
```
^statblock