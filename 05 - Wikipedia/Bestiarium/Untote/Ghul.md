---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- Quelle/5e/MM
- Habitat/Unterreich
- Habitat/Stadt
- Habitat/Sumpf
- Größe/Mittelgroß
- Typ/Untote
aliases: ["Ghoul"]
---
```statblock
statblock: true
name: Ghul
image: [[Ghoul.png]]
source: Grundregelwerk
size: Mittelgroß
type: Untoter
alignment: chaotisch böse
ac: 12
hp: 22
hit_dice: 5d8
speed: 9 Meter.
stats: [13, 15, 10, 7, 10, 6]
skillsaves:
  - Heimlichkeit: 6
damage_vulnerabilities: ""
damage_resistances: ""
damage_immunities: "Gift"
condition_immunities: "n Bezaubert, Erschöpft, Vergiftet"
senses: Dunkelsicht 18 Meter, passive Wahrnehmung 10
languages: Gemeinsprache
cr: 1
environment: Stadt, Sümpfe, Unterreich
bestiary: true
actions:
  - name: Biss
    desc: "Nahkampfwaffenangriff: +2 auf Treffer, Reichweite 1,5 m, eine Kreatur. Treffer: 9 (`2W6+2`) Stichschaden."
    attack_bonus: 2
    damage_dice: 2d6
    damage_bonus: 2
  - name: Klauen
    desc: "Nahkampfwaffenangriff: +4 auf Treffer, Reichweite 1,5 m, ein Ziel. Treffer: 7 (`2W4+2`) Hiebschaden. Falls das Ziel eine Kreatur ist, aber kein Elf oder Untoter, muss es einen Konstitutions-Rettungswurf (SG 10) bestehen, um nicht eine Minute lang gelähmt zu werden. Das Ziel kann den Rettungswurf am Ende jedes seiner Züge wiederholen und den Effekt bei einem Erfolg beenden."
    attack_bonus: 4
    damage_dice: 2d4
    damage_bonus: 2
```