---
cssclasses: dnd5e-only-statblock
prefer-view: edit-source read
Bezeichnung:
Typ: Bestie
Größe:
HG:
status:
image:
tags:
  - Quelle/5e/mm
  - Monster/HG/1
  - Monster/Habitat/Wüste
  - Monster/Habitat/Wald
  - Monster/Habitat/Sumpf
  - Monster/Habitat/Unterreich
  - Monster/Habitat/Stadt
  - Monster/Größe/Groß
  - Monster/Typ/Tier
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Giant Spider
---
# Riesenspinne
*Source: Monster Manual p. 328. Available in the <span title='Systems Reference Document (5.1)'>SRD</span> and the Basic Rules (2014)*  

Um ihre Beute zu fangen, weben Riesenspinnen komplexe Netze oder schießen klebrige Stränge aus ihrem Unterleib. Riesenspinnen findet man vor allem unter der Erde, wo sie sich an der Decke oder in dunklen, mit Netzen gefüllten Spalten niederlassen. Solche Behausungen sind oft mit Netzkokons behangen, in denen vorherige Opfer eingesponnen sind.

```statblock
"name": "Giant Spider"
"size": "Large"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "14"
"ac_class": "natural armor"
"hp": !!int "26"
"hit_dice": "4d10 + 4"
"modifier": !!int "3"
"stats":
  - !!int "14"
  - !!int "16"
  - !!int "12"
  - !!int "2"
  - !!int "11"
  - !!int "4"
"speed": "30 ft., climb 30 ft."
"skillsaves":
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+7"
"senses": "[blindsight](/3-Mechanics/CLI/senses.md#Blindsight) 10 ft., [darkvision](/3-Mechanics/CLI/senses.md#Darkvision)\
  \ 60 ft., passive Perception 10"
"languages": ""
"cr": "1"
"traits":
  - "desc": "The spider can climb difficult surfaces, including upside down on ceilings,\
      \ without needing to make an ability check."
    "name": "Spider Climb"
  - "desc": "While in contact with a web, the spider knows the exact location of any\
      \ other creature in contact with the same web."
    "name": "Web Sense"
  - "desc": "The spider ignores movement restrictions caused by webbing."
    "name": "Web Walker"
"actions":
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one creature. *Hit:* 7\
      \ (1d8 + 3) piercing damage, and the target must make a DC 11 Constitution saving\
      \ throw, taking 9 (2d8) poison damage on a failed save, or half as much damage\
      \ on a successful one. If the poison damage reduces the target to 0 hit points,\
      \ the target is stable but [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)\
      \ for 1 hour, even after regaining hit points, and is [paralyzed](/3-Mechanics/CLI/conditions.md#Paralyzed)\
      \ while [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned) in this way."
    "name": "Bite"
  - "desc": "*Ranged Weapon Attack:* +5 to hit, range 30/60 ft., one creature. *Hit:*\
      \ The target is [restrained](/3-Mechanics/CLI/conditions.md#Restrained) by webbing.\
      \ As an action, the [restrained](/3-Mechanics/CLI/conditions.md#Restrained)\
      \ target can make a DC 12 Strength check, bursting the webbing on a success.\
      \ The webbing can also be attacked and destroyed (AC 10; hp 5; vulnerability\
      \ to fire damage; immunity to bludgeoning, poison, and psychic damage)."
    "name": "Web (Recharge 5-6)"
"source":
  - "MM"
"image": "/3-Mechanics/CLI/bestiary/beast/token/giant-spider.webp"
```
^statblock

## Environment

underdark, forest, swamp, urban, desert

---

```statblock
statblock: true
name: Riesenspinne
image: [[Giant-Spider.webp]]
source: Grundregelwerk
size: Groß
type: Bestie
alignment: gesinnungslos
ac: 14
hp: 26
hit_dice: 4d10 + 4
speed: 9 Meter, 9m kletternd.
stats: [14, 16, 12, 2, 11, 4]
skillsaves:
  - Heimlichkeit: 7
damage_vulnerabilities: ""
damage_resistances: ""
damage_immunities: ""
condition_immunities: ""
senses: Blindsicht 3 Meter, Dunkelsicht 18 Meter, passive Wahrnehmung 10
languages: -
cr: 1
environment: Stadt, Sümpfe, Unterreich, Wüste, Wälder
bestiary: true
traits:
  - name: Netzsinn
    desc: "Solange die Spinne in Kontakt mit einem Spinnennetz ist, weiß sie genau, wo sich andere Kreaturen aufhalten, die in Kontakt mit demselben Netz sind."
    attack_bonus: 0
  - name: Netzwandler
    desc: "Die Spinne ignoriert Bewegungseinschränkungen, die durch Netze verursacht werden."
    attack_bonus: 0
  - name: Spinnenklettern
    desc: "Die Spinne kann an schwierigen Oberflächen klettern, auch kopfüber an der Decke, ohne Attributswürfe ausführen zu müssen."
    attack_bonus: 0
actions:
  - name: Biss
    desc: "Nahkampfwaffenangriff: +5 auf Treffer, Reichweite 1,5 m, ein Ziel. Treffer: 7 (`1W8+3`) Stichschaden, und das Ziel muss einen SG-11-Konstitutionsrettungswurf ausführen. Scheitert der Wurf, erleidet es 9 (`2W8`) Giftschaden, anderenfalls die Hälfte. Wenn die Trefferpunkte des Ziels durch den Giftschaden auf 0 sinken, ist das Ziel stabil, aber eine Stunde lang vergiftet sowie gelähmt, selbst wenn es Trefferpunkte zurückgewinnt"
    attack_bonus: 5
    damage_dice: 1d8
    damage_bonus: 3
  - name: Netz (Aufladung 5–6)
    desc: "Fernkampfwaffenangriff: +5 auf Treffer, Reichweite 9/18 m, ein Ziel. Treffer: Das Ziel ist durch das Netz festgesetzt. Als Aktion kann dasfestgesetzte Ziel einen SG-12-Stärkewurf ausführen. Bei einem Erfolg befreit es sich aus den Netzen. Das Netz kann auch angegriffen und zerstört werden (RK 10, 5 Trefferpunkte, anfällig für Feuerschaden, immun gegen Gift-, psychischen und Wuchtschaden)."
    attack_bonus: 5
```