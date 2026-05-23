---
prefer-view: edit-source read
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Otyugh
Kategorie: Aberration
Größe: Groß
HG: 5
Habitat:
  - Unterreich
image: token/otyugh-webp
status: WIP
tags:
  - Monster/Größe/Groß
  - Monster/Habitat/Unterreich
  - Monster/HG/5
  - Monster/Typ/Aberration
  - Quelle/5e/mm
aliases:
  - Otyugh
---
# Otyugh
*Quelle: Monsterhandbuch S. 215. Verfügbar im <span title='Systems Reference Document (5.1)'>SRD</span>*

Ein Otyugh ist eine groteske, knollige Kreatur, die auf drei stämmigen Beinen umherläuft. Ihre Augen und Nase sitzen auf einem tentakelartigen Stiel, der von der Spitze seines aufgedunsenen Körpers ragt. Zwei gummiartige Tentakel enden in stachligen, blattartigen Auswüchsen, die der Otyugh verwendet, um Nahrung in sein klaffendes Maul zu schaufeln.

$\quad$Ein Otyugh vergräbt sich unter Haufen von Abfällen und Aas und lässt nur seinen Sinnesstiel herausragen. Wenn eine essbare Kreatur vorbeikommt, brechen die Tentakel des Otyugh aus dem Schmutz hervor und packen sie.

$\quad$Otyughs nutzen jede Gelegenheit, Beute zu überfallen und zu fressen. Sie verwenden eine eingeschränkte Form von Telepathie, um denkende Kreaturen dazu zu drängen, sich in Richtung ihrer Behausungen zu bewegen, manchmal indem sie vorgeben, etwas anderes zu sein.

## Bewohner der Dunkelheit

Otyughs dulden helles Licht nur dann, wenn beträchtliche Vorräte an Aas oder Müll in Reichweite sind. In der Wildnis hausen sie in abgestandenen Sümpfen, Tümpeln voller Schlacke und feuchten Waldtälern. Der Gestank von Friedhöfen, städtischen Kanalisationen, Misthaufen in Dörfern und mit Dung gefüllten Tiergehegen lockt sie in zivilisierte Regionen.

$\quad$Da Otyughs sich einzig um Nahrung scheren, sammeln sich in ihren Nestern manchmal eine Vielzahl von Schätzen, die von ihren Opfern stammen und mit den Abfällen vermischt sind.

## Symbiotische Wächter

Denkende unterirdische Wesen können mit den Otyughs koexistieren und nutzen sie als Müllentsorgung. Mit dieser üppigen Ernährung können Otyughs in ihren Suhlen fett werden und haben keine anderen Ziele oder Wünsche. Diese ortsgebundene Gefräßigkeit macht sie zu verlässlichen Wächtern. Solange ein Otyugh gefüttert wird, lässt er davon ab, andere Kreaturen anzugreifen. Allerdings kann jemand, der sich zum Meister eines Otyughs aufschwingen möchte, die Mengen an Abfall, Aas und Fleisch, die notwendig sind, damit der Otyugh nicht auf der Suche nach Nahrung weiterzieht, leicht unterschätzen. Mehr als ein „zahmer" Otyugh hat seinen Meister gefressen, nachdem alle Abfälle in seiner Suhle aufgebraucht waren.

```statblock
name: Otyugh
image: token/otyugh.webp
source: MM
size: Groß
type: Aberration
alignment: Neutral
ac: 14
ac_class: natürliche Rüstung
hp: 114
hit_dice: 12d10 + 48
modifier: 0
stats:
  - 16
  - 11
  - 19
  - 6
  - 13
  - 6
speed: 9 m
saves:
  - Kon: 7
senses: <STATBLOCK-MARKDOWN-LINK>01-Spielleiter/Sinne-phb#Dunkelsicht|Dunkelsicht<STATBLOCK-MARKDOWN-LINK> 36 m, passive Wahrnehmung 11
languages: Otyugh
cr: 5
traits:
  - name: Eingeschränkte Telepathie
    desc: "Der Otyugh kann magisch einfache Botschaften und Bilder an jede Kreatur innerhalb von 36 m, die eine Sprache verstehen kann, übermitteln. Diese Form der Telepathie erlaubt es der empfangenden Kreatur nicht, telepathisch zu antworten."
actions:
  - name: Merhfachangriff
    desc: "Der Otyugh führt drei Angriffe durch; einen mit seinem Biss und zwei mit seinen Tentakeln."
  - name: Biss
    desc: "*Nahkampf-Waffenangriff:* +6 zum Treffen, Reichweite 1,5 m, ein Ziel. *Treffer:* 12 (2d8+3) Stichschaden. Wenn das Ziel eine Kreatur ist, muss sie einen `Konstitutionsrettungswurf` gegen Krankheit mit `SG 15` ablegen, um nicht <STATBLOCK-MARKDOWN-LINK>01-Spielleiter/Zustände-phb#Vergiftet|vergiftet<STATBLOCK-MARKDOWN-LINK> zu werden, bis die Krankheit geheilt ist. Alle 24 Stunden, die vergehen, muss das Ziel den Rettungswurf wiederholen und bei einem Fehlschlag seine maximalen Trefferpunkte um 5 (1d10) verringern. Die Krankheit wird bei einem Erfolg geheilt. Das Ziel stirbt, wenn die Krankheit es auf0 maximale Trefferpunkte reduziert. Diese Verringerung der maximalen Trefferpunkte des Ziels hält an, bis die Krankheit geheilt wird."
  - name: Tentakel
    desc: "*Nahkampf-Waffenangriff:* +6 zum Treffen, Reichweite 3 m, ein Ziel. *Treffer:* 7 (1d8+3) Wuchtschaden plus 4 (1d8) Stichschaden. Wenn das Ziel mittelgroß oder kleiner ist, wird es <STATBLOCK-MARKDOWN-LINK>01-Spielleiter/Zustände-phb#Gepackt|gepackt<STATBLOCK-MARKDOWN-LINK> (SG zum Entkommen 13) und <STATBLOCK-MARKDOWN-LINK>01-Spielleiter/Zustände-phb#Festgesetzt|festgesetzt<STATBLOCK-MARKDOWN-LINK>, bis der Haltegriff endet. Der Otyugh hat zwei Tentakel, und er kann mit jedem davon ein Ziel packen."
  - name: Tentakelramme
    desc: Der Otyugh rammt Kreaturen, die er <STATBLOCK-MARKDOWN-LINK>01-Spielleiter/Zustände-phb#Gepackt|gepackt<STATBLOCK-MARKDOWN-LINK> hat, ineinander oder in eine feste Oberfläche. Jede Kreatur muss einen `Konstitutionsrettungswurf` gegen SG `14` ablegen, um nicht 10 (2W6+3) Wuchtschaden zu erleiden und bis zum Ende des nächsten Zugs des Otyughs <STATBLOCK-MARKDOWN-LINK>01-Spielleiter/Zustände-phb#Betäubt|betäubt<STATBLOCK-MARKDOWN-LINK> zu sein. Bei einem erfolgreichen Rettungswurf erleidet das Ziel den halben Wuchtschaden und ist nicht <STATBLOCK-MARKDOWN-LINK>01-Spielleiter/Zustände-phb#Betäubt|betäubt<STATBLOCK-MARKDOWN-LINK>.
```
^statblock

## Vorkommen

Unterreich