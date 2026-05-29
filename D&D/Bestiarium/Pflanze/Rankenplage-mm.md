---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Rankenplage
linter-yaml-title-alias: Rankenplage
tags:
  - Monster/Größe/Mittelgroß
  - Monster/Habitat/Wald
  - Monster/HG/1-2
  - Monster/Typ/Pflanze
  - Quelle/5e/mm
aliases:
  - Rankenplage
  - Vine Blight
---
# Rankenplage
*Source: Monster Manual p. 32*  

Rankenplagen erscheinen als Massen aus sich windenden Ranken und verstecken sich im Unterholz, um auf Beute zu warten. Indem sie die Pflanzen in der Umgebung beleben, können Rankenplagen ihre Feinde behindern, ehe sie angreifen. 

Rankenplagen sind die einzigen Plagen, die sprechen können. Durch ihre Verbindung mit dem bösen Geist des Gulthias-Baumes, dem sie dient, spricht eine Rankenplage in einer gebrochenen Version der Stimme ihres toten Meisters, um Opfer zu verspotten oder mit mächtigen Feinden zu verhandeln.

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
"name": "Vine Blight"
"size": "Medium"
"type": "plant"
"alignment": "Neutral Evil"
"ac": !!int "12"
"ac_class": "natural armor"
"hp": !!int "26"
"hit_dice": "4d8 + 4"
"modifier": !!int "-1"
"stats":
  - !!int "15"
  - !!int "8"
  - !!int "14"
  - !!int "5"
  - !!int "10"
  - !!int "3"
"speed": "10 ft."
"skillsaves":
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+1"
"condition_immunities": "[blinded](/3-Mechanics/CLI/conditions.md#Blinded), [deafened](/3-Mechanics/CLI/conditions.md#Deafened)"
"senses": "[blindsight](/3-Mechanics/CLI/senses.md#Blindsight) 60 ft. (blind beyond\
  \ this radius), passive Perception 10"
"languages": "Common"
"cr": "1/2"
"traits":
  - "desc": "While the blight remains motionless, it is indistinguishable from a tangle\
      \ of vines."
    "name": "False Appearance"
"actions":
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 10 ft., one target. *Hit:* 9\
      \ (2d6 + 2) bludgeoning damage, and a Large or smaller target is [grappled](/3-Mechanics/CLI/conditions.md#Grappled)\
      \ (escape DC 12). Until this grapple ends, the target is [restrained](/3-Mechanics/CLI/conditions.md#Restrained),\
      \ and the blight can't constrict another target."
    "name": "Constrict"
  - "desc": "Grasping roots and vines sprout in a 15-foot radius centered on the blight,\
      \ withering away after 1 minute. For the duration, that area is difficult terrain\
      \ for nonplant creatures. In addition, each creature of the blight's choice\
      \ in that area when the plants appear must succeed on a DC 12 Strength saving\
      \ throw or become [restrained](/3-Mechanics/CLI/conditions.md#Restrained). A\
      \ creature can use its action to make a DC 12 Strength check, freeing itself\
      \ or another entangled creature within reach on a success."
    "name": "Entangling Plants (Recharge 5-6)"
"source":
  - "MM"
"image": "/3-Mechanics/CLI/bestiary/plant/token/vine-blight.webp"
```
^statblock

## Environment

forest

---

```statblock
statblock: true
name: Rankenplage
image: [[VineBlight.webp]]
source: Grundregelwerk
size: Mittel
type: Pflanze
alignment: neutral böse
ac: 12
hp: 26
hit_dice: 4d8 + 8
speed: 9 Meter.
stats: [15, 8, 14, 5, 10, 3]
skillsaves:
  - Heimlichkeit: 1
damage_vulnerabilities: ""
damage_resistances: ""
damage_immunities: ""
condition_immunities: "Blind, Taub"
senses: Dunkelsicht 18 Meter (darüber hinaus blind), passive Wahrnehmung 10
languages: Gemeinsprache
cr: 1/2
environment: Wälder
bestiary: true
traits:
  - name: Falsche Erscheinung
    desc: Solange die Plage unbeweglich bleibt, ist sie von einem toten Strauch nicht zu unterscheiden.
    attack_bonus: 0
actions:
  - name: Verschlingen
    desc: "_Nahkampf-Waffenangriff_: +4 zum Treffen, Reichweite 3m, ein Ziel. _Treffer_: 9 (2W6 + 2) Wuchtschaden und ein Ziel der Größe Groß oder kleiner wird festgesetzt (Entkommen-SG 12). Bis dieser Griff endet, ist die Kreatur festgesetzt, und die Plage kann kein weiteres Ziel einschnüren."
    attack_bonus: 4
    damage_dice: 2d6
    damage_bonus: 2
  - name: Umschlingende Pflanzen (Aufladung 5-6)
    desc: "Greifende Wurzeln und Ranken sprießen in einem 4,5m Radius um die Plage herum und verdorren nach 1 Minute. Während dieser Zeit ist das Gebiet für Kreaturen, die keine Pflanzen sind, schwieriges Terrain. Außerdem muss jede Kreatur, welche die Plage auswählt, die sich in diesem Gebiet befindet, wenn die Pflanzen erscheinen, einen Stärke-Rettungswurf (SG 12) bestehen oder sie wird gefesselt. Eine Kreatur kann ihre Aktion nutzen, um einen Stärkewurf (SG 12) zu unternehmen und sich oder eine andere gefesselte Kreatur in Reichweite bei einem Erfolg zu befreien."
```