---
cssclasses: dnd5e-only-statblock
prefer-view: edit-source read
Bezeichnung:
Typ: Untoter
Größe: Mittelgroß
HG: 1
Habitat:
  - Stadt
  - Unterreich
status: WIP
image:
tags: [Quelle/5e/mm]
aliases: [Specter]
---
```statblock
statblock: true
name: Schreckgespenst
image: [[Specter.png]]
source: Monsterhandbuch 2014
size: Mittelgroß
type: Untoter
alignment: Chaotisch böse
ac: 12
hp: 22
hit_dice: 5d8
speed: 9 Meter.
stats: [1, 14, 11, 10, 10, 11]
damage_vulnerabilities: ""
damage_resistances: "Blitz, Feuer, Kälte, Säure, Schall; Hieb, Stich und Wucht durch nichtmagische Angriffe"
damage_immunities: "Gift, Nekrotisch"
condition_immunities: "Bezaubert, Bewusstlos, Erschöpft, Festgesetzt, Gelähmt, Gepackt, Liegend, Vergiftet, Versteiner"
senses: Dunkelsicht 18 Meter, passive Wahrnehmung 10
languages: Versteht alle zu Lebzeiten bekannten Sprachen, kann aber nicht sprechen
cr: 1
environment: Stadt, Unterreich
bestiary: true
traits:
  - name: Empfindlich gegenüber Sonnenlicht
    desc: "Im Sonnenlicht ist das Schreckgespenst bei Angriffswürfen sowie bei Weisheitswürfen (Wahrnehmung), die Sicht erfordern, im Nachteil."
  - name: Körperlose Bewegung
    desc: "Das Schreckgespenst kann sich durch andere Kreaturen und Gegenstände bewegen, als wären sie schwieriges Gelände. Es erleidet 5 (1W10) Energieschaden, wenn es seinen Zug in einem Gegenstand beendet."
actions:
  - name: Lebensentzug
    desc: "_Nahkampf-Zauberangriff:_ +4 auf Treffer, Reichweite 1,5 m, eine Kreatur. _Treffer:_ 10 (`3W6`) nekrotischer Schaden. Das Ziel muss einen SG-10- Konstitutionsrettungswurf bestehen, oder sein Trefferpunktemaximum wird um den Betrag des erlittenen Schadens verringert. Es bleibt verringert, bis die Kreatur eine lange Rast beendet. Wenn das Trefferpunktemaximum durch diesen Effekt auf 0 sinkt, stirbt das Ziel."
    attack_bonus: 4
    damage_dice: 3d6
    damage_bonus: 0
```