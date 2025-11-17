---
tags:
  - Quelle/5e/mm
  - Monster/Typ/Monstrosität
  - Monster/Größe/Mittelgroß
  - Monster/HG/2
  - Monster/Habitat/Wald
  - Monster/Habitat/Unterreich
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Grick
---
# Grick
*Quelle: Monsterhandbuch S. 173. Available in the <span title='Systems Reference Document (5.1)'>SRD</span> and the Basic Rules (2014)*  

Die wurmartigen Gricks warten unsichtbar und verschmelzen mit den Felsen der Höhlen und Kavernen, die sie heimsuchen. Nur wenn die Beute nahe kommt, erheben sie sich, und ihre vier Tentakel entfalten sich, um hungrige, schnappende Schnabel zu offenbaren.

## Passive Raubtiere

Gricks jagen nur selten. Stattdessen schleppen sie ihre gummiartigen Körper an Orte, an denen regelmäßig Kreaturen vorbeikommen. Sie lauern außer Sicht zwischen Geröll und Schutt, quetschen sich in Erdlöcher und Spalten, klettern Simse empor oder wickeln sich um Stalaktiten, um sich auf arglose Beute herunter fallen zu lassen. Ein Grick verschlingt so gut wie alles, das sich bewegt, mit Ausnahme von anderen Gricks. Er greift die Beute an, die ihm am nächsten ist. Gefallene Kreaturen packt er mit seinen Tentakeln und schleppt sie weg, um sie alleine zu verspeisen.

## Umherziehende Lauerjäger

Gricks bleiben in einem Gebiet, bis das Nahrungsvorkommen knapp wird, oft, weil sich denkende Wesen ihrer Präsenz bewusst werden und alternative Wege um ihr Revier planen. Wenn Beute im Unterreich knapp ist, ziehen Gricks an die Oberfläche, um in der Wildnis zu jagen. Sie lauern dann auf Bäumen oder an Klippen. Ein Grick-Rudel wird oft von einem gut genährten, übergroßen Alpha angeführt, um den sich die anderen sammeln.

## Beute des Gemetzels

Im Lauf der Zeit sammeln sich in Grick-Behausungen die ehemaligen Besitztümer intelligenter Beute, und erfahrene Führer wissen, wie sie nach diesen verräterischen Zeichen suchen müssen. Erforscher des Unterreichs versiegeln manchmal Wege, die zu einer Grick-Behausung führen , um sie so auszuhungern, und beanspruchen dann die Besitztümer der Beute der ekelhaften Kreatur.

```statblock
name: Grick
image: token/grick.webp
source: Monsterhandbuch 2014
size: Mittel
type: Monstrosität
alignment: neutral
ac: !!int "14"
ac_class: "Natürliche Rüstung"
hp: !!int "27"
hit_dice: "6d8"
modifier: !!int "2"
stats:
  - !!int "14"
  - !!int "14"
  - !!int "11"
  - !!int "3"
  - !!int "14"
  - !!int "5"
speed: "9 Meter, klettern 9 Meter."
damage_resistances: "Wucht-, Stich- und Hiebschaden durch
nicht-magische Waffen"
senses: "Dunkelsicht 18 m, passive Wahrnehmung 12"
languages: ""
cr: "2"
traits:
  - name: "Steintarnung."
    desc: "Der Grick hat einen Vorteil bei Würfen auf Geschicklichkeit (Heimlichkeit), wenn er sich in felsigem Gelände verstecken möchte."
actions:
  - name: Mehrfachangriff
    desc: "Der Grick führt ei nen Angriff mit seinen Tentakeln
aus. Wenn der Angriff trifft, kann der Grick einen Schnabel-
Angriff gegen dasselbe Ziel ausführen."
  - name: Tentakel
    desc: "_Nahkampf-Waffenangriff:_ +4 auf Treffer, Reichweite 1,5 m, ein Ziel. _Treffer:_ 9 (2W6 + 2) Hiebschaden."
  - name: Schnabel
    desc: "_Nahkampf-Waffenangriff:_ +4 auf Treffer, Reichweite 1,5 m, ein Ziel. _Treffer:_ 5 (1W6 + 2) Stichschaden."
```
^statblock

## Environment

underdark, forest