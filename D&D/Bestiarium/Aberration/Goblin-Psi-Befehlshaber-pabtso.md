---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Goblin-Psi-Befehlshaber
Kategorie: Aberration (Goblinoid)
Größe: Klein
HG: 4
Habitat:
  - /
image: token/goblin-psi-commander-pabtso.webp
status: WIP
tags:
  - Monster/Größe/Klein
  - Monster/HG/4
  - Monster/Typ/Aberration/Goblinoid
  - Quelle/5e/pabtso
aliases:
  - Goblin Psi Commander
---
# Goblin-Psi-Befehlshaber
*Quelle: Die Tiefen von Phandelver: Der zersplitterte Obelisk S. 214*  

Goblin-Psi-Kommandanten gehören zu den wenigen psionischen Goblins, die ihre Kräfte vollständig kontrollieren können. Diese Kontrolle ermöglicht es den Goblin-Psi-Kommandanten, Waffen aus reiner psychischer Energie zu führen. Sie können Schilde aus Geisteskraft beschwören, während sie ihre Gegner mit einem gedankenspaltenden Stoß ins Wanken bringen.

## Psionischer Goblin

Nicht alle psionischen Goblins entstehen auf dieselbe Weise. Manche sind schon bei ihrer Geburt von der Energie des Fernen Reichs so verändert. Andere verwandeln sich mit ihrer psionischen Kraft selbst oder gehen Vereinbarungen mit anderen Aberrationen ein, die ihnen bei der Verwandlung helfen, wenn sie dafür als Mitglied ihrer Stoßtruppen dienen. Das Ergebnis ist allerdings immer dasselbe: ein Goblin mit widernatürlichen und kaum kontrollierten psychischen Kräften.

$\quad$Psionische Goblins haben oft Schwierigkeiten, die turbulente psychische Energie zu kontrollieren, die ihren Körper und Geist durchdringt. Diejenigen psionischen Goblins, die lernen, ihre psychischen Kräfte willentlich zu nutzen, sind beachtliche Gegner im Kampf. Psionische Goblins ergänzen ihre Kampffähigkeiten häufig mit Telekinese, und im Geheimen agierende Gruppen aus psionischen Goblin-Kriegern können telepathisch miteinander kommunizieren - ein großer Vorteil für geheime Missionen.

```statblock
name: Goblin Psi Commander (PaBTSO)
image: token/goblin-psi-commander-pabtso.webp
source: PaBTSO
size: Klein
type: Aberration
subtype: Goblinoid
alignment: jede Gesinnung
ac: 16
ac_class: "<STATBLOCK-MARKDOWN-LINK>Gegenstände/Beschlagene_Rüstung-phb|beschlagene Rüstung<STATBLOCK-MARKDOWN-LINK>"
hp: 58
hit_dice: 13d6 + 13
modifier: 4
stats:
  - 12
  - 19
  - 13
  - 17
  - 15
  - 10
speed: 9 m
saves:
  - Int: 5
  - Wei: 4
skillsaves:
  - name: <STATBLOCK-MARKDOWN-LINK>01-Spielleiter/Fertigkeiten-phb#Heimlichkeit|Heimlichkeit<STATBLOCK-MARKDOWN-LINK>
    desc: "+8"
damage_resistances: Psychisch
senses: <STATBLOCK-MARKDOWN-LINK>01-Spielleiter/Sinne-phb#Dunkelsicht|Dunkelsicht<STATBLOCK-MARKDOWN-LINK> 18 m, passive Wahrnehmung 12
languages: Gemeinsprache, Goblinisch, Telepathie auf 18 m
cr: "4"
traits:
  - name: Mentaler Ausbruch
    desc: "Wenn der Goblin stirbt, entlädt sich seine mentale Energie in einer psychischen Explosion. Jede Kreatur im Abstand von bis zu 1,5 Metern von ihm muss einen `SG-13-Intelligenzrettungswurf` bestehen, oder sie erleidet 10 (4d4) psychischen Schaden."
  - name: Mentale Ausdauer
    desc: "Der Goblin ist bei Rettungswürfen gegen Effekte, die ihn <STATBLOCK-MARKDOWN-LINK>01-Spielleiter/Zustände-phb#Bezaubert|bezaubern<STATBLOCK-MARKDOWN-LINK> oder <STATBLOCK-MARKDOWN-LINK>01-Spielleiter/Zustände-phb#Verängstigt|verängstigen<STATBLOCK-MARKDOWN-LINK> würden, im Vorteil."
actions:
  - name: Mehrfachangriff
    desc: "Der Goblin führt drei Psychische-Klinge-Angriffe aus."
  - name: Psychische Klinge
    desc: "*Nahkampf- oder Fernkampf-Waffenangriff* +6 zum Treffen, Reichweite 1,5 m oder 18 m, ein Ziel. *Treffer:* 11 (2d6 + 4) psychischer Schaden. Das Ziel muss 1W4 von seinem nächsten Angriffs- oder Rettungswurf abziehen, den es vor dem Ende des nächsten Zugs des Goblins ausführt."
  - name: Synaptische Entzweiung (Aufladung 5-6)
    desc: "Der Goblin entfesselt an einem Punkt im Abstand von bis zu 18 Metern von sich, den er sehen kann, psychische Energie in einer Kugel mit einem Radius von neun Metern. Jede Kreatur in diesem Bereich muss einen `SG-13-lntelligenzrettungswurf` ausführen. Scheitert der Wurf, erleidet die Kreatur 14 (4d6) psychischen Schaden und ist bis zum Ende des nächsten Zugs des Goblins <STATBLOCK-MARKDOWN-LINK>01-Spielleiter/Zustände-phb#Kampfunfähig|kampfunfähig<STATBLOCK-MARKDOWN-LINK>. Bei einem erfolgreichen Rettungswurf erleidet die Kreatur nur halb so viel Schaden."
  - name: Zauberwirken (Psionik)
    desc:  |-
      Der Goblin wirkt einen der folgenden Zauber. Er benötigt dazu keine Zauberkomponenten und verwendet Intelligenz als Attribut zum Zauberwirken (Zauberrettungswurf-SG 13):

      **Beliebig oft:** <STATBLOCK-MARKDOWN-LINK>Zauber/Einfache_Illusion-phb.md|Einfache Illusion<STATBLOCK-MARKDOWN-LINK>, <STATBLOCK-MARKDOWN-LINK>Zauber/Magierhand-phb|Magierhand<STATBLOCK-MARKDOWN-LINK> (die Hand ist unsichtbar)
      **je 1-mal täglich:** <STATBLOCK-MARKDOWN-LINK>Zauber/Dissonantes_Flüstern-phb.md|Dissonantes Flüstern<STATBLOCK-MARKDOWN-LINK>, <STATBLOCK-MARKDOWN-LINK>Zauber/Person_bezaubern-phb.md|Person bezaubern<STATBLOCK-MARKDOWN-LINK>, <STATBLOCK-MARKDOWN-LINK>Zauber/Telekinese-phb.md|Telekinese<STATBLOCK-MARKDOWN-LINK>
bonus_actions:
  - name: Behändes Entkommen
    desc: "Der Goblin führt die <STATBLOCK-MARKDOWN-LINK>01-Spielleiter/Aktionen-phb#Rückzug|Rückzug<STATBLOCK-MARKDOWN-LINK>- oder <STATBLOCK-MARKDOWN-LINK>01-Spielleiter/Aktionen-phb#Verstecken|Verstecken<STATBLOCK-MARKDOWN-LINK>-Aktion aus."
reactions:
  - name: Psionischer Schild
    desc: Wenn der Goblin oder einer seiner Verbündeten im Abstand von bis zu 4,5 Metern von ihm von einem Angriffswurf getroffen wird, beschwört der Goblin einen Schild aus Energie. Das Ziel des Angriffs erhält gegen den auslösenden Angriffswurf einen Bonus von +3 auf seine RK, sodass der Angriff möglicherweise fehlschlägt.
```
^statblock