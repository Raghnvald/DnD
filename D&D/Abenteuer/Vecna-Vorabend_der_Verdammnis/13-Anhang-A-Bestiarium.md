---
Bezeichnung: "Anhang A: Bestiarium"
Status: WIP
linter-yaml-title-alias: "Anhang A: Bestiarium"
tags:
  - Quelle/5e/veor
aliases:
  - "Anhang A: Bestiarium"
  - "Appendix A: Bestiary"
---
# Anhang A: Bestiarium
*Quelle: Vecna: Vorabend der Verdammnis* 

In diesem Anhang werden Kreaturen, die im Abenteuer auftreten, in alphabetischer Reihenfolge beschrieben. In der Einführung des *Monsterhandbuchs* wird erklärt, wie die Spielwerte einer Kreatur zu verstehen sind. 

```base
filters:
  and:
    - file.folder.startsWith("D&D/Bestiarium")
formulas:
  Bezeichnung: link(file, Bezeichnung)
views:
  - type: table
    name: Status
    filters:
      and:
        - file.tags.contains("Quelle/5e/veor")
    order:
      - file.name
      - formula.Bezeichnung
      - Kategorie
      - Größe
      - HG
      - Habitat
      - status
      - Image
  - type: cards
    name: Anhang A Kreaturen
    filters:
      or:
        - file.tags.contains("Quelle/5e/veor")
    order:
      - Bezeichnung
    cardSize: 130
    image: note.Image
    imageFit: contain

```