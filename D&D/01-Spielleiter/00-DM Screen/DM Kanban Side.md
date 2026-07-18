---
Bezeichnung: DM Kanban Side
Status: WIP
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

> [!tldr]- Attributswürfe
> [[01. Grundregelwerk 2014/07-Attributswerte-verwenden#Attributswürfe|Attributswürfe]]
> [[01. Grundregelwerk 2014/07-Attributswerte-verwenden#Heben und Tragen|Heben und Tragen]]
>[[01. Grundregelwerk 2014/08-Abenteuersuche#Lichtverhältnisse und Sicht|Lichtverhältnisse und Sicht]]
> [[Magie entdecken]]
> [[01. Grundregelwerk 2014/07-Attributswerte-verwenden#Passive Attributswürfe|Passive Attributswürfe]]
> [[01. Grundregelwerk 2014/07-Attributswerte-verwenden#Übungsbonus|Übungsbonus]]
> [[01. Grundregelwerk 2014/07-Attributswerte-verwenden#Vor- und Nachteil|Vor- und Nachteil]]
> [[01. Grundregelwerk 2014/07-Attributswerte-verwenden#Wettstreit|Wettstreit]]

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

## Zustände

> [!embed-condition]- Betäubt
> ![Betäubt](Zustände-phb#Betäubt)

> [!embed-condition]- Bewusstlos
> ![Bewusstlos](Zustände-phb#Bewusstlos)

> [!embed-condition]- Bezaubert
> ![Bezaubert](Zustände-phb#Bezaubert)

> [!embed-condition]- Blind
> ![Blind](Zustände-phb#Blind)

> [!embed-condition]- Erschöpfung
> ![Erschöpfung](Zustände-phb#Erschöpfung)

> [!embed-condition]- Festgesetzt
> ![Festgesetzt](Zustände-phb#Festgesetzt)

> [!embed-condition]- Gelähmt
> ![Gelähmt](Zustände-phb#Gelähmt)

> [!embed-condition]- Gepackt
> ![Gepackt](Zustände-phb#Gepackt)

> [!embed-condition]- Kampfunfähig
> ![Kampfunfähig](Zustände-phb#Kampfunfähig)

> [!embed-condition]- Liegend
> ![Liegend](Zustände-phb#Liegend)

> [!embed-condition]- Taub
> ![Taub](Zustände-phb#Taub)

> [!embed-condition]- Unsichtbar
> ![Unsichtbar](Zustände-phb#Unsichtbar)

> [!embed-condition]- Verängstigt
> ![Verängstigt](Zustände-phb#Verängstigt)

> [!embed-condition]- Vergiftet
> ![Vergiftet](Zustände-phb#Vergiftet)

> [!embed-condition]- Versteinert
> ![Versteinert](Zustände-phb#Versteinert)

## Tabellen

**Improvisierter Schaden**

| Würfel  | Beispiele                                                                                                                        | 
| ------- | -------------------------------------------------------------------------------------------------------------------------------- |
| `1d10`  | Burned by coals, hit by a falling bookcase, pricked by a poison needle                                                           |
| `2d10`  | Struck by lightning, stumbling into a firepit                                                                                    |
| `4d10`  | Hit by falling rubble in a collapsing tunnel, tumbling into a vat of acid                                                        |
| `10d10` | Crushed by compacting walls, hit by whirling steel blades, wading through lava                                                   |
| `18d10` | Submerged in lava, hit by a crashing flying fortress                                                                             |
| `24d10` | Tumbling into a vortex of fire on the Elemental Plane of Fire, crushed in the jaws of a godlike creature or a moon-sized monster |
^improvising-damage

**Damage Severity and Level**

| Character Levels | Nuisance | Deadly |
|------------------|----------|--------|
| 1–4 | 5 (`1d10`) | 11 (`2d10`) |
| 5–10 | 11 (`2d10`) | 22 (`4d10`) |
| 11–16 | 22 (`4d10`) | 55 (`10d10`) |
| 17–20 | 55 (`10d10`) | 99 (`18d10`) |
^damage-severity-and-level

**Aktionen**

| Aktion | Zusammenfassung |
|--------|---------|
| [[Aktionen-phb#Angriff\|Angriff]] | Angriff mit einer Waffe oder [[Unbewaffneter-Angriff-xphb\|Unbewaffnetem Angriff]]. |
| [[Aktionen-phb#Spurt\|Spurt]] | Du erhälst bist zum Ende deines Zuges zusätzliche Bewegung in Höhe deiner [[Bewegungsrate-xphb\|Bewegungsrate]]. |
| [[Aktionen-phb#Rückzug\|Rückzug]] | Your movement doesn't provoke [[Aktionen#Opportunity Attack]] for the rest of the turn. |
| [Dodge](3-Mechanics/CLI/rules/actions.md#Dodge) | Until the start of your next turn, attack rolls against you have [Disadvantage](3-Mechanics/CLI/rules/variant-rules/disadvantage-xphb.md), and you make Dexterity saving throws with [Advantage](3-Mechanics/CLI/rules/variant-rules/advantage-xphb.md). You lose this benefit if you have the [Incapacitated](3-Mechanics/CLI/rules/conditions.md#Incapacitated) condition or if your [Speed](3-Mechanics/CLI/rules/variant-rules/speed-xphb.md) is 0. |
| [Help](3-Mechanics/CLI/rules/actions.md#Help) | Help another creature's ability check or attack roll, or administer first aid. |
| [Hide](3-Mechanics/CLI/rules/actions.md#Hide) | Make a Dexterity ([Stealth](3-Mechanics/CLI/rules/skills.md#Stealth)) check. |
| [Influence](3-Mechanics/CLI/rules/actions.md#Influence) | Make a Charisma ([Deception](3-Mechanics/CLI/rules/skills.md#Deception), [Intimidation](3-Mechanics/CLI/rules/skills.md#Intimidation), [Performance](3-Mechanics/CLI/rules/skills.md#Performance), or [Persuasion](3-Mechanics/CLI/rules/skills.md#Persuasion)) or Wisdom ([Animal Handling](3-Mechanics/CLI/rules/skills.md#Animal%20Handling)) check to alter a creature's attitude. |
| [Magic](3-Mechanics/CLI/rules/actions.md#Magic) | Cast a spell, use a magic item, or use a magical feature. |
| [Ready](3-Mechanics/CLI/rules/actions.md#Ready) | Prepare to take an action in response to a trigger you define. |
| [Search](3-Mechanics/CLI/rules/actions.md#Search) | Make a Wisdom ([Insight](3-Mechanics/CLI/rules/skills.md#Insight), [Medicine](3-Mechanics/CLI/rules/skills.md#Medicine), [Perception](3-Mechanics/CLI/rules/skills.md#Perception), or [Survival](3-Mechanics/CLI/rules/skills.md#Survival)) check. |
| [Study](3-Mechanics/CLI/rules/actions.md#Study) | Make an Intelligence ([Arcana](3-Mechanics/CLI/rules/skills.md#Arcana), [History](3-Mechanics/CLI/rules/skills.md#History), [Investigation](3-Mechanics/CLI/rules/skills.md#Investigation), [Nature](3-Mechanics/CLI/rules/skills.md#Nature), or [Religion](3-Mechanics/CLI/rules/skills.md#Religion)) check. |
| [Utilize](3-Mechanics/CLI/rules/actions.md#Utilize) | Use a nonmagical object. |
^actions

*See the Player's Handbook rules glossary for full action definitions*

> [!embed-variantrule]- Hochsprung
> ![High Jump](Regelvarianten/Hochsprung-xphb.md)

> [!embed-variantrule]- Weitsprung
> ![Long Jump](Regelvarianten/Weitsprung-xphb.md)

> [!embed-status]- Konzentration
> ![Konzentration](Zustände-phb#Konzentration)

**Fertigkeit**

| Fertigkeit                                                  | Attribut         |
| ----------------------------------------------------------- | ---------------- |
| [[Fertigkeiten-phb#Akrobatik\|Akrobatik]]                   | Geschicklichkeit |
| [[Fertigkeiten-phb#Arkane Kunde\|Arkane Kunde]]             | Intelligenz      |
| [[Fertigkeiten-phb#Athletik\|Athletik]]                     | Stärke           |
| [[Fertigkeiten-phb#Auftreten\|Auftreten]]                   | Charisma         |
| [[Fertigkeiten-phb#Einschüchtern\|Einschüchtern]]           | Charisma         |
| [[Fertigkeiten-phb#Fingerfertigkeit\|Fingerfertigkeit]]     | Geschicklichkeit |
| [[Fertigkeiten-phb#Geschichte\|Geschichte]]                 | Intelligenz      |
| [[Fertigkeiten-phb#Heilkunde\|Heilkunde]]                   | Weisheit         |
| [[Fertigkeiten-phb#Heimlichkeit\|Heimlichkeit]]             | Geschicklichkeit |
| [[Fertigkeiten-phb#Mit Tieren umgehen\|Mit Tieren umgehen]] | Weisheit         |
| [[Fertigkeiten-phb#Motiv erkennen\|Motiv erkennen]]         | Weisheit         |
| [[Fertigkeiten-phb#Nachforschungen\|Nachforschungen]]       | Intelligenz      |
| [[Fertigkeiten-phb#Naturkunde\|Naturkunde]]                 | Intelligenz      |
| [[Fertigkeiten-phb#Religion\|Religion]]                     | Intelligenz      |
| [[Fertigkeiten-phb#Täuschen\|Täuschen]]                     | Charisma         |
| [[Fertigkeiten-phb#Überlebenskunst\|Überlebenskunst]]       | Weisheit         |
| [[Fertigkeiten-phb#Überzeugen\|Überzeugen]]                 | Charisma         |
| [[Fertigkeiten-phb#Wahrnehmung\|Wahrnehmung]]               | Weisheit         |
^skills

### Todesrettungswurf

Wenn du deinen Zug mit 0 TP beginnst, würfle mit einem `d20`. Ist das Ergebnis 10 oder höher bist du erfolgreich.

- **Dritter Erfolg.** Du wirst [[Zustände-phb#Stabilisieren|stabilisiert]].
- **Dritter Misserfolg.** Du stirbst.  
- **Eine 1 würfeln.** Zählt als 2 Misserfolge.  
- **Eine 20 würfeln.** Du erhälst 1 TP.  

Wenn du Schaden erleidest, während du bereits auf 0 Trefferpunkte reduziert bist, zählt dies als Misserfolg bei einem Todesrettungswurf.
Wird der Schaden durch einen kritischen Treffer verursacht, gilt dies als zwei Misserfolge.

**Objektrüstungsklassen**

| Substanz             | RK  |
| -------------------- | --- |
| Stoff, Papier, Steil | 11  |
| Kristall, Glas, Eis  | 13  |
| Holz, Knochen        | 15  |
| Stein                | 17  |
| Eisen, Stahl         | 19  |
| Mithril              | 21  |
| Adamant              | 23  |
^object-armor-class

**Objekttrefferpunkte**

| Größe                             | Zerbrechlich | Widerstandsfähig |
| --------------------------------- | ------------ | ---------------- |
| Winzig (Flasche, Schloss)         | 2 (`1d4`)    | 5 (`2d4`)        |
| Klein (Truhe, Laute)              | 3 (`1d6`)    | 10 (`3d6`)       |
| Mittelgroß (Fass, Kerzenleuchter) | 4 (`1d8`)    | 18 (`4d8`)       |
| Groß (Wagen, Esstisch)            | 5 (`1d10`)   | 27 (`5d10`)      |
^object-hit-points

**Essen, Trinken und Unterkunft**

| Name                                                        | Kosten |
| ----------------------------------------------------------- | ------:|
| *Bier*                                                      |        |
| &emsp;[[Bier-Fass-phb\|Fass (knapp 4 Liter)]]               |   2 SM |
| &emsp;[[Bier-Humpen-phb\|Humpen]]                           |   4 KM |
| [[Brotlaib-phb\|Brot, Laib]]                                |   2 KM |
| [[Käselaib-phb\|Käse, Laib]]                                |   1 SM |
| [[Fleisch-Stück-phb\|Fleisch, Stück]]                       |   3 SM |
| *Übernachtung im Gasthof (pro Tag)*                         |        |
| &emsp;Ärmlich                                               |   7 KM |
| &emsp;Schlecht                                              |   1 SM |
| &emsp;Einfach                                               |   5 SM |
| &emsp;Komfortabel                                           |   8 SM |
| &emsp;Wohlhabend                                            |   2 GM |
| &emsp;Edel                                                  |   4 GM |
| *Mahlzeiten (pro Tag)*                                      |        |
| &emsp;Ärmlich                                               |   3 KM |
| &emsp;Schlecht                                              |   6 KM |
| &emsp;Einfach                                               |   3 SM |
| &emsp;Komfortabel                                           |   5 SM |
| &emsp;Wohlhabend                                            |   8 SM |
| &emsp;Edel                                                  |   2 GM |
| *Wein*                                                      |        |
| &emsp;[[Wein-gewöhnlich-Karaffe-phb\|Gewöhnlich (Karaffe)]] |   2 SM |
| &emsp;[[Wein-fein-Flasche-phb\|Fein (Flasche)]]             |  10 GM |
^food-drink-and-lodging

**Typische Schwierigkeitsgrade**

| Aufgabe        | SG  |
| -------------- | --- |
| Sehr leicht    | 5   |
| Leicht         | 10  |
| Mittelschwer   | 15  |
| Schwer         | 20  |
| Sehr schwer    | 25  |
| Fast unmöglich | 30  |
^typical-difficulty-classes

**Lichtquelle**

| Quelle                                         | Helles Licht                          | Dämmriges Licht                | Duration  |
| ---------------------------------------------- | ------------------------------------- | ------------------------------ | --------- |
| [[Abdeckbare_Laterne-phb\|Abdeckbare Laterne]] | 9 Meter (nichts abgedeckt)            | +9 Meter (1,5 Meter abgedeckt) | 6 Stunden |
| [[Blendlaterne-phb\|Blendlaterne]]             | 18 Meter [[Flächeneffekt-Kegel-xphb]] | +18 Meter                      | 6 Stunden |
| [[Fackel-phb\|Fackel]]                         | 6 Meter                               | +6 Meter                       | 1 Stunde  |
| [[Kerze-phb\|Kerze]]                           | 1,5 Meter                             | +1,5 Meter                     | 1 Stunde  |
| [[Lampe-phb\|Lampe]]                           | 4,5 Meter                             | +30 feet                       | 6 Stunden |
^light-sources

**Obscured Areas**

| Obscureness | Effect | Examples |
|-------------|--------|----------|
| [Lightly Obscured](3-Mechanics/CLI/rules/variant-rules/lightly-obscured-xphb.md) | Creatures have [Disadvantage](3-Mechanics/CLI/rules/variant-rules/disadvantage-xphb.md) on Wisdom ([Perception](3-Mechanics/CLI/rules/skills.md#Perception)) checks that rely on sight | [Dim Light](3-Mechanics/CLI/rules/variant-rules/dim-light-xphb.md), patchy fog, moderate foliage |
| [Heavily Obscured](3-Mechanics/CLI/rules/variant-rules/heavily-obscured-xphb.md) | Creatures have the [Blinded](3-Mechanics/CLI/rules/conditions.md#Blinded) condition | [Darkness](3-Mechanics/CLI/rules/variant-rules/darkness-xphb.md), heavy fog, dense foliage |
^obscured-areas

**Travel Pace**

<table>
<tr>
  <th></th>
  <th colspan="3">Distance Traveled Per...</th>
  <th></th>
</tr>
<tr>
  <th>Pace</th>
  <th>Minute</th>
  <th>Hour</th>
  <th>Day</th>
  <th>Effect</th>
</tr>
<tr>
  <td>Fast</td>
  <td>400 feet</td>
  <td>4 miles</td>
  <td>30 miles</td>
  <td><a href="3-Mechanics/CLI/rules/variant-rules/disadvantage-xphb.md">Disadvantage</a> on Wisdom (<a href="3-Mechanics/CLI/rules/skills.md#Perception">Perception</a> or <a href="3-Mechanics/CLI/rules/skills.md#Survival">Survival</a>) and Dexterity (<a href="3-Mechanics/CLI/rules/skills.md#Stealth">Stealth</a>) checks</td>
</tr>
<tr>
  <td>Normal</td>
  <td>300 feet</td>
  <td>3 miles</td>
  <td>24 miles</td>
  <td><a href="3-Mechanics/CLI/rules/variant-rules/disadvantage-xphb.md">Disadvantage</a> on Dexterity (<a href="3-Mechanics/CLI/rules/skills.md#Stealth">Stealth</a>) checks</td>
</tr>
<tr>
  <td>Slow</td>
  <td>200 feet</td>
  <td>2 miles</td>
  <td>18 miles</td>
  <td><a href="3-Mechanics/CLI/rules/variant-rules/advantage-xphb.md">Advantage</a> on Wisdom (<a href="3-Mechanics/CLI/rules/skills.md#Perception">Perception</a> or <a href="3-Mechanics/CLI/rules/skills.md#Survival">Survival</a>) checks</td>
</tr>
</table>
^travel-pace

**Travel Terrain**

| Terrain | Maximum Pace | Encounter Distance | Foraging DC | Navigation DC | Search DC |
|---------|--------------|--------------------|-------------|---------------|-----------|
| Arctic | Fast* | `6d6 × 10` feet | 20 | 10 | 10 |
| Coastal | Normal | `2d10 × 10` feet | 10 | 5 | 15 |
| Desert | Normal | `6d6 × 10` feet | 20 | 10 | 10 |
| Forest | Normal | `2d8 × 10` feet | 10 | 15 | 15 |
| Grassland | Fast | `6d6 × 10` feet | 15 | 5 | 15 |
| Hill | Normal | `2d10 × 10` feet | 15 | 10 | 15 |
| Mountain | Slow | `4d10 × 10` feet | 20 | 15 | 20 |
| Swamp | Slow | `2d8 × 10` feet | 10 | 15 | 20 |
| Underdark | Normal | `2d6 × 10` feet | 20 | 10 | 20 |
| Urban | Normal | `2d6 × 10` feet | 20 | 15 | 15 |
| Waterborne | Special† | `6d6 × 10` feet | 15 | 10 | 15 |
^travel-terrain

*Appropriate equipment (such as skis) is necessary to keep up a Fast pace in Arctic terrain.

†Characters' rate of travel while waterborne depends on the vehicle carrying them.

**Cover**

| Cover Degree | Benefit to Target |
|--------------|-------------------|
| Half Cover | +2 bonus to AC and Dexterity saving throws |
| Three-Quarters Cover | +5 bonus to AC and Dexterity saving throws |
| Total Cover | Can't be targeted directly |
^cover

**Audible Distance**

| Noise | Distance |
|-------|----------|
| Trying to be quiet | `2d6 × 5` feet |
| Normal noise level | `2d6 × 10` feet |
| Very loud | `2d6 × 50` feet |
^audible-distance

**Visibility Outdoors**

| Conditions | Distance |
|------------|----------|
| Clear day, no obstructions | 2 miles (40 miles from a height) |
| Rain ([Lightly Obscured](3-Mechanics/CLI/rules/variant-rules/lightly-obscured-xphb.md)) | 1 mile |
| Fog ([Lightly Obscured](3-Mechanics/CLI/rules/variant-rules/lightly-obscured-xphb.md)) | 100 to 300 feet |
^visibility-outdoors

### Weather

**Weather**

| dice: 1d20 | Temperature |
|------------|-------------|
| 1–14 | Normal for the season |
| 15–17 | `1d4 × 10` degrees Fahrenheit colder |
| 18–20 | `1d4 × 10` degrees Fahrenheit hotter |
^weather

| dice: 1d20 | Wind | Precipitation |
|------------|------|---------------|
| 1–12 | None | None |
| 13–17 | Light | Light rain or light snowfall |
| 18–20 | Strong | Heavy rain or heavy snowfall |
^1-wind-precipitation