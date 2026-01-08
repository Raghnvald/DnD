---
cssclasses:
  - json5e-monster
tags:
  - Quelle/5e/mm
  - Monster/HG/2
  - Monster/Habitat/Wüste
  - Monster/Habitat/Wald
  - Monster/Habitat/Sumpf
  - Monster/Habitat/Unterreich
  - Monster/Habitat/underwater
  - Monster/Größe/Riesig
  - Monster/Typ/Tier
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Giant Constrictor Snake
---
# Riesenwürgeschlange
*Quelle: Monsterhandbuch S. 324. Available in the <span title='Systems Reference Document (5.1)'>SRD</span> and the Basic Rules (2014)*  

```statblock
name: Riesenwürgeschlange
image: token/giant-constrictor-snake.webp
source: Monsterhandbuch 2014
size: "Riesig"
type: "Tier"
alignment: "gesinnungslos"
ac: !!int "12"
hp: !!int "60"
hit_dice: "8d12 + 8"
modifier: !!int "2"
stats:
  - !!int "19"
  - !!int "14"
  - !!int "12"
  - !!int "1"
  - !!int "10"
  - !!int "3"
speed: "9 Meter, schwimmen 9 Meter"
skillsaves:
  - "name": "[Wahrnehmung](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+2"
senses": "Blindsicht 3 m, passive Wahrnehmung 12"
languages: ""
cr: "2"
actions:
  - name: Biss
    desc: "_Nahkampf-Waffenangriff:_ +6 zum Treffen, Reichweite 3 m, eine Kreatur. _Treffer:_ 11 (2W6 + 4) Stichschaden."
  - name: Umschlingen
    desc: "_Nahkampf-Waffenangriff:_ +6 zum Treffen, Reichweite 1,5 m, eine Kreatur. _Treffer:_ 13 (2W8 + 4) Wuchtschaden, und das Ziel ist gepackt (SG zum Entkommen 16). Bis der Haltegriff endet, ist die Kreatur festgesetzt, und die Schlange kann kein anderes Ziel umschlingen."

```
^statblock