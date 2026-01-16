---
cssclasses: dnd5e-only-statblock
prefer-view: edit-source read
Bezeichnung:
Typ: Aberration
Größe: Mittelgroß
HG: 2
Habitat: Unterreich
status:
image:
tags:
  - Quelle/5e/mm
  - Monster/HG/2
  - Monster/Habitat/Unterreich
  - Monster/Größe/Mittelgroß
  - Monster/Typ/Aberration
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Nothic
---
# Nothic
*Source: Monster Manual p. 236. Available in the Basic Rules (2014)*  

Ein gehässiges Auge starrt aus der Finsternis. Sein Schimmern deutet auf eine eigenartige Intelligenz und verstörende Bösartigkeit hin. Meistens ist ein Nothic damit zufrieden, zu beobachten und die Kreaturen, denen er begegnet, einzuschätzen. Wenn er zur Gewa lt getrieben wird, nutzt er seinen grauenvollen Blick, um das Fleisch von den Knochen seiner Feinde faulen zu lassen.

## Verfluchte Arkanisten

Anstatt die gottgleiche Überlegenheit zu erlangen, die sie sich wünschen, verwandeln sich manche Magier, die ihr Leben der Entdeckung arkaner Geheimnisse widmen, in kriechende, gequälte Monster. Dies ist die Folge eines Fluchs, den Vecna zurückgelassen hat, ein mächtiger Lich, der in einigen Welten seine untote Existenz hinter sich gelassen hat, um ein Gott der Geheimnisse zu werden. Nothics haben kein Wissen über ihr ehemaliges Selbst. Sie haus en in den Schatten und suchen Orte heim, die voll von magischem Wissen sind. Dabei werden sie von Erinnerungen und Impulsen getrieben, die sie nicht ganz verstehen können.

## Dunkle Orakel

Nothics verfügen über eine seltsame magische Einsicht, die es ihnen erlaubt, Wissen aus anderen Kreaturen zu ziehen. Dies gewährt ihnen ein einzigartiges Verständnis für geheimes und verbotenes Wissen, das sie teilen - für einen Preis. Ein Nothic begehrt magische Gegenstände und nimmt solche Geschenke gierig von Kreaturen an, die sein Wissen suchen.

### Lauerer an magischen Orten

Nothics sind dafür berüchtigt, in arkane Akademien und andere Orte, die reich an magischem Wissen sind, einzudringen. Sie werden vom vagen Wissen angetrieben, dass es eine Methode gibt, ihren Zustand umzukehren. Dies ist kein klares, bewusstes Ziel, mehr ein zwanghaftes Zerren an ihrem Verstand. Einige Nothics sind schlau genug, um zu begreifen, dass dies nur ein Teil dieser seltsamen Lektion für ihre Narrheit ist, eine falsche Hoffnung, die sie dazu treibt, noch mehr arkane Geheimnisse zu suchen.

```statblock
"name": "Nothic"
"size": "Medium"
"type": "aberration"
"alignment": "Neutral Evil"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "45"
"hit_dice": "6d8 + 18"
"modifier": !!int "3"
"stats":
  - !!int "14"
  - !!int "16"
  - !!int "16"
  - !!int "13"
  - !!int "10"
  - !!int "8"
"speed": "30 ft."
"skillsaves":
  - "name": "[Arcana](/3-Mechanics/CLI/skills.md#Arcana)"
    "desc": "+3"
  - "name": "[Insight](/3-Mechanics/CLI/skills.md#Insight)"
    "desc": "+4"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+2"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+5"
"senses": "[truesight](/3-Mechanics/CLI/senses.md#Truesight) 120 ft., passive Perception\
  \ 12"
"languages": "Undercommon"
"cr": "2"
"traits":
  - "desc": "The nothic has advantage on Wisdom ([Perception](/3-Mechanics/CLI/skills.md#Perception))\
      \ checks that rely on sight."
    "name": "Keen Sight"
"actions":
  - "desc": "The nothic makes two claw attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one target. *Hit:* 6 (1d6\
      \ + 3) slashing damage."
    "name": "Claw"
  - "desc": "The nothic targets one creature it can see within 30 feet of it. The\
      \ target must succeed on a DC 12 Constitution saving throw against this magic\
      \ or take 10 (3d6) necrotic damage."
    "name": "Rotting Gaze"
  - "desc": "The nothic targets one creature it can see within 30 feet of it. The\
      \ target must contest its Charisma ([Deception](/3-Mechanics/CLI/skills.md#Deception))\
      \ check against the nothic's Wisdom ([Insight](/3-Mechanics/CLI/skills.md#Insight))\
      \ check. If the nothic wins, it magically learns one fact or secret about the\
      \ target. The target automatically wins if it is immune to being [charmed](/3-Mechanics/CLI/conditions.md#Charmed)."
    "name": "Weird Insight"
"source":
  - "MM"
"image": "/3-Mechanics/CLI/bestiary/aberration/token/nothic.webp"
```
^statblock

## Environment

underdark

---

```statblock
statblock: true
name: Nothic (2014)
image: [[Nothic.webp]]
source: Monsterhandbuch 2014
size: Mittelgroß
type: Aberation
alignment: neutral böse
ac: 15
hp: 45
hit_dice: 6d8 +18
speed: 9 Meter.
stats: [14, 16, 16, 13, 10, 8]
skillsaves:
  - Arkane Kunde: 3
  - Heimlichkeit: 5
  - Motiv erkennen: 4
  - Wahrnehmung: 2
damage_vulnerabilities: ""
damage_resistances: ""
damage_immunities: ""
condition_immunities: ""
senses: Wahre Sicht 36 Meter, passive Wahrnehmung 12
languages: Gemeinsprache der Unterreiche
cr: 2
environment: Unterreich
bestiary: true
traits:
  - name: Scharfe Sicht
    desc: "Der Nothic hat einen Vorteil bei Würfen auf Weisheit (Wahrnehmung), die mit Sicht zusammenhängen."
actions:
  - name: Mehrfachangriff
    desc: "Der Nothic führt zwei Klauenangriffe aus."
  - name: Klauen
    desc: "Nahkampfangriff: +4 zum Treffen, Reichweite 1,5m, ein Ziel. Treffer: `6` (`1W6 + 3`) Hiebschaden."
    attack_bonus: 4
    damage_dice: 1d6
    damage_bonus: 3
  - name: Verfaulender Blick
    desc: "Der Nothic wählt eine Kreatur innerhalb von 9 m um sich aus, die er sehen kann. Das Ziel muss einen Konstitutionsrettungswurf gegen SG 12 schaffen, sonst erleidet es 10 (3W6) nekrotischen Schaden."
  - name: Seltsame Einsicht
    desc: "Der Nothic wählt eine Kreatur innerhalb von 9 m um sich aus, die er sehen kann. Das Ziel muss einen vergleichenden Wurf auf Charisma (Täuschung) gegen Weisheit (Motiv erkennen) des Nothics ablegen. Wenn der Nothic gewinnt, erfährt er auf magische Weise eine Tatsache oder ein Geheimnis über die Kreatur. Das Ziel gewinnt automatisch, wenn es nicht bezaubert werden kann."
```