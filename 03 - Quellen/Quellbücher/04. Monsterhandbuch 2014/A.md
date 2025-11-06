---
tags: [Quelle/5e/mm]
---
```base
views:
  - type: table
    name: Table
    filters:
      and:
        - file.folder.startsWith("D&D/05 - Wikipedia/Bestiarium")
        - file.fullname.endsWith(".md")
    order:
      - file.name
      - Typ
      - Größe
      - HG
    columnSize:
      file.name: 209
```