---
Bezeichnung: "Appendix D: Creatures"
Status: WIP
linter-yaml-title-alias: "Appendix D: Creatures"
tags:
  - Quelle/5e/bgdia
aliases:
  - "Appendix D: Creatures"
---
# Appendix D: Creatures
*Source: Baldur's Gate: Descent Into Avernus, p. 228* 

Creatures that are not described in the "Monster Manual" but appear multiple times in the adventure are presented in this appendix in alphabetical order.

```base
filters:
  and:
    - file.folder.startsWith("D&D/Bestiarium")
views:
  - type: cards
    name: Anhang A Kreaturen
    filters:
      or:
        - file.tags.contains("Quelle/5e/bgdia")
    order:
      - Name
    cardSize: 130
    image: note.IMAGE
    imageFit: contain

```