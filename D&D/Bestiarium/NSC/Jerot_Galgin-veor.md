---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Jerot Galgin
Kategorie: Humanoid
Größe: Mittelgroß
HG: 9
Habitat: /
image: token/jerot-galgin-veor.webp
status: WIP
tags:
  - Monster/Größe/Mittelgroß
  - Monster/HG/9
  - Monster/Typ/Humanoid
  - Quelle/5e/veor
aliases:
  - Jerot Galgin
linter-yaml-title-alias: Jerot Galgin
---
# Jerot Galgin
*Quelle: Vecna: Vorabend der Verdammnis*  

```statblock
name: Jerot Galgin
image: token/jerot-galgin-veor.webp
source:
  - VEoR
size: Mittelgroß
type: Humanoid
alignment: jede Gesinnung
ac: 12
ac_class: 15 mit <STATBLOCK-MARKDOWN-LINK>Magierrüstung-phb|Magierrüstung<STATBLOCK-MARKDOWN-LINK>
hp: 110
hit_dice: 20d8 + 20
modifier: 2
stats:
  - 9
  - 14
  - 12
  - 17
  - 12
  - 11
speed: 9 m
saves:
  - Intelligenz: 7
  - Weisheit: 5
skillsaves:
  - name: <STATBLOCK-MARKDOWN-LINK>Fertigkeiten-phb#Arkane%20Kunde|Arkane Kunde<STATBLOCK-MARKDOWN-LINK>
    desc: "+7"
  - name: <STATBLOCK-MARKDOWN-LINK>Fertigkeiten-phb#Geschichte|Geschichte<STATBLOCK-MARKDOWN-LINK>
    desc: "+7"
damage_resistances: Nekrotisch
senses: passive Wahrnehmung 11
languages: Vier beliebige Sprachen
cr: "9"
actions:
  - name: Mehrfachangriff
    desc: Jerot führt drei Arkane-Explosion-Angriffe aus. 
  - name: Arkane Explosion
    desc: "*Nahkampf- oder Fernkampf-Zauberangriff:* +7 auf Treffer, Reichweite 1,5 m oder 36 m, ein Ziel. *Treffer:* 25 (4d10 + 3) nekrotischer Schaden."
  - name: Zauberwirken
    desc: |-
      Jerot wirkt einen der folgenden Zauber und verwendet Intelligenz als Attribut zum Zauberwirken (SG-15-Zauberrettungswurf): 

      **Beliebig oft:** <STATBLOCK-MARKDOWN-LINK>Magierhand-phb|Magierhand<STATBLOCK-MARKDOWN-LINK>, <STATBLOCK-MARKDOWN-LINK>Tanzende_Lichter-phb|Tanzende Lichter<STATBLOCK-MARKDOWN-LINK>, <STATBLOCK-MARKDOWN-LINK>Taschenspielerei-phb|Taschenspielerei<STATBLOCK-MARKDOWN-LINK>

      **jeweils 2/Tag:** <STATBLOCK-MARKDOWN-LINK>Dimensionstür-phb|Dimensionstür<STATBLOCK-MARKDOWN-LINK>, <STATBLOCK-MARKDOWN-LINK>Fluch-phb|Fluch<STATBLOCK-MARKDOWN-LINK>, <STATBLOCK-MARKDOWN-LINK>Magierrüstung-phb|Magierrüstung<STATBLOCK-MARKDOWN-LINK>, <STATBLOCK-MARKDOWN-LINK>Spinnennetz-phb|Spinnennetz<STATBLOCK-MARKDOWN-LINK>

      **jeweils 1/Tag:** <STATBLOCK-MARKDOWN-LINK>Todeskreis-phb|Todeskreis<STATBLOCK-MARKDOWN-LINK>
bonus_actions:
  - name: Untote beschwören (1/Tag)
    desc: Jerot verwendet Magie, um fünf <STATBLOCK-MARKDOWN-LINK>Skelett-mm|Skelette<STATBLOCK-MARKDOWN-LINK> oder <STATBLOCK-MARKDOWN-LINK>Zombie-mm|Zombies<STATBLOCK-MARKDOWN-LINK> zu beschwören. Die beschworenen Kreaturen erscheinen in einem freien Bereich innerhalb von 18 Metern von Jerot und gehorchen seinen Befehlen. Ihre Züge geschehen direkt nach dem Jerots. Jede Kreatur bleibt eine Stunde lang bestehen, bis sie oder der Nekromant stirbt, oder bis der Nekromant sie als Bonusaktion entlässt. 
reactions:
  - name: Grausame Ernte
    desc: "Wenn Jerot eine Kreatur mit nekrotischem Schaden tötet, erhält der Nekromant 9 (2d8) Trefferpunkte zurück. "
```
^statblock