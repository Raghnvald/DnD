```base
views:
  - type: table
    name: Table
    filters:
      and:
        - file.tags.contains("Typ/Elementar")
    order:
      - file.name
      - Bezeichnung.asLink()

```