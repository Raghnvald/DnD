---
cssclasses: dnd5e-only-statblock
prefer-view: edit-source read
Name: Blutmücke
Kategorie: Tier
Größe: Winzig
HG: 1/8
Habitat:
  - Berg
  - Grasland
  - Hügel
  - Küste
  - Stadt
  - Sumpf
  - Unterreich
  - Wald
  - Wüste
status: completed
image: image/stirge.webp
tags:
  - Quelle/5e/mm
  - Monster/HG/1-8
  - Monster/Größe/Winzig
  - Monster/Habitat/Berg
  - Monster/Habitat/Grasland
  - Monster/Habitat/Hügel
  - Monster/Habitat/Küste
  - Monster/Habitat/Stadt
  - Monster/Habitat/Sumpf
  - Monster/Habitat/Unterreich
  - Monster/Habitat/Wald
  - Monster/Habitat/Wüste
  - Monster/Typ/Tier
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Stirge
---
# Blutmücke
*Quelle: Monsterhandbuch S. 284. Verfügbar im <span title='Systems Reference Document (5.1)'>SRD</span> und dem Grundregelwerk (2014)*  

Diese grässlichen Kreaturen sehen aus wie eine Mischung aus einer großen Fledermaus und einem übergroßen Moskito. Ihre Beine enden in scharfen Zangen, und ihr langer, nadelartiger Saugrüssel zischt durch die Luft, wenn sie ihre nächste Mahlzeit sucht.

$\quad$Blutmücken ernähren sich vom Blut lebender Kreaturen, indem sie sich an ihnen anheften und sie langsam aussaugen. Auch wenn sie kleiner Zahl nicht besonders gefährlich sind, können große Rudel von Blutmücken eine beträchtliche Bedrohung darstellen, da sie sich so schnell anhaften, wie ihre schwächer werdende Beute sie abreißen kann.

## Blut aussaugen

Eine Blutmücke greift an, indem sie auf dem Opfer landet, einen verwundbaren Punkt' findet und den Saugrüssel ins Fleisch versenkt, während sie ihre scherenartigen Beine nutzt, um sich am Opfer festzukrallen. Sobald die Blutmücke satt ist, löst sie sich und fliegt davon, um ihre Mahlzeit zu verdauen.

```statblock
name: Blutmücke
image: token/stirge.webp
source:
  - MM
  - EGW
size: Winzig
type: Tier
alignment: gesinnungslos
ac: 14
ac_class: natürliche Rüstung
hp: 2
hit_dice: 1d4
modifier: 3
stats:
  - 4
  - 16
  - 11
  - 2
  - 8
  - 6
speed: 3 Meter, Fliegen 12 Meter
senses: <STATBLOCK-MARKDOWN-LINK>01-Spielleiter/Sinne-phb#Dunkelsicht|Dunkelsicht<STATBLOCK-MARKDOWN-LINK> 18 Meter, passive Wahrnehmung 9
languages: 
cr: 1/8
actions:
  - name: Blut aussaugen
    desc: |-
      *Nahkampf-Waffenangriff:* +5 zum Treffen, Reichweite 1,5 m, ein Ziel. *Treffer:* 5 (1d4+3) Wuchtschaden, und die Blutmücke heftet sich an das Ziel an. Solange die Blutmücke angeheftet ist, greift sie nicht an. Stattdessen verliert das Ziel zu Beginn eines jeden Zugs der Blutmücke 5 (1d4+3) Trefferpunkte aufgrund des Blutverlusts.

      Die Blutmücke kann sich lösen, indem sie 1,5 m ihrer Bewegung verwendet. Das tut sie, nachdem sie 10 Trefferpunkte an Blut ausgesaugt hat oder wenn das Ziel stirbt. Eine Kreatur, auch das Ziel, kann eine Aktion verwenden, um die Blutmücke zu lösen.
```
^statblock

## Vorkommen

Berg, Grasland, Hügel, Küste, Stadt, Sumpf, Unterreich, Wald, Wüste