---
cssclasses:
  - json5e-monster
prefer-view:
  - edit-source read
type:
  - creature
tags:
  - Quelle/5e/Monster_Manual
  - Monster/Typ/Unhold/Teufel
  - Monster/Größe/Mittelgroß
  - Habitat/Planar/Untere Ebenen
aliases:
  - Barbed Devil
link:
status:
Typ: Unhold
---
# Barbed Devil
*Source: SRD / Basic Rules*  

```statblock
name: Barbed Devil
size: Mittelgroß
source: SRD / Basic Rules
type: Teufel
subtype: ""
alignment: Gesetzlich Böse
ac: 15
hp: 110
hit_dice: 13d8 + 52
speed: 30 Meter
stats: [16, 17, 18, 12, 14, 14]
saves:
  - STR: +6
  - KON: +7
  - WEI: +5
  - CHA: +5
skillsaves:
  - Täuschung: +5
  - Einsicht: +5
  - Wahrnehmung: +8
damage_vulnerabilities: ""
damage_resistances: "Kälte; Hieb‑, Stich‑ und Wuchtschaden von nichtmagischen Angriffen, die nicht versilbert sind"
damage_immunities: "Feuer, Gift"
condition_immunities: "Vergiftet"
senses: "Dunkelsicht 120 Meter, passive Wahrnehmung 18"
languages: "Infernal, telepathisch 120 Meter"
cr: 5
bestiary: true
traits:
  - name: Barbed Hide.
    desc: "Zu Beginn jedes Zuges fügt der barben Teufel jeder Kreatur, die ihn packt, 5 (1d10) Stichschaden zu."
  - name: Devil's Sight.
    desc: "Magische Dunkelheit behindert die Dunkelsicht des Teufels nicht."
  - name: Magic Resistance.
    desc: "Der Teufel hat Vorteil bei Rettungswürfen gegen Zauber und andere magische Effekte."
actions:
  - name: Multiattack.
    desc: "Der Teufel führt drei Nahkampfangriffe aus: einen mit seinem Schwanz und zwei mit seinen Klauen. Alternativ kann er zweimal Flammwurf einsetzen."
  - name: Claw.
    desc: "_Nahkampfangriff_: +6 zum Treffen, Reichweite 5 ft., ein Ziel. _Treffer_: 6 (1d6 + 3) Stichschaden."
    attack_bonus: 6
    damage_dice: 1d6
    damage_bonus: 3
  - name: Tail.
    desc: "_Nahkampfangriff_: +6 zum Treffen, Reichweite 5 ft., ein Ziel. _Treffer_: 10 (2d6 + 3) Stichschaden."
    attack_bonus: 6
    damage_dice: 2d6
    damage_bonus: 3
  - name: Hurl Flame.
    desc: "_Fernkampfangriff (Zauberangriff)_: +5 zum Treffen, Reichweite 150 ft., ein Ziel. _Treffer_: 10 (3d6) Feuerschaden. Trifft ein brennbares Objekt, das nicht getragen wird, so fängt es Feuer."
    attack_bonus: 5
    damage_dice: 3d6
    damage_bonus: 0
```