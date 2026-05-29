---
Bezeichnung: "Anhang A: Bestiarium"
linter-yaml-title-alias: "Anhang A: Bestiarium"
tags:
  - Quelle/5e/veor
aliases:
  - "Anhang A: Bestiarium"
  - Appendix A: Bestiary
---
# Anhang A: Bestiarium
*Quelle: Vecna: Vorabend der Verdammnis* 

In diesem Anhang werden Kreaturen, die im Abenteuer auftreten, in alphabetischer Reihenfolge beschrieben. In der Einführung des *Monsterhandbuchs* wird erklärt, wie die Spielwerte einer Kreatur zu verstehen sind. 

```base
filters:
  and:
    - file.folder.startsWith("D&D/Bestiarium")
views:
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
  - type: table
    name: Status
    filters:
      and:
        - file.tags.contains("Quelle/5e/veor")
    order:
      - file.name
      - Bezeichnung
      - Kategorie
      - Größe
      - HG
      - Habitat
      - status
      - IMAGE
```

---

- [[Blauer_Abishai-mpmm|Blauer Abishai]]
- [[Grüner_Abishai-mpmm|Grüner Abishai]]
- [[Roter_Abishai-mpmm|Roter Abishai]]
- [[Astralschlächter-mpmm|Astralschlächter]] 
- [[Borthak-veor|Borthak]] 
- [[Brandbär-veor|Brandbär]]
- [[Degloth-veor|Degloth]]
- [[Falscher_Lich-veor|Falscher Lich]]
- [[Granit-Moloch-veor|Granit-Moloch]]
- [[Hazvongel-veor|Hazvongel]]
- [[Hertilod-veor|Hertilod]]
- [[Inquisitor_des_Folianten-vrgr|Inquisitor des Folianten]]
- [[Klingenleutnant-veor|Klingenleutnant]]
- [[Klingenspäher-veor|Klingenspäher]]
- [[Knochenroch-veor|Knochenroch]]
- [[Kosmischer_Horror-bam|Kosmischer Horror]]
- [[Kriegsgeschmiedeter_Krieger-veor|Kriegsgeschmiedeter Krieger]]
- [[Einsamer_Kummergeschworener-mpmm|Einsamer Kummergeschworener]]
- [[Verlorener_Kummergeschworener-mpmm|Verlorener Kummergeschworener]]
- [[Leichensammler-mpmm|Leichensammler]]
- [[Magier-Nekromant-mpmm|Magier-Nekromant]]
- [[Maulauge-bam|Maulauge]]
- [[Ausgewachsener_Monddrache-bam|Ausgewachsener Monddrache]]
- [[Mondscheinwächter-veor|Mondscheinwächter]]
- [[Nachtplünderer-bam|Nachtplünderer]]
- [[Priester_von_Osybus-vrgr|Priester von Osybus]]
- [[Schwarzrosenträger-veor|Schwarzrosenträger]]
- [[Spiegelschatten-veor|Spiegelschatten]] 
- [[Spinnendrache-veor|Spinnendrache]]
- [[Kakkuu-Spinnenunhold-veor|Kakkuu-Spinnenunhold]]
- [[Phisarazu-Spinnenunhold-veor|Phisarazu-Spinnenunhold]]
- [[Quavilithku-Spinnenunhold-veor|Quavilithku-Spinnenunhold]]
- [[Raklupis-Spinnenunhold-veor|Raklupis-Spinnenunhold]]
- [[Sternangler-veor|Sternangler]]
- [[Todesrinden-Dryade-veor|Todesrinden-Dryade]]
- [[Todeswolf-veor|Todeswolf]]
- [[Unermüdlicher_Pfähler-veor|Unermüdlicher Pfähler]] 
- [[Vlazok-veor|Vlazok]]
- [[Wirbelnder_Lüster-veor|Wirbelnder Lüster]]
- [[Zitadellenspinne-veor|Zitadellenspinne]]