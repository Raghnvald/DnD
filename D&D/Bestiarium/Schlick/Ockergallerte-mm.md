---
prefer-view: edit-source read
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Ockergallerte
Kategorie: Schleim
Größe: Groß
HG: 2
Habitat:
  - Unterreich
image: image/ocre-jelly-webp
status: completed
linter-yaml-title-alias: Ockergallerte
tags:
  - Monster/Größe/Groß
  - Monster/Habitat/Unterreich
  - Monster/HG/2
  - Monster/Typ/Schleim
  - Quelle/5e/mm
aliases:
  - Ochre Jelly
  - Ockergallerte
---
# Ockergallerte
*Quelle: Monsterhandbuch S. 250. Verfügbar im <span title='Systems Reference Document (5.1)'>SRD</span> und dem Grundregelwerk (2014)*  

Ockergallerten sind gelbliche Blobs, die unter Türen und durch schmale Spalten gleiten können, um Kreaturen zu verfolgen und zu verschlingen. Sie haben genug tierhafte Intelligenz, um große Gruppen von Gegnern zu meiden. Eine Ockergallerte folgt in sicherer Entfernung, während sie ihre Beute jagt. Ihre Verdauungsenzyme löschen Fleisch schnell auf, haben aber keinen Effekt auf andere Substanzen wie Knochen, Holz und Metall.

## Schlicke

Schlicke gedeihen in der Dunkelheit. Sie meiden Orte mit hellem Licht und Temperaturextreme. Sie fließen durch den klammen Untergrund, ernähren sich von allen Kreaturen oder Gegenständen, die aufgelöst werden können, schleichen über den Boden, tropfen von Mauern und Decken, breiten sich über die Ränder unterirdischer Wasserbecken aus und quetschen sich durch enge Spalten. Die erste Warnung, die ein Abenteuer bezüglich der Präsenz eines Schlicks erhält, ist oft der brennende Schmerz seiner Säureberührung.

Schlicke werden von Bewegung und Wärme angelockt. Organische Materialien sind Nahrung für sie, und wenn Beute knapp ist, fressen sie Dreck, Pilze und Abfälle. Erfahrene Entdecker wissen, dass ein makellos sauberer Korridor ein wahrscheinliches Zeichen ist, dass ein Schlick in der Nähe haust.

### Langsamer Tod

Ein Schlick tötet seine Beute langsam. Einige Varianten, wie der Schwarze Blob und der Gallertwürfel, umschlingen Kreaturen, um ihre Flucht zu verhindern. Der einzige Vorteil dieses qualvollen Todes ist, dass die Gefährten des Opfers es retten können, ehe es zu spät ist.

Da nicht jeder Schlickjede Art von Substanz zersetzen kann, haben einige Schlicke Münzen, metallene Ausrüstung, Knochen und andere Überbleibsel in ihren bebenden Körpern schweben. Ein getöteter Schlick kann eine reichhaltige Quelle für Schätze sein.

### Geistlose Diener

Auch wenn ein Schlick nicht die Intelligenz hat, sich mit anderen Kreaturen zu verbünden, könnten andere, die verstehen, dass er fressen muss, ihn an einen Ort locken, wo er nützlich sein kann. Schlaue Monster halten Schlicke in ihrer Nähe, damit sie Korridore bewachen oder Abfälle verzehren. Gleichermaßen kann ein Schlick in eine Grubenfalle gelockt werden, wo ihn seine Fänger häufig genug füttern, sodass er sie nicht angreift. Schlaue Kreaturen stellen Fackeln und lodernde Feuerschalen an strategischen Orten auf, um zu verhindern, dass ein Schlick einen bestimmten Tunnel oder Raum verlässt.

### Brut von Jubilex

Glaubt man dem Demonomicon von Iggwilv und anderen Quellen sind Schlicke verstreute Fragmente oder Nachkommen des Dämonenfürsten Jubilex. Ob dies wahr ist oder nicht, der Gesichtslose Fürst ist eines der wenigen Wesen, die Schlicke kontrollieren und sie mit einer gewissen Intelligenz erfüllen können. Meistens besitzen Schlicke kein Gefühl für Taktik oder Selbsterhaltung. Sie sind direkt und vorhersehbar und greifen ohne jeden Verstand an, um zu fressen. Unter der Kontrolle von Jubilex weisen sie einen Hauch von Bewusstsein und bösartiger Intelligenz auf.

### Schlicknatur

Ein Schlick muss nicht schlafen.

```statblock
name: Ockergallerte
image: token/ochre-jelly.webp
source: MM
size: Groß
type: Schleim
alignment: gesinnungslos
ac: 8
hp: 45
hit_dice: 6d10 + 12
modifier: -2
stats:
  - 15
  - 6
  - 14
  - 2
  - 6
  - 1
speed: 3 Meter, klettern 3 Meter
damage_resistances: Säure
damage_immunities: Blitz, Hieb
condition_immunities: "<STATBLOCK-MARKDOWN-LINK>01-Spielleiter/Zustände-phb#Bezaubert|Bezaubert<STATBLOCK-MARKDOWN-LINK>, <STATBLOCK-MARKDOWN-LINK>01-Spielleiter/Zustände-phb#Blind|Blind<STATBLOCK-MARKDOWN-LINK>, <STATBLOCK-MARKDOWN-LINK>01-Spielleiter/Zustände-phb#Erschöpfung|erschöpft<STATBLOCK-MARKDOWN-LINK>, <STATBLOCK-MARKDOWN-LINK>01-Spielleiter/Zustände-phb#Liegend|Liegend<STATBLOCK-MARKDOWN-LINK>, <STATBLOCK-MARKDOWN-LINK>01-Spielleiter/Zustände-phb#Taub|Taub<STATBLOCK-MARKDOWN-LINK>, <STATBLOCK-MARKDOWN-LINK>01-Spielleiter/Zustände-phb#Verängstigt|Verängstigt<STATBLOCK-MARKDOWN-LINK>"
senses: <STATBLOCK-MARKDOWN-LINK>01-Spielleiter/Sinne-phb#Blindsicht|Blindsicht<STATBLOCK-MARKDOWN-LINK> 18 m (darüber hinaus blind), passive Wahrnehmung 8
languages: ""
cr: "2"
traits:
  - name: Amorph
    desc: "Die Gallerte kann sich durch einen Bereich bewegen, der nicht größer als 2,5 Zentimeter ist, ohne sich quetschen zu müssen."
  - name: Spinnenklettern
    desc: "Die Gallerte kann an schwierigen Oberflächen klettern, auch kopfüber an der Decke, ohne Attributswürfe ablegen zu müssen."
actions:
  - name: "Scheinfuß"
    desc: "*Nahkampf-Waffenangriff:* +4 zum Treffen, Reichweite 1,5 m, ein Ziel. *Treffer:* 9 (2d6+2) Wuchtschaden plus 3 (1d6) Säureschaden."
reactions:
  - name: Teilen
    desc: "Wenn eine Gallerte, die mittelgroß oder größer ist, Blitz- oder Hiebschaden erleidet, teilt sie sich in zwei neue Gallerten auf, wenn sie mindestens 10 Trefferpunkte besitzt. Jede neue Gallerte hat Trefferpunkte gleich der Hälfte der ursprünglichen Gallerte, abgerundet. Neue Gallerten sind eine Größenkategorie kleiner als die ursprüngliche Gallerte."
```
^statblock

## Vorkommen

Unterreich