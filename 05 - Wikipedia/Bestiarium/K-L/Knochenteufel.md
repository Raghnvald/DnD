---
cssclasses:
  - json5e-monster
prefer-view:
  - edit-source read
type:
  - creature
tags:
  - Quelle/5e/Monster_Manual
  - Typ/Unhold/Teufel
  - Größe/Groß
  - Habitat/Planar/Untere Ebenen
aliases:
  - Bone Devil
link:
status:
Typ: Unhold
---
# Bone Devil
*Source: SRD / Basic Rules*  

```statblock
name: Bone Devil
size: Groß
source: SRD / Basic Rules
type: Teufel
subtype: ""
alignment: Gesetzlich Böse
ac: 19
hp: 142
hit_dice: 15d10 + 60
speed: 40 Meter, Fliegen 40 Meter
stats: [18, 16, 18, 13, 14, 16]
saves:
  - INT: +5
  - WEI: +6
  - CHA: +7
skillsaves:
  - Täuschung: +7
  - Einsicht: +6
damage_vulnerabilities: ""
damage_resistances: "Kälte; Hieb‑, Stich‑ und Wuchtschaden von nichtmagischen Angriffen, die nicht versilbert sind"
damage_immunities: "Feuer, Gift"
condition_immunities: "Vergiftet"
senses: "Dunkelsicht 120 Meter, passive Wahrnehmung 12"
languages: "Infernal, telepathisch 120 Meter"
cr: 9
bestiary: true
traits:
  - name: Devil's Sight.
    desc: "Magische Dunkelheit behindert die Dunkelsicht des Teufels nicht."
  - name: Magic Resistance.
    desc: "Der Teufel hat Vorteil bei Rettungswürfen gegen Zauber und andere magische Effekte."
actions:
  - name: Multiattack.
    desc: "Der Teufel führt drei Angriffe aus: zwei Klauen und einen Stich."
  - name: Claw.
    desc: "_Nahkampfangriff_: +8 zum Treffen, Reichweite 10 ft., ein Ziel. _Treffer_: 8 (1d8 + 4) Hiebschaden."
    attack_bonus: 8
    damage_dice: 1d8
    damage_bonus: 4
  - name: Sting.
    desc: "_Nahkampfangriff_: +8 zum Treffer, Reichweite 10 ft., ein Ziel. _Treffer_: 13 (2d8 + 4) Stichschaden plus 17 (5d6) Giftschaden. Das Ziel muss einen Konstitutions‑Rettungswurf (SG 14) bestehen, sonst wird es 1 Minute lang vergiftet. Der Rettungswurf kann am Ende jedes Zuges wiederholt werden."
    attack_bonus: 8
    damage_dice: 2d8
    damage_bonus: 4
```