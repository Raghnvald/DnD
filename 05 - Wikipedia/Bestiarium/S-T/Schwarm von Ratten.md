---
cssclasses: dnd5e-only-statblock
prefer-view: edit-source read
Bezeichnung: Schwarm von Ratten
Typ: Bestie
Größe: Mittelgroß
HG: 1/4
status:
order:
parent:
image: 
tags:
- Quelle/5e/Monster_Manual
- Typ/Tier
- Größe/Mittelgroß
- Habitat/Sumpf
- Habitat/Stadt
aliases:
- Swarm of Rats
---
# Schwarm von Ratten

```statblock
name: Schwarm von Ratten
size: Mittelgroßer Schwarm
type: winzige Tiere
alignment: gesinnungslos
ac: 10
hp: 24
hit_dice: 7d8 - 7
speed: 9 Meter.
stats: [9, 11, 9, 2, 10, 3]
damage_vulnerabilities: ""
damage_resistances: "Hieb, Stich, Wucht"
damage_immunities: ""
condition_immunities: "Betäubt, bezaubert, festgesetzt, gelähmt, gepackt, liegend, verängstigt, versteinert"
senses: [[Regularien/2014/Grundregelwerk/08-Abenteuersuche#Dunkelsicht|Dunkelsicht]] 9 Meter, passive Wahrnehmung 10
languages: n/v
cr: 1/4
bestiary: true
traits:
  - name: Scharfer Geruchssinn
    desc: "Der Schwarm hat einen Vorteil bei Würfen auf Weisheit (Wahrnehmung), die mit dem Geruchssinn zusammenhängen."
  - name: Schwarm
    desc: "Der Schwarm kann sich im Bereich einer anderen Kreatur aufhalten und andersherum. Der Schwarm kann sich durch jede Öffnung bewegen, die groß genug für eine winzige Ratte ist. Der Schwarm kann keine Trefferpunkte zurückerhalten und keine temporären Trefferpunkte erhalten"
actions:
  - name: Biss
    desc: "_Nahkampf-Waffenangriff:_ +2, Reichweite 0m, ein Ziel im Bereich des Schwarms. _Treffer:_ 7 (`dice: 2d6`) Stichschaden oder 3 (`dice: 1d6`) Stichschaden, wenn der Schwarm die Hälfte seiner Trefferpunkte oder weniger besitzt."
    attack_bonus: 2
    damage_dice: 2d6
    damage_bonus: 0
    alternate_damage:
      condition: "bei ≤ ½ TP"
      damage_dice: "1d6"
      damage_bonus: 0
```