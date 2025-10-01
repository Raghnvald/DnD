---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- Quelle/5e/MM
- Habitat/Wald
- Habitat/Grasland
- Habitat/Hügel
- Größe/Mittelgroß
- Typ/Bestie
aliases: ["Wolf"]
---
```statblock
statblock: true
name: Wolf
image: [[Wolf.png]]
source: Grundregelwerk
size: Medium
type: Bestie 
alignment: ohne Gesinnung
ac: 13
hp: 11
hit_dice: 2d8+2
speed: 12 Meter.
stats: [12, 15, 12, 3, 12, 6]
skillsaves:
  - Heimlichkeit: 4
  - Wahrnehmung: 3
damage_vulnerabilities: ""
damage_resistances: ""
damage_immunities: ""
condition_immunities: ""
senses: passive Wahrnehmung 13
languages:
cr: 1/4
environment: Wälder, Grasland, Hügel
bestiary: true
traits:
  - name: Scharfes Gehör und scharfer Geruchssinn
    desc: Der Wolf hat Vorteil bei Proben auf Weisheit(Wahrnehmung), die auf Gehör oder Geruch beruhen.
  - name: Rudeltaktik
    desc: Der Wolf hat Vorteil bei Angriffswürfen gegen eine Kreatur, wenn sich mindestens ein Verbündeter des Wolfs im Umkreis von 1,5 Metern um die Kreatur befindet und der Verbündete nicht außer Gefecht gesetzt ist.
actions:
  - name: Biss
    desc: "Nahkampfangriff: +4 zum Treffen, Reichweite 1,5m, ein Ziel. Treffer: 7 (2W4 + 2) Stichschaden. Handelt es sich bei dem Ziel um eine Kreatur, muss sie einen SG 11 Rettungswurf auf Stärke bestehen oder wird niedergeschmettert."
    attack_bonus: 4
    damage_dice: 2d4
    damage_bonus: 2
```