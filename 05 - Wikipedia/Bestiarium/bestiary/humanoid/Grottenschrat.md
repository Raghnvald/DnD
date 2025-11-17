---
Typ: Humanoid
tags:
  - Quelle/5e/mm
  - Monster/HG/1
  - Monster/Habitat/Wald
  - Monster/Habitat/Grasland
  - Monster/Habitat/Unterreich
  - Monster/Größe/Mittelgroß
  - Monster/Typ/Humanoid/goblinoid
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Bugbear
---
# Bugbear
*Quelle: Monsterhandbuch S. 33. Available in the <span title='Systems Reference Document (5.1)'>SRD</span> and the Basic Rules (2014)*  

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
source: Monsterhandbuch 2014
size: Medium
type: Humanoid
subtype: goblinoid
alignment: chaotisch böse
ac: !!int "16"
ac_class: "[[Fellrüstung]], [[Gegenstände/Schild|Schild]]"
hp: 27
hit_dice: 5d8+5
modifier: !!int "2"
stats:
  - !!int "15"
  - !!int "14"
  - !!int "13"
  - !!int "8"
  - !!int "11"
  - !!int "9"
speed: 9 Meter.
skillsaves:
  - "name": "[Heimlichkeit](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+6"
  - "name": "[Überleben](/3-Mechanics/CLI/skills.md#Survival)"
    "desc": "+2"
senses: Dunkelsicht 18 Meter, passive Wahrnehmung 10
languages: Gemeinsprache, Goblin
cr: "1"
traits:
  - name: Wüstling
    desc: "Eine Nahkampfwaffe fügt einen zusätzlichen Würfel ihres Schadens zu, wenn der Grottenschrat mit ihr trifft (im Angriff enthalten)."
  - name: Überraschungsangriff
    desc: "Wenn der Grottenschrat eine Kreatur überrascht und sie in der ersten Runde des Kampfes mit einem Angriff trifft, erleidet das Ziel zusätzlich 7 (2W6) Schaden durch den Angriff."
actions:
  - name: Morgenstern
    desc: "_Nahkampf-Waffenangriff:_ +4 zum Treffen, Reichweite 1,5m, ein Ziel. _Treffer:_ 11 (2W8 + 2) Stichschaden."
  - name: Wurfspeer
    desc: "_Nahkampf- oder Fernkampf-Waffenangriff:_ +4 zum Treffen, Reichweite 1,5m oder 30m/36m, ein Ziel. _Treffer:_ 9 (2W6+2) Stichschaden im Nahkampf oder 5 (1W6 + 2) Stichschaden im Fernkampf."


```
^statblock