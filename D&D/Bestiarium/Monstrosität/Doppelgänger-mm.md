---
cssclasses: dnd5e-only-statblock
prefer-view: edit-source read
Name: Doppelgänger
Typ: Monstrosität
Größe: Mittelgroß
HG: 3
Habitat:
  - Stadt
  - Unterreich
status: completed
image: image/doppelganger-webp
tags:
  - Quelle/5e/mm
  - Monster/HG/3
  - Monster/Habitat/Unterreich
  - Monster/Habitat/Stadt
  - Monster/Größe/Mittelgroß
  - Monster/Typ/Monstrosität/shapechanger
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Doppelganger
---
# Doppelgänger
*Quelle: Monsterhandbuch S. 316. Verfügbar im <span title='Systems Reference Document (5.1)'>SRD</span> und dem Grundregelwerk (2014)*  

Doppelgänger sind verschlagene Gestaltwandler, die das Aussehen anderer Humanoider annehmen können, um Verfolger abzuschütteln oder Opfer mit Täuschung und Verkleidung in ihren Untergang zu locken. Wenige Kreaturen sind besser darin, Furcht, Misstrauen und Verrat zu säen als Doppelgänger. Man findet sie in allen Ländern und Kulturen, und sie können das Aussehen von Personen aller Völker annehmen.

## Geheimnisraub

Die angenommene Form eines Doppelgängers erlaubt es ihm, sich in fast jede Gruppe oder Gemeinschaft zu mischen, doch verleiht sie ihm keine Sprachen, Manierismen, Erinnerungen oder Persönlichkeit der Person. Doppelgänger folgen oft Kreaturen, die sie nachahmen wollen, oder fangen sie, um sie zu studieren und ihren Verstand nach Geheimnissen abzusuchen. Doppelgänger können die oberflächlichen Gedanken von Kreaturen lesen, sodass sie den Namen, die Begierden und Ängste der Kreatur in Erfahrung bringen können, zusammen mit einigen zufälligen Erinnerungen.

$\quad$Ein Doppelgänger, der als Teil einer langfristigen Intrige eine bestimmte Kreatur nachahmt, hält manchmal sein Double für Wochen am Leben und in seiner Nähe, um täglich seine Gedanken zu sondieren und zu lernen, wie er sich authentisch benehmen und sprechen muss.

## Genusssüchtige Schwindler

Doppelgänger arbeiten alleine oder in kleinen Gruppen, wobei sich die Rollen in der Gruppe von Komplott zu Komplott ändern können. Während ein Doppelgänger den Platz eines ermordeten Kaufmanns oder Adeligen einnimmt, übernehmen die anderen Rollen, die die Umstände erfordern. Sie spielen die Rolle von Familienmitgliedern und Dienern, während sie von den Reichtümern des Opfers leben.

## Wechselbälger

Doppelgänger sind zu faul und selbstsüchtig, um ihre Kinder großzuziehen. Sie nehmen attraktive männliche Gestalten an und verführen Frauen, die sie zurücklassen, um ihre Nachkommenschaft großzuziehen. Ein Doppelgängerkind scheint ein normales Mitglied der Spezies der Mutter zu sein, bis er in die Pubertät kommt; dann erkennt er sein wahres Wesen und verspürt den Drang, andere seiner Art zu finden und sich ihnen anzuschließen.

```statblock
name: Doppelgänger
image: token/doppelganger.webp
source: MM
size: Mittelgroß
type: Monstrosität
subtype: Gestaltwandler
alignment: Neutral
ac: 14
hp: 52
hit_dice: 8d8 + 16
modifier: 4
stats:
  - 11
  - 18
  - 14
  - 11
  - 12
  - 14
speed: 9 m
skillsaves:
  - name: <STATBLOCK-MARKDOWN-LINK>01-Spielleiter/Fertigkeiten-phb#Motiv%20erkennen|Motiv erkennen<STATBLOCK-MARKDOWN-LINK>
    desc: "+3"
  - name: <STATBLOCK-MARKDOWN-LINK>01-Spielleiter/Fertigkeiten-phb#Täuschen|Täuschen<STATBLOCK-MARKDOWN-LINK>
    desc: "+6"
condition_immunities: <STATBLOCK-MARKDOWN-LINK>01-Spielleiter/Zustände-phb#Bezaubert|Bezaubert<STATBLOCK-MARKDOWN-LINK>
senses: <STATBLOCK-MARKDOWN-LINK>01-Spielleiter/Sinne-phb#Dunkelsicht|Dunkelsicht<STATBLOCK-MARKDOWN-LINK> 18 Meter, passive Wahrnehmung 11
languages: Gemeinsprache
cr: 3
traits:
  - name: Gestaltwandler
    desc: "Der Doppelgänger kann seine Aktion verwenden, um sich in die Gestalt eines kleinen oder mittelgroßen Humanoiden zu verwandeln oder seine wahre Gestalt anzunehmen. Seine Spielwerte sind gleich, egal, welche Form er gerade hat. Jede Ausrüstung, die er tragen oder in der Hand halten sollte, wird mit verwandelt. Er nimmt wieder seine wahre Gestalt an, wenn er stirbt."
  - name: Lauerjäger
    desc: "In der ersten Kampfrunde hat der Doppelgänger einen Vorteil auf seine Angriffswürfe gegen jede Kreatur, die er <STATBLOCK-MARKDOWN-LINK>01-Spielleiter/Zustände-phb#Überraschung|überrascht<STATBLOCK-MARKDOWN-LINK> hat."
  - name: Überraschungsangriff
    desc: "Wenn der Doppelgänger eine Kreatur überrascht und sie in der ersten Kampfrunde mit einem Angriff trifft, dann erleidet das Ziel zusätzlich 10 (3d6) Schaden durch den Angriff."
actions:
  - name: Mehrfachangriff
    desc: Der Doppelgänger führt zwei Nahkampfangriffe durch.
  - name: Hieb
    desc: "*Nahkampf-Waffenangriff:* +6 zum Treffen, Reichweite 1,5 m, ein Ziel. *Treffer:* 7 (1d6+4) Wuchtschaden."
  - name: Gedanken lesen
    desc: Der Doppelgänger liest die oberflächlichen Gedanken einer Kreatur innerhalb von 18 m um sich. Der Effekt kann Hindernisse durchdringen, aber 90 cm Holz oder Erde, 60 cm Stein, 5 cm Metall oder eine dünne Schicht Blei blockieren ihn. Solange das Ziel in Reichweite ist, kann der Doppelgänger weiter seine Gedanken lesen, solange die <STATBLOCK-MARKDOWN-LINK>01-Spielleiter/Zustände-phb#Konzentration|Konzentration<STATBLOCK-MARKDOWN-LINK> des Doppelgängers nicht gebrochen wird (als würde er sich auf einen Zauber <STATBLOCK-MARKDOWN-LINK>01-Spielleiter/Zustände-phb#Konzentration|konzentrieren<STATBLOCK-MARKDOWN-LINK>). Solange der Doppelgänger die Gedanken eines Ziels liest, hat er einen Vorteil auf Würfe mit Weisheit (<STATBLOCK-MARKDOWN-LINK>01-Spielleiter/Fertigkeiten-phb#Motiv%20erkennen|Motiv erkennen<STATBLOCK-MARKDOWN-LINK>) und Charisma (<STATBLOCK-MARKDOWN-LINK>01-Spielleiter/Fertigkeiten-phb#MTäuschen|Täuschen<STATBLOCK-MARKDOWN-LINK>, <STATBLOCK-MARKDOWN-LINK>01-Spielleiter/Fertigkeiten-phb#Einschüchtern|Einschüchtern<STATBLOCK-MARKDOWN-LINK> und <STATBLOCK-MARKDOWN-LINK>01-Spielleiter/Fertigkeiten-phb#Überzeugen|Überzeugen<STATBLOCK-MARKDOWN-LINK>) gegen das Ziel. 
```
^statblock

## Vorkommen

Stadt, Unterreich