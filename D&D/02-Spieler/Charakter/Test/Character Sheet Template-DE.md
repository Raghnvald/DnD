---
Bezeichnung: "**Character Name**"
ac: 15
AC1: false
AC2: true
AC3: false
AC4: false
ALIGN: Chaotisch Gut
ammo1:
ammo2:
BG: Unterhaltungskünstler
BOND: Someone stole my precious instrument, and someday I’ll get it back.
CARRY:
CL: Barde 6
CP: 0
EP: 0
EXP: "0"
EYE: Braun
FLAW: I once satirized a noble who still wants my head. It was a mistake that I will likely repeat.
GP: 48
HAIR: Braun
HI:
hp: 57
IDEAL: People. I like seeing the smiles on people’s faces when I perform. That’s all that matters. (Neutral)
IMAGE:
LBS:
level: 6
PERS: |-
  I know a story relevant to almost every situation.
  I love a good insult, even one directed at me.
  I’ll settle for nothing less than perfection.
PN: Fayn
PP: 0
proficiency_bonus:
RACE: Halb-Elf
SKIN: Hellhäutig
SP: 3
SP1-1: true
SP1-10: false
SP1-11: false
SP1-12: false
SP1-13: false
SP1-2: true
SP1-3: true
SP1-4: true
SP1-5: false
SP1-6: false
SP1-7: false
SP1-8: false
SP1-9: false
SP2-1: true
SP2-10: false
SP2-11: false
SP2-12: false
SP2-13: false
SP2-2: true
SP2-3: true
SP2-4: true
SP2-5: true
SP2-6: true
SP2-7: false
SP2-8: false
SP2-9: false
SP3-1: true
SP3-10: false
SP3-11: false
SP3-12: false
SP3-13: false
SP3-2: true
SP3-3: true
SP3-4: true
SP3-5: false
SP3-6: false
SP3-7: false
SP3-8: false
SP3-9: false
SP4-1: false
SP4-10: false
SP4-11: false
SP4-12: false
SP4-13: false
SP4-2: false
SP4-3: false
SP4-4: false
SP4-5: false
SP4-6: false
SP4-7: false
SP4-8: false
SP4-9: false
SP5-1: false
SP5-2: false
SP5-3: false
SP5-4: false
SP5-5: false
SP5-6: false
SP5-7: false
SP5-8: false
SP5-9: false
SP6-1: false
SP6-2: false
SP6-3: false
SP6-4: false
SP6-5: false
SP6-6: false
SP6-7: false
SP6-8: false
SP6-9: false
SP7-1: false
SP7-2: false
SP7-3: false
SP7-4: false
SP7-5: false
SP7-6: false
SP7-7: false
SP7-8: false
SP7-9: false
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
speed: 9
TREASURE:
---

# **Character Name**

~~~tabs
---Allgemein
![[#General|no-h1 full clean]]
---Beschreibung
![[#Description|no-h1 full clean]]
---Bilder
![[#Image Gallery|no-h1 full clean]]
---Konfig
![[#Config|no-h1 full clean]]
---Quick Ref.
![[#Quick Reference|no-h1 full clean]]
~~~

~~~tabs
---Fertigkeiten
![[#Abilities|no-h1 full clean]]
---Ausrüstung
![[#Equipment|no-h1 full clean]]
---Inventar
![[#Inventory|no-h1 full clean]]
---Zauberwirken
![[#Spellcasting|no-h1 full clean]]
---Merkmale & Talente
![[#Features & Traits|no-h1 full clean]]
---Hintergrund
![[#Backstory|no-h1 full clean]]
---Misc.
![[#Misc.|no-h1 full clean]]
---Notizen
![[#Notes|no-h1 full clean]]
~~~

---
---

# General
[[#General|🔗]] 

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
    value: '{{ modifier abilities.dexterity }}'
  - label: Bew.
    value: '{{ frontmatter.speed }}'
  - label: Inspiration
    value: '[ ]'
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
# Description
[[#Description|🔗]] 

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
# Image Gallery
[[#Image Gallery|🔗]]  

```meta-bind
INPUT[imageListSuggester:IMAGE]
```
# Config
[[#Config|🔗]]  

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
# Abilities
[[#Abilities|🔗]]  

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
  - Perception
  - Investigation

bonuses:
  - name: 
    target: 
    value: 
    modifies: 
```

```skills
proficiencies:
  - acrobatics

expertise:
  - perception
  - investigation
```
```badges
items:
  - label: Passive Wahrnehmung
    value: '{{ add 10 (modifier abilities.wisdom) }}'
```

> [!recite|bg-white t-w ws-med] Andere Übungen & Training
> | Übungsart         | Beschreibung         |
> | ----------------- | ------------------- |
> | **Rüstung** |  Leichte Rüstung   |
> | **Waffen**          | Einfache Waffen, Rapier, Pistole, Kurzschwert, Handarmbrust  |
> | **Werkzeuge**    |  Dudelsack, Flöte, Laute, Leier, Verkleidungsausrüstung   |
> | **Sprachen**     | Gemeinsprache, Elfisch, Zwergisch |
> | **Anderes**   |     |

# Quick Reference
[[#Quick Reference|🔗]]  

**A quick reference for things you can do on your turn, as well as various conditions and effects**
<iframe
src="https://donjon.bin.sh/5e/quickref/"
width="150"
height="300"
style="overflow: auto; resize: both; aspect-ratio: 16 / 9; width: 100%; height: 100%;">
</iframe> 

# Equipment
[[#Equipment|🔗]]  

## Waffen #action

| Gegenstand               | Reichweite | ATK Bonus | Schaden / Art | *Eigenschaften / Notizen* |
| ------------------------ | ---------- | --------- | ------------- | ------------------------- |
| [[Dolch-phb\|Dolch]]     |            |           | 1d4 Stich     |                           |
| [[Pistole-dmg\|Pistole]] |            |           | 1d10 Stich    |                           |
| [[Pistole-dmg\|Pistole]] |            |           | 1d10 Stich    |                           |
| [[Rapier-phb\|Rapier]]   |            |           | 1d8 Stich     |                           |
|                          |            |           |               |                           |

| Ammunition Type | Count                                              |
| --------------- | -------------------------------------------------- |
|                 | `INPUT[number(class(wider),placeholder(0)):ammo1]` |
|                 | `INPUT[number(class(wider),placeholder(0)):ammo2]` |
## Rüstung

| Equip               | Gegenstand               | Reichweite | ATK Bonus | Schaden / Art | *Eigenschaften / Notizen* |
| ------------------- | ---------------------------------- | ------ | ------ | ------- | -------------------- |
| `INPUT[toggle:AC1]` | Unarmored                          | Leicht | 10+GES | ---     |                      |
| `INPUT[toggle:AC2]` | [[Lederrüstung-phb\|Lederrüstung]] | Leicht | 11+GES | ---     |                      |
| `INPUT[toggle:AC3]` |                                    |        |        |         |                      |
| `INPUT[toggle:AC4]` |                                    |        |        |         |                      |
## Einstimmungsplätze

| Slot  | Item | Body Part | Summary |
| ----- | ---- | --------- | ------- |
| **1** |      |           |         |
| **2** |      |           |         |
| **3** |      |           |         |
# Inventory
[[#Inventory|🔗]]  

- **Current Encumbrance**
	- `INPUT[number(class(wider),placeholder(Held)):CARRY]`**lbs**
```badges
items:
  - label: Capacity
    value: '{{ multiply 15 abilities.strength }}lbs'
```

## Münzbeutel

> [!recite|wm-sm txt-c t-w table-cell-top] Treasure
> | KM | SM | EM | GM | PM |
> | --- | --- | --- | --- | --- |
> | `INPUT[number(class(wider),placeholder(0)):CP]` | `INPUT[number(class(wider),placeholder(0)):SP]` | `INPUT[number(class(wider),placeholder(0)):EP]` | `INPUT[number(class(wider),placeholder(0)):GP]` | `INPUT[number(class(wider),placeholder(0)):PP]` |
> `INPUT[textArea(placeholder(Treasure)):TREASURE]`

## Getragene Gegenstände

> [!recite]- Flöte
> **Menge:** 1x
> **Gewicht:** 0,5 kg.
> **Gegenstandsart:** Instrument
> ---
> **Beschreibung.** Wenn du ein bestimmtes Musikinstrument beherrschst, kannst du deinen [Kompetenzbonus] zu allen Fertigkeitswürfen addieren, die du zum Musizieren mit dem Instrument machst. Ein Barde kann ein Musikinstrument als Zauberfokus verwenden. Jede Art von Musikinstrument erfordert eine eigene Befähigung.

> [!recite]- Kleidung (gewöhnlich)
> **Menge:** 1x
> **Gewicht:** 1,5 kg.
> **Gegenstandsart:** Abenteuerausrüstung
> ---

> [!recite]- Laute
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

> [!recite]- Kerze
> **Menge:** 1x
> **Gewicht:** /
> **Gegenstandsart:** Abenteuerausrüstung
> ---
> **Beschreibung.** Eine Kerze spendet 1 Stunde lang helles Licht in einem Radius von 1,5 Meter und schwaches Licht für weitere 1,5 Meter.

> [!recite]- Schlafsack
> **Menge:** 1x
> **Gewicht:** 3,5 kg.
> **Gegenstandsart:** Abenteuerausrüstung
> ---

> [!recite]- Tagesration
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

> [!recite]- Verkleidungsausrüstung
> **Menge:** 1x
> **Gewicht:** 1,0 kg.
> **Gegenstandsart:** Werkzeug
> ---

> [!recite]- Wasserschlauch
> **Menge:** 1x
> **Gewicht:** 2,5 kg.
> **Gegenstandsart:** Abenteuerausrüstung
> ---
**Beschreibung.** Ein Wasserschlauch hat ein Fassungsvermögen von 4 Liter Flüssigkeit.

## Andere Behälter (Nimmervoller Beutel, etc)
- **Fassungsvermögen:** X kg.
# Spellcasting
[[#Spellcasting|🔗]]  

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
> | Flöte | Instrument |
> | Laute | Instrument |
> | Leise | Instrument |

> [!columns|no-t nmg] Zauberliste
> > [!recite|t-w] Zaubertricks
> > | Zauber | Zeit-aufwand | Reich-weite | Wirkungs-dauer | Kompon-enten |
> > | ----- | ------------- | ------- | --------- | ------------- |
> > | Einfache Illusion |  |  |  |  |
> > | Gehässiger Spott |  |  |  |  |
> > | Licht |  |  |  |  |
> > |  |  |  |  |  |
> > |  |  |  |  |  |
> > |  |  |  |  |  |
> > |  |  |  |  |  |
> > |  |  |  |  |  |
>
> > [!recite|t-w txt-s nmg] 1st Level
> > > [!recite|txt-s alt-line] LV1 Spell Slots
> > > ```consumable
> > > items:
> > >   - label: "Spell Slots LV1"
> > >     state_key: my_character_SPL1
> > >     reset_on: long-rest
> > >     uses: 4
> > > ```
> > 
> > | Prep. | Zauber | Zeit-aufwand | Reich-weite | Wirkungs-dauer | Kompon-enten |
> > | ----- | ----- |------------- | ------- | --------- | ------------- |
> > | `INPUT[toggle:SP1-1]` | Dissonantes Flüstern | 1 Aktion | 18m | Unmittelbar | V |
> > | `INPUT[toggle:SP1-2]` | Heilendes Wort | 1 Bonus | 18m | Unmittelbar | V |
> > | `INPUT[toggle:SP1-3]` | Lautloses Trugbild | 1 Aktion | 18m | Konzentration, bis zu 10 Min | V, G, M |
> > | `INPUT[toggle:SP1-4]` | Magie entdecken | 1 Aktion | Selbst | Konzentration, bis zu 10 Min | V, G |
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
> > [!recite|t-w txt-s nmg] 2nd Level
> > > [!recite|txt-s alt-line] LV2 Spell Slots
> > > ```consumable
> > > items:
> > >   - label: "Spell Slots LV2"
> > >     state_key: my_character_SPL2
> > >     reset_on: long-rest
> > >     uses: 3
> > > ```
> > 
> > | Prep. | Zauber | Zeit-aufwand | Reich-weite | Wirkungs-dauer | Kompon-enten |
> > | ----- | ----- |------------- | ------- | --------- | ------------- |
> > | `INPUT[toggle:SP2-1]` | Dissonantes Flüstern | 1 Aktion | 18m | Unmittelbar | V |
> > | `INPUT[toggle:SP2-2]` | Heilendes Wort | 1 Bonus | 18m | Unmittelbar | V |
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
> > [!recite|t-w txt-s nmg] 3rd Level
> > > [!recite|txt-s alt-line] LV3 Spell Slots
> > > ```consumable
> > > items:
> > >   - label: "Spell Slots LV3"
> > >     state_key: my_character_SPL3
> > >     reset_on: long-rest
> > >     uses: 3
> > > ```
> > 
> > | Prep. | Zauber | Zeit-aufwand | Reich-weite | Wirkungs-dauer | Kompon-enten |
> > | ----- | ----- |------------- | ------- | --------- | ------------- |
> > | `INPUT[toggle:SP3-1]` | Dissonantes Flüstern | 1 Aktion | 18m | Unmittelbar | V |
> > | `INPUT[toggle:SP3-2]` | Heilendes Wort | 1 Bonus | 18m | Unmittelbar | V |
> > | `INPUT[toggle:SP3-3]` | Leomunds winzige Hütte |  |  |  |  |
> > | `INPUT[toggle:SP3-4]` | Magie bannen |  |  |  |  |
> > | `INPUT[toggle:SP3-5]` | Mit Toten sprechen |  |  |  |  |
> > | `INPUT[toggle:SP3-6]` |  |  |  |  |  |
> > | `INPUT[toggle:SP3-7]` |  |  |  |  |  |
> > | `INPUT[toggle:SP3-8]` |  |  |  |  |  |
> > | `INPUT[toggle:SP3-9]` |  |  |  |  |  |
> > | `INPUT[toggle:SP3-10]` |  |  |  |  |  |
> > | `INPUT[toggle:SP3-11]` |  |  |  |  |  |
> > | `INPUT[toggle:SP3-12]` |  |  |  |  |  |
> > | `INPUT[toggle:SP3-13]` |  |  |  |  |  |
> 
> > [!recite|t-w txt-s nmg] 4th Level
> > > [!recite|txt-s alt-line] LV4 Spell Slots
> > > ```consumable
> > > items:
> > >   - label: "Spell Slots LV4"
> > >     state_key: my_character_SPL4
> > >     reset_on: long-rest
> > >     uses: 0
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
> > [!recite|t-w txt-s nmg] 5th Level
> > > [!recite|txt-s alt-line] LV5 Spell Slots
> > > ```consumable
> > > items:
> > >   - label: "Spell Slots LV5"
> > >     state_key: my_character_SPL5
> > >     reset_on: long-rest
> > >     uses: 0
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
> > [!recite|t-w txt-s nmg] 6th Level
> > > [!recite|txt-s alt-line] LV6 Spell Slots
> > > ```consumable
> > > items:
> > >   - label: "Spell Slots LV6"
> > >     state_key: my_character_SPL6
> > >     reset_on: long-rest
> > >     uses: 0
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
> > [!recite|t-w txt-s nmg] 7th Level
> > > [!recite|txt-s alt-line] LV7 Spell Slots
> > > ```consumable
> > > items:
> > >   - label: "Spell Slots LV7"
> > >     state_key: my_character_SPL7
> > >     reset_on: long-rest
> > >     uses: 0
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
> > [!recite|t-w txt-s nmg] 8th Level
> > > [!recite|txt-s alt-line] LV8 Spell Slots
> > > ```consumable
> > > items:
> > >   - label: "Spell Slots LV8"
> > >     state_key: my_character_SPL8
> > >     reset_on: long-rest
> > >     uses: 0
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
> > [!recite|t-w txt-s nmg] 9th Level
> > > [!recite|txt-s alt-line] LV9 Spell Slots
> > > ```consumable
> > > items:
> > >   - label: "Spell Slots LV9"
> > >     state_key: my_character_SPL9
> > >     reset_on: long-rest
> > >     uses: 0
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

# Features & Traits
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

#### Senses & Vulnerabilities
**Senses:** Dunkelsicht
**Resistances:** 
**Vulnerabilities:** 
**Immunities:** Magischer Schlaf

## Actions 

## Bonus Actions #

## Other Features

> [!recite|nmg]+ Feature Example
> # Feature
> *Source: Lvl 10 Class Feature / PHB / Race / ETC*
> \--
> ```consumable
> items:
>   - label: "Charges"
>     state_key: my_character_feature
>     uses: 3
>     reset_on: long-rest
> ```
> Description of feature.
> 

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
