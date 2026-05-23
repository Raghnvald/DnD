---
Bezeichnung: "Anhang A: Kreaturen"
tags:
  - Quelle/5e/pabtso
aliases:
  - Appendix A: Bestiary
---
# Anhang A: Kreaturen
*Quellen: Die Tiefen von Phandelver: Der zersplitterte Obelisk, S. 203* 

Dieser Anghang beschreibt die Kreaturen, welche in diesem Abenteuer erscheinen, in alphabetischer Reihenfolge. Die "Einführung" des "Monsterhandbuchs" erklärt, wie die Wertekästen der Kreaturen zu lesen sind.

```base
filters:
  and:
    - file.folder.startsWith("D&D/Bestiarium")
views:
  - type: cards
    name: Anhang A Kreaturen
    filters:
      or:
        - file.tags.contains("Quelle/5e/lmop")
        - file.tags.contains("Quelle/5e/pabtso")
    order:
      - Bezeichnung
    cardSize: 130
    image: note.Image
    imageFit: contain
```