---
cssclasses:
  - json5e-monster
tags:
  - Monster/Größe/Klein
  - Monster/Habitat/Stadt
  - Quelle/5e/cos
  - Monster/Typ/Konstrukt
aliases:
  - Broom of animated attack
---
# Besen des belebten Angriffs
Ein Besen des belebten Angriffs ist leicht mit einem Flugbesen zu verwechseln. Er attackiert jede Kreatur, die ihn ergreift oder zu reiten versucht.
$\quad$ **_Fliegender Besen._** Einige Besen des belebten Angriffs erlauben ihren Schöpfern, sie zu reiten, in welchem Fall sie sich wie typische Flugbesen verhalten. Ein Besen des belebten Angriffs kann jedoch nur das halbe Gewicht eines Flugbesens tragen (siehe Kapitel 7, „Schätze", des Spielleiterhandbuchs)

```statblock
statblock: true
name: Besen des belebten Angriffs
image: 
source: Fluch des Strahd
size: Klein
type: Konstrukt
alignment: Gesinnungslos
ac: 15
hp: 17
hit_dice: 5d6
speed: 0 Meter, fliegend 15m (schweben)
stats: [10, 17, 10, 1, 5, 1]
damage_vulnerabilities: ""
damage_resistances: ""
damage_immunities: "Gift, psychisch"
condition_immunities: "Bezaubert, blind, erschöpft, gelähmt, liegend, taub, verängstigt, vergiftet, versteinert"
senses: Blindsicht 10 m (ü ber diesen Radius hinaus blind),passive Wahrnehmung 7
languages: -
cr: 1/4
bestiary: true
traits:
  - name: Antimagische Empfindlichkeit.
    desc: "Der Besen wird kampfunfähig, wenn er sich im Bereich eines [Antimagischen Feldes](Antimagisches-Feld.md) befindet. Wenn der Besen Ziel von Magie bannen wird, muss er einen Konstitutions-Rettungswurf gegen den Zauberrettungswurf-SG des Zauberwirkers ablegen, um nicht für 1 Minute bewusstlos zu werden."
  - name: Falsches Erscheinungsbild.
    desc: "Solange der Besen bewegungslos bleibt und nicht fliegt, ist er nicht von einem normalen Besen zu unterscheiden"
actions:
  - name: Mehrfachangriff
    desc: "Der Besen führt zwei Nahkampfangriffe aus."
  - name: Wurfpfeil
    desc: "Nahkampf-Waffenangriff_: +5 zum Treffen, Reichweite 1,50 m, ein Ziel. _Treffer_: 5 (`1W4 + 3`) Wuchtschaden."
    attack_bonus: 5
    damage_dice: 1d4
    damage_bonus: 3
reactions:
  - name: Belebter Angriff
    desc: "Wenn der Besen bewegungslos ist und eine Kreatur ihn ergreift, legt der Besen einen vergleichenden Geschicklichkeitswurf gegen einen Stärkewurf der Kreatur ablegen. Wenn der Besen den vergleichenden Wurf gewinnt, fliegt er aus dem Griff der Kreatur und führt einen Nahkampfangriff mit einem Vorteil beim Angriffswurf aus"
```