---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Priester
Kategorie: Humanoid
Größe: Mittelgroß
HG: 2
Habitat:
  - Stadt
image:
status: completed
tags:
  - Monster/Größe/Mittelgroß
  - Monster/Habitat/Stadt
  - Monster/HG/2
  - Monster/Typ/Humanoid/any-race
  - Quelle/5e/mm
aliases:
  - Priest
---
# Priester
*Quelle: Monsterhandbuch S. 349. Verfügbar im <span title='Systems Reference Document (5.1)'>SRD</span> und dem Grundregelwerk (2014)*  

Priester bringen dem einfachen Volk die Lehren ihres Gottes. Sie sind die spirituellen Führer von Tempeln und Schreinen und haben oft einflussreiche Positionen in ihren Gemeinschaften inne. Böse Priester könnten offen unter einem Tyrannen auftreten, oder sie könnten die Anführer religiöser Sekten sein, die sich im Schatten einer Gesellschaft guter Gesinnung verbergen und verkommene Riten überwachen.

Ein Priester hat normalerweise einen oder mehrere Akolythen, die ihn bei religiösen Zeremonien und anderen heiligen Pflichten unterstützen.

```statblock
name: Priester
image: token/priest.webp
source:
  - MM
size: Mittelgroß
type: Humanoid
subtype: jedes Volk
alignment: jede Gesinnung
ac: 13
ac_class: <STATBLOCK-MARKDOWN-LINK>Gegenstände/Kettenhemd-phb|Kettenhemd<STATBLOCK-MARKDOWN-LINK>
hp: 27
hit_dice: 5d8 + 5
modifier: 0
stats:
  - 10
  - 10
  - 12
  - 13
  - 16
  - 13
speed: 9 m
skillsaves:
  - name: <STATBLOCK-MARKDOWN-LINK>01-Spielleiter/Fertigkeiten-phb#Heilkunde|Heilkunde<STATBLOCK-MARKDOWN-LINK>
    desc: "+7"
  - name: <STATBLOCK-MARKDOWN-LINK>01-Spielleiter/Fertigkeiten-phb#Religion|Religion<STATBLOCK-MARKDOWN-LINK>
    desc: "+5"
  - name: <STATBLOCK-MARKDOWN-LINK>01-Spielleiter/Fertigkeiten-phb#Überzeugen|Überzeugen<STATBLOCK-MARKDOWN-LINK>
    desc: "+3"
senses: passive Wahrnehmung 13
languages: zwei Sprachen nach Wahl
cr: "2"
environment: Stadt
traits:
  - name: Göttliche Eminenz
    desc: Als Bonusaktion kann der Priester einen Zauberplatz aufwenden, damit seine Nahkampfwaffen bei einem Treffer dem Ziel auf magische Weise zusätzlich 10 (3d6) gleißenden Schaden zufügen. Dieser Vorteil hält bis zum Ende des nächsten Zugs an. Wenn der Priester einen Zauberplatz des 2. oder höheren Grades verwendet, steigt der Schaden um 1d6 für jeden Zauberplatz nach dem ersten.
  - name: Zauberwirken
    desc: |-
      Der Priester ist ein Zauberwirker der 5. Stufe. Sein Attribut zum Zauberwirken ist Weisheit (Zauberrettungswurf-SG 13, +5 zum Treffen mit Zauberangriffen). Der Priester hat die folgenden Klerikerzauber vorbereitet:

      **Zaubertricks (beliebig oft):** <STATBLOCK-MARKDOWN-LINK>Heilige_Flamme-phb|Heilige Flamme<STATBLOCK-MARKDOWN-LINK>, <STATBLOCK-MARKDOWN-LINK>Licht-phb|Licht<STATBLOCK-MARKDOWN-LINK>, <STATBLOCK-MARKDOWN-LINK>Thaumaturgie-phb|Thaumaturgie<STATBLOCK-MARKDOWN-LINK>

      **1. Grad (4 Plätze):** <STATBLOCK-MARKDOWN-LINK>Heiligtum-phb|Heiligtum<STATBLOCK-MARKDOWN-LINK>, <STATBLOCK-MARKDOWN-LINK>Lenkendes_Geschoss-phb|Lenkendes Geschoss<STATBLOCK-MARKDOWN-LINK>, <STATBLOCK-MARKDOWN-LINK>Wunden_heilen-phb|Wunden heilen<STATBLOCK-MARKDOWN-LINK>

      **2. Grad (3 Plätze):** <STATBLOCK-MARKDOWN-LINK>Schwache_Genesung-phb|Schwache Genesung<STATBLOCK-MARKDOWN-LINK>, <STATBLOCK-MARKDOWN-LINK>Waffe_des_Glaubens-phb|Waffe des Glaubens<STATBLOCK-MARKDOWN-LINK>

      **3. Grad (2 Plätze):** <STATBLOCK-MARKDOWN-LINK>Magie_bannen-phb|Magie bannen<STATBLOCK-MARKDOWN-LINK>, <STATBLOCK-MARKDOWN-LINK>Schutzgeister-phb|Schutzgeister<STATBLOCK-MARKDOWN-LINK>
actions:
  - name: Streitkolben
    desc: "*Nahkampf-Waffenangriff:* +2 zum Treffen, Reichweite 1,5 m, ein Ziel. *Treffer:* 3 (1d6) Wuchtschaden."
```
^statblock