---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Schildwächter
Kategorie: Konstrukt
Größe: Groß
HG: 7
Habitat:
  - Stadt
image: token/shield-guardian.webp
status: WIP
linter-yaml-title-alias: Schildwächter
tags:
  - Monster/Größe/Groß
  - Monster/Habitat/Stadt
  - Monster/HG/7
  - Monster/Typ/Konstrukt
  - Quelle/5e/mm
aliases:
  - Schildwächter
  - Shield Guardian
---
# Schildwächter
*Quelle: Monsterhandbuch S. 247. Verfügbar im <span title='Systems Reference Document (5.1)'>SRD</span>*  

Magier und andere Zauberwirker erschaffen Schildwächter zu ihrem Schutz. Ein Schildwächter bewegt sich an der Seite seines Meisters und absorbiert Schaden, um ihn so lange wie möglich am Leben zu halten.

## Amulett des Meisters

eder Schildwächter ist auf magische Weise mit einem Amulett verbunden. Ein Schildwächter kann nur mit einem Amulett verbunden sein, und wenn das Amulett zerstört wird, ist der Schildwächter [[Zustände-phb#Kampfunfähig|kampfunfähig]], bis ein Ersatzamulett erschaffen wird. Das Amulett eines Schildwächters kann direkt angegriffen werden, wenn es nicht getragen oder in der Hand gehalten wird. Es hat RK 10, 10 Trefferpunkte und ist immun gegen Giftschaden und psychischen Schaden. Ein Amulett zu erschaffen, dauert 1 Woche und kostet 1.000 GM in Komponenten.

Der einzige Fokus des Schildwächters ist es, den Träger des Amuletts zu schützen. Der Träger des Amuletts kann dem Wächter befehlen, seine Feinde anzugreifen oder den Träger vor Angriffen zu schützen. Wenn ein Angriff droht, den Träger zu verwunden, kann das Konstrukt den Hieb magisch in seinen eigenen Körper absorbieren, selbst auf Entfernung.

Ein Zauberwirker kann einen einzelnen Zauber im Schildwächter speichern, den dieser dann auf Befehl oder unter bestimmten Bedingungen wirken kann. Viele Magier wurden von ihren Gegnern schon für wehrlos erachtet, als der Schildwächter mächtige magische Energie auf sie entfesselte und sie so überraschte.

## Kostbarer Schatz 

Weil der Besitz eines Schildwächters übertragen werden kann, indem sein Amulett einer anderen Kreatur überreicht wird, verlangen manche Magier exorbitante Summen von Prinzen, Adeligen und Verbrecherfürsten, um für sie Schildwächter zu erschaffen. Gleichzeitig ist ein Schildwächter eine mächtige Beute für jeden, der es schafft, seinen Meister zu erschlagen und das Amulett für sich zu beanspruchen.

## Konstruktnatur

Ein Schildwächter muss nicht atmen, essen, trinken oder schlafen.

``` statblock
name: Schildwächter
image: token/shield-guardian.webp
source:
  - MM
size: Groß
type: Konstrukt
alignment: gesinnungslos
ac: 17
ac_class: natürliche Rüstung
hp: 142
hit_dice: 15d10 + 60
modifier: -1
stats:
  - 18
  - 8
  - 18
  - 7
  - 10
  - 3
speed: 9 m
damage_immunities: Gift
condition_immunities: <STATBLOCK-MARKDOWN-LINK>01-Spielleiter/Zustände-phb#Bezaubert|Bezaubert<STATBLOCK-MARKDOWN-LINK>, <STATBLOCK-MARKDOWN-LINK>01-Spielleiter/Zustände-phb#Erschöpft|Erschöpft<STATBLOCK-MARKDOWN-LINK>, <STATBLOCK-MARKDOWN-LINK>01-Spielleiter/Zustände-phb#Gelähmt|Gelähmt<STATBLOCK-MARKDOWN-LINK>, <STATBLOCK-MARKDOWN-LINK>01-Spielleiter/Zustände-phb#Verängstigt|Verängstigt<STATBLOCK-MARKDOWN-LINK>, <STATBLOCK-MARKDOWN-LINK>01-Spielleiter/Zustände-phb#Vergiftet|Vergiftet<STATBLOCK-MARKDOWN-LINK>
senses: <STATBLOCK-MARKDOWN-LINK>01-Spielleiter/Sinne-phb#Blindsicht|Blindsicht<STATBLOCK-MARKDOWN-LINK> 3 m, <STATBLOCK-MARKDOWN-LINK>01-Spielleiter/Sinne-phb#Dunkelsicht|Dunkelsicht<STATBLOCK-MARKDOWN-LINK> 18 m, passive Wahrnehmung 10
languages: Versteht Befehle in jeder Sprache, kann aber nicht sprechen
cr: "7"
traits:
  - name: Gebunden
    desc: "Der Schildwächter ist magisch an ein Amulett gebunden. Solange sich der Wächter und sein Amulett auf der gleichen Existenzebene befinden, kann der Träger des Amuletts den Wächter telepathisch auffordern, an seine Seite zu kommen, und der Wächter kennt die Entfernung und Richtung zum Amulett. Wenn sich der Schildwächter innerhalb von 18 m zum Träger des Amuletts befindet, wird der halbe Schaden, den der Träger erleidet (aufgerundet) auf den Schildwächter übertragen."
  - name: Regeneration
    desc: "Der Schildwächter erhält zu Beginn seines Zugs 10 Trefferpunkte zurück, wenn er mindestens 1 Trefferpunkt besitzt."
  - name: Zauberspeicher
    desc: "Ein Zauberwirker, der das Amulett des Schildwächters trägt, kann den Schildwächter einen Zauber des 4. Grades oder niedriger speichern lassen. Dazu muss der Träger den Zauber auf den Wächter wirken. Der Zauber hat keinen Effekt, wird aber im Wächter gespeichert. Wenn der Träger des Amuletts es ihm befiehlt oder wenn die Situation eintritt, die der Zauberwirker bestimmt hat, wirkt der Schildwächter den gespeicherten Zauber mit allen Parametern, die der ursprüngliche Zauberwirker festgelegt hat. Dabei sind keine Komponenten notwendig. Wenn der Zauber gewirkt oder ein neuer Zauber gespeichert wird, gehen zuvor gespeicherte Zauber verloren."
actions:
  - name: Mehrfachangriff
    desc: "Der Schildwächter führt zwei Faust-Angriffe durch."
  - name: Faust
    desc: "*Nahkampf-Waffenangriff:* +7 zum Treffen, Reichweite 1,5 m, ein Ziel. *Treffer:* 11 (2d6 + 4) Wuchtschaden."
reactions:
  - name: Abschirmen
    desc: "Wenn eine Kreatur einen Angriff gegen den Träger des Amuletts des Schildwächters ausführt, dann gewährt der Schildwächter dem Träger +2 RK, wenn er sich innerhalb von 1,5 m zum Träger aufhält."
```
^statblock

## Vorkommen

Stadt