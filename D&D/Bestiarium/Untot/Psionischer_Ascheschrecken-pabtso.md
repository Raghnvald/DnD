---
prefer-view: edit-source read
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Psionischer Ascheschrecken
Kategorie: Untoter
Größe: Mittelgroß
HG: 7
Habitat:
  - /
Status: WIP
linter-yaml-title-alias: Psionischer Ascheschrecken
tags:
  - Monster/Größe/Mittelgroß
  - Monster/HG/7
  - Monster/Typ/Untote
  - Quelle/5e/pabtso
aliases:
  - Psionic Ashenwight
  - Psionischer Ascheschrecken
image: token/psionic-ashenwight-pabtso.webp
status: WIP
---
# Psionischer Ascheschrecken
*Quelle: Die Tiefen von Phandelver: Der zersplitterte Obelisk S. 204*  

Wenn ein Ascheschrecken in der Nähe einer Kristallader entsteht, die mit aberranter Energie erfüllt ist, oder wenn ein Ascheschrecken sich länger in einem Bereich voller finsterer Magie aufhält, kann er psionische Fähigkeiten entwickeln. Ein psionischer Ascheschrecken ist deutlich intelligenter als andere Ascheschrecken. Allerdings ist das daraus entstehende Bewusstsein neu und hat keinerlei Verbindung zum Bewusstsein, das der Ascheschrecken hatte, als er noch am Leben war.

Manche psionische Ascheschrecken widmen ihr Dasein der Rekonstruktion ihres früheren Lebens, andere streben danach, anderen Ascheschrecken zu dieser neuen psionischen Kraft zu verhelfen.

## Ascheschrecken

Wenn ein von Grausamkeit und Wut erfüllter Humanoide in einem Bereich stirbt, der vom Fernen Reich korrumpiert ist, ersteht die Kreatur manchmal als Ascheschrecken wieder auf. Die Haut dieser schrecklichen Untoten ist ausgetrocknet und in ihren Augen leuchtet oft eine außerweltliche Macht.

```statblock
name: Psionischer Ascheschrecken
image: token/psionic-ashenwight-pabtso.webp
source: PaBTSO
size: Mittelgroß
type: Untoter
alignment: normalerweise  Neutral
ac: 16
ac_class: natürliche Rüstung
hp: 78
hit_dice: 12d8 + 24
modifier: 1
stats:
  - 19
  - 13
  - 15
  - 17
  - 14
  - 6
speed: 7,5 m
saves:
  - Str: 7
  - Kon: 5
  - Int: 6
  - Wei: 5
damage_resistances: Gift, Nekrotisch, Psychisch
condition_immunities: Bewusstlos, Bezaubert, Erschöpft, Gelähmt, Verängstigt, Vergiftet
senses: passive Wahrnehmung 12
languages: Versteht alle zu Lebzeiten bekannten Sprachen, aber kann nicht sprechen, Telepathie auf 36 m
cr: 7
actions:
  - name: Mehrfachangriff
    desc: Der Ascheschrecken führt zwei Nekrotischer-Splitter-Angriffe aus. Er setzt auch seine Psionische Krone ein, falls sie verfügbar ist.
  - name: Nekrotischer Splitter
    desc: "*Nahkampf- oder Fernkampf-Waffenangriff:* +7 zum Treffen, Reichweite 1,5 m oder 18 m, ein Ziel. *Treffer:* 7 (1d6 + 4) Stichschaden plus 9 (2d8) nekrotischer Schaden. Wenn das Ziel eine Kreatur ist, ist es bei seinem nächsten Angriffswurf vor dem Ende seines nächsten Zugs im Nachteil."
  - name: Psionische Krone (Aufladung 5-6)
    desc: "Der Ascheschrecken bekränzt den Kopf einer Kreatur, die er im Abstand von bis zu 18 Metern von sich sehen kann, mit einer Krone aus spitzen, geisterhaften Kristallen. Das Ziel muss einen `SG-14- Weisheitsrettungswurf` bestehen, oder es ist eine Minute lang <STATBLOCK-MARKDOWN-LINK>Zustände-phb#Bezaubert|bezaubert<STATBLOCK-MARKDOWN-LINK>. Während es auf diese Weise <STATBLOCK-MARKDOWN-LINK>Zustände-phb#Bezaubert|bezaubert<STATBLOCK-MARKDOWN-LINK> ist, sind die Gedanken des Ziels verlangsamt. Es kann keine Reaktionen verwenden, seine Bewegungsrate ist halbiert und es erleidet zu Beginn jedes seiner Züge 9 (2d8) psychischen Schaden. Das Ziel kann den Rettungswurf am Ende jedes seiner Züge wiederholen und den Effekt bei einem Erfolg beenden."
  - name: Zauberwirken (Psionik)
    desc: |-
      Der Ascheschrecken wirkt einen der folgenden Zauber. Er benötigt dazu keine Komponenten und verwendet Intelligenz als Attribut zum Zauberwirken (Zauberrettungswurf-SC 14):

      **Beliebig oft:** <STATBLOCK-MARKDOWN-LINK>Magierhand-phb|Magierhand<STATBLOCK-MARKDOWN-LINK> (die Hand ist unsichtbar)

      **1-mal täglich:** <STATBLOCK-MARKDOWN-LINK>Gefühle_besänftigen-phb|Gefühle besänftigen<STATBLOCK-MARKDOWN-LINK>
```
^statblock