---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Geist
Kategorie: Untoter
Größe: Mittelgroß
HG: 4
Habitat:
  - Stadt
  - Unterreich
image: token/ghost.webp
Status: completed
linter-yaml-title-alias: Geist
tags:
  - Monster/Größe/Mittelgroß
  - Monster/Habitat/Stadt
  - Monster/Habitat/Unterreich
  - Monster/HG/4
  - Monster/Typ/Untote
  - Quelle/5e/mm
aliases:
  - Geist
---
# Geist
*Quelle: Monsterhandbuch  S. 132. Verfügbar im <span title='Systems Reference Document (5.1)'>SRD</span> und dem Grundregelwerk (2014)*  

Ein Geist ist die Seele einer einst lebenden Kreatur, die gebunden ist, einen bestimmten Ort, eine Kreatur oder einen Gegenstand heimzusuchen, der ihr im Leben wichtig war.

## Unerledigte Aufgaben

Ein Geist sehnt sich danach, eine unerledigte Aufgabe aus seinem Leben zu erfüllen. Er könnte seinen Tod rächen, einen Eid erfüllen oder einem geliebten Menschen eine Nachricht überbringen wollen. Ein Geist begreift vielleicht nicht, dass er gestorben ist, und folgt weiter den alltäglichen Routinen seines Lebens. Andere werden von Bösartigkeit oder Gehässigkeit angetrieben, wie bei einem Geist, der nicht ruhen will, bis alle Mitglieder einer bestimmten Familie oder Organisation tot sind.

Die sicherste Methode, um einen Geist loszuwerden, besteht darin, seine unerledigte Aufgabe zu erfüllen. Ein Geist kann leichter zerstört werden, indem man eine Schwäche nutzt, die mit seinem früheren Leben verbunden ist. Der Geist einer Person, die zu Tode gefoltert worden ist, könnte durch diese Folter erneut getötet werden. Der Geist eines Gärtners könnte verwundbarer werden, wenn er dem starken Duft von Blumen ausgesetzt ist.

## Gespenstische Manifestationen

Empfindungen von tiefer Trauer, Einsamkeit und unerfüllter Sehnsucht gehen von Orten aus, an denen es zu Geistererscheinungen kommt. Seltsame Geräusche oder unnatürliche Stille erschaffen eine unheimliche Atmosphäre. Kalte Flecken breiten sich in Räumen mit einem prasselnden Feuer aus. Ein erstickender Gestank könnte in einen Bereich eindringen, unbelebte Gegenstände könnten sich selbstständig bewegen und Leichen könnten sich aus ihren Gräbern erheben. Der Geist hat keine Kontrolle über diese Manifestationen; sie treten einfach ein.

## Untote Natur

Ein Geist braucht keine Luft, Nahrung, Wasser oder Schlaf.

```statblock
name: Geist
image: token/ghost.webp
source:
  - MM
size: Mittelgroß
type: Untot
alignment: jede Gesinnung
ac: 11
hp: 45
hit_dice: 10d8
modifier: 1
stats:
  - 7
  - 13
  - 10
  - 10
  - 12
  - 17
speed: 0 m, fliegen 12 m (schweben)
damage_resistances: Blitz, Feuer, Säure, Schall; Wucht-, Stichund Hiebschaden durch nichtmagische Angriffe
damage_immunities: Gift, Kälte, nekrotisch
condition_immunities: <STATBLOCK-MARKDOWN-LINK>Zustände-phb#Bezaubert|Bezaubert<STATBLOCK-MARKDOWN-LINK>, <STATBLOCK-MARKDOWN-LINK>Zustände-phb#erschöpft|erschöpft<STATBLOCK-MARKDOWN-LINK>, <STATBLOCK-MARKDOWN-LINK>Zustände-phb#festgesetzt|festgesetzt<STATBLOCK-MARKDOWN-LINK>, <STATBLOCK-MARKDOWN-LINK>Zustände-phb#gelähmt|gelähmt<STATBLOCK-MARKDOWN-LINK>, <STATBLOCK-MARKDOWN-LINK>Zustände-phb#gepackt|gepackt<STATBLOCK-MARKDOWN-LINK>, <STATBLOCK-MARKDOWN-LINK>Zustände-phb#liegend|liegend<STATBLOCK-MARKDOWN-LINK>, <STATBLOCK-MARKDOWN-LINK>Zustände-phb#verängstigt|verängstigt<STATBLOCK-MARKDOWN-LINK>, <STATBLOCK-MARKDOWN-LINK>Zustände-phb#vergiftet|vergiftet<STATBLOCK-MARKDOWN-LINK>, <STATBLOCK-MARKDOWN-LINK>Zustände-phb#versteinert|versteinert<STATBLOCK-MARKDOWN-LINK>
senses: <STATBLOCK-MARKDOWN-LINK>Sinne-phb#Dunkelsicht|Dunkelsicht<STATBLOCK-MARKDOWN-LINK> 18 m, passive Wahrnehmung 11
languages: Alle Sprachen die er im Leben kannte
cr: "4"
environment: Stadt, Unterreich
traits:
  - name: Ätherische Sicht
    desc: Der Geist kann 18 min die Ätherebene blicken, wenn er sich auf der Materiellen Ebene befindet, und andersherum.
  - name: Körperlose Bewegung
    desc: Der Geist kann sich durch Kreaturen und Gegenstände bewegen, als seien sie schwieriges Gelände. Er erleidet 5 (1d10) Energieschaden, wenn er seinen Zug in einem Gegenstand beendet.
actions:
  - name: Verdorrende Berührung
    desc: "*Nahkampf-Waffenangriff:* +5 zum Treffen, Reichweite 1,5 m, ein Ziel. *Treffer:* 17 (4d6 + 3) nekrotischer Schaden."
  - name: Körperlosigkeit
    desc: Der Geist kann die Ätherebene von der Materiellen Ebene aus betreten und andersherum. Er ist auf der Materiellen Ebene sichtbar, solange er sich in der Äthergrenze befindet, doch kann er nichts auf der anderen Ebene beeinflussen oder beeinflusst werden.
  - name: Grauenhaftes Antlitz
    desc: Alle nicht untoten Kreaturen im Umkreis von 18 m um den Geist, die ihn sehen können, müssen einen Weisheits-Rettungswurf gegen SG 13 schaffen, um nicht für 1 Minute <STATBLOCK-MARKDOWN-LINK>Zustände-phb#Verängstigt|verängstigt<STATBLOCK-MARKDOWN-LINK> zu werden. Wenn der Rettungswurf um 5 oder mehr Punkte misslingt, altert das Ziel außerdem um 1d4 × 10 Jahre. Die Kreatur kann den gleichen Rettungswurf am Ende eines jeden Zuges wiederholen und den Effekt auf sich selbst bei einem Erfolg beenden. Wenn der Rettungswurf des Ziels erfolgreich ist oder der Effekt für es endet, ist es für die nächsten 24 Stunden gegen das Grauenhafte Antlitz des Geistes immun. Der Alterungseffekt kann mit dem Zauber <STATBLOCK-MARKDOWN-LINK>Vollständige_Genesung-phb|Vollständige Genesung<STATBLOCK-MARKDOWN-LINK> umgekehrt werden, aber nur innerhalb von 24 Stunden, nachdem er eingetreten ist.
  - name: Inbesitznahme (Aufladung 6)
    desc: |-
      Ein Humanoider, der sich innerhalb von 1,5 m um den Geist befindet und den dieser sehen kann, muss einen Charismarettungswurf gegen SG 13 schaffen, um nicht von dem Geist besessen zu werden; der Geist verschwindet, und das Ziel ist <STATBLOCK-MARKDOWN-LINK>Zustände-phb#Kampfunfähig|kampfunfähig<STATBLOCK-MARKDOWN-LINK> und verliert die Kontrolle über seinen Körper. 

      Der Geist kontrolliert jetzt den Körper, nimmt dem Ziel aber nicht sein Bewusstsein. Der Geist kann nicht Ziel von Angriffen, Zaubern oder anderen Effekten werden, außer solchen, die Untote vertreiben, und er behält seine Gesinnung, Intelligenz, Weisheit, Charisma sowie seine Immunität gegen die Zustände <STATBLOCK-MARKDOWN-LINK>Zustände-phb#Bezaubert|bezaubert<STATBLOCK-MARKDOWN-LINK> und <STATBLOCK-MARKDOWN-LINK>Zustände-phb#Verängstigt|verängstigt<STATBLOCK-MARKDOWN-LINK>. Er verwendet ansonsten die Spielwerte des besessenen Ziels, erhält aber keinen Zugriff auf sein Wissen, seine Klassenmerkmale oder Übungsboni.

      Die Inbesitznahme hält an, bis der Körper auf 0 TP fällt, der Geist sie als Bonusaktion beendet, oder der Geist vertrieben oder von einem Effekt wie dem Zauber <STATBLOCK-MARKDOWN-LINK>Gutes_und_Böses_bannen-phb|Gutes und Böses bannen<STATBLOCK-MARKDOWN-LINK> ausgetrieben wird. Wenn die Inbesitznahme endet, taucht der Geist in einem nicht besetzten Bereich innerhalb von 1,5 m um den Körper auf. Das Ziel ist für 24 Stunden nach Ende der Besessenheit oder einem erfolgreichem Rettungswurf gegen die Inbesitznahme durch diesen Geist immun.
```
^statblock