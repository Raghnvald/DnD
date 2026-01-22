---
cssclasses:
  - json5e-monster
tags:
  - Quelle/5e/mm
  - Monster/HG/0
  - Monster/Habitat/Arktis
  - Monster/Habitat/Küste
  - Monster/Habitat/Wüste
  - Monster/Habitat/Wald
  - Monster/Habitat/Grasland
  - Monster/Habitat/Hügel
  - Monster/Habitat/Stadt
  - Monster/Größe/Mittelgroß
  - Monster/Typ/Humanoid/jede-rasse
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Commoner
---
# [Commoner](3-Mechanics\CLI\bestiary\humanoid/commoner.md)
*Source: Monster Manual p. 345. Available in the <span title='Systems Reference Document (5.1)'>SRD</span> and the Basic Rules (2014)*  

Commoners include peasants, serfs, slaves, servants, pilgrims, merchants, artisans, and hermits.

```statblock
"name": "Commoner"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Any alignment"
"ac": !!int "10"
"hp": !!int "4"
"hit_dice": "1d8"
"modifier": !!int "0"
"stats":
  - !!int "10"
  - !!int "10"
  - !!int "10"
  - !!int "10"
  - !!int "10"
  - !!int "10"
"speed": "30 ft."
"senses": "passive Perception 10"
"languages": "any one language (usually Common)"
"cr": "0"
"actions":
  - "desc": "*Melee Weapon Attack:* +2 to hit, reach 5 ft., one target. *Hit:* 2 (1d4)\
      \ bludgeoning damage."
    "name": "Club"
"source":
  - "MM"
"image": "/3-Mechanics/CLI/bestiary/humanoid/token/commoner.webp"
```
^statblock

## Environment

arctic, desert, coastal, grassland, hill, urban, forest

```statblock
statblock: true
name: Gemeiner
image: [[Gemeiner.png]]
source: Grundregelwerk
size: Mittel
type: Humanoide (jedes Volk)
alignment: jede Gesinnung
ac: 10
hp: 4
hit_dice: 1d8
speed: 9 Meter.
stats: [10, 10, 10, 10, 10, 10]
damage_vulnerabilities: ""
damage_resistances: ""
damage_immunities: ""
condition_immunities: ""
senses: passive Wahrnehmung 10
languages: Eine beliebige Sprache (normalerweise Gemeinsprache)
cr: 0
environment: Arktis, Grasland, Hügel, Küste, Stadt, Wälder, Wüste
bestiary: true
actions:
  - name: Knüppel
    desc: "_Nahkampf-Waffenangriff:_ +2 auf Treffer, Reichweite 1,5 m, ein Ziel. _Treffer:_ 2 (`1W4`) Wuchtschaden."
    attack_bonus: 2
    damage_dice: 1d4
    damage_bonus: 0
```

**Gemeine** sind Bauern, Leibeigene, Diener, Sklaven, Pilger, Händler, Künstler und Einsiedler.
