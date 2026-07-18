---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Acolyte
Kategorie: Humanoid (jede Rasse)
Größe: Mittelgroß
HG: 1/4
Habitat:
  - Stadt
Status: WIP
linter-yaml-title-alias: Acolyte
tags:
  - Monster/Größe/Mittelgroß
  - Monster/Habitat/Stadt
  - Monster/HG/1-4
  - Monster/Typ/Humanoid/any-race
  - Quelle/5e/mm
aliases:
  - Acolyte
image: token/acolyte.webp
status: WIP
---
# [Acolyte](3-Mechanics\CLI\bestiary\humanoid/acolyte.md)
*Source: Monster Manual p. 342. Available in the <span title='Systems Reference Document (5.1)'>SRD</span> and the Basic Rules (2014)*  

Acolytes are junior members of a clergy, usually answerable to a priest. They perform a variety of functions in a temple and are granted minor spellcasting power by their deities.

```statblock
"name": "Acolyte"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Any alignment"
"ac": !!int "10"
"hp": !!int "9"
"hit_dice": "2d8"
"modifier": !!int "0"
"stats":
  - !!int "10"
  - !!int "10"
  - !!int "10"
  - !!int "10"
  - !!int "14"
  - !!int "11"
"speed": "30 ft."
"skillsaves":
  - "name": "[Medicine](/3-Mechanics/CLI/skills.md#Medicine)"
    "desc": "+4"
  - "name": "[Religion](/3-Mechanics/CLI/skills.md#Religion)"
    "desc": "+2"
"senses": "passive Perception 12"
"languages": "any one language (usually Common)"
"cr": "1/4"
"traits":
  - "desc": "The acolyte is a 1st-level spellcaster. Its spellcasting ability is Wisdom\
      \ (spell save DC 12, +4 to hit with spell attacks). The acolyte has following\
      \ cleric spells prepared:\n\n**Cantrips (at will):** [light](/3-Mechanics/CLI/spells/light.md),\
      \ [sacred flame](/3-Mechanics/CLI/spells/sacred-flame.md), [thaumaturgy](/3-Mechanics/CLI/spells/thaumaturgy.md)\n\
      \n**1st level (3 slots):** [bless](/3-Mechanics/CLI/spells/bless.md), [cure\
      \ wounds](/3-Mechanics/CLI/spells/cure-wounds.md), [sanctuary](/3-Mechanics/CLI/spells/sanctuary.md)"
    "name": "Spellcasting"
"actions":
  - "desc": "*Melee Weapon Attack:* +2 to hit, reach 5 ft., one target. *Hit:* 2 (1d4)\
      \ bludgeoning damage."
    "name": "Club"
"source":
  - "MM"
"image": "/3-Mechanics/CLI/bestiary/humanoid/token/acolyte.webp"
```
^statblock

## Environment

urban

```statblock
statblock: true
name: Akolyth
image: [[Akolyt.png]]
source: Grundregelwerk
size: Mittel
type: Humanoid
subtype: jede Rasse
alignment: jede Gesinnung
ac: 10
hp: 9
hit_dice: 2d8
speed: 9 Meter.
stats: [10, 10, 10, 10, 14, 11]
skillsaves:
  - Heilkunde: 4
  - Religion: 2
damage_vulnerabilities: ""
damage_resistances: ""
damage_immunities: ""
condition_immunities: ""
senses: passive Wahrnehmung 12
languages: eine beliebige Sprachen (normalerweise Gemeinsprache)
cr: 1/4
environment: Stadt
bestiary: true
actions:
  - name: Knüppel
    desc: "*Nahkampfangriff:* +2 zum Treffen, 1,5m Reichweite., ein Ziel. *Treffer:* 2 (`1d4`) Wuchtschaden."
    attack_bonus: 3
    damage_dice: 1W8
    damage_bonus: 1
spells:
  - "Der Akolyth ist ein Zauberwirker des 1. Grades. Seine Zauberfertigkeit ist Weisheit (Zauberrettungswurf SG 12, +4 zum Treffen mit Zauberangriffen). Der Akolyth hat folgende Klerikerzauber vorbereitet:"
  - Zaubertricks: [[Licht.md|Licht]], [[Heilige-Flamme.md|Heilige Flamme]], [[Thaumaturgie.md|Thaumaturgie]]
  - Zaubergrad 1 (3 Zauberplätze): [Segnen](Kompendium/Zauber/Segnen.md), [Wunden heilen](Kompendium/Zauber/Wunden-heilen.md), [Heiligtum](Kompendium/Zauber/Heiligtum.md)
```

### Beschreibung

Akolythen sind untergeordnete Mitglieder des Klerus, die in der Regel einem Priester unterstellt sind. Sie erfüllen eine Vielzahl von Aufgaben in einem Tempel und erhalten von ihren Göttern eine geringe Zauberkraft.