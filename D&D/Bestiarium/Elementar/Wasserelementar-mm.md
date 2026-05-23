---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Wasserelementar
Kategorie: Elementar
Größe: Groß
HG: 5
Habitat:
  - Küste
  - Sumpf
  - Unterwasser
image: token/water-elemental.webp
tags:
  - Monster/Größe/Groß
  - Monster/Habitat/Küste
  - Monster/Habitat/Sumpf
  - Monster/Habitat/Unterwasser
  - Monster/HG/5
  - Monster/Typ/Elementar
  - Quelle/5e/mm
aliases:
  - Water Elemental
---
# Wasserelementar
*Quelle: Monsterhandbuch S. 109. Verfügbar im <span title='Systems Reference Document (5.1)'>SRD</span> und dem Grundregelwerk (2014)*  

Ein Wasserelementar ist eine ansteigende Welle, die sich über den Boden wälzt und in größeren Gewässern fast unsichtbar wird. Er umschlingt Kreaturen, die in seinem Weg stehen, und füllt ihre Münder und Lungen so mühelos, wie er Flammen erstickt.

## Elementare

Elementare sind Inkarnationen der Elemente, aus denen das Universum besteht: Erde, Feuer, Luft und Wasser. Auch wenn sie auf ihrer eigenen Existenzebene wenig mehr als belebte Energie sind, können sie doch von Zauberwirkern und mächtigen Wesen gerufen werden, um eine Gestalt anzunehmen und Aufgaben zu erfüllen.

### Lebende Elemente

Auf ihrer Heimatebene sind Elementare nur körperlose Lebenskraft. Ihr dumpfes Bewusstsein manifestiert nur dann eine physische Gestalt, wenn es durch die Macht der Magie fokussiert wird. Ein wilder Geist der elementaren Macht hat keinen Wunsch, außer sich durch das Element seiner Heimatebene zu bewegen. Wie die Tiere der Materiellen Ebene haben diese Elementargeister keine Gesellschaft oder Kultur und wenig Bewusstsein für ihr Selbst.

### Von Magie gerufen

Bestimmte Zauber und magische Gegenstände können einen Elementar beschwören, indem sie ihn von den Inneren Ebenen auf die Materielle Ebene rufen. Elementare haben eine instinktive Abneigung dagegen, von ihrer Heimatebene gerufen und zum Dienst gezwungen zu werden. Eine Kreatur, die einen Elementar beschwört, muss ihren Willen nutzen, um ihn zu beherrschen.

### Gebunden und geformt

Mächtige Magie kann einen Elementargeist in eine materielle Schablone binden, die eine bestimmte Verwendung und Funktion bestimmt. Unsichtbare Pirscher sind Luftelementare, die in eine bestimmte Gestalt gebunden sind, so wie Wasserelementare in Wassergeister geformt werden können.

Die Stärke der Magie und Materialien, die einen Elementar binden, bestimmt, wie gut der Elementar in einer gebundenen Form funktioniert. Golems sind Elementargeister, die in physische Formen gebunden sind, aber schwächere Materialien wie Fleisch und Lehm können die elementare Macht nicht ausreichend binden. Robuste Materialien wie Stein und Eisen erfordern stärkere Magie, die den Elementar aber auch sicherer binden kann.

### Elementare Natur

Ein Elementar braucht keine Luft, Nahrung, Wasser oder Schlaf.

```statblock
name: Wasserelementar
image: token/water-elemental.webp
source:
  - MM
size: Groß
type: Elementar
alignment: Neutral
ac: 14
ac_class: natürliche Rüstung
hp: 114
hit_dice: 12d10 + 48
modifier: 2
stats:
  - 18
  - 14
  - 18
  - 5
  - 10
  - 8
speed: 9 m, schwimmen 27 m
damage_resistances: Säure; Wucht-, Stich- und Hiebschaden durch nichtmagische Angriffe
damage_immunities: Gift
condition_immunities: <STATBLOCK-MARKDOWN-LINK>Zustände-phb#Bewusstlos|Bewusstlos<STATBLOCK-MARKDOWN-LINK>, <STATBLOCK-MARKDOWN-LINK>Zustände-phb#Erschöpfung|erschöpft<STATBLOCK-MARKDOWN-LINK>, <STATBLOCK-MARKDOWN-LINK>Zustände-phb#Festgesetzt|festgesetzt<STATBLOCK-MARKDOWN-LINK>, <STATBLOCK-MARKDOWN-LINK>Zustände-phb#Gelähmt|gelähmt<STATBLOCK-MARKDOWN-LINK>, <STATBLOCK-MARKDOWN-LINK>Zustände-phb#Gepackt|gepackt<STATBLOCK-MARKDOWN-LINK>, <STATBLOCK-MARKDOWN-LINK>Zustände-phb#Liegend|liegend<STATBLOCK-MARKDOWN-LINK>, <STATBLOCK-MARKDOWN-LINK>Zustände-phb#Vergiftet|vergiftet<STATBLOCK-MARKDOWN-LINK>, <STATBLOCK-MARKDOWN-LINK>Zustände-phb#Versteinert|versteinert<STATBLOCK-MARKDOWN-LINK>
senses: <STATBLOCK-MARKDOWN-LINK>Sinne-phb#Dunkelsicht|Dunkelsicht<STATBLOCK-MARKDOWN-LINK> 18 m, passive Wahrnehmung 10
languages: Aqual
cr: "5"
environment: Küste, Sumpf, Unterwasser
traits:
  - name: Wasserform
    desc: Der Elementar kann den Bereich einer feindlichen Kreatur betreten und dort anhalten. Er kann sich durch Bereiche, die nur 2,5 cm groß sind, bewegen, ohne sich quetschen zu müssen.
  - name: Gefrieren
    desc: Wenn der Elementar Kälteschaden erleidet, friert er zum Teil ein; seine Bewegungsrate wird bis zum Ende des nächsten Zugs um 6 m verringert.
actions:
  - name: Mehrfachangriff
    desc: Der Elementar führt zwei Hieb-Angriffe aus.
  - name: Hieb
    desc: "*Nahkampf-Waffenangriff:* +7 zum Treffen, Reichweite 1,5 m, ein Ziel. *Treffer:* 13 (2d8 + 4) Wuchtschaden."
  - name: Überschütten (Aufladung 4-6)
    desc: |-
      jede Kreatur im Bereich des Elementars muss einen Stärkerettungswurf gegen SG 15 ablegen. Bei einem Fehlschlag erleidet ein Ziel 13 (2d8 + 4) Wuchtschaden. Wenn es sich um ein Großes oder kleineres Ziel handelt, wird es außerdem <STATBLOCK-MARKDOWN-LINK>Zustände-phb#Gepackt|gepackt<STATBLOCK-MARKDOWN-LINK> (SG zum Entkommen 14). Bis der Haltegriffendet, ist das Ziel <STATBLOCK-MARKDOWN-LINK>Zustände-phb#Festgesetzt|festgesetzt<STATBLOCK-MARKDOWN-LINK> und kann nicht atmen, es sei denn, es kann Wasser atmen. Wenn der Rettungswurf erfolgreich ist, wird das Ziel aus dem Bereich des Elementars geschoben.

      Der Elementar kann mit dieser Fähigkeit eine große Kreatur oder bis zu zwei mittelgroße oder kleinere Kreaturen auf einmal festhalten. Zu Beginn eines jeden Zuges des Elementars erleidet jedes <STATBLOCK-MARKDOWN-LINK>Zustände-phb#Gepackt|gepackte<STATBLOCK-MARKDOWN-LINK> Ziel 13 (2d8 + 4) Wuchtschaden. Als Aktion kann eine Kreatur innerhalb von 1,5 m um den Elementar eine Kreatur oder einen Gegenstand aus dem Elementar herausziehen, indem sie einen Stärkewurf gegen SG 14 schafft.
```
^statblock