---
Bezeichnung: DM Kanban Side
tags:
  - Quelle/5e/dmg
---
# DM Kanban Side
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
> ![[D&D/Tabellen/Charakterentwicklung/Fertigkeiten-phb#^ability-skills]]

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
> [[10-Kapitel_09-Kampf#Surprise|Surprise]]
> [[10-Kapitel_09-Kampf#Initiative|Initiative]]
> [[10-Kapitel_09-Kampf#Reactions|Reactions]]
> [[10-Kapitel_09-Kampf#Moving around Other Creatures|Moving around Other Creatures]]
> [[10-Kapitel_09-Kampf#Unseen Attackers and Targets|Unseen Attackers and Targets]]
> [[10-Kapitel_09-Kampf#Grappling|Grappling]]
> [[10-Kapitel_09-Kampf#Shoving a Creature|Shoving a Creature]]
> [[10-Kapitel_09-Kampf#Two-Weapon Fighting|Two-Weapon Fighting]]
> [[06-Kapitel_05-Ausrüstung#Improvised Weapons|Improvised Weapons]]
> [[10-Kapitel_09-Kampf#Being Prone|Being Prone]]
> [[10-Kapitel_09-Kampf#Ranged Attacks in Close Combat|Ranged Attacks in Close Combat]]
> [[10-Kapitel_09-Kampf#Mounted Combat|Mounted Combat]]

> [!tldr]- Bewegung
> [[09-Kapitel_08-Auf_Abenteuer_ausziehen#Movement|Movement]]
> [[09-Kapitel_08-Auf_Abenteuer_ausziehen#Difficult Terrain|Difficult Terrain]]
> [[09-Kapitel_08-Auf_Abenteuer_ausziehen#Movement#Travel Pace|Travel Pace]]
> [[09-Kapitel_08-Auf_Abenteuer_ausziehen#Movement#Forced March|Forced March]]
> [[09-Kapitel_08-Auf_Abenteuer_ausziehen#Movement#Mounts and Vehicles|Mounts and Vehicles]]
> [[09-Kapitel_08-Auf_Abenteuer_ausziehen#Movement#Difficult Terrain|Difficult Terrain]]
> [[09-Kapitel_08-Auf_Abenteuer_ausziehen#Movement#Special Types of Movement|Special Types of Movement]]
> [[09-Kapitel_08-Auf_Abenteuer_ausziehen#Movement#Climbing, Swimming, and Crawling|Climbing, Swimming, and Crawling]]
> [[09-Kapitel_08-Auf_Abenteuer_ausziehen#Movement#Jumping|Jumping]]
> [[09-Kapitel_08-Auf_Abenteuer_ausziehen#Movement#Activity While Traveling|Activity While Traveling]]

> [!tldr]- Rasten
> [[09-Kapitel_08-Auf_Abenteuer_ausziehen#Food and Water|Food and Water]]
> [[09-Kapitel_08-Auf_Abenteuer_ausziehen#Resting|Resting]]
> [[09-Kapitel_08-Auf_Abenteuer_ausziehen#Short Rest|Short Rest]]
> [[09-Kapitel_08-Auf_Abenteuer_ausziehen#Long Rest|Long Rest]]
> [[09-Kapitel_08-Auf_Abenteuer_ausziehen#Recuperating|Recuperating]]

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