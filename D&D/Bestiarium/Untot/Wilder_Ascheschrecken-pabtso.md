---
prefer-view: edit-source read
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Wilder Ascheschrecken
Kategorie: Untoter
Größe: Mittelgroß
HG: 5
Habitat:
  - /
image: token/feral-ashenwight-pabtso.webp
status: WIP
tags:
  - Monster/Größe/Mittelgroß
  - Monster/HG/5
  - Monster/Typ/Untote
  - Quelle/5e/pabtso
aliases:
  - Wilder Ascheschrecken
  - Feral Ashenwight
linter-yaml-title-alias: Wilder Ascheschrecken
---
# Wilder Ascheschrecken
*Quelle: Die Tiefen von Phandelver: Der zersplitterte Obelisk S. 204*  

Wilde Ascheschrecken erhalten immer noch einen Splitter des Funkens, den sie zu Lebzeiten hatten. Sie haben jedoch keinerlei Erinnerungen oder Gedanken - nur das unbändige Verlangen, alle lebenden Kreaturen zu zerstören, die ihnen begegnen.

## Ascheschrecken

Wenn ein von Grausamkeit und Wut erfüllter Humanoide in einem Bereich stirbt, der vom Fernen Reich korrumpiert ist, ersteht die Kreatur manchmal als Ascheschrecken wieder auf. Die Haut dieser schrecklichen Untoten ist ausgetrocknet und in ihren Augen leuchtet oft eine außerweltliche Macht.

```statblock
name: Wilder Ascheschrecken
image: token/feral-ashenwight-pabtso.webp
source: PaBTSO
size: Mittelgroß
type: Untoter
alignment: normalerweise Neutral Böse
ac: 16
ac_class: natürliche Rüstung
hp: 65
hit_dice: 10d8 + 20
modifier: 1
stats:
  - 19
  - 13
  - 15
  - 4
  - 14
  - 6
speed: 7,5 m
saves:
  - Str: 7
  - Kon: 5
damage_resistances: Gift, Nekrotisch
condition_immunities: Bewusstlos, Bezaubert, Erschöpft, Gelähmt, Verängstigt, Vergiftet
senses: <STATBLOCK-MARKDOWN-LINK>01-Spielleiter/Sinne-phb#Dunkelsicht|Dunkelsicht<STATBLOCK-MARKDOWN-LINK> 36 m, passive Wahrnehmung 12
languages: Versteht zu Lebzeiten bekannte Sprachen, kann aber nicht sprechen
cr: 5
actions:
  - name: Mehrfachangriff
    desc: Der Ascheschrecken führt zwei Nekrotischer-Splitter-Angriffe aus.
  - name: Nekrotischer Splitter
    desc: "*Nahkampf- oder Fernkampf-Waffenangriff:* +7 zum Treffen, Reichweite 1,5 m oder 18 m, ein Ziel. *Treffer:* 7 (1d6+4) nekrotischer Schaden. Wenn das Ziel eine Kreatur ist, ist es bei seinem nächsten Angriffswurf vor dem Ende seines nächsten Zugs im Nachteil."
```
^statblock