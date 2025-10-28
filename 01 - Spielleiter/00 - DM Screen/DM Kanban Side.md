---
tags: [Quelle/5e/Dungeon_Masters_Guide]
---
```base
properties:
  file.basename:
    displayName: Name
views:
  - type: table
    name: TSV
    filters:
      and:
        - file.inFolder("D&D/02 - Spieler/Gruppe")
        - file.name != "Gruppenübersicht"
    order:
      - file.basename
      - RK
      - pW
      - ZR
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
> [[01. Grundregelwerk 2014/07-Attributswerte-verwenden#Stärke|Stärke]]
> [[01. Grundregelwerk 2014/07-Attributswerte-verwenden#Geschicklichkeit|Geschicklichkeit]]
> [[01. Grundregelwerk 2014/07-Attributswerte-verwenden#Konstitution|Konstitution]]
> [[01. Grundregelwerk 2014/07-Attributswerte-verwenden#Intelligenz|Intelligenz]]
> [[01. Grundregelwerk 2014/07-Attributswerte-verwenden#Weisheit|Weisheit]]
> [[01. Grundregelwerk 2014/07-Attributswerte-verwenden#Charisma|Charisma]]

> [!tldr]- Fertigkeiten
> [[01. Grundregelwerk 2014/07-Attributswerte-verwenden##Akrobatik|Akrobatik]]
> [[01. Grundregelwerk 2014/07-Attributswerte-verwenden#Arkane Kunde|Arkane Kunde]]
> [[01. Grundregelwerk 2014/07-Attributswerte-verwenden#Athletik|Athletik]]
> [[01. Grundregelwerk 2014/07-Attributswerte-verwenden#Auftreten|Auftreten]]
> [[01. Grundregelwerk 2014/07-Attributswerte-verwenden#Einschüchtern|Einschüchtern]]
> [[01. Grundregelwerk 2014/07-Attributswerte-verwenden#Fingerfertigkeit|Fingerfertigkeit]]
> [[01. Grundregelwerk 2014/07-Attributswerte-verwenden#Geschichte|Geschichte]]
> [[01. Grundregelwerk 2014/07-Attributswerte-verwenden#Heilkunde|Heilkunde]]
> [[01. Grundregelwerk 2014/07-Attributswerte-verwenden#Heimlichkeit|Heimlichkeit]]
> [[01. Grundregelwerk 2014/07-Attributswerte-verwenden#Mit Tieren umgehen|Mit Tieren umgehen]]
> [[01. Grundregelwerk 2014/07-Attributswerte-verwenden#Motiv erkennen|Motiv erkennen]]
> [[01. Grundregelwerk 2014/07-Attributswerte-verwenden#Nachforschungen|Nachforschungen]]
> [[01. Grundregelwerk 2014/07-Attributswerte-verwenden#Naturkunde|Naturkunde]]
> [[01. Grundregelwerk 2014/07-Attributswerte-verwenden#Religion|Religion]]
> [[01. Grundregelwerk 2014/07-Attributswerte-verwenden#Täuschen|Täuschen]]
> [[01. Grundregelwerk 2014/07-Attributswerte-verwenden#Überlebenskunst|Überlebenskunst]]
> [[01. Grundregelwerk 2014/07-Attributswerte-verwenden#Überzeugen|Überzeugen]]
> [[01. Grundregelwerk 2014/07-Attributswerte-verwenden#Wahrnehmung|Wahrnehmung]]

> [!tldr]- Attributswürfe
>[[01. Grundregelwerk 2014/07-Attributswerte-verwenden#Attributswürfe|Attributswürfe]]
>[[01. Grundregelwerk 2014/07-Attributswerte-verwenden#Fertigkeiten|Fertigkeiten]]
> [[01. Grundregelwerk 2014/07-Attributswerte-verwenden#Heben und Tragen|Heben und Tragen]]
>[[01. Grundregelwerk 2014/08-Abenteuersuche#Lichtverhältnisse und Sicht|Lichtverhältnisse und Sicht]]
> [[Magie entdecken]]
> [[01. Grundregelwerk 2014/07-Attributswerte-verwenden#Passive Attributswürfe|Passive Attributswürfe]]
> [[01. Grundregelwerk 2014/07-Attributswerte-verwenden#Übungsbonus|Übungsbonus]]
> [[01. Grundregelwerk 2014/07-Attributswerte-verwenden#Vor- und Nachteil|Vor- und Nachteil]]
> [[01. Grundregelwerk 2014/07-Attributswerte-verwenden#Wettstreit|Wettstreit]]

> [!tldr]- Zustände
> [[01. Grundregelwerk 2014/Anhang PH-A#Betäubt|Betäubt]]
> [[01. Grundregelwerk 2014/Anhang PH-A#Bewusstlos|Bewusstlos]]
> [[01. Grundregelwerk 2014/Anhang PH-A#Bezaubert|Bezaubert]]
> [[01. Grundregelwerk 2014/Anhang PH-A#Blind|Blind]]
> [[01. Grundregelwerk 2014/Anhang PH-A#Erschöpfung|Erschöpfung]]
> [[01. Grundregelwerk 2014/Anhang PH-A#Festgesetzt|Festgesetzt]]
> [[01. Grundregelwerk 2014/Anhang PH-A#Gelähmt|Gelähmt]]
> [[01. Grundregelwerk 2014/Anhang PH-A#Gepackt|Gepackt]]
> [[01. Grundregelwerk 2014/Anhang PH-A#Kampfunfähig|Kampfunfähig]]
> [[01. Grundregelwerk 2014/10-Zauberwirken#Konzentration|Konzentration]]
> [[01. Grundregelwerk 2014/Anhang PH-A#Liegend|Liegend]]
> [[01. Grundregelwerk 2014/Anhang PH-A#Taub|Taub]]
> [[01. Grundregelwerk 2014/Anhang PH-A#Unsichtbar|Unsichtbar]]
> [[01. Grundregelwerk 2014/Anhang PH-A#Verängstigt|Verängstigt]]
> [[01. Grundregelwerk 2014/Anhang PH-A#Vergiftet|Vergiftet]]
> [[01. Grundregelwerk 2014/Anhang PH-A#Versteinert|Versteinert]]

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
> [[actions#Actions#Disarm|Disarm]]
> [[actions#Actions#Mark|Mark]]
> [[actions#Actions#Tumble|Tumble]]

> [!tldr]- Verschiedenes im Kampf
> [[10-combat#Surprise|Surprise]]
> [[10-combat#Initiative|Initiative]]
> [[10-combat#Reactions|Reactions]]
> [[10-combat#Moving around Other Creatures|Moving around Other Creatures]]
> [[10-combat#Unseen Attackers and Targets|Unseen Attackers and Targets]]
> [[10-combat#Grappling|Grappling]]
> [[10-combat#Shoving a Creature|Shoving a Creature]]
> [[10-combat#Two-Weapon Fighting|Two-Weapon Fighting]]
> [[06-equipment#Improvised Weapons|Improvised Weapons]]
> [[10-combat#Being Prone|Being Prone]]
> [[10-combat#Ranged Attacks in Close Combat|Ranged Attacks in Close Combat]]
> [[10-combat#Mounted Combat|Mounted Combat]]

> [!tldr]- Bewegung
> [[09-adventuring#Movement|Movement]]
> [[09-adventuring#Difficult Terrain|Difficult Terrain]]
> [[09-adventuring#Movement#Travel Pace|Travel Pace]]
> [[09-adventuring#Movement#Forced March|Forced March]]
> [[09-adventuring#Movement#Mounts and Vehicles|Mounts and Vehicles]]
> [[09-adventuring#Movement#Difficult Terrain|Difficult Terrain]]
> [[09-adventuring#Movement#Special Types of Movement|Special Types of Movement]]
> [[09-adventuring#Movement#Climbing, Swimming, and Crawling|Climbing, Swimming, and Crawling]]
> [[09-adventuring#Movement#Jumping|Jumping]]
> [[09-adventuring#Movement#Activity While Traveling|Activity While Traveling]]

> [!tldr]- Rasten
> [[09-adventuring#Food and Water|Food and Water]]
> [[09-adventuring#Resting|Resting]]
> [[09-adventuring#Short Rest|Short Rest]]
> [[09-adventuring#Long Rest|Long Rest]]
> [[09-adventuring#Recuperating|Recuperating]]

> [!tldr]- Schaden und Heilung
> [[01. Grundregelwerk 2014/09-Kampf#Schaden und Heilung#Heilung|Heilung]]
> [[01. Grundregelwerk 2014/09-Kampf#Auf 0 Trefferpunkte sinken#Sofortiger Tod|Sofortiger Tod]]
> [[01. Grundregelwerk 2014/09-Kampf#Auf 0 Trefferpunkte sinken#Das Bewusstsein verlieren|Das Bewusstsein verlieren]]
> [[01. Grundregelwerk 2014/09-Kampf#Auf 0 Trefferpunkte sinken#Todesrettungswürfe|Todesrettungswürfe]]
> [[01. Grundregelwerk 2014/09-Kampf#Auf 0 Trefferpunkte sinken#Eine Kreatur stabilisieren|Eine Kreatur stabilisieren]]
> [[01. Grundregelwerk 2014/09-Kampf#Auf 0 Trefferpunkte sinken#Monster und der Tod|Monster und der Tod]]

> [!tldr]- Waffen und Rüstungen
> [[00. Ausrüstung.base|Abenteuerausrüstung]]
> [[01. Grundregelwerk 2014/14-Magische-Gegenstände#Einen Gegenstand aktivieren|Einen Gegenstand aktivieren]]
> [[01. Grundregelwerk 2014/14-Magische-Gegenstände#Einstimmung|Einstimmung]]
> [[00. Ausrüstung.base#Gifte|Gifte]]
> [[00. Ausrüstung.base#Handelsgüter|Handelsgüter]]
> [[00. Rüstungen.base|Rüstungen und Schilde]]
> [[03. Spielleiterhandbuch 2024/07-Schätze#Seltenheit und Wert magischer Gegenstände|Seltenheit und Wert magischer Gegenstände]]
> [[00. Waffen.base|Waffen]]
> [[Tabellen/Zauberschriftrolle-Zauberschriftrolle|Zauberschriftrolle]]


> [!tldr]- Magic Schools - WIP
> [[Schools of Magic]]
> [[wizard-school-of-abjuration|Abjuration]]
> [[wizard-school-of-conjuration|Conjuration]]
> [[wizard-school-of-divination|Divination]]
> [[wizard-school-of-enchantment|Enchantment]]
> [[wizard-school-of-evocation|Evocation]]
> [[wizard-school-of-illusion|Illusion]]
> [[wizard-school-of-necromancy|Necromancy]]
> [[wizard-school-of-transmutation|Transmutation]]