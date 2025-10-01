---
cssclasses: 
- json5e-monster
prefer-view: 
- edit-source read
type: 
- creature
tags: 
- Quelle/5e/MM
- Typ/Unhold/Teufel
- Größe/Mittelgroß
- Habitat/Planar/Neun-Höllen
aliases: 
- Chain Devil
link:
status:
order:
parent:
---
# Chain Devil
*Source: SRD / Basic Rules*  

```statblock
name: Chain Devil
size: Mittelgroß
source: SRD / Basic Rules
type: Teufel
subtype: ""
alignment: Gesetzlich Böse
ac: 16
hp: 85
hit_dice: 10d8 + 40
speed: 30 Meter
stats: [18, 15, 18, 11, 12, 14]
saves:
  - KON: +7
  - WEI: +4
  - CHA: +5
skillsaves: []
damage_vulnerabilities: ""
damage_resistances: "Kälte; Hieb‑, Stich‑ und Wuchtschaden von nichtmagischen Angriffen, die nicht versilbert sind"
damage_immunities: "Feuer, Gift"
condition_immunities: "Vergiftet"
senses: "Dunkelsicht 120 Meter, passive Wahrnehmung 11"
languages: "Infernal, telepathisch 120 Meter"
cr: 8
bestiary: true
traits:
  - name: Devil's Sight.
    desc: "Magische Dunkelheit behindert die Dunkelsicht des Teufels nicht."
  - name: Magic Resistance.
    desc: "Der Teufel hat Vorteil bei Rettungswürfen gegen Zauber und andere magische Effekte."
actions:
  - name: Multiattack.
    desc: "Der Teufel führt zwei Angriffe mit seinen Ketten aus."
  - name: Chain.
    desc: "_Nahkampfangriff_: +8 zum Treffen, Reichweite 10 ft., ein Ziel. _Treffer_: 11 (2d6 + 4) Hiebschaden. Das Ziel wird (falls nicht bereits gefesselt) **gefasst** (Flucht‑SG 14). Solange die Fesselung besteht, ist das Ziel **gehemmt** und erleidet zu Beginn jedes seiner Züge 7 (2d6) Stichschaden."
    attack_bonus: 8
    damage_dice: 2d6
    damage_bonus: 4
  - name: Animate Chains (nach kurzer/langer Pause wiederaufladbar).
    desc: "Bis zu vier Ketten im Umkreis von 60 ft., die der Teufel sehen kann, erhalten Rasierkanten und werden animiert. Jede animierte Kette hat AC 20, 20 TP, Resistenz gegen Stichschaden und Immunität gegen psychischen und Donnerschaden. Während des Zuges kann der Teufel jede animierte Kette benutzen, um einen zusätzlichen Kettenangriff auszuführen (wie oben). Eine animierte Kette kann ein Ziel fassen, aber nicht angreifen, solange sie gefasst ist. Sie wird wieder zu einer normalen Kette, wenn sie 0 TP hat oder der Teufel kampfunfähig wird."
reactions:
  - name: Unnerving Mask.
    desc: "Wenn eine Kreatur, die der Teufel sehen kann, ihren Zug innerhalb von 30 ft. von ihm beginnt, kann der Teufel die Illusion erzeugen, dass er das verstorbene geliebte Wesen oder einen erbitterten Feind der Kreatur ist. Die Kreatur muss einen Weisheits‑Rettungswurf (SG 14) bestehen, sonst ist sie bis zum Ende ihres Zuges **verängstigt**."
```