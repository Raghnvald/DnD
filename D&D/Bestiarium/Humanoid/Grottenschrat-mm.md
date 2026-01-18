---
cssclasses: dnd5e-only-statblock
prefer-view: edit-source read
Name: Grottenschrat
Typ: Humanoid
Größe: Mittelgroß
HG: 1
Habitat:
  - Grasland
  - Unterreich
  - Wald
status: completed
image: image/bugbear.webp
tags:
  - Quelle/5e/mm
  - Monster/HG/1
  - Monster/Habitat/Grasland
  - Monster/Habitat/Unterreich
  - Monster/Habitat/Wald
  - Monster/Größe/Mittelgroß
  - Monster/Typ/Humanoid/goblinoid
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Bugbear
---
# Grottenschrat
*Quelle: Monsterhandbuch S. 33. Verfügbar im <span title='Systems Reference Document (5.1)'>SRD</span> und dem Grundregelwerk (2014)*  

Grottenschrate sind für Kampf und Unheil geboren. Sie überleben durch Überfälle und Jagd, sie schikanieren Schwächere und hassen es, herumkommandiert zu werden, doch bedeutet ihre Liebe zum Blutvergießen auch, dass sie für mächtige Meister kämpfen werden, wenn ihnen versichert wird, dass Gemetzel und Schätze auf sie warten.

## Goblinoide

Grottenschrate findet man oft in der Gesellschaft ihrer Vettern, Hobgoblins und Goblins. Normalerweise versklaven Grottenschrate alle Goblins, die sie treffen, und sie schikanieren Hobgoblins, bis sie ihnen Gold und Nahrung dafür geben, dass sie als Kundschafter und Schocktruppen dienen. Selbst wenn sie bezahlt werden, sind Grottenschrate bestenfalls unzuverlässige Verbündete, doch Goblins und Hobgoblins wissen, dass egal, wie sehr Grottenschrate die Vorräte ihres Stammes belasten, sie doch eine beträchtliche Macht darstellen.

## Anhänger von Hruggek

Grottenschrate verehren Hruggek, einen niederen Gott, der auf der Ebene Acheron existiert. In der Abwesenheit anderer goblinoider Verwandter bilden Grottenschrate lose Kriegstrupps, die von ihrem brutalsten Mitglied angeführt werden. Grottenschrate glauben, dass ihre Geister, wenn sie sterben, die Gelegenheit haben werden, an Hruggeks Seite zu kämpfen. Sie versuchen sich als würdig zu erweisen, indem sie so viele Feinde wie möglich bezwingen.

## Korrupte Lauerer

Trotz ihrer einschüchternden Statur bewegen sich Grottenschrate mit überraschender Heimlichkeit. Sie legen gerne Hinterhalte und flüchten, wenn sie unterlegen sind. Sie sind verlässliche Söldner, solange man ihnen Nahrung, Waser und Schätze zur Verfügung stellt, doch vergisst ein Grottenschrat jedes Bündnis, wenn sein Leben auf dem Spiel steht. Ein verwundetes Mitglied einer Grottenschratbande wird oft zurückgelassen, damit die anderen entkommen können. Danach könnte dieser Grottenschrat dabei helfen, seine ehemaligen Gefährten zu verfolgen, wenn das sein Leben rettet.

```statblock
name: Grottenschrat
image: token/bugbear.webp
source:
  - MM
  - EGW
size: Medium
type: Humanoid
subtype: goblinoid
alignment: chaotisch böse
ac: !!int "16"
ac_class: "<STATBLOCK-MARKDOWN-LINK>Gegenstände/Fellrüstung-phb|Fellrüstung<STATBLOCK-MARKDOWN-LINK>, <STATBLOCK-MARKDOWN-LINK>Gegenstände/Schild-phb|Schild<STATBLOCK-MARKDOWN-LINK>"
hp: 27
hit_dice: 5d8 + 5
modifier: 2
stats:
  - 15
  - 14
  - 13
  - 8
  - 11
  - 9
speed: 9 Meter.
skillsaves:
  - name: <STATBLOCK-MARKDOWN-LINK>01-Spielleiter/Fertigkeiten-phb#Heimlichkeit|Heimlichkeit<STATBLOCK-MARKDOWN-LINK>
    "desc": "+6"
  - name: <STATBLOCK-MARKDOWN-LINK>01-Spielleiter/Fertigkeiten-phb#Überleben|Überleben<STATBLOCK-MARKDOWN-LINK>
    "desc": "+2"
senses: senses: <STATBLOCK-MARKDOWN-LINK>01-Spielleiter/Sinne-phb#Dunkelsicht|Dunkelsicht<STATBLOCK-MARKDOWN-LINK> 18 Meter, passive Wahrnehmung 10
languages: Gemeinsprache, Goblinisch
cr: "1"
traits:
  - name: Wüstling
    desc: "Eine Nahkampfwaffe verursacht einen zusätzlichen Schadenswürfel, wenn der Grottenschrat mit ihr trifft (in den Angriff bereits eingerechnet)."
  - name: Überraschungsangriff
    desc: "Wenn der Grottenschrat eine Kreatur überrascht und sie in der ersten Kampfrunde mit einem Angriff trifft, dann erleidet das Ziel zusätzlich 7 (2d6) Schaden durch den Angriff."
actions:
  - name: Morgenstern
    desc: "*Nahkampf-Waffenangriff:* +4 zum Treffen, Reichweite 1,5m, ein Ziel. *Treffer:* 11 (2d8+2) Stichschaden."
  - name: Wurfspeer
    desc: "*Nahkampf- oder Fernkampf-Waffenangriff:* +4 zum Treffen, Reichweite 1,5m oder Reichweite 9m/36m, ein Ziel. *Treffer:* 9 (2d6+2) Stichschaden im Nahkampf oder 5 (1d6 + 2) Stichschaden auf Entfernung."
```
^statblock