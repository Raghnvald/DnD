---
prefer-view: edit-source read
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Goblin-Psi-Raufbold
Kategorie: Aberration (Goblinoid)
Größe: Klein
HG: 2
Habitat:
  - /
image: token/goblin-psi-brawler-pabtso.webp
status: completed
linter-yaml-title-alias: Goblin-Psi-Raufbold
tags:
  - Monster/Größe/Klein
  - Monster/HG/2
  - Monster/Typ/Aberration/Goblinoid
  - Quelle/5e/pabtso
aliases:
  - Goblin Psi Brawler
  - Goblin-Psi-Raufbold
---
# Goblin-Psi-Raufbold
*Quelle: Die Tiefen von Phandelver: Der zersplitterte Obelisk S. 214*  

Goblin-Psi-Raufbolde nutzen ihre psionischen Fähigkeiten, um ihre physische Kraft zu erhöhen. Ihre Schläge werden vom Knistern psychischer Energie begleitet, und wenn sie verärgert sind, können Goblin-Psi-Raufbolde einen telekinetischen Stoß entfesseln, der ihre Gegner umwerfen kann.

## Psionischer Goblin

Nicht alle psionischen Goblins entstehen auf dieselbe Weise. Manche sind schon bei ihrer Geburt von der Energie des Fernen Reichs so verändert. Andere verwandeln sich mit ihrer psionischen Kraft selbst oder gehen Vereinbarungen mit anderen Aberrationen ein, die ihnen bei der Verwandlung helfen, wenn sie dafür als Mitglied ihrer Stoßtruppen dienen. Das Ergebnis ist allerdings immer dasselbe: ein Goblin mit widernatürlichen und kaum kontrollierten psychischen Kräften.

$\quad$Psionische Goblins haben oft Schwierigkeiten, die turbulente psychische Energie zu kontrollieren, die ihren Körper und Geist durchdringt. Diejenigen psionischen Goblins, die lernen, ihre psychischen Kräfte willentlich zu nutzen, sind beachtliche Gegner im Kampf. Psionische Goblins ergänzen ihre Kampffähigkeiten häufig mit Telekinese, und im Geheimen agierende Gruppen aus psionischen Goblin-Kriegern können telepathisch miteinander kommunizieren - ein großer Vorteil für geheime Missionen.

```statblock
name: Goblin-Psi-Raufbold
source: PaBTSO
image: token/goblin-psi-brawler-pabtso.webp
size: Klein
type: Aberration
subtype: Goblinoid
alignment: jede Gesinnung
ac: 15
ac_class: "<STATBLOCK-MARKDOWN-LINK>Gegenstände/Beschlagene_Rüstung-phb|beschlagene Rüstung<STATBLOCK-MARKDOWN-LINK>"
hp: 31
hit_dice: 7d6 + 7
modifier: 3
stats:
  - 9
  - 17
  - 12
  - 16
  - 15
  - 10
speed: 9 m
saves:
  - Int: 5
  - Wei: 4
skillsaves:
  - name: <STATBLOCK-MARKDOWN-LINK>01-Spielleiter/Fertigkeiten-phb#Heimlichkeit|Heimlichkeit<STATBLOCK-MARKDOWN-LINK>
    desc: "+7"
damage_resistances: Psychisch
senses: <STATBLOCK-MARKDOWN-LINK>01-Spielleiter/Sinne-phb#Dunkelsicht|Dunkelsicht<STATBLOCK-MARKDOWN-LINK> 18 m, passive Wahrnehmung 12
languages: Gemeinsprache, Goblinisch, Telepathie auf 9 m
cr: "2"
traits:
  - name: Mentaler Ausbruch
    desc: "Wenn der Goblin stirbt, entlädt sich seine mentale Energie in einer psychischen Explosion. Jede Kreatur im Abstand von bis zu 1,5 Metern von ihm muss einen `SG-13-Intelligenzrettungswurf` bestehen, oder sie erleidet 5 (2d4) psychischen Schaden."
  - name: Mentale Ausdauer
    desc: "Der Goblin ist bei Rettungswürfen gegen Effekte, die ihn <STATBLOCK-MARKDOWN-LINK>01-Spielleiter/Zustände-phb#Bezaubert|bezaubern<STATBLOCK-MARKDOWN-LINK> oder <STATBLOCK-MARKDOWN-LINK>01-Spielleiter/Zustände-phb#Verängstigt|verängstigen<STATBLOCK-MARKDOWN-LINK> würden, im Vorteil."
actions:
  - name: Mehrfachangriff
    desc: "Der Goblin führt zwei waffenlose Angriffe aus."
  - name: Waffenloser Angriff
    desc: "*Nahkampf-Waffenangriff:* +5 auf Treffer, Reichweite 1,5 m, ein Ziel. *Treffer:* 5 (1d4+3) Wuchtschaden plus 3 (1d6) psychischer Schaden."
bonus_actions:
  - name: Behändes Entkommen
    desc: "Der Goblin führt die <STATBLOCK-MARKDOWN-LINK>01-Spielleiter/Aktionen-phb#Rückzug|Rückzug<STATBLOCK-MARKDOWN-LINK>- oder <STATBLOCK-MARKDOWN-LINK>01-Spielleiter/Aktionen-phb#Verstecken|Verstecken<STATBLOCK-MARKDOWN-LINK>-Aktion aus."
  - name: Telekinetischer Schub
    desc: "Der Goblin zielt auf eine Kreatur im Abstand von bis zu neun Metern von sich, die er sehen kann und entfesselt einen Schub aus telekinetischer Energie. Das Ziel muss einen `SG-13-Stärkerettungswurf` bestehen, oder es wird <STATBLOCK-MARKDOWN-LINK>01-Spielleiter/Zustände-phb#Liegend|umgestoßen<STATBLOCK-MARKDOWN-LINK>."
```
^statblock