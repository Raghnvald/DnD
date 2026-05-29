---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Needle Blight
linter-yaml-title-alias: Needle Blight
tags:
  - Monster/Größe/Mittelgroß
  - Monster/Habitat/Wald
  - Monster/HG/1-4
  - Monster/Typ/Pflanze
  - Quelle/5e/mm
aliases:
  - Needle Blight
---
# Needle Blight
*Source: Monster Manual p. 32*  

In den Schatten der Wälder kann man Nadelplagen auf Entfernung für schlurfende, bucklige Humanoide halten. Aus der Nähe offenbaren sich diese Kreaturen als grässliche Pflanzen, deren nadelbaumartige Stacheln in bebenden Büscheln an ihrem ganzen Körper wachsen. Eine Nadelplage schlägt mit diesen Nadeln zu oder schleudert sie durch die Luft, wobei sie Rüstung und Fleisch durchschlagen können.

Wenn Nadelplagen eine Bedrohung wahrnehmen, geben sie Pollen ab, die der Wind zu anderen Nadelplagen im ganzen Wald trägt. Wenn sie so auf die Position eines Feindes aufmerksam gemacht werden, eilen Nadelplagen von allen Seiten herbei, um ihre Wurzeln in Blut zu tränken.

## Plagen

Plagen sind erwachte Pflanzen, die mit Intelligenz und Beweglichkeit gesegnet worden sind und Land heimsuchen, das von der Dunkelheit kontaminiert worden ist. Eine Plage trinkt die Dunkelheit aus dem Boden. Entsprechend versucht sie, den Willen eines uralten Bösen zu erfüllen und dieses Böse zu verbreiten, wo sie kann.

### Wurzeln des Gulthias-Baumes

Legenden erzählen von einem Vampir namens Gulthias, der schreckliche Magie wirkte und einen grauenvollen Turm erschuf, der als die Nachtfangspitze bekannt war. Gulthias wurde zerstört, als ein Held einen hölzernen Pflock in seinem Herzen versenkte, doch als der Vampir vernichtet wurde, erfüllte sein Blut den Pflock mit schrecklicher Macht. Nach einer Weile wucherten neue Tentakelranken aus dem Holz und wurden zu einem Setzling, der von der bösen Essenz des Vampirs erfüllt war. Man sagt, dass ein wahnsinniger Druide den Setzling entdeckte und in einer unterirdischen Höhle einpflanzte, wo er gedeihen konnte. An diesem Gulthias-Baum wuchsen die Samen, aus denen die ersten Plagen entstanden.

### Dunkle Eroberung

Immer wenn ein Baum von einem Fragment eines bösen Geists oder einer dunklen Macht verseucht wird, kann sich ein Gulthias-Baum erheben und den Wald der Umgebung korrumpieren. Sein Böses breitet sich über die Wurzeln und Erde auf andere Pflanzen aus, die entweder sterben oder sich in Plagen verwandeln. Während sich diese Plagen ausbreiten, vergiften und entwurzeln sie gesunde Pflanzen und ersetzen sie durch Domsträucher, giftiges Unkraut und andere ihrer Art. Mit der Zeit kann eine Verseuchung durch Plagen jedes Land und jeden Wald in einen Ort der Korruption verwandeln.

In Wäldern, die von Plagen heimgesucht sind, wachsen Bäume und Pflanzen mit übernatürlicher Geschwindigkeit. Ranken und Unterholz breiten sich schnell durch Gebäude aus und überwuchern Wege und Straßen. Nachdem die Plagen alle Bewohner vertrieben oder umgebracht haben, können ganze Dörfer innerhalb von wenigen Tagen verschwinden.

### Vom Bösen beherrscht

Plagen sind unabhängige Kreaturen, doch die meisten stehen unter dem Einfluss eines Gulthias-Baumes. Oft zeigen sie Eigenheiten und Eigenschaften der Lebenskraft oder des Geistes, der sie erzeugt hat. Indem sie die alten Feinde ihres Stammvaters angreifen oder Schätze suchen, die ihm wertvoll waren, führen sie das Vermächtnis des uralten Bösen fort.

> [!quote]  
> 
> Siehe das Vermächtnis von Gulthias, dem Vampir: Pflanzen mit einer Vorliebe für Blut.

```statblock
"name": "Needle Blight"
"size": "Medium"
"type": "plant"
"alignment": "Neutral Evil"
"ac": !!int "12"
"ac_class": "natural armor"
"hp": !!int "11"
"hit_dice": "2d8 + 2"
"modifier": !!int "1"
"stats":
  - !!int "12"
  - !!int "12"
  - !!int "13"
  - !!int "4"
  - !!int "8"
  - !!int "3"
"speed": "30 ft."
"condition_immunities": "[blinded](/3-Mechanics/CLI/conditions.md#Blinded), [deafened](/3-Mechanics/CLI/conditions.md#Deafened)"
"senses": "[blindsight](/3-Mechanics/CLI/senses.md#Blindsight) 60 ft. (blind beyond\
  \ this radius), passive Perception 9"
"languages": "understands Common but can't speak"
"cr": "1/4"
"actions":
  - "desc": "*Melee Weapon Attack:* +3 to hit, reach 5 ft., one target. *Hit:* 6 (2d4\
      \ + 1) piercing damage."
    "name": "Claws"
  - "desc": "*Ranged Weapon Attack:* +3 to hit, range 30/60 ft., one target. *Hit:*\
      \ 8 (2d6 + 1) piercing damage."
    "name": "Needles"
"source":
  - "MM"
"image": "/3-Mechanics/CLI/bestiary/plant/token/needle-blight.webp"
```
^statblock

## Environment

forest

---

```statblock
statblock: true
name: Nadelplage
image: [[NeedleBlight.webp]]
source: Grundregelwerk
size: Mittel
type: Pflanze
alignment: neutral böse
ac: 12
hp: 11
hit_dice: 2d8+2
speed: 9 Meter.
stats: [12, 12, 13, 4, 8, 3]
condition_immunities: "Blind, Taub"
senses: Blindsicht 18 Meter (darüber hinaus blind), passive Wahrnehmung 9
languages: versteht die Gemeinsprache, kann aber nicht sprechen
cr: 1/4
environment: Wälder
bestiary: true
actions:
  - name: Klauen
    desc: "Nahkampf-Waffenangriff: +3 zum Treffen, Reichweite 1,5m, ein Ziel. Treffer: 6 (2W4 + 1) Stichschaden."
  - name: Nadeln
    desc: "Fernkampf-Waffenangriff: +3 auf Treffer, Reichweite 9/18m, ein Ziel. Treffer: 8 (`2W6+1`) Stichschaden."
```