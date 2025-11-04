---
cssclasses: json5e-monster
tags:
  - Quelle/5e/Monster_Manual
  - Monster/Habitat/Wald
  - Monster/Habitat/Grasland
  - Monster/Habitat/Unterreich
  - Monster/Größe/Mittelgroß
  - Monster/Typ/Humanoid/Goblinoid
aliases:
  - Bugbear
Typ: Humanoid
---
```statblock
statblock: true
name: Grottenschrat
image: [[Grottenschrat.png]]
source: Grundregelwerk
size: Medium
type: humanoid
subtype: goblinoid
alignment: chaotisch böse
ac: 16
hp: 27
hit_dice: 5d8+5
speed: 9 Meter.
stats: [15, 14, 13, 8, 11, 9]
skillsaves:
  - Heimlichkeit: 6
  - Überleben: 2
damage_vulnerabilities: ""
damage_resistances: ""
damage_immunities: ""
condition_immunities: ""
senses: Dunkelsicht 18 Meter, passive Wahrnehmung 10
languages: Gemeinsprache, Goblin
cr: 1
environment: Wald, Grasland, Unterreich
bestiary: true
traits:
  - name: Wüstling
    desc: "Eine Nahkampfwaffe fügt einen zusätzlichen Würfel ihres Schadens zu, wenn der Grottenschrat mit ihr trifft (im Angriff enthalten)."
    attack_bonus: 0
  - name: Überraschungsangriff
    desc: "Wenn der Grottenschrat eine Kreatur überrascht und sie in der ersten Runde des Kampfes mit einem Angriff trifft, erleidet das Ziel zusätzlich 7 (2W6) Schaden durch den Angriff."
    attack_bonus: 0
actions:
  - name: Morgenstern
    desc: "Nahkampfangriff: +4 zum Treffen, Reichweite 1,5m, ein Ziel. Treffer: 11 (2W8 + 2) Stichschaden."
    attack_bonus: 4
    damage_dice: 2d8
    damage_bonus: 2
  - name: Wurfspeer
    desc: "Nah- oder Fernkampfangriff: +4 zum Treffen, Reichweite 1,5m oder 30m/36m, ein Ziel. Treffer: 9 (2W6+2) Stichschaden im Nahkampf oder 5 (1W6 + 2) Stichschaden im Fernkampf."
    attack_bonus: 4
    damage_dice: 1d6
    damage_bonus: 2
```