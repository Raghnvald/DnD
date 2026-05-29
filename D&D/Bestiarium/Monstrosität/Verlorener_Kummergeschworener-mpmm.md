---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Verlorener Kummergeschworener
Kategorie: Monstrosität
Größe: Mittelgroß
HG: 7
Habitat:
  - Arktis
  - Berg
  - Stadt
  - Sumpf
  - Unterreich
  - Wald
  - Wüste
image: token/lost-sorrowsworn-mpmm.webp
status: completed
linter-yaml-title-alias: Verlorener Kummergeschworener
tags:
  - Monster/Größe/Mittelgroß
  - Monster/Habitat/Arktis
  - Monster/Habitat/Berg
  - Monster/Habitat/Stadt
  - Monster/Habitat/Sumpf
  - Monster/Habitat/Unterreich
  - Monster/Habitat/Wald
  - Monster/Habitat/Wüste
  - Monster/HG/7
  - Monster/Typ/Monstrosität
  - Quelle/5e/mpmm
  - Quelle/5e/veor
aliases:
  - Lost Sorrowsworn
  - Verlorener Kummergeschworener
---
# Verlorener Kummergeschworener
*Quelle: Mordenkainen präsentiert: Monster des Multiversums S. 167*  

Das Schattenfell verwirrt Besucher, bis sie in seiner verdrehten Landschaft festsitzen. Verlorene Kummergeschworene - oft als Verlorene bezeichnet - repräsentieren die Sorge und Furcht, die verirrte Personen erleben. Diese Kummergeschworenen wirken verzweifelt und panisch.

Verlorene Kummergeschworene greifen nach allen Kreaturen in ihrer Reichweite. Das Opfer erlebt eine Woge aus Furcht und Panik, während sein Verstand unter der Wucht dieses Angriffs zusammenbricht.Je mehr die Verbündeten eines Opfers kämpfen, um es aus der Umklammerung zu befreien, desto mehr leidet das Opfer.

## Kummergeschworener

Die durchdringende Melancholie des Schattenfells führt manchmal zu seltsamen Inkarnationen der trostlosen Natur der Ebene. Kummergeschworene verkörpern die Formen des Leidens, die der schattenhaften Landschaft innewohnen, und verbreiten Grauen bei denen, die in ihre Mitte stolpern. Jeder Kummergeschworene verkörpert einen anderen Aspekt der Verzweiflung oder des Elends.

```statblock
name: Verlorener Kummergeschworener
image: token/lost-sorrowsworn-mpmm.webp
source:
  - MPMM
size: Mittelgroß
type: Monstrosität
alignment: normalerweise Neutral böse
ac: 15
ac_class: natürliche Rüstung
hp: 78
hit_dice: 12d8 + 24
modifier: 1
stats:
  - 17
  - 12
  - 15
  - 6
  - 7
  - 5
speed: 9 m
skillsaves:
  - name: <STATBLOCK-MARKDOWN-LINK>01-Spielleiter/Fertigkeiten-phb#Athletik|Athletik<STATBLOCK-MARKDOWN-LINK>
    desc: "+6"
damage_resistances: Hieb, Stich und Wucht bei dämmrigem Licht oder Dunkelheit
senses: <STATBLOCK-MARKDOWN-LINK>Sinne-phb#Dunkelsicht|Dunkelsicht<STATBLOCK-MARKDOWN-LINK> 18 m, Passive Wahrnehmung 8
languages: Gemeinsprache
cr: "7"
environment: Arktis, Berg, Stadt, Sumpf, Unterreich, Wald, Wüste
actions:
  - name: Mehrfachangriff
    desc: Der Verlorene Kummergeschworene führt zwei Armstachel-Angriffe aus.
  - name: Armstachel
    desc: "*Nahkampf-Waffenangriff:* +6 aufTreffer, Reichweite 3 m, ein Ziel. *Treffer:* 14 (2d10 + 3) Stichschaden."
  - name: Umarmung (Aufladung 4-6)
    desc: "*Nahkampf-Waffenangriff:* +6 aufTreffer, Reichweite 1,5 m, ein Ziel. *Treffer:* 25 (4d10 + 3) Stichschaden, und das Ziel wird <STATBLOCK-MARKDOWN-LINK>Zustände-phb#gepackt|gepackt<STATBLOCK-MARKDOWN-LINK> (SG zum Entkommen 14) wenn es sich um eine höchstens mittelgroße Kreatur handelt. Ein gepacktes Ziel ist <STATBLOCK-MARKDOWN-LINK>Zustände-phb#verängstigt|verängstigt<STATBLOCK-MARKDOWN-LINK> und erleidet am Ende jedes seiner Züge 27 (6d8) psychischen Schaden. Der Verlorene Kummergeschworene kann jeweils nur eine Kreatur gleichzeitig packen."
reactions:
  - name: Einengende Umarmung
    desc: Wenn der Verlorene Kummergeschworene Schaden erleidet, erleidet die von der Umarmung <STATBLOCK-MARKDOWN-LINK>Zustände-phb#gepackt|gepackte<STATBLOCK-MARKDOWN-LINK> Kreatur 18 (4d8) psychischen Schaden.
```
^statblock