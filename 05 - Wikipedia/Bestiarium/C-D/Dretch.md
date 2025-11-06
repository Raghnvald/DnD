---
cssclasses:
  - json5e-monster
prefer-view:
  - edit-source read
status:
tags:
  - Monster/Größe/Klein
  - Monster/Habitat/Planar/Abyss
  - Quelle/5e/mm
  - Monster/Typ/Unhold/Dämon
aliases:
  - Dretch
link:
type:
  - creature
Typ: Unhold
---
# Dretch
*Source: SRD / Basic Rules*  

```statblock
name: Dretch
size: Klein
source: SRD / Basic Rules
type: Dämon
subtype: ""
alignment: Chaotisch Böse
ac: 11
hp: 18
hit_dice: 4d6 + 4
speed: 20 Meter
stats: [11, 11, 12, 5, 8, 3]
saves:
  - STR: +0
  - GES: +0
  - KON: +0
  - INT: +0
  - WEI: +0
  - CHA: +0
skillsaves: []
damage_vulnerabilities: ""
damage_resistances: "Kälte, Blitz, Blitzschlag"
damage_immunities: "Gift"
condition_immunities: "Vergiftet"
senses: "Dunkelsicht 60 Meter, passive Wahrnehmung 9"
languages: "Abyssal, telepathisch 60 Meter (nur für Wesen, die Abyssal verstehen)"
cr: 0.25
bestiary: true
traits:
  - name: Fetid Cloud (1/Tag).
    desc: "Ein 10‑ft‑Radius grüner Gestank breitet sich vom Dretch aus. Das Gebiet ist leicht verdunkelt. Jede Kreatur, die ihren Zug dort beginnt, muss einen Konstitutions‑Rettungswurf (SG 11) bestehen, sonst wird sie bis zum Beginn ihres nächsten Zuges vergiftet. Während sie vergiftet ist, kann sie entweder eine Aktion **oder** eine Bonusaktion ausführen, aber nicht beides, und sie kann keine Reaktionen nutzen."
actions:
  - name: Multiattack.
    desc: "Der Dretch führt zwei Angriffe aus: einen Biss und einen Klauenangriff."
  - name: Bite.
    desc: "_Nahkampfangriff_: +2 zum Treffen, Reichweite 5 ft., ein Ziel. _Treffer_: 3 (1d6) Stichschaden."
    attack_bonus: 2
    damage_dice: 1d6
    damage_bonus: 0
  - name: Claws.
    desc: "_Nahkampfangriff_: +2 zum Treffen, Reichweite 5 ft., ein Ziel. _Treffer_: 5 (2d4) Hiebschaden."
    attack_bonus: 2
    damage_dice: 2d4
    damage_bonus: 0
```