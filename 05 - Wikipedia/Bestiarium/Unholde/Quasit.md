---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- Quelle/5e/MM
- Größe/Winzig
- Typ/Unhold/Dämon
aliases: ["Quasit"]
---
```statblock
statblock: true
name: Quasit (2014)
image: [[Quasit.png]]
source: Monsterhandbuch 2014
size: Klein
type: Unhold
alignment: Chaotisch böse
ac: 13
hp: 7
hit_dice: 3d4
speed: 12 Meter.
stats: [5, 17, 10, 7, 10, 10]
skillsaves:
  - Heimlichkeit: 5
damage_vulnerabilities: ""
damage_resistances: "Blitz, Feuer, Kälte; Hieb, Stich und Wucht durch nichtmagische Angriffe"
damage_immunities: "Gift"
condition_immunities: "Vergiftet"
senses: Dunkelsicht 36 Meter, passive Wahrnehmung 10
languages: Abyssisch, Gemeinsprache
cr: 1
bestiary: true
traits:
  - name: Gestaltwandler
    desc: "Der Quasit kann seine Aktion verwenden, um sich in eine Tiergestalt wie eine Fledermaus (Bewegungsrate 3 m, Fliegen 12 m), eine Kröte (12 m, Schwimmen 12 m), einen Tausendfüßler (12 m, Klettern 12 m) oder zurück in seine wahre Gestalt zu verwandeln. Seine Spielwerte sind in allen Gestalten bis auf die angegebenen Bewegungsraten gleich. Ausrüstung, die er trägt oder hält, wird nicht verwandelt. Wenn er stirbt, nimmt er seine wahre Gestalt an."
    attack_bonus: 0
  - name: Magieresistenz
    desc: "Der Quasit ist bei Rettungswürfen gegen Zauber und andere magische Effekte im Vorteil."
    attack_bonus: 0
actions:
  - name: Klauen (Biss in Tiergestalt)
    desc: "Nahkampfwaffenangriff: +4 auf Treffer, Reichweite 1,5 m, ein Ziel. Treffer: 5 (`1W4+3`) Stichschaden, und das Ziel muss einen Konstitutions-Rettungswurf (SG 10) bestehen, oder es erleidet 5 (`2W4`) Giftschaden und ist eine Minute lang vergiftet. Das Ziel kann den Rettungswurf am Ende jedes seiner Züge wiederholen und den Effekt bei einem Erfolg beenden."
    attack_bonus: 4
    damage_dice: 1d4
    damage_bonus: 3
  - name: Unsichtbarkeit
    desc: "Der Quasit wird magisch unsichtbar, bis er angreift, Verängstigen einsetzt, oder bis seine Konzentration endet (wie bei einem Zauber). Ausrüstung, die der Quasit trägt oder hält, ist ebenfalls unsichtbar."
  - name: Verängstigen (1-mal täglich)
    desc: "Eine Kreatur nach Wahl des Quasiten im Abstand von bis zu sechs Metern von ihm muss einen SG-10-Weisheitsrettungswurf bestehen, oder sie ist eine Minute lang verängstigt. Das Ziel kann den Rettungswurf am Ende jedes seiner Züge wiederholen. Wenn der Quasit in Sichtlinie ist, so ist der Rettungswurf im Nachteil. Bei einem Erfolg endet der Effekt."
```