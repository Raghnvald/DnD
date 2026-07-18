---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Wolf
Status: WIP
linter-yaml-title-alias: Wolf
tags:
  - Monster/Größe/Mittelgroß
  - Monster/Habitat/Grasland
  - Monster/Habitat/Hügel
  - Monster/Habitat/Wald
  - Monster/HG/1-4
  - Monster/Typ/Tier
  - Quelle/5e/mm
aliases:
  - Wolf
---
# [Wolf](3-Mechanics\CLI\bestiary\beast/wolf.md)
*Source: Monster Manual p. 341. Available in the <span title='Systems Reference Document (5.1)'>SRD</span> and the Basic Rules (2014)*  

```statblock
"name": "Wolf"
"size": "Medium"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "13"
"ac_class": "natural armor"
"hp": !!int "11"
"hit_dice": "2d8 + 2"
"modifier": !!int "2"
"stats":
  - !!int "12"
  - !!int "15"
  - !!int "12"
  - !!int "3"
  - !!int "12"
  - !!int "6"
"speed": "40 ft."
"skillsaves":
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+3"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+4"
"senses": "passive Perception 13"
"languages": ""
"cr": "1/4"
"traits":
  - "desc": "The wolf has advantage on Wisdom ([Perception](/3-Mechanics/CLI/skills.md#Perception))\
      \ checks that rely on hearing or smell."
    "name": "Keen Hearing and Smell"
  - "desc": "The wolf has advantage on an attack roll against a creature if at least\
      \ one of the wolf's allies is within 5 feet of the creature and the ally isn't\
      \ [incapacitated](/3-Mechanics/CLI/conditions.md#Incapacitated)."
    "name": "Pack Tactics"
"actions":
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one target. *Hit:* 7 (2d4\
      \ + 2) piercing damage. If the target is a creature, it must succeed on a DC\
      \ 11 Strength saving throw or be knocked [prone](/3-Mechanics/CLI/conditions.md#Prone)."
    "name": "Bite"
"source":
  - "MM"
"image": "/3-Mechanics/CLI/bestiary/beast/token/wolf.webp"
```
^statblock

## Environment

grassland, forest, hill

```statblock
statblock: true
name: Wolf
image: [[Wolf.png]]
source: Grundregelwerk
size: Medium
type: Bestie 
alignment: ohne Gesinnung
ac: 13
hp: 11
hit_dice: 2d8+2
speed: 12 Meter.
stats: [12, 15, 12, 3, 12, 6]
skillsaves:
  - Heimlichkeit: 4
  - Wahrnehmung: 3
damage_vulnerabilities: ""
damage_resistances: ""
damage_immunities: ""
condition_immunities: ""
senses: passive Wahrnehmung 13
languages:
cr: 1/4
environment: Wälder, Grasland, Hügel
bestiary: true
traits:
  - name: Scharfes Gehör und scharfer Geruchssinn
    desc: Der Wolf hat Vorteil bei Proben auf Weisheit(Wahrnehmung), die auf Gehör oder Geruch beruhen.
  - name: Rudeltaktik
    desc: Der Wolf hat Vorteil bei Angriffswürfen gegen eine Kreatur, wenn sich mindestens ein Verbündeter des Wolfs im Umkreis von 1,5 Metern um die Kreatur befindet und der Verbündete nicht außer Gefecht gesetzt ist.
actions:
  - name: Biss
    desc: "Nahkampfangriff: +4 zum Treffen, Reichweite 1,5m, ein Ziel. Treffer: 7 (2W4 + 2) Stichschaden. Handelt es sich bei dem Ziel um eine Kreatur, muss sie einen SG 11 Rettungswurf auf Stärke bestehen oder wird niedergeschmettert."
    attack_bonus: 4
    damage_dice: 2d4
    damage_bonus: 2
```