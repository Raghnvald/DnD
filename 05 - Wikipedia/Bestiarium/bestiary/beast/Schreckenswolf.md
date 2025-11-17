---
cssclasses:
  - json5e-monster
tags:
  - Quelle/5e/mm
  - Monster/HG/1
  - Monster/Habitat/Wald
  - Monster/Habitat/Hügel
  - Monster/Größe/Groß
  - Monster/Typ/Tier
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Dire Wolf
---
# [Dire Wolf](3-Mechanics\CLI\bestiary\beast/dire-wolf.md)
*Source: Monster Manual p. 321. Available in the <span title='Systems Reference Document (5.1)'>SRD</span> and the Basic Rules (2014)*  

```statblock
"name": "Dire Wolf"
"size": "Large"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "14"
"ac_class": "natural armor"
"hp": !!int "37"
"hit_dice": "5d10 + 10"
"modifier": !!int "2"
"stats":
  - !!int "17"
  - !!int "15"
  - !!int "15"
  - !!int "3"
  - !!int "12"
  - !!int "7"
"speed": "50 ft."
"skillsaves":
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+3"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+4"
"senses": "passive Perception 13"
"languages": ""
"cr": "1"
"traits":
  - "desc": "The wolf has advantage on Wisdom ([Perception](/3-Mechanics/CLI/skills.md#Perception))\
      \ checks that rely on hearing or smell."
    "name": "Keen Hearing and Smell"
  - "desc": "The wolf has advantage on an attack roll against a creature if at least\
      \ one of the wolf's allies is within 5 feet of the creature and the ally isn't\
      \ [incapacitated](/3-Mechanics/CLI/conditions.md#Incapacitated)."
    "name": "Pack Tactics"
"actions":
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one target. *Hit:* 10\
      \ (2d6 + 3) piercing damage. If the target is a creature, it must succeed on\
      \ a DC 13 Strength saving throw or be knocked [prone](/3-Mechanics/CLI/conditions.md#Prone)."
    "name": "Bite"
"source":
  - "MM"
"image": "/3-Mechanics/CLI/bestiary/beast/token/dire-wolf.webp"
```
^statblock

## Environment

forest, hill

```statblock
statblock: true
name: Schreckenswolf (2014)
image: [[Dire-wolf.png]]
source: Monsterhandbuch 2014
size: Groß
type: Biest
alignment: gesinnungslos
ac: 14
hp: 37
hit_dice: 5d10+10
speed: 15 Meter.
stats: [17, 15, 15, 3, 12, 7]
skillsaves:
  - Heimlichkeit: 4
  - Wahrnehmung: +3
damage_vulnerabilities: ""
damage_resistances: ""
damage_immunities: ""
condition_immunities: ""
senses: passive Wahrnehmung 13
languages: -
cr: 1
environment: Wälder, Hügel
bestiary: true
traits:
  - name: Scharfes Gehör und Geruch
    desc: "Der Wolf hat einen Vorteil bei Proben auf Weisheit (Wahrnehmung), die auf Gehör oder Geruch beruhen."
  - name: Rudeltaktik
    desc: "Der Wolf hat einen Vorteil bei einem Angriffswurf gegen eine Kreatur, wenn sich mindestens ein Verbündeter des Wolfes innerhalb von 1,5 Metern um die Kreatur befindet und der Verbündete nicht außer Gefecht gesetzt ist."
actions:
  - name: Biss
    desc: "_Nahkampfangriff_: +5 auf Treffer, Reichweite 1,5m., ein Ziel. Treffer: 10 (`2W6` + 3) Stichschaden. Handelt es sich bei dem Ziel um eine Kreatur, muss diese einen Stärke-Rettungswurf SG 13 bestehen, oder sie wird auf den Boden geworfen."
    attack_bonus: 5
    damage_dice: 2d6
    damage_bonus: 3
```