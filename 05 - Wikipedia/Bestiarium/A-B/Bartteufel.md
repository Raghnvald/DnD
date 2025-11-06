---
cssclasses:
  - json5e-monster
prefer-view:
  - edit-source read
status:
tags:
  - Monster/Größe/Mittelgroß
  - Habitat/Planar/Untere Ebenen
  - Quelle/5e/mm
  - Monster/Typ/Unhold/Teufel
aliases:
  - Bearded Devil
link:
type:
  - creature
Typ: Unhold
---
# Bearded Devil
*Source: SRD / Basic Rules*  

```statblock
name: Bearded Devil
size: Mittelgroß
source: SRD / Basic Rules
type: Teufel
subtype: ""
alignment: Gesetzlich Böse
ac: 13
hp: 52
hit_dice: 8d8 + 16
speed: 30 Meter
stats: [16, 15, 15, 9, 11, 11]
saves:
  - STR: +5
  - KON: +4
  - WEI: +2
skillsaves: []
damage_vulnerabilities: ""
damage_resistances: "Kälte; Hieb‑, Stich‑ und Wuchtschaden von nichtmagischen Angriffen, die nicht versilbert sind"
damage_immunities: "Feuer, Gift"
condition_immunities: "Vergiftet"
senses: "Dunkelsicht 120 Meter, passive Wahrnehmung 10"
languages: "Infernal, telepathisch 120 Meter"
cr: 3
bestiary: true
traits:
  - name: Devil's Sight.
    desc: "Magische Dunkelheit behindert die Dunkelsicht des Teufels nicht."
  - name: Magic Resistance.
    desc: "Der Teufel hat Vorteil bei Rettungswürfen gegen Zauber und andere magische Effekte."
  - name: Steadfast.
    desc: "Der Teufel kann nicht verängstigt werden, solange er innerhalb von 30 ft. ein verbündetes Wesen sehen kann."
actions:
  - name: Multiattack.
    desc: "Der Teufel führt zwei Angriffe aus: einen mit seinem Bart und einen mit seiner Gleve."
  - name: Beard.
    desc: "_Nahkampfangriff_: +5 zum Treffen, Reichweite 5 ft., ein Ziel. _Treffer_: 6 (1d8 + 2) Stichschaden, und das Ziel muss einen Konstitutions‑Rettungswurf (SG 12) bestehen, sonst wird es 1 Minute lang vergiftet und kann währenddessen keine Trefferpunkte zurückgewinnen. Der Rettungswurf kann am Ende jedes Zuges wiederholt werden."
    attack_bonus: 5
    damage_dice: 1d8
    damage_bonus: 2
  - name: Glaive.
    desc: "_Nahkampfangriff_: +5 zum Treffen, Reichweite 10 ft., ein Ziel. _Treffer_: 8 (1d10 + 3) Hiebschaden. Ist das Ziel kein Untoter oder Konstrukt, muss es einen Konstitutions‑Rettungswurf (SG 12) bestehen, sonst erleidet es zu Beginn jedes seiner Züge 5 (1d10) zusätzlichen Schaden durch eine infernale Wunde. Jeder weitere Treffer mit der Gleve erhöht diesen Zusatzschaden um weitere 5 (1d10). Eine Kreatur kann eine Aktion verwenden, um die Wunde mit einer erfolgreichen Weisheits‑(Heilkunde)-Prüfung (SG 12) zu stillen; magische Heilung schließt die Wunde automatisch."
    attack_bonus: 5
    damage_dice: 1d10
    damage_bonus: 3
```