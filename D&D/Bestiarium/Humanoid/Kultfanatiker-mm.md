---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Kultfanatiker
Kategorie: Humanoide
Größe: Mittelgroß
HG: 2
Habitat:
  - Stadt
image: token/cult-fanatic.webp
status: completed
tags:
  - Monster/Größe/Mittelgroß
  - Monster/Habitat/Stadt
  - Monster/HG/2
  - Monster/Typ/Humanoid/any-race
  - Quelle/5e/egw
  - Quelle/5e/mm
aliases:
  - Cult Fanatic
---
# Kultfanatiker
*Quelle: Monsterhandbuch S. 347, Explorer's Guide to Wildemount. Verfügbar im <span title='Systems Reference Document (5.1)'>SRD</span>*  

Fanatiker sind oft Teil der Führungsriege eines Kults. Sie nutzen ihr Charisma und Dogma, um alle, die einen schwächeren Willen haben, zu beeinflussen und auszunutzen. Die meisten sind vor allem an persönlicher Macht interessiert. 

```statblock
name: Kultfanatiker
image: Humanoid/token/cult-fanatic.webp
source:
  - MM
  - EGW
size: Mittelgroß
type: Humanoid
subtype: jedes Volk
alignment: jede nicht gute Gesinnung
ac: 13
ac_class: <STATBLOCK-MARKDOWN-LINK>Gegenstände/Lederrüstung-phb|Lederrüstung<STATBLOCK-MARKDOWN-LINK>
hp: 33
hit_dice: 6d8 + 6
modifier: 2
stats:
  - 11
  - 14
  - 12
  - 10
  - 13
  - 14
speed: 9 m
skillsaves:
  - name: Religion
    desc: "+2"
  - name: Täuschen
    desc: "+4"
  - name: Überzeugen
    desc: "+4"
senses: passive Wahrnehmung 11
languages: eine Sprache nach Wahl (normalerweise Gemeinsprache)
cr: "2"
environment: Stadt
traits:
  - name: Dunkle Hingabe
    desc: Der Fanatiker hat einen Vorteil auf Rettungswürfe gegen die Zustände bezaubert und verängstigt. 
  - name: Zauberwirken
    desc: |-
      Der Fanatiker ist ein Zauberwirker der 4. Stufe. Sein Attribut zum Zauberwirken ist Weisheit (Zauberrettungswurf-SG 11, +3 zum Treffen mit Zauberangriffen). Der Fanatiker hat die folgenden Klerikerzauber vorbereitet:

      **Zaubertricks (beliebig oft):** Heilige Flamme, Licht, Thaumaturgie

      **1. Grad (4 Plätze):** Befehl, Schild des Glaubens, Wunden verursachen

      **2. Grad (3 Plätze):** Person festhalten, Spirituelle Waffe
actions:
  - name: Mehrfachangriff
    desc: Der Fanatiker führt zwei Nahkampfangriffe durch. 
  - name: Dolch
    desc: "*Nahkampf- oder Fernkampf-Waffenangrif:* +4 zum Treffen, Reichweite 1,5 m oder Reichweite 6/18 m, eine Kreatur. *Treffer:* 4 (1d4 + 2) Stichschaden."
```
^statblock