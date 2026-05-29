---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Ruxithid der Auserwählte
Kategorie: Aberration (Goblinoid)
Größe: Mittelgroß
HG: 5
Habitat:
  - /
image: token/ruxithid-the-chosen-pabtso.webp
status: WIP
linter-yaml-title-alias: Ruxithid der Auserwählte
tags:
  - Monster/Größe/Mittelgroß
  - Monster/HG/5
  - Monster/Typ/Aberration/Goblinoid
  - Quelle/5e/pabtso
aliases:
  - Ruxithid der Auserwählte
  - Ruxithid the Chosen
---
# Ruxithid der Auserwählte
*Quelle: Phandelver and Below: The Shattered Obelisk p. 99*  

Vor Jahrhunderten wurde der Außenposten von Gedankenschindern erobert. Die Goblins dort waren den seltsamen Kräften der Illithiden ausgesetzt, wodurch eine Untergruppe von Goblins ungewöhnliche psionische Kräfte entwickelte. Die Gedankenschinder zogen schließlich ab, aber die Goblins blieben abgeschottet vom Rest der Welt zurück, bis die Gedankenschinder-Fanatiker sie vor Kurzem aufsuchten. Einige der Nachkommen dieser Goblins besitzen psionische Kräfte, wie die Goblin-PsiBefehlshaber und Goblin-Psi-Raufbolde in ihren Reihen beweisen. Die Goblins nennen sich selbst „Sägezank": eine vereinfachte Form des Wortes für ,,Goblin" im Dialekt der Illithiden der Tiefensprache.

In den letzten Wochen hat der Anführer der SägezankGoblins einen geheimnisvollen Edelstein gefunden. Ruxithid der Auserwählte weiß nicht, dass eine neue Gruppe Gedankenschinder-Fanatiker, die Macht aus dem Femen Reich beziehen, ihm den Edelstein untergeschoben haben. Der Edelstein ermöglicht es Ruxithid, telepathisch mit den Gedankenschindern zu kommunizieren, die er für Götter hält.

```statblock
name: Ruxithid der Auserwählte
image: [[token/ruxithid-the-chosen-pabtso.webp]]
source: PaBTSO
size: Mittelgroß
type: Aberration
subtype: Goblinoid
alignment: Neutral Böse
ac: 15
ac_class: "<STATBLOCK-MARKDOWN-LINK>Gegenstände/Kettenhemd-phb.md|Kettenhemd<STATBLOCK-MARKDOWN-LINK>"
hp: 88
hit_dice: 16d8 + 16
modifier: 4
stats:
  - 14
  - 19
  - 12
  - 18
  - 15
  - 12
speed: 9 m, Fliegen 9 m (Schweben)
saves:
  - Int: 7
  - Wei: 5
skillsaves:
  - name: <STATBLOCK-MARKDOWN-LINK>01-Spielleiter/Fertigkeiten-phb#Heimlichkeit|Heimlichkeit<STATBLOCK-MARKDOWN-LINK>
    desc: "+5"
  - name: <STATBLOCK-MARKDOWN-LINK>01-Spielleiter/Fertigkeiten-phb#Motiv%20erkennen|Motiv erkennen<STATBLOCK-MARKDOWN-LINK>
    desc: "+5"
  - name: <STATBLOCK-MARKDOWN-LINK>01-Spielleiter/Fertigkeiten-phb#Wahrnehmung|Wahrnehmung<STATBLOCK-MARKDOWN-LINK>
    desc: "+10"
damage_resistances: Psychisch
senses: <STATBLOCK-MARKDOWN-LINK>01-Spielleiter/Sinne-phb#Dunkelsicht|Dunkelsicht<STATBLOCK-MARKDOWN-LINK> 18 m, passive Wahrnehmung 15
languages: Gemeinsprache, Goblinisch, Telepathie auf 18 m
cr: "5"
traits:
  - name: Legendäre Resistenz (2-mal täglich)
    desc: "Wenn sein Rettungswurf scheitert, kann Ruxithid den Wurf in einen Erfolg verwandeln."
  - name: Mentale Ausdauer
    desc: "Ruxithid ist bei Rettungswürfen gegen Effekte, die ihn <STATBLOCK-MARKDOWN-LINK>01-Spielleiter/Zustände-phb#Bezaubert|bezaubern<STATBLOCK-MARKDOWN-LINK> oder <STATBLOCK-MARKDOWN-LINK>01-Spielleiter/Zustände-phb#Verängstigt|verängstigen<STATBLOCK-MARKDOWN-LINK> würden, im Vorteil."
actions:
  - name: Mehrfachangriff
    desc: "Ruxithid führt zwei Psionisch-aufgeladener-Krummsäbel-Angriffe aus."
  - name: Psionisch aufgeladener Krummsäbel
    desc: "*Nahkampf-Waffenangriff:* +7 auf Treffer, Reichweite 1,5 m, ein Ziel. *Treffer:* 11 (2d6+4) Hiebschaden plus 7 (2d6) psychischen Schaden."
bonus_actions:
  - name: Gehirntentakel (Aufladung 5-6)
    desc: "Ruxithid entfesselt psychische Kristalltentakel aus seinem Gehirn und zielt auf eine Kreatur im Abstand von bis zu neun Metern von ihm, die er sehen kann. Das Ziel muss einen `SG-15-Geschicklichkeits-Rettungswurf` bestehen, oder es erleidet 9 (2d8) psychischen Schaden und ist bis zum Beginn von Ruxithids nächstem Zug <STATBLOCK-MARKDOWN-LINK>01-Spielleiter/Zustände-phb#Betäubt|betäubt<STATBLOCK-MARKDOWN-LINK>."
  - name: Kampfbefehl
    desc: "Ruxithid befiehlt einer verbündeten Kreatur im Abstand von bis zu 18 Metern von ihm, die er sehen kann, anzugreifen. Die Kreatur kann ihre Reaktion sofort nutzen, um einen Nahkampfwaffenangriff gegen ein Ziel in Reichweite auszuführen."
```
^statblock