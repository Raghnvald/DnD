---
prefer-view: edit-source read
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Violetter Pilz
Kategorie: Pflanze
Größe: Mittelgroß
HG: 1/4
Habitat:
  - Unterreich
Status: WIP
linter-yaml-title-alias: Violetter Pilz
tags:
  - Monster/Größe/Mittelgroß
  - Monster/Habitat/Unterreich
  - Monster/HG/1-4
  - Monster/Typ/Pflanze
  - Quelle/5e/mm
aliases:
  - Violet Fungus
  - Violetter Pilz
image: token/violet-fungus.webp
status: completed
---
# Violetter Pilz
*Quelle: Monsterhandbuch S. 220. Verfügbar im <span title='Systems Reference Document (5.1)'>SRD</span>*  

Dieser leicht violette Pilz nutzt wurzelartige Fühler, die aus seinem Fuß wachsen, um über Höhlenböden zu kriechen. Die vier Stiele, die aus der zentralen Masse eines Violetten Pilzes wachsen, werden verwendet, um nach Beute zu schlagen und deren Fleisch mit der leisesten Berührung verrotten zu lassen. Jede Kreatur, die von einem Violetten Pilz getötet wird, verwest ausgesprochen schnell. Ein neuer Violetter Pilz wächst aus der schimmelnden Leiche und wächst innerhalb von `2W6` Tagen zur vollständigen Größe heran.

## Pilze

Das Unterreich, mit seinem Himmel aus schroffem Stein und seiner ewigen Dunkelheit, ist Heimat für viele Arten von Pilzen. Pilze nehmen in diesem unterirdischen Reich die Rolle von Pflanzen ein und sind entscheidend für das Überleben vieler unterirdischer Spezies. Sie stellen in der unbarmherzigen Finsternis Nahrung und Zuflucht dar.

$\quad$Pilze wachsen auf organischer Materie und zersetzen sie, um sie zu verzehren. Sie ernähren sich von Abfall und Kadavern. Wenn Pilze wachsen, geben sie Sporen ab, die auf der leichtesten Brise davonschweben und neue Pilze erschaffen.

$\quad$Pilze brauchen weder Sonnenlicht noch Wärme, um zu wachsen, und gedeihen in jeder Ecke und Nische des Unterreichs.

$\quad$Die Pilze des Unterreichs werden von der Magie verwandelt, die dieses unterirdische Reich erfüllt, und oft entwickeln sie dadurch mächtige Verteidigungsmechanismen oder die Fähigkeiten der Nachahmung und des Angriffs. Die größten Exemplare können sich ausbreiten, um gigantische unterirdische Wälder zu erschaffen, in denen zahllose Kreaturen leben und sich ernähren können.

```statblock
name: Violetter Pilz
image: token/violet-fungus.webp
source: MM
size: Mittelgroß
type: Pflanze
alignment: gesinnungslos
ac: 5
hp: 18
hit_dice: 4d8
modifier: -5
stats:
  - 3
  - 1
  - 10
  - 1
  - 3
  - 1
speed: 1,5 m
condition_immunities: <STATBLOCK-MARKDOWN-LINK>01-Spielleiter/Zustände-phb#Blind|Blind<STATBLOCK-MARKDOWN-LINK>, <STATBLOCK-MARKDOWN-LINK>01-Spielleiter/Zustände-phb#Taub|Taub<STATBLOCK-MARKDOWN-LINK>, <STATBLOCK-MARKDOWN-LINK>01-Spielleiter/Zustände-phb#Verängstigt|Verängstigt<STATBLOCK-MARKDOWN-LINK>
senses: <STATBLOCK-MARKDOWN-LINK>01-Spielleiter/Sinne-phb#Blindsicht|Blindsicht<STATBLOCK-MARKDOWN-LINK> 9 m (darüber hinaus blind), passive Wahrnehmung 6
languages: 
cr: 1/4
traits:
  - name: Falsches Erscheinungsbild
    desc: Wenn der Violette Pilz bewegungslos bleibt, ist er nicht von einem normalen Pilz zu unterscheiden.
actions:
  - name: Mehrfachangriff
    desc: Der Fungus führt 1W4 Angriffe mit Verfaulende Berührung durch.
  - name: Verfaulende Berührung
    desc: "*Nahkampf-Waffenangriff:* +2 zum Treffen, Reichweite 3 m, ein Ziel. *Treffer:* 4 (1d8) nekrotischer Schaden."
```
^statblock

## Vorkommen

Unterreich