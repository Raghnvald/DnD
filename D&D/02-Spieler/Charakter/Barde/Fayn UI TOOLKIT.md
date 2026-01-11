---
cssclasses:
  - tag-bubble
obsidianUIMode: reading
level: 6
proficiency_bonus:
hp: 57
ac: 15
speed: 9
CL: Barde 6
RACE: Halb-Elf
BG: Unterhaltungskünstler
ALIGN: Chaotisch Gut
PN: Fayn
EXP: "0"
HI:
LBS:
EYE: Braun
SKIN: Hellhäutig
HAIR: Braun
PERS: |-
  Ich kenne eine Geschichte, die zu fast jeder Situation passt.

  Ich liebe eine gute Beleidigung, auch wenn sie gegen mich gerichtet ist.

  Ich lasse mich auf nichts weniger als Perfektion ein.
IDEAL: Menschen. Ich liebe es, wenn die Menschen sich freuen wenn ich spiele. Das ist alles was zählt (neutral)
BOND: Jemand hat mein wertvolles Instrument gestohlen und eines Tages werde ich es zurück haben.
FLAW: Ich habe mal einen Witz über einen Adeligen gemacht, der nun meinen Kopf will. Es war ein Fehler den ich wahrscheinlich wiederholen werde.
IMAGE:
ammo1: 0
ammo2:
AC1: false
AC2: true
AC3: false
AC4: false
CP: 0
SP: 3
EP: 0
GP: 48
PP: 0
TREASURE:
CARRY:
SP1-1: true
SP1-2: true
SP1-3: true
SP1-4: true
SP1-5: false
SP1-6: false
SP1-7: false
SP1-8: false
SP1-9: false
SP1-10: false
SP1-11: false
SP1-12: false
SP1-13: false
SP2-1: true
SP2-2: true
SP2-3: true
SP2-4: true
SP2-5: true
SP2-6: true
SP2-7: false
SP2-8: false
SP2-9: false
SP2-10: false
SP2-11: false
SP2-12: false
SP2-13: false
SP3-1: true
SP3-2: true
SP3-3: true
SP3-4: true
SP3-5: true
SP3-6: false
SP3-7: false
SP3-8: false
SP3-9: false
SP3-10: false
SP3-11: false
SP3-12: false
SP3-13: false
SP4-1: false
SP4-2: false
SP4-3: false
SP4-4: false
SP4-5: false
SP4-6: false
SP4-7: false
SP4-8: false
SP4-9: false
SP4-10: false
SP4-11: false
SP4-12: false
SP4-13: false
SP5-1: false
SP5-2: false
SP5-3: false
SP5-4: false
SP5-5: false
SP5-6: false
SP5-7: false
SP5-8: false
SP5-9: false
SP6-9: false
SP6-8: false
SP6-7: false
SP6-6: false
SP6-5: false
SP6-4: false
SP6-3: false
SP6-2: false
SP6-1: false
SP7-9: false
SP7-8: false
SP7-7: false
SP7-6: false
SP7-5: false
SP7-4: false
SP7-3: false
SP7-2: false
SP7-1: false
SP8-1: false
SP8-2: false
SP8-3: false
SP8-4: false
SP8-5: false
SP8-6: false
SP8-7: false
SP9-1: false
SP9-2: false
SP9-3: false
SP9-4: false
SP9-5: false
SP9-6: false
SP9-7: false
---
# **Fayn**

~~~tabs
---Allgemein
![[#Allgemein|no-h1 full clean]]
---Beschreibung
![[#Beschreibung|no-h1 full clean]]
---Fertigkeiten
![[#Fertigkeiten|no-h1 full clean]]
---Ausrüstung
![[#Ausrüstung|no-h1 full clean]]
~~~

~~~tabs
---Zauber
![[#Zauber|no-h1 full clean]]
---Inventar
![[#Inventar|no-h1 full clean]]
---Misc.
![[#Misc.|no-h1 full clean]]
---Notizen
![[#Notes|no-h1 full clean]]
~~~


---
---

# Allgemein
[[#Allgemein|🔗]] 

```event-btns
items:
  - name: Kurze Rast
    value: short-rest
  - name: Lange Rast
    value: long-rest
```
```badges
items:
  - label: Stufe
    value: '{{ frontmatter.level }}'
  - label: Übungsbonus
    value: '+{{ frontmatter.proficiency_bonus }}'
  - label: RK
    value: '{{ frontmatter.ac }}'
  - label: Initiative
    value: '+{{ add (modifier abilities.dexterity) (floor (divide frontmatter.proficiency_bonus 2)) }}'
  - label: Bew.
    value: '{{ frontmatter.speed }}'
```
```healthpoints
state_key: my_character_hp
health: '{{ frontmatter.hp }}'
death_saves: true
hitdice:
  dice: d8
  value: 6
```
> [!column|no-t]
> > [!recite] Bardische Inspiration
> > ```consumable
> > items:
> >  - label: "BI"
> >    state_key: BI
> >    uses: 4
> >    reset_on: ["short-rest", "long-rest"] # Reset on either rest type
> > ```
> 
> > [!recite] Feenberührt
> > ```consumable
> > items:
> >  - label: "Magie entdecken"
> >    state_key: Magie_entdecken
> >    uses: 1
> >    reset_on: long-rest
> >  - label: "Nebelschritt"
> >    state_key: Nebelschritt
> >    uses: 1
> >    reset_on: long-rest
> > ```
> 
> > [!recite] Inspiration
> > ```consumable
> > items:
> >  - label: "Inspiration"
> >    state_key: I
> >    uses: 1
> > ```

# Beschreibung
[[#Beschreibung|🔗]] 
> [!columns|no-t]
> 
> > [!recite|bg-white t-w] Charakterinfo
> > | Info              | Description         |
> > | ----------------- | ------------------- |
> > | **Klasse & Stufe** | `INPUT[text(placeholder(Class & Level)):CL]`    |
> > | **Rasse**          | `INPUT[text(placeholder(Race)):RACE]`  |
> > | **Hintergrund**    | `INPUT[text(placeholder(Background)):BG]`    |
> > | **Gesinnung**     | `INPUT[text(placeholder(Alignment)):ALIGN]` |
> > | **Spielername**   | `INPUT[text(placeholder(Player)):PN]`    |
> > | **Erfahrung**    | `INPUT[text(placeholder(EXP)):EXP]`   |
> 
> > [!recite|bg-white t-w] Charakteraussehen
> > | Info              | Description         |
> > | ----------------- | ------------------- |
> > | **Alter** | `INPUT[text(placeholder(Age)):AGE]`    |
> > | **Größe**          | `INPUT[text(placeholder(Height)):HI]`  |
> > | **Gewicht**    | `INPUT[text(placeholder(Weight)):LBS]`    |
> > | **Augen**     | `INPUT[text(placeholder(Eyes)):EYE]` |
> > | **Haut**   | `INPUT[text(placeholder(Skin/Fur/Etc)):SKIN]`    |
> > | **Haare**    | `INPUT[text(placeholder(Hair)):HAIR]`   |
> 
> > [!recite|bg-white] Persönlichkeit
> > `INPUT[textArea(placeholder(Personality Traits or Quote)):PERS]`
> 
> > [!recite|bg-white] Ideale
> > `INPUT[textArea(placeholder(Ideals and Morals)):IDEAL]`
> 
> > [!recite|bg-white] Bindungen
> > `INPUT[textArea(placeholder(Bonds and Boundaries)):BOND]`
> 
> > [!recite|bg-white] Makel
> > `INPUT[textArea(placeholder(Flaws and Fears)):FLAW]`

# Fertigkeiten
[[#Fertigkeiten|🔗]]  

```ability
abilities:
  strength: 17
  dexterity: 18
  constitution: 18
  intelligence: 14
  wisdom: 15
  charisma: 19

proficiencies:
  - dexterity
  - charisma

bonuses:
  - name: 
    target: 
    value: 
    modifies: 
```

```skills
proficiencies:
  - Acrobatics # Hintergrund
  - Deception # Charaktererstellung
  - Investigation # Charaktererstellung
  - Perception # Charaktererstellung
  - Performance # Hintergrund
  - Persuasion # Rasse
  - Sleight of Hand # Rasse

expertise:
  - Investigation
  - Perception

half_proficiencies:
  - Animal Handling # Jack of all Trades
  - Arcana # Jack of all Trades
  - Athletics # Jack of all Trades
  - History # Jack of all Trades
  - Insight # Jack of all Trades
  - Intimidation # Jack of all Trades
  - Medicine # Jack of all Trades
  - Nature # Jack of all Trades
  - Religion # Jack of all Trades
  - Stealth # Jack of all Trades
  - Survival # Jack of all Trades
```
```badges
items:
  - label: Passive Wahrnehmung
    value: '{{ add 10 (modifier abilities.wisdom) }}'
```

> [!recite|bg-white t-w ] Andere Übungen & Training
> | Übungsart | Beschreibung  |
> | ----------------- | ------------------- |
> | **Rüstung** |  Leichte Rüstung   |
> | **Waffen** | Einfache Waffen, Handarmbrust, Kurzschwert, Langschwert, Pistole, Rapier  |
> | **Werkzeuge** |  Dudelsack, Flöte, Laute, Leier, Verkleidungsausrüstung   |
> | **Sprachen** | Gemeinsprache, Elfisch, Zwergisch |
> | **Anderes** | |

# Ausrüstung
[[#Ausrüstung|🔗]]  

## Waffen 

| Gegenstand               | Reichweite  | ATK Bonus | Schaden    | *Eigenschaften / Notizen*  |
| ------------------------ | ----------- | --------- | ---------- | -------------------------- |
| [[Dolch-phb\|Dolch]]     | 1,5m/6m/18m | STR/GES   | 1d4 Stich  | Finesse, Leicht, Wurfwaffe |
| [[Pistole-dmg\|Pistole]] | 9m/27m      | GES       | 1d10 Stich | Geschosse, Laden           |
| [[Pistole-dmg\|Pistole]] | 9m/27m      | GES       | 1d10 Stich | Geschosse, Laden           | 
| [[Rapier-phb\|Rapier]]   | 1,5m        | STR/GES   | 1d8 Stich  | Finesse                    |

| Munitionsart     | Anzahl                                             |
| ---------------- | -------------------------------------------------- |
| Kugeln (Pistole) | `INPUT[number(class(wider),placeholder(0)):ammo1]` |
|                  | `INPUT[number(class(wider),placeholder(0)):ammo2]` |
## Rüstung

| Ausgerüstet         | Gegenstand                         | Reichweite | RK Bonus | Art     | *Eigenschaften / Notizen* |
| ------------------- | ---------------------------------- | ---------- | -------- | ------- | ------------------------- |
| `INPUT[toggle:AC1]` | Ohne Rüstung                       | Leicht     | 10+GES   | ---     |                           |
| `INPUT[toggle:AC2]` | [[Lederrüstung-phb\|Lederrüstung]] | Leicht     | 11+GES   | Rüstung |                           |
| `INPUT[toggle:AC3]` |                                    |            |          |         |                           |
| `INPUT[toggle:AC4]` |                                    |            |          |         |                           |
## Einstimmungsplätze

| Platz | Gegenstand | Wo am Körper? | Zusammenfassung |
| ----- | ---------- | ------------- | --------------- |
| **1** |            |               |                 |
| **2** |            |               |                 |
| **3** |            |               |                 |

# Inventar
[[#Inventar|🔗]]  

- **Aktuelle Traglast**
	- `INPUT[number(class(wider),placeholder(Held)):CARRY]`**lbs**
```badges
items:
  - label: Traglast
    value: '{{ multiply 15 abilities.strength }}lbs'
```

## Münzbeutel

> [!recite|txt-c t-w table-cell-top] Beute
> | KM | SM | EM | GM | PM |
> | --- | --- | --- | --- | --- |
> | `INPUT[number(class(wider),placeholder(0)):CP]` | `INPUT[number(class(wider),placeholder(0)):SP]` | `INPUT[number(class(wider),placeholder(0)):EP]` | `INPUT[number(class(wider),placeholder(0)):GP]` | `INPUT[number(class(wider),placeholder(0)):PP]` |
> `INPUT[textArea(placeholder(Beute)):TREASURE]`

## Getragene Gegenstände

> [!recite]- [[Flöte-phb|Flöte]]
> **Menge:** 1x
> **Gewicht:** 0,5 kg.
> **Gegenstandsart:** Instrument
> ---
> **Beschreibung.** Wenn du ein bestimmtes Musikinstrument beherrschst, kannst du deinen [Kompetenzbonus] zu allen Fertigkeitswürfen addieren, die du zum Musizieren mit dem Instrument machst. Ein Barde kann ein Musikinstrument als Zauberfokus verwenden. Jede Art von Musikinstrument erfordert eine eigene Befähigung.

> [!recite]- [[Kleidung-gewöhnlich-phb|Kleidung (gewöhnlich)]]
> **Menge:** 1x
> **Gewicht:** 1,5 kg.
> **Gegenstandsart:** Abenteuerausrüstung
> ---

> [!recite]- [[Laute-phb|Laute]]
> **Menge:** 1x
> **Gewicht:** 1,0 kg.
> **Gegenstandsart:** Instrument
> ---
> **Beschreibung.** Wenn du ein bestimmtes Musikinstrument beherrschst, kannst du deinen [Kompetenzbonus] zu allen Fertigkeitswürfen addieren, die du zum Musizieren mit dem Instrument machst. Ein Barde kann ein Musikinstrument als Zauberfokus verwenden. Jede Art von Musikinstrument erfordert eine eigene Befähigung.

> [!recite]- Leise
> **Menge:** 1x
> **Gewicht:** 1,0 kg.
> **Gegenstandsart:** Instrument
> ---
> **Beschreibung.** Wenn du ein bestimmtes Musikinstrument beherrschst, kannst du deinen [Kompetenzbonus] zu allen Fertigkeitswürfen addieren, die du zum Musizieren mit dem Instrument machst. Ein Barde kann ein Musikinstrument als Zauberfokus verwenden. Jede Art von Musikinstrument erfordert eine eigene Befähigung.

> [!recite]- Taschenuhr
> **Menge:** 1x
> **Gewicht:** /
> **Gegenstandsart:** Abenteuerausrüstung
> ---

## Rucksack
- **Fassungsvermögen:** 15 kg.

> [!recite]- [[Kerze-xphb|Kerze]]
> **Menge:** 1x
> **Gewicht:** /
> **Gegenstandsart:** Abenteuerausrüstung
> ---
> **Beschreibung.** Eine Kerze spendet 1 Stunde lang helles Licht in einem Radius von 1,5 Meter und schwaches Licht für weitere 1,5 Meter.

> [!recite]- [[Schlafsack-phb|Schlafsack]]
> **Menge:** 1x
> **Gewicht:** 3,5 kg.
> **Gegenstandsart:** Abenteuerausrüstung
> ---

> [!recite]- [[Tagesration-phb|Tagesration]]
> **Menge:** 8x
> **Gewicht:** 8 kg.
> **Gegenstandsart:** Abenteuerausrüstung
> ---
**Beschreibung.** Die Rationen bestehen aus trockenen Lebensmitteln, die für längere Reisen geeignet sind, einschließlich Dörrfleisch, Trockenobst, Hartriegel und Nüsse.
> ```consumable
> items:
>   - label: "Charges"
>     state_key: my_character_example_item
>     uses: 10
>     reset_on: long-rest
> ```
> ^unique-item-ID

> [!recite]- [[Verkleidungsausrüstung-phb|Verkleidungsausrüstung]]
> **Menge:** 1x
> **Gewicht:** 1,0 kg.
> **Gegenstandsart:** Werkzeug
> ---

> [!recite]- [[Wasserschlauch-phb|Wasserschlauch]]
> **Menge:** 1x
> **Gewicht:** 2,5 kg.
> **Gegenstandsart:** Abenteuerausrüstung
> ---
**Beschreibung.** Ein Wasserschlauch hat ein Fassungsvermögen von 4 Liter Flüssigkeit.

## Andere Behälter (Nimmervoller Beutel, etc)
- **Fassungsvermögen:** X kg.

# Zauber
[[#Zauber|🔗]]  

```stats
items:
  - label: Attribut
    value: Charisma
  - label: Zauberrettungswurf
    value: '{{ add 8 frontmatter.proficiency_bonus (modifier abilities.charisma) }}'
  - label: Zauberangriffsbonus
    value: '+{{ add frontmatter.proficiency_bonus (modifier abilities.charisma) }}'

grid:
  columns: 3

dense: true
```

> [!recite|t-w]- Zauberfokus
> | Name | Typ | Eigenschaften & Notizen |
> | ------ | ----- | -------------------- |
> | Flöte | Instrument |  |
> | Laute | Instrument |  |
> | Leise | Instrument |  |

> [!columns|no-t nmg] Zauberliste
> > [!recite|t-w] Zaubertricks
> > | Zauber | Zeit-aufwand | Reich-weite | Wirkungs-dauer | Kompon-enten |
> > | ----- | ------------- | ------- | --------- | ------------- |
> > | [[Einfache_Illusion-phb\|Einfache Illusion]] | 1 Aktion | 9m | 1 Minute | G, M |
> > | [[Gehässiger_Spott-phb\|Gehässiger Spott]] | 1 Aktion | 18m | Unmittelbar | V |
> > | [[Licht-phb\|Licht]] | 1 Aktion  | Berührung | 1 Stunde | V, M |
> > |  |  |  |  |  |
>
> > [!recite|t-w txt-s nmg] Zaubergrad 1
> > > [!recite|txt-s alt-line] Zauberplätze Grad 1
> > > ```consumable
> > > items:
> > >   - label: "Zauberplätze LV1"
> > >     state_key: my_character_SPL1
> > >     reset_on: long-rest
> > >     uses: 4
> > > ```
> > 
> > | Prep. | Zauber | Zeit-aufwand | Reich-weite | Wirkungs-dauer | Kompon-enten |
> > | ----- | ----- |------------- | ------- | --------- | ------------- |
> > | `INPUT[toggle:SP1-1]` | [[Dissonantes_Flüstern-phb\|Dissonantes Flüstern]] | 1 Aktion | 18m | Unmittelbar | V |
> > | `INPUT[toggle:SP1-2]` | [[Heilendes_Wort-phb\|Heilendes Wort]] | 1 Bonus | 18m | Unmittelbar | V |
> > | `INPUT[toggle:SP1-3]` | [[Lautloses_Trugbild-phb\|Lautloses Trugbild]] | 1 Aktion | 18m | Konzentration, bis zu 10 Min | V, G, M |
> > | `INPUT[toggle:SP1-4]` | [[Magie_entdecken-phb\|Magie entdecken]] | 1 Aktion | Selbst | Konzentration, bis zu 10 Min | V, G |
> > | `INPUT[toggle:SP1-5]` |  |  |  |  |  |
> > | `INPUT[toggle:SP1-6]` |  |  |  |  |  |
> > | `INPUT[toggle:SP1-7]` |  |  |  |  |  |
> > | `INPUT[toggle:SP1-8]` |  |  |  |  |  |
> > | `INPUT[toggle:SP1-9]` |  |  |  |  |  |
> > | `INPUT[toggle:SP1-10]` |  |  |  |  |  |
> > | `INPUT[toggle:SP1-11]` |  |  |  |  |  |
> > | `INPUT[toggle:SP1-12]` |  |  |  |  |  |
> > | `INPUT[toggle:SP1-13]` |  |  |  |  |  |
> 
> > [!recite|t-w txt-s nmg] Zaubergrad 2
> > > [!recite|txt-s alt-line] Zauberplätze Grad 2
> > > ```consumable
> > > items:
> > >   - label: "Zauberplätze LV2"
> > >     state_key: my_character_SPL2
> > >     reset_on: long-rest
> > >     uses: 3
> > > ```
> > 
> > | Prep. | Zauber | Zeit-aufwand | Reich-weite | Wirkungs-dauer | Kompon-enten |
> > | ----- | ----- |------------- | ------- | --------- | ------------- |
> > | `INPUT[toggle:SP2-1]` | [[Dissonantes_Flüstern-phb\|Dissonantes Flüstern]] | 1 Aktion | 18m | Unmittelbar | V |
> > | `INPUT[toggle:SP2-2]` | [[Heilendes_Wort-phb\|Heilendes Wort]] | 1 Bonus | 18m | Unmittelbar | V |
> > | `INPUT[toggle:SP2-3]` | Klopfen |  |  |  |  |
> > | `INPUT[toggle:SP2-4]` | Nebelschritt |  |  |  |  |
> > | `INPUT[toggle:SP2-5]` | Spiegelbild |  |  |  |  |
> > | `INPUT[toggle:SP2-6]` | Stille |  |  |  |  |
> > | `INPUT[toggle:SP2-7]` |  |  |  |  |  |
> > | `INPUT[toggle:SP2-8]` |  |  |  |  |  |
> > | `INPUT[toggle:SP2-9]` |  |  |  |  |  |
> > | `INPUT[toggle:SP2-10]` |  |  |  |  |  |
> > | `INPUT[toggle:SP2-11]` |  |  |  |  |  |
> > | `INPUT[toggle:SP2-12]` |  |  |  |  |  |
> > | `INPUT[toggle:SP2-13]` |  |  |  |  |  |
> 
> > [!recite|t-w txt-s nmg] Zaubergrad 3
> > > [!recite|txt-s alt-line] Zauberplätze Grad 3
> > > ```consumable
> > > items:
> > >   - label: "Zauberplätze LV3"
> > >     state_key: my_character_SPL3
> > >     reset_on: long-rest
> > >     uses: 3
> > > ```
> > 
> > | Prep. | Zauber | Zeit-aufwand | Reich-weite | Wirkungs-dauer | Kompon-enten |
> > | ----- | ----- |------------- | ------- | --------- | ------------- |
> > | `INPUT[toggle:SP3-1]` | [[Dissonantes_Flüstern-phb\|Dissonantes Flüstern]] | 1 Aktion | 18m | Unmittelbar | V |
> > | `INPUT[toggle:SP3-2]` | [[Heilendes_Wort-phb\|Heilendes Wort]] | 1 Bonus | 18m | Unmittelbar | V |
> > | `INPUT[toggle:SP3-3]` | Leomunds winzige Hütte |  |  |  |  |
> > | `INPUT[toggle:SP3-4]` | [[Magie_bannen-phb\|Magie bannen]] |  |  |  |  |
> > | `INPUT[toggle:SP3-5]` | [[Mit_Toten_sprechen-phb\|Mit Toten sprechen]] |  |  |  |  |
> > | `INPUT[toggle:SP3-6]` |  |  |  |  |  |
> > | `INPUT[toggle:SP3-7]` |  |  |  |  |  |
> > | `INPUT[toggle:SP3-8]` |  |  |  |  |  |
> > | `INPUT[toggle:SP3-9]` |  |  |  |  |  |
> > | `INPUT[toggle:SP3-10]` |  |  |  |  |  |
> > | `INPUT[toggle:SP3-11]` |  |  |  |  |  |
> > | `INPUT[toggle:SP3-12]` |  |  |  |  |  |
> > | `INPUT[toggle:SP3-13]` |  |  |  |  |  |
> 
> > [!recite|t-w txt-s nmg] Zaubergrad 4
> > > [!recite|txt-s alt-line] Zauberplätze Grad 4
> > > ```consumable
> > > items:
> > >   - label: "Zauberplätze LV4"
> > >     state_key: my_character_SPL4
> > >     reset_on: long-rest
> > >     uses: 3
> > > ```
> > 
> > | Prep. | Zauber | Zeit-aufwand | Reich-weite | Wirkungs-dauer | Kompon-enten |
> > | ----- | ----- |------------- | ------- | --------- | ------------- |
> > | `INPUT[toggle:SP4-1]` |  |  |  |  |  |
> > | `INPUT[toggle:SP4-2]` |  |  |  |  |  |
> > | `INPUT[toggle:SP4-3]` |  |  |  |  |  |
> > | `INPUT[toggle:SP4-4]` |  |  |  |  |  |
> > | `INPUT[toggle:SP4-5]` |  |  |  |  |  |
> > | `INPUT[toggle:SP4-6]` |  |  |  |  |  |
> > | `INPUT[toggle:SP4-7]` |  |  |  |  |  |
> > | `INPUT[toggle:SP4-8]` |  |  |  |  |  |
> > | `INPUT[toggle:SP4-9]` |  |  |  |  |  |
> > | `INPUT[toggle:SP4-10]` |  |  |  |  |  |
> > | `INPUT[toggle:SP4-11]` |  |  |  |  |  |
> > | `INPUT[toggle:SP4-12]` |  |  |  |  |  |
> > | `INPUT[toggle:SP4-13]` |  |  |  |  |  |
> 
> > [!recite|t-w txt-s nmg] Zaubergrad 5
> > > [!recite|txt-s alt-line] Zauberplätze Grad LV5
> > > ```consumable
> > > items:
> > >   - label: "Zauberplätze LV5"
> > >     state_key: my_character_SPL5
> > >     reset_on: long-rest
> > >     uses: 3
> > > ```
> > 
> > | Prep. | Zauber | Zeit-aufwand | Reich-weite | Wirkungs-dauer | Kompon-enten |
> > | ----- | ----- |------------- | ------- | --------- | ------------- |
> > | `INPUT[toggle:SP5-1]` |  |  |  |  |  |
> > | `INPUT[toggle:SP5-2]` |  |  |  |  |  |
> > | `INPUT[toggle:SP5-3]` |  |  |  |  |  |
> > | `INPUT[toggle:SP5-4]` |  |  |  |  |  |
> > | `INPUT[toggle:SP5-5]` |  |  |  |  |  |
> > | `INPUT[toggle:SP5-6]` |  |  |  |  |  |
> > | `INPUT[toggle:SP5-7]` |  |  |  |  |  |
> > | `INPUT[toggle:SP5-8]` |  |  |  |  |  |
> > | `INPUT[toggle:SP5-9]` |  |  |  |  |  |
> 
> > [!recite|t-w txt-s nmg] Zaubergrad 6
> > > [!recite|txt-s alt-line] Zauberplätze Grad 6
> > > ```consumable
> > > items:
> > >   - label: "Zauberplätze LV6"
> > >     state_key: my_character_SPL6
> > >     reset_on: long-rest
> > >     uses: 2
> > > ```
> > 
> > | Prep. | Zauber | Zeit-aufwand | Reich-weite | Wirkungs-dauer | Kompon-enten |
> > | ----- | ----- |------------- | ------- | --------- | ------------- |
> > | `INPUT[toggle:SP6-1]` |  |  |  |  |  |
> > | `INPUT[toggle:SP6-2]` |  |  |  |  |  |
> > | `INPUT[toggle:SP6-3]` |  |  |  |  |  |
> > | `INPUT[toggle:SP6-4]` |  |  |  |  |  |
> > | `INPUT[toggle:SP6-5]` |  |  |  |  |  |
> > | `INPUT[toggle:SP6-6]` |  |  |  |  |  |
> > | `INPUT[toggle:SP6-7]` |  |  |  |  |  |
> > | `INPUT[toggle:SP6-8]` |  |  |  |  |  |
> > | `INPUT[toggle:SP6-9]` |  |  |  |  |  |
> 
> > [!recite|t-w txt-s nmg] Zaubergrad 7
> > > [!recite|txt-s alt-line] Zauberplätze Grad 7
> > > ```consumable
> > > items:
> > >   - label: "Zauberplätze LV7"
> > >     state_key: my_character_SPL7
> > >     reset_on: long-rest
> > >     uses: 2
> > > ```
> > 
> > | Prep. | Zauber | Zeit-aufwand | Reich-weite | Wirkungs-dauer | Kompon-enten |
> > | ----- | ----- |------------- | ------- | --------- | ------------- |
> > | `INPUT[toggle:SP7-1]` |  |  |  |  |  |
> > | `INPUT[toggle:SP7-2]` |  |  |  |  |  |
> > | `INPUT[toggle:SP7-3]` |  |  |  |  |  |
> > | `INPUT[toggle:SP7-4]` |  |  |  |  |  |
> > | `INPUT[toggle:SP7-5]` |  |  |  |  |  |
> > | `INPUT[toggle:SP7-6]` |  |  |  |  |  |
> > | `INPUT[toggle:SP7-7]` |  |  |  |  |  |
> > | `INPUT[toggle:SP7-8]` |  |  |  |  |  |
> > | `INPUT[toggle:SP7-9]` |  |  |  |  |  |
> 
> > [!recite|t-w txt-s nmg] Zaubergrad 8
> > > [!recite|txt-s alt-line] Zauberplätze Grad 8
> > > ```consumable
> > > items:
> > >   - label: "Zauberplätze LV8"
> > >     state_key: my_character_SPL8
> > >     reset_on: long-rest
> > >     uses: 1
> > > ```
> > 
> > | Prep. | Zauber | Zeit-aufwand | Reich-weite | Wirkungs-dauer | Kompon-enten |
> > | ----- | ----- |------------- | ------- | --------- | ------------- |
> > | `INPUT[toggle:SP8-1]` |  |  |  |  |  |
> > | `INPUT[toggle:SP8-2]` |  |  |  |  |  |
> > | `INPUT[toggle:SP8-3]` |  |  |  |  |  |
> > | `INPUT[toggle:SP8-4]` |  |  |  |  |  |
> > | `INPUT[toggle:SP8-5]` |  |  |  |  |  |
> > | `INPUT[toggle:SP8-6]` |  |  |  |  |  |
> > | `INPUT[toggle:SP8-7]` |  |  |  |  |  |
> 
> > [!recite|t-w txt-s nmg] Zaubergrad 9
> > > [!recite|txt-s alt-line] Zauberplätze Grad 9
> > > ```consumable
> > > items:
> > >   - label: "Zauberplätze LV9"
> > >     state_key: my_character_SPL9
> > >     reset_on: long-rest
> > >     uses: 1
> > > ```
> > 
> > | Prep. | Zauber | Zeit-aufwand | Reich-weite | Wirkungs-dauer | Kompon-enten |
> > | ----- | ----- |------------- | ------- | --------- | ------------- |
> > | `INPUT[toggle:SP9-1]` |  |  |  |  |  |
> > | `INPUT[toggle:SP9-2]` |  |  |  |  |  |
> > | `INPUT[toggle:SP9-3]` |  |  |  |  |  |
> > | `INPUT[toggle:SP9-4]` |  |  |  |  |  |
> > | `INPUT[toggle:SP9-5]` |  |  |  |  |  |
> > | `INPUT[toggle:SP9-6]` |  |  |  |  |  |
> > | `INPUT[toggle:SP9-7]` |  |  |  |  |  |


# Talente & Merkmale
[[#Features & Traits|🔗]]  
> [!recite]- Search Action/Bonus Action/Reaction
> > [!recite|alt-line txt-s]- Actions
> > ```query
> > line:#action
> > title: A C T I O N S
> > ```
> 
> > [!recite|alt-line txt-s]- Bonus Actions
> > ```query
> > line:#bonus-action
> > title: B O N U S - A C T I O N S
> > ```
> 
> > [!recite|alt-line txt-s]- Reactions
> > ```query
> > line:#reaction
> > title: R E A C T I O N S
> > ```
> 

#### Sinne & Verwundbarkeiten
**Sinne:** Dunkelsicht
**Resistenzen:** 
**Verwundbarkeiten:** 
**Immunität:** Magischer Schlaf

## Aktionen

Angriffe pro Aktion: 1

- Pistole
- Pistole
- Rapier
- Dissonantes Flüstern
- Waffenloser Angriff

Aktionen im Kampf
	Attack, Dash, Disengage, Dodge, Grapple, Help, Hide, Improvise, Influence, Magic, Ready, Search, Shove, Study, Utilize

- Bannlied
- Universelle Sprache
- Waffenloser Angriff

## Bonusaktionen

Aktionen im Kampf
- Kampf mit zwei Waffen

Zauber
- Heilendes Wort
- Nebelschritt

---

- Bardische Inspiration
- Verunsichernde Worte

## Reaktionen

Aktionen im Kampf
- Gelegenheitsangriff

## Andere Merkmale

Aktionen im Kampf
- Interact with an Object

Zauber
- Leomunds Winzige Hütte

Ritualzauber
- Leomunds Winzige Hütte
- Stille

## Klassenmerkmale

> [!recite|nmg]+ Bardische Inspiration
> # Klassenmerkmal
> *Quelle: PHB / Stufe 1 Klassenmerkmal / PHB*
> \--
> Du vermagst andere zu inspirieren, indem du eine bewegende Rede hältst oder ermutigende Musik erklingen lässt. Als Bonusaktion kannst du in deinem Zug innerhalb von 18 m Reichweite eine Kreatur außer dir selbst bestimmen, die in der Lage sein muss, dich zu hören. Diese Kreatur erhält einen bardischen Inspirationswürfel, auf der 1. Stufe einen W6. 
> $\quad$Einmal innerhalb der nächsten 10 Minuten kann die Kreatur diesen Würfel nutzen und das gewürfelte Ergebnis auf einen Attributs-, Angriffs- oder Rettungswurf addieren. Sie kann auch nach diesem Wurf entscheiden, ob sie den bardischen Inspirationswürfel einsetzen möchte. Allerdings muss sie ihre Entscheidung treffen, bevor der SL bekannt gibt, ob das Ergebnis ein Erfolg oder Misserfolg ist. Wurde der bardische lnspirationswürfel benutzt, ist er verbraucht. Jede Kreatur darf nur über einen Inspirationswürfel gleichzeitig verfügen. Du kannst dieses Merkmal so oft einsetzen, wie es der Höhe deines Charismamodifikators entspricht (mindestens 1). Nach einer langen Rast erhältst du alle verbrauchten Anwendungen zurück.
> $\quad$Der Inspirationswürfel ändert sich, wenn du bestimmte Stufen als Barde erreichst: Auf der 5. Stufe wird er zu einem W8, auf der 10. zu einem W10 und auf der 15. zu einem W12. 

> [!recite|nmg]+ Alleskönner
> # Klassenmerkmal
> *Quelle: PHB / Stufe 2 Klassenmerkmal / PHB*
> \--
> Ab der 2. Stufe kannst du deinen halben Übungsbonus (abgerundet) auf jeden Attributswurf addieren, der nicht bereits durch deinen Übungsbonus verbessert wird. 
> 

> [!recite|nmg]+ Lied der Erholung
> # Klassenmerkmal
> *Quelle: PHB / Stufe 2 Klassenmerkmal / PHB*
> \--
> Von der 2. Stufe an kannst du während einer kurzen Rast mit sanfter Musik oder Gesängen den Heilungsprozess deiner verwundeten Verbündeten beschleunigen. Wenn du oder eine befreundete Kreatur durch das Ausgeben von Trefferwürfeln zum Ende einer kurzen Rast Trefferpunkte wiedererlangt, erhält der Betroffene 1W6 zusätzliche Trefferpunkte zurück. Die befreundete Kreatur muss deine Darbietung hören können, um von diesem Effekt zu profitieren. 
> $\quad$Die zusätzlichen Trefferpunkte erhöhen sich mit dem Aufstieg in dieser Klasse: ab der 9. Stufe auf 1W8, ab der 13. Stufe auf 1W10 und ab der 17. Stufe auf 1W12. 

> [!recite|nmg]+ Bardenschule
> # Klassenmerkmal
> *Quelle: PHB / Stufe 3 Klassenmerkmal / PHB*
> \--
> Auf Stufe 3 wirst du in die fortgeschrittenen Techniken einer Bardenschule deiner Wahl eingeweiht. Wähle die Schule des Wagemuts oder die Schule des Wissens, beide sind am Ende dieses Abschnitts näher beschrieben. Deine Wahl verleiht dir auf der 3., 6. und 14. Stufe jeweils ein Merkmal. 
> 
> - Schule der Eloquenz 

> [!recite|nmg]+ Expertise
> # Klassenmerkmal
> *Quelle: PHB / Stufe 3 Klassenmerkmal / PHB*
> \--
> Mit Stufe 3 wählst du zwei deiner Fertigkeiten aus, in denen du geübt bist. Dein Übungsbonus wird bei allen Attributswürfen verdoppelt, bei denen diese Fertigkeiten zur Anwendung kommen.
> $\quad$Auf der 10. Stufe kannst du dir zwei weitere deiner geübten Fertigkeiten aussuchen, in denen du den gleichen Vorzug erhältst. 
> - Nachforschung
> - Wahrnehmung

> [!recite|nmg]+ Silberzunge
> # Schule-der-Eloquenz-Merkmal
> *Quelle: TCE / Stufe 3 Klassenmerkmal*
> \--
> Du bist Meister darin, das Richtige zur richtigen Zeit zu sagen. Wenn du einen Wurf auf Charisma (Überzeugen) oder Charisma (Täuschen) ausführst, darfst du W20-Augenzahlen von 9 oder geringer als 10 behandeln. 

> [!recite|nmg]+ Verstörende Worte
> # Schule-der-Eloquenz-Merkmal
> *Quelle: TCE / Stufe 3 Klassenmerkmal*
> \--
> Du kannst Worte mit Magie versehen und eine Kreatur mit ihr verunsichern, sodass sie an sich zweifelt. Als Bonusaktion kannst du deine Bardische Inspiration einsetzen und eine Kreatur, die du sehen kannst, innerhalb von 18 Metern von dir auswählen. Wirf den Würfel der Bardischen Inspiration. Die Kreatur muss die erwürfelte Augenzahl von ihrem nächsten Rettungswurf vor Beginn deiner nächsten Runde abziehen. 

> [!recite|nmg]+ Attributswerterhöhung
> # Klassenmerkmal
> *Quelle: PHB / Stufe 4 Klassenmerkmal / PHB*
> \--
> Beim Erreichen der 4. Stufe und dann wieder auf der 8., 12., 16. und 19. Stufe kannst du einen Attributswert deiner Wahl um 2 Punkte erhöhen oder ein anderes Talent deiner Wahl, für das du qualifiziert bist wählen. Du kannst stattdessen auch zwei Attributswerte um jeweils 1 Punkt erhöhen. Kein Attribut darf auf diese Weise über einen Wert von 20 steigen. 
> - Von Feen berührt

> [!recite|nmg]+ Quelle der Inspiration
> # Klassenmerkmal
> *Quelle: PHB / Stufe 3 Klassenmerkmal / PHB*
> \--
> Von der 5. Stufe an erhältst du all deine Anwendungen der Bardischen Inspiration zurück, sobald du eine kurze oder lange Rast beendet hast. 

> [!recite|nmg]+ Bannlied
> # Klassenmerkmal
> *Quelle: PHB / Stufe 3 Klassenmerkmal / PHB*
> \--
> Auf Stufe 6 erlangst du die Fähigkeit, mit Zaubern gewobene Musik und Worte der Macht zu nutzen, um geistesbeeinflussende Effekte abzuwenden. Als Aktion kannst du eine Darbietung geben, die bis zum Ende deines nächsten Zuges andauert. Während dieser Zeit sind du und deine verbündeten Kreaturen im Umkreis von 9 m im Vorteil bei Rettungswürfen, um nicht bezaubert oder verängstigt zu sein. Die betroffene Kreatur muss in der Lage sein, dich zu hören, damit sie in den Genuss dieses Vorzugs kommt. Die Darbietung endet vorzeitig, falls du zum Schweigen gebracht wirst oder kampfunfähig wirst. Du kannst sie auch freiwillig beenden, wozu keine Aktion notwendig ist. 

> [!recite|nmg]+ Unfehlbare Inspiration
> # Schule-der-Eloquenz-Merkmal
> *Quelle: TCE / Stufe 6 Klassenmerkmal*
> \--
> Deine inspirierenden Worte sind so überzeugend, dass sie andere anspornen. Wenn eine Kreatur einen deiner Würfel der Bardischen Inspiration ihrem Attributs-, Angriffs-oder Rettungswurf hinzufügt und der Wurf scheitert, kann die Kreatur den Würfel der Bardischen Inspiration behalten. 

> [!recite|nmg]+ Universelle Sprache
> # Schule-der-Eloquenz-Merkmal
> *Quelle: TCE / Stufe 6 Klassenmerkmal*
> \--
> Du erhältst die Fähigkeit, dich für alle Kreaturen verständlich auszudrücken. Wähle als Aktion mindestens eine Kreatur innerhalb von 18 Metern von dir aus, höchstens so viele Kreaturen, dass ihre Anzahl deinem Charismasmodifikator entspricht (mindestens eine Kreatur). Die ausgewählten Kreaturen können dich unabhängig von der Sprache, die du sprichst, eine Stunde lang auf magische Art verstehen. 
> $\quad$Du kannst dieses Merkmal erst nach einer langen Rast erneut verwenden, es sei denn, du verbrauchst einen Zauberplatz beliebigen Grads, um es erneut einzusetzen. 

## Rassenmerkmale

> [!recite|nmg]+ Attributswerterhöhung
> # Merkmal
> *Quelle: PHB / Halb-Elf*
> \--
> Dein Charismawert wird um 2 Punkte erhöht. Außerdem steigen zwei weitere Attributswerte deiner Wahl um je 1 Punkte an. 
> 
> Stärke +1
> Konstitution+1

> [!recite|nmg]+ Dunkelsicht
> # Merkmal
> *Quelle: PHB / Halb-Elf*
> \--
> Dank deines elfischen Blutes besitzt du eine überlegene Sicht in dunklen und dämmrigen Lichtverhältnissen. Behandle im Umkreis von 18 m dämmriges Licht wie helles Licht und Dunkelheit wie dämmriges Licht. Allerdings kannst du im Dunkeln keine Farben erkennen, nur Graustufen. 
> 

> [!recite|nmg]+ Feenblut
> # Merkmal
> *Quelle: PHB / Halb-Elf*
> \--
> Du bist bei Rettungswürfen gegen Bezauberungen im Vorteil und immun gegen Schlafzauber. 
> 

> [!recite|nmg]+ Vielseitigkeit
> # Merkmal
> *Quelle: PHB / Halb-Elf*
> \--
> Du bist geübt in zwei Fertigkeiten deiner Wahl. 
> - Fingerfertigkeit
> - Überzeugung

## Talente

> [!recite|nmg]+ Von Feen berührt
> # Talent
> *Quelle: TCE / Stufe 4 Talent*
> \--
> - Charisma +1
> ```consumable
> items:
>   - label: "Magie entdecken"
>     state_key: Magie_entdecken
>     uses: 1
>     reset_on: long-rest
>   - label: "Nebelschritt"
>     state_key: Nebelschritt
>     uses: 1
>     reset_on: long-rest
> ```
> Dein Kontakt mit der Magie des Feenwild hat dich verändert und dir folgende Vorzüge gewährt: 
> 	- Deine Intelligenz, deine Weisheit oder dein Charisma wird um 1 Punkt erhöht (auf maximal 20). 
> 	- Du lernst den Zauber [[Nebelschritt-phb|Nebelschritt]] und einen Zauber des 1. Grads deiner Wahl. Letzterer muss aus der Schule der Erkenntnismagie oder der Verzauberung stammen. Du musst keinen Zauberplatz verbrauchen, um diese Zauber zu wirken. Wirkst du einen dieser Zauber, kannst du ihn erst nach einer langen Rast erneut wirken. Du kannst diese Zauber auch mit einem beliebigen verfügbaren Zauberplatz des entsprechenden Grads wirken. Das Attribut zum Zauberwirken für diesen Zauber ist das durch dieses Talent erhöhte. 
> 

# Konfiguration
[[#Konfiguration|🔗]]  

> [!columns|no-t]
> > [!recite|bg-white no-t t-w]
> > | Info                  | Description                       |
> > | --------------------- | --------------------------------- |
> > | **Total Level**       | `INPUT[number(placeholder(Level)):level]`             |
> > | **Proficiency Bonus** | `INPUT[number(placeholder(+X)):proficiency_bonus]` |
> > | **Max Hit Points**    | `INPUT[number(placeholder(Hit Die + CON)):hp]`                |
> > | **Armor Class**       | `INPUT[number(placeholder(Check Equipment for more)):ac]`                |
> > | **Speed**             | `INPUT[number(placeholder(Walking Speed)):speed]`             |
> > Leave **Proficiency Bonus** blank to automatically calculate based on **Total Level**.
> 
> > [!recite|bg-white] State Keys
> > Character sheets each need unique state keys in order to function wherever they appear. You can edit the code blocks where they appear, replacing `my_character` with your character name (Or whatever your preference is! Just *make sure* that the state key is unique across your entire vault). State keys tend to appear wherever there are checkboxes. Specifically, they appear in the `healthpoints` block and the `consumable` blocks.
> 
> > [!recite|bg-white] Ability Scores & Skills
> > Your character's ability scores need to be modified in the `ability` code block under the [[#Abilities]] section. You can also adjust your saving throws under the `proficiencies` section of that code block. Lastly, you can add bonuses (like from items and features) in the `bonuses` section of the code block following the structure provided. You can change your skill proficiencies within the `skills` code block right beneath.
> 
> > [!recite|bg-yellow] Tips and Credits
> > The DnD-UI Toolkit plugin has some bugs with showing abilities and skills in the main tab box as of July 2025. The Initiative badge and Skills block don't render properly at the moment, so you need to click the link button at the top of the General block and Abilities block to see them accurately.
> > If you are struggling with any of the formatting and syntax of this template, check out the docs from the following sources: [Obsidian](https://help.obsidian.md/syntax), [ITS Theme](https://publish.obsidian.md/slrvb-docs/ITS+Theme/ITS+Theme), [DND UI Toolkit](https://hay-kot.github.io/obsidian-dnd-ui-toolkit/), [MetaBind](https://www.moritzjung.dev/obsidian-meta-bind-plugin-docs/).
> > Additionally, if you need to add any new text boxes or in-table check boxes, check the MetaBind plugin documentation (listed above). You will need to add a new unique Property (at the top of the Note) and tie it to the INPUT field you created.
> > Lastly, this Vault comes with an alphabetical Spellbook folder. It is recommended to link your spells in [[#Spellcasting]] to those notes for easy access. Items placed in the Equipment section can also be linked in the [[#Inventory]] section for quick descriptions. Using tags on Features & Traits such as Action, Bonus Action, or Reaction can help sort abilities quicker.
> > This character sheet template was made lovingly by [Cupcaeke](https://cupcaeke.carrd.co). I made this to work as a sort of middle-ground between a good ole pdf/paper sheet and something like DNDBeyond or Orcpub. I hope you enjoy!

# Backstory
[[#Backstory|🔗]]  

---

---
# Misc.
[[#Misc.|🔗]]  

---

---
# Notes
[[#Notes|🔗]]  

---
