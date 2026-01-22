---
tags: [Quelle/5e/dmg]
---
```base
properties:
  file.basename:
    displayName: Name
  note.level:
    displayName: Stufe
  note.hp:
    displayName: TP
  note.ac:
    displayName: RK
  note.modifier:
    displayName: Initiative
views:
  - type: table
    name: TSV
    filters:
      and:
        - file.inFolder("D&D/02-Spieler/Gruppe")
        - file.name != "Gruppenübersicht"
        - file.fullname.endsWith(".md")
    order:
      - file.basename
      - level
      - hp
      - ac
      - modifier
    columnSize:
      note.RK: 58
      note.ZR: 178

```

<br>

| Name                | Effekt                              |
| ------------------- | ----------------------------------- |
| Resistenz           | 1/2 Schaden                         |
| Immunität           | 0 Schaden                           |
| Verwundbarkeit      | x2 Schaden                          |
| Halbe Deckung       | +2 RK & GES-RW                      |
| 3/4 Deckung         | +5 RK & GES-RW                      |
| Volle Deckung       | Kann nicht direkt anvisiert werden  |
| Verschleiert        | Nachteil (ähnlich Blind)            |
| Leicht verschleiert | Nachteil auf Weisheit (Wahrnehmung) |
|                     |                                     |

<br>

> [!tldr]- Attribute
> ![[Fertigkeitsproben-dmg#^ability-checks]]

> [!tldr]- Fertigkeiten
> ![[D&D/Tabellen/Fertigkeiten-phb#^ability-skills]]

> [!tldr]- Attributswürfe
> [[01. Grundregelwerk 2014/07-Attributswerte-verwenden#Attributswürfe|Attributswürfe]]
>[[01. Grundregelwerk 2014/07-Attributswerte-verwenden#Fertigkeiten|Fertigkeiten]]
> [[01. Grundregelwerk 2014/07-Attributswerte-verwenden#Heben und Tragen|Heben und Tragen]]
>[[01. Grundregelwerk 2014/08-Abenteuersuche#Lichtverhältnisse und Sicht|Lichtverhältnisse und Sicht]]
> [[Magie entdecken]]
> [[01. Grundregelwerk 2014/07-Attributswerte-verwenden#Passive Attributswürfe|Passive Attributswürfe]]
> [[01. Grundregelwerk 2014/07-Attributswerte-verwenden#Übungsbonus|Übungsbonus]]
> [[01. Grundregelwerk 2014/07-Attributswerte-verwenden#Vor- und Nachteil|Vor- und Nachteil]]
> [[01. Grundregelwerk 2014/07-Attributswerte-verwenden#Wettstreit|Wettstreit]]

> [!tldr]- Zustände
> ![[Zustände-phb#Zustände]]

> [!tldr]- Aktionen im Kampf
> [[01. Grundregelwerk 2014/09-Kampf#Angriff|Angriff]]
> [[01. Grundregelwerk 2014/09-Kampf#Ausweichen|Ausweichen]]
> [[01. Grundregelwerk 2014/09-Kampf#Gegenstand verwenden|Gegenstand verwenden]]
> [[01. Grundregelwerk 2014/09-Kampf#Helfen|Helfen]]
> [[01. Grundregelwerk 2014/09-Kampf#Mit Gegenständen in der Nähe Interagieren|Mit einem Gegenstand Interagieren]]
> [[01. Grundregelwerk 2014/09-Kampf#Modifikatoren für den Wurf|Modifikatoren für den Wurf]]
> [[01. Grundregelwerk 2014/09-Kampf#Ringen|Einem Haltegriff entkommen]]
> [[01. Grundregelwerk 2014/09-Kampf#Rückzug|Rückzug]]
> [[01. Grundregelwerk 2014/09-Kampf#Spurt|Spurt]]
> [[01. Grundregelwerk 2014/09-Kampf#Suchen|Suchen]]
> [[01. Grundregelwerk 2014/09-Kampf#Verstecken|Verstecken]]
> [[01. Grundregelwerk 2014/09-Kampf#Vorbereiten|Vorbereiten]]
> [[01. Grundregelwerk 2014/09-Kampf#Zauber wirken|Zauber wirken]]
> [[Aktionen-phb#Actions#Disarm|Disarm]]
> [[Aktionen-phb#Actions#Mark|Mark]]
> [[Aktionen-phb#Actions#Tumble|Tumble]]

> [!tldr]- Verschiedenes im Kampf
> [[D&D/Bücher/Spielerhandbuch-2014/10-combat#Surprise|Surprise]]
> [[D&D/Bücher/Spielerhandbuch-2014/10-combat#Initiative|Initiative]]
> [[D&D/Bücher/Spielerhandbuch-2014/10-combat#Reactions|Reactions]]
> [[D&D/Bücher/Spielerhandbuch-2014/10-combat#Moving around Other Creatures|Moving around Other Creatures]]
> [[D&D/Bücher/Spielerhandbuch-2014/10-combat#Unseen Attackers and Targets|Unseen Attackers and Targets]]
> [[D&D/Bücher/Spielerhandbuch-2014/10-combat#Grappling|Grappling]]
> [[D&D/Bücher/Spielerhandbuch-2014/10-combat#Shoving a Creature|Shoving a Creature]]
> [[D&D/Bücher/Spielerhandbuch-2014/10-combat#Two-Weapon Fighting|Two-Weapon Fighting]]
> [[D&D/Bücher/Spielerhandbuch-2014/06-equipment#Improvised Weapons|Improvised Weapons]]
> [[D&D/Bücher/Spielerhandbuch-2014/10-combat#Being Prone|Being Prone]]
> [[D&D/Bücher/Spielerhandbuch-2014/10-combat#Ranged Attacks in Close Combat|Ranged Attacks in Close Combat]]
> [[D&D/Bücher/Spielerhandbuch-2014/10-combat#Mounted Combat|Mounted Combat]]

> [!tldr]- Bewegung
> [[D&D/Bücher/Spielerhandbuch-2014/09-adventuring#Movement|Movement]]
> [[D&D/Bücher/Spielerhandbuch-2014/09-adventuring#Difficult Terrain|Difficult Terrain]]
> [[D&D/Bücher/Spielerhandbuch-2014/09-adventuring#Movement#Travel Pace|Travel Pace]]
> [[D&D/Bücher/Spielerhandbuch-2014/09-adventuring#Movement#Forced March|Forced March]]
> [[D&D/Bücher/Spielerhandbuch-2014/09-adventuring#Movement#Mounts and Vehicles|Mounts and Vehicles]]
> [[D&D/Bücher/Spielerhandbuch-2014/09-adventuring#Movement#Difficult Terrain|Difficult Terrain]]
> [[D&D/Bücher/Spielerhandbuch-2014/09-adventuring#Movement#Special Types of Movement|Special Types of Movement]]
> [[D&D/Bücher/Spielerhandbuch-2014/09-adventuring#Movement#Climbing, Swimming, and Crawling|Climbing, Swimming, and Crawling]]
> [[D&D/Bücher/Spielerhandbuch-2014/09-adventuring#Movement#Jumping|Jumping]]
> [[D&D/Bücher/Spielerhandbuch-2014/09-adventuring#Movement#Activity While Traveling|Activity While Traveling]]

> [!tldr]- Rasten
> [[D&D/Bücher/Spielerhandbuch-2014/09-adventuring#Food and Water|Food and Water]]
> [[D&D/Bücher/Spielerhandbuch-2014/09-adventuring#Resting|Resting]]
> [[D&D/Bücher/Spielerhandbuch-2014/09-adventuring#Short Rest|Short Rest]]
> [[D&D/Bücher/Spielerhandbuch-2014/09-adventuring#Long Rest|Long Rest]]
> [[D&D/Bücher/Spielerhandbuch-2014/09-adventuring#Recuperating|Recuperating]]

> [!tldr]- Schaden und Heilung
> [[01. Grundregelwerk 2014/09-Kampf#Schaden und Heilung#Heilung|Heilung]]
> [[01. Grundregelwerk 2014/09-Kampf#Auf 0 Trefferpunkte sinken#Sofortiger Tod|Sofortiger Tod]]
> [[01. Grundregelwerk 2014/09-Kampf#Auf 0 Trefferpunkte sinken#Das Bewusstsein verlieren|Das Bewusstsein verlieren]]
> [[01. Grundregelwerk 2014/09-Kampf#Auf 0 Trefferpunkte sinken#Todesrettungswürfe|Todesrettungswürfe]]
> [[01. Grundregelwerk 2014/09-Kampf#Auf 0 Trefferpunkte sinken#Eine Kreatur stabilisieren|Eine Kreatur stabilisieren]]
> [[01. Grundregelwerk 2014/09-Kampf#Auf 0 Trefferpunkte sinken#Monster und der Tod|Monster und der Tod]]

> [!tldr]- Waffen und Rüstungen
> [[Ausrüstung.base|Abenteuerausrüstung]]
> [[01. Grundregelwerk 2014/14-Magische-Gegenstände#Einen Gegenstand aktivieren|Einen Gegenstand aktivieren]]
> [[01. Grundregelwerk 2014/14-Magische-Gegenstände#Einstimmung|Einstimmung]]
> [[Ausrüstung.base#Gifte|Gifte]]
> [[Ausrüstung.base#Handelsgüter|Handelsgüter]]
> [[Rüstungen-xPHB.base|Rüstungen und Schilde]]
> [[03. Spielleiterhandbuch 2024/07-Schätze#Seltenheit und Wert magischer Gegenstände|Seltenheit und Wert magischer Gegenstände]]
> [[Waffen.base|Waffen]]
> [[Tabellen/Zauberschriftrolle-Zauberschriftrolle|Zauberschriftrolle]]


> [!tldr]- Magic Schools - WIP
> [[Schools of Magic]]
> [[Magier-phb-Schule_der_Bannmagie-phb|Abjuration]]
> [[Magier-phb-Schule_der_Beschwörung-phb|Conjuration]]
> [[Magier-phb-Schule_der_Erkenntnismagie-phb|Divination]]
> [[Magier-phb-Schule_der_Verzauberung-phb|Enchantment]]
> [[Magier-phb-Schule_der_Hervorrufung|Evocation]]
> [[Magier-phb-Schule_der_Illusion-phb|Illusion]]
> [[Magier-phb-Schule_der_Nekromantie-phb|Necromancy]]
> [[Magier-phb-Schule_der_Verwandlung|Transmutation]]