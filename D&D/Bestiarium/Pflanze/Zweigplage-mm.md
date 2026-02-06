---
tags:
  - Quelle/5e/mm
  - Monster/HG/1-8
  - Monster/Habitat/Wald
  - Monster/Größe/Klein
  - Monster/Typ/Pflanze
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Twig Blight
---
# Zweigplage
*Source: Monster Manual p. 32. Available in the Basic Rules (2014)*  

Zweigplagen können im Boden wurzeln und tun dies auch, wenn lebende Beute selten ist. Wenn sie verwurzelt sind, ähneln sie holzigen Sträuchern. Wenn sie ihre Wurzeln aus dem Boden ziehen, um sich zu bewegen, verdrehen sich die Zweige einer Zweigplage miteinander, um einen humanoid erscheinenden Körper mit einem Kopf und Gliedmaßen zu bilden.

weigplagen suchen Lager und Wasserquellen auf und wurzeln dort, um Hinterhalte für potentielle Opfer zu legen, die kommen, um zu trinken oder sich auszuruhen. Wenn sie in Gruppen zusammenstehen, verschmelzen Zweigplagen mit der natürlichen Vegetation des Ortes oder mit Haufen aus Schutt oder Feuerholz.

Da sie so trocken sind, sind Zweigplagen besonders anfällig für Feuer.

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
"name": "Twig Blight"
"size": "Small"
"type": "plant"
"alignment": "Neutral Evil"
"ac": !!int "13"
"ac_class": "natural armor"
"hp": !!int "4"
"hit_dice": "1d6 + 1"
"modifier": !!int "1"
"stats":
  - !!int "6"
  - !!int "13"
  - !!int "12"
  - !!int "4"
  - !!int "8"
  - !!int "3"
"speed": "20 ft."
"skillsaves":
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+3"
"damage_vulnerabilities": "fire"
"condition_immunities": "[blinded](/3-Mechanics/CLI/conditions.md#Blinded), [deafened](/3-Mechanics/CLI/conditions.md#Deafened)"
"senses": "[blindsight](/3-Mechanics/CLI/senses.md#Blindsight) 60 ft. (blind beyond\
  \ this radius), passive Perception 9"
"languages": "understands Common but can't speak"
"cr": "1/8"
"traits":
  - "desc": "While the blight remains motionless, it is indistinguishable from a dead\
      \ shrub."
    "name": "False Appearance"
"actions":
  - "desc": "*Melee Weapon Attack:* +3 to hit, reach 5 ft., one target. *Hit:* 3 (1d4\
      \ + 1) piercing damage."
    "name": "Claws"
"source":
  - "MM"
"image": "/3-Mechanics/CLI/bestiary/plant/token/twig-blight.webp"
```
^statblock

## Environment

forest

```statblock
statblock: true
name: Zweigplage
image: [[TwigBlight.webp]]
source: Grundregelwerk
size: Klein
type: Pflanze
alignment: neutral böse
ac: 13
hp: 4
hit_dice: 1d6+1
speed: 6 Meter.
stats: [6, 13, 12, 4, 8, 3]
skillsaves:
  - Heimlichkeit: 3
damage_vulnerabilities: "Feuer"
damage_resistances: ""
damage_immunities: ""
condition_immunities: "Blind, Taub"
senses: Dunkelsicht 18 Meter (darüber hinaus blind), passive Wahrnehmung 9
languages: versteht Gemeinsprache, kann sie aber nicht sprechen
cr: 1/8
environment: Wälder
bestiary: true
traits:
  - name: Falsche Erscheinung
    desc: Solange die Plage unbeweglich bleibt, ist sie von einem toten Strauch nicht zu unterscheiden.
    attack_bonus: 0
actions:
  - name: Klauen
    desc: "Nahkampfangriff: +3 zum Treffen, Reichweite 1,5m, ein Ziel. Treffer: 3 (1W4 + 1) Stichschaden."
    attack_bonus: 3
    damage_dice: 1d4
    damage_bonus: 1
```