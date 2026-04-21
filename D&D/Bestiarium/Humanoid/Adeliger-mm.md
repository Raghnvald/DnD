---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Noble
tags:
  - Monster/Größe/Mittelgroß
  - Monster/Habitat/Stadt
  - Monster/HG/1-8
  - Monster/Typ/Humanoid/any-race
  - Quelle/5e/mm
aliases:
  - Noble
---
# [Noble](3-Mechanics\CLI\bestiary\humanoid/noble.md)
*Source: Monster Manual p. 348. Available in the <span title='Systems Reference Document (5.1)'>SRD</span>*  

Nobles wield great authority and influence as members of the upper class, possessing wealth and connections that can make them as powerful as monarchs and generals. A noble often travels in the company of guards, as well as servants who are commoners.

The noble's statistics can also be used to represent courtiers who aren't of noble birth.

```statblock
"name": "Noble"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Any alignment"
"ac": !!int "15"
"ac_class": "[breastplate](/3-Mechanics/CLI/items/breastplate.md)"
"hp": !!int "9"
"hit_dice": "2d8"
"modifier": !!int "1"
"stats":
  - !!int "11"
  - !!int "12"
  - !!int "11"
  - !!int "12"
  - !!int "14"
  - !!int "16"
"speed": "30 ft."
"skillsaves":
  - "name": "[Deception](/3-Mechanics/CLI/skills.md#Deception)"
    "desc": "+5"
  - "name": "[Insight](/3-Mechanics/CLI/skills.md#Insight)"
    "desc": "+4"
  - "name": "[Persuasion](/3-Mechanics/CLI/skills.md#Persuasion)"
    "desc": "+5"
"senses": "passive Perception 12"
"languages": "any two languages"
"cr": "1/8"
"actions":
  - "desc": "*Melee Weapon Attack:* +3 to hit, reach 5 ft., one target. *Hit:* 5 (1d8\
      \ + 1) piercing damage."
    "name": "Rapier"
"reactions":
  - "desc": "The noble adds 2 to its AC against one melee attack that would hit it.\
      \ To do so, the noble must see the attacker and be wielding a melee weapon."
    "name": "Parry"
"source":
  - "MM"
"image": "/3-Mechanics/CLI/bestiary/humanoid/token/noble.webp"
```
^statblock

## Environment

urban

```statblock
statblock: true
name: Adeliger
image: [[Adeliger.png]]
source: Grundregelwerk
size: Medium
type: Humanoid
subtype: jede Rasse
alignment: jede Gesinnung
ac: 15 
hp: 9
hit_dice: 2d8
speed: 9 Meter.
stats: [11, 12, 11, 12, 14, 16]
skillsaves:
  - Motiv erkennen: 6
  - Täuschung: 5
  - Überzeugen: 5
damage_vulnerabilities: ""
damage_resistances: ""
damage_immunities: ""
condition_immunities: ""
senses: passive Wahrnehmung 12
languages: zwei beliebige Sprachen
cr: 1/8
environment: Stadt
bestiary: true
actions:
  - name: Rapier
    desc: "Nahkampfangriff: +3 zum Treffen, Reichweite 1,5m, ein Ziel. Treffer: 5 (1W8 + 1) Stichschaden."
    attack_bonus: 3
    damage_dice: 1W8
    damage_bonus: 1
reactions:
  - name: Parieren
    desc: "Der Adelige fügt seiner Rüstungsklasse 2 gegen einen Nahkampfangriff hinzu, welcher ihn ansonsten treffen würde. Hierzu muss der Adelige den Angreifer sehen und eine Nahkampfwaffe tragen."
```

### Beschreibung
Als Angehörige der Oberschicht verfügen Adlige über große Autorität und Einfluss. Sie besitzen Reichtum und Verbindungen, die sie ebenso mächtig machen können wie Monarchen und Generäle. Ein Adliger reist oft in Begleitung von Wachen und Dienern, die dem einfachen Volk angehören. Die Statistik des Adligen kann auch für Höflinge verwendet werden, die nicht von adliger Geburt sind.