--
Type: Player
Art: "![[Fayn-Steampunk.jpg]]"
Stufe: 6
Erfahrung: 0
RK: 15
Übung: 3
TP: 57
Trefferwürfel: W8
Bewegungsrate: 9 Meter
STR: 17
GES: 18
KON: 18
INT: 14
WEI: 15
CHA: 18
Rasse: Halb-Elf
Gesinnung: Chaotisch Gut
Geschlecht: Männlich
Alter: "34"
Klasse: Barde
Unterklasse: Schule der Eloquenz
Übungsbonus:
  - Akrobatik
  - Auftreten
  - Fingerfertigkeit
  - Nachforschungen
  - Täuschen
  - Überzeugung
  - Wahrnehmung
  - Dudelsack
  - Flöte
  - Laute
  - Pistole
Resistances:
  - NONE
Sprachen:
  - Gemeinsprache
  - Elfisch
  - Zwergisch
DmgTkn: 0
TempHP: 0
Kupfer: 0
Silber: 0
Elektrum: 0
Gold: 15
Platinum: 0
CoinsGold: 15
this:
  CoinsGold: 48
  CoinsSilver: 3
  CoinsCopper: 2
  CoinsPlatinum: 0
---
>[!column|flex 2]
>> [!infobox]
>> # `=this.file.name`
>> ![[Fayn-Steampunk.jpg]]
>> ###### Bio
>>   |
>> ---|---|
>> **Rasse** | `=this.Rasse` |
>> **Geschlecht** | `=this.Geschlecht` |
>> **Alter** | `=this.Alter` |
>> **Gesinnung** | `=this.Gesinnung` |
>> **Sprachen** | `=this.Sprachen`
>> ###### Info
>>   |
>> ---|---|
>> **Klassen** | `=this.Klasse` |
>> **Unterklassen** | `=this.Unterklasse`
>> **Gruppe(n)** | `=this.AssociatedGroup` |
>> 
>>  ### Währungen
>>  |
>>  --- |---|
>>**Kupfer** | `INPUT[number:this.CoinsCopper]` | 
>>**Silber** |`INPUT[number:this.CoinsSilver]` | 
>>**Gold** |`INPUT[number:this.CoinsGold]` | 
>>**Platinum** |`INPUT[number:this.CoinsPlatinum]` |
>
>> [!infobox]
>> ###### Stats
>>  |
>> ---|---|
>> **Stufe** |`=this.Stufe` |
>> **Bewegungsrate** |`=this.Bewegungsrate` |
>> **Übungsbonus** | `=this.Übung` |
>> **Initiative** | +`=floor(((this.GES - 10) / 2) + this.Übung / 2)` |
>> **Max. Trefferpunkte** | `=this.TP` |
>> **Schaden** | `INPUT[number:DmgTkn]`|
>> **Temporäre TP** | `INPUT[number:TempHP]`|
>> **Rüstungsklasse** | `=this.RK`
>> **Trefferwürfel** | `=this.Stufe + this.Trefferwürfel`  |
>> **Zauberrettungswurf** | `=(this.CHA - 10) / 2 + 8 + this.Übung`
>> **Passive Wahrnehmung** | `=floor((this.WEI - 10) / 2) + 10` |
>>
>> ### Todesrettungen
| Erfolge | <input type="checkbox" unchecked>  | <input type="checkbox" unchecked> | <input type="checkbox" unchecked> | 
| ------- | --- | --------------------------------- | --------------------------------- |
>>
| Misserfolge | <input type="checkbox" unchecked>  | <input type="checkbox" unchecked> | <input type="checkbox" unchecked> | 
| ----- | --- | --------------------------------- | --------------------------------- |
>
>> [!infobox]
>> ### Attributswerte
| Attribut                                          | Wert        | Mod                            | Übung                             | RW                                          |
| ------------------------------------------------- | ----------- | ------------------------------ | --------------------------------- | ------------------------------------------- |
| <font color="#ff0000">**Stärke**</font>           | `=this.STR` | +`=floor((this.STR - 10) / 2)` | <input type="checkbox" unchecked> | +`=floor((this.STR - 10) / 2)`              |
| <font color="#ffff00">**Geschicklichkeit**</font> | `=this.GES` | +`=floor((this.GES - 10) / 2)` | <input type="checkbox" checked>   | +`=floor((this.GES - 10) / 2) + this.Übung` |
| <font color="#de7802">**Konstitution**</font>     | `=this.KON` | +`=floor((this.KON - 10) / 2)` | <input type="checkbox" unchecked> | +`=floor((this.KON - 10) / 2)`              |
| <font color="#245bdb">**Intelligenz**</font>      | `=this.INT` | +`=floor((this.INT - 10) / 2)` | <input type="checkbox" unchecked> | +`=floor((this.INT - 10) / 2)`              |
| <font color="#00b050">**Weisheit**</font>         | `=this.WEI` | +`=floor((this.WEI - 10) / 2)` | <input type="checkbox" unchecked> | +`=floor((this.WEI - 10) / 2)`              |
| <font color="#7030a0">**Charisma**</font>         | `=this.CHA` | +`=floor((this.CHA - 10) / 2)` | <input type="checkbox" checked>   | +`=floor((this.CHA - 10) / 2) + this.Übung` |
>>
>> ### Proben
| Fähigkeit                                             | Übung  / Expertise                | Mod                                                 | 
| ----------------------------------------------------- | --------------------------------- | --------------------------------------------------- |
| Akrobatik (<font color="#ffff00">GES</font>)          | <input type="checkbox" unchecked><input type="checkbox" unchecked> | +`=floor((this.GES - 10) / 2) + this.Übung`         |
| Arkane Kunde (<font color="#245bdb">INT</font>)       | <input type="checkbox" unchecked><input type="checkbox" unchecked> | +`=floor((this.INT - 10) / 2) + ((this.Übung) / 2)` |
| Athletik (<font color="#ff0000">STR</font>)           | <input type="checkbox" unchecked><input type="checkbox" unchecked> | +`=floor((this.STR - 10) / 2) + ((this.Übung) / 2)` |
| Auftreten (<font color="#7030a0">CHA</font>)          | <input type="checkbox" unchecked><input type="checkbox" unchecked> | +`=floor((this.CHA - 10) / 2) + this.Übung`         |
| Einschüchtern (<font color="#7030a0">CHA</font>)      | <input type="checkbox" unchecked><input type="checkbox" unchecked> | +`=floor((this.CHA - 10) / 2) + ((this.Übung) / 2)` |
| Fingerfertigkeit (<font color="#ffff00">GES</font>)   | <input type="checkbox" checked><input type="checkbox" unchecked>   | +`=floor((this.GES - 10) / 2) + this.Übung`         |
| Geschichte (<font color="#245bdb">INT</font>)         | <input type="checkbox" unchecked><input type="checkbox" unchecked> | +`=floor((this.INT - 10) / 2) + ((this.Übung) / 2)` |
| Heilkunde (<font color="#00b050">WEI</font>)          | <input type="checkbox" unchecked><input type="checkbox" unchecked> | +`=floor((this.WEI - 10) / 2) + ((this.Übung) / 2)` |
| Heimlichkeit (<font color="#ffff00">GES</font>)       | <input type="checkbox" unchecked><input type="checkbox" unchecked> | +`=floor((this.GES - 10) / 2) + ((this.Übung) / 2)` |
| Mit Tieren umgehen (<font color="#00b050">WEI</font>) | <input type="checkbox" unchecked><input type="checkbox" unchecked> | +`=floor((this.WEI - 10) / 2) + ((this.Übung) / 2)` |
| Motiv erkennen (<font color="#00b050">WEI</font>)     | <input type="checkbox" unchecked><input type="checkbox" unchecked> | +`=floor((this.WEI - 10) / 2) + ((this.Übung) / 2)` |
| Nachforschungen (<font color="#245bdb">INT</font>)    | <input type="checkbox" checked><input type="checkbox" checked>   | +`=floor((this.INT - 10) / 2) + ((this.Übung) * 2)` |
| Naturkunde (<font color="#245bdb">INT</font>)         | <input type="checkbox" unchecked><input type="checkbox" unchecked> | +`=floor((this.INT - 10) / 2) + ((this.Übung) / 2)` |
| Religion (<font color="#245bdb">INT</font>)           | <input type="checkbox" unchecked><input type="checkbox" unchecked> | +`=floor((this.INT - 10) / 2) + ((this.Übung) / 2)` |
| Täuschen (<font color="#7030a0">CHA</font>)           | <input type="checkbox" checked><input type="checkbox" unchecked>   | +`=floor((this.CHA - 10) / 2) + this.Übung`         |
| Überlebenskunst (<font color="#00b050">WEI</font>)    | <input type="checkbox" unchecked><input type="checkbox" unchecked> | +`=floor((this.WEI - 10) / 2) + ((this.Übung) / 2)` |
| Überzeugen (<font color="#7030a0">CHA</font>)         | <input type="checkbox" checked><input type="checkbox" unchecked>   | +`=floor((this.CHA - 10) / 2) + this.Übung`         |
| Wahrnehmung (<font color="#00b050">WEI</font>)        | <input type="checkbox" checked><input type="checkbox" checked>   | +`=floor((this.WEI - 10) / 2) + ((this.Übung) * 2)`         |

---

### Inventar

```base
properties:
  property.Bezeichnung:
    displayName: Name
  file.name:
    displayName: File
views:
  - type: table
    name: Ausrüstung
    filters:
      or:
        - property.Bezeichnung == "Dolch"
        - property.Bezeichnung == "Pistole"
        - property.Bezeichnung == "Rapier"
        - property.Bezeichnung == "Lederrüstung"
        - property.Bezeichnung == "Flöte"
        - property.Bezeichnung == "Gewöhnliche Kleidung"
    order:
      - Aktiv
      - Bezeichnung
      - Menge
      - Schaden
      - Schadensart
      - Kosten
      - Gewicht
      - Eigenschaften
      - file.name
    sort:
      - column: property.Bezeichnung
        direction: ASC
    columnSize:
      property.Komponenten: 386

```

```base
display:
  property.Bezeichnung: Name
  file.name: File
views:
  - type: table
    name: Inventar
    filters:
      or:
        - property.Bezeichnung == "Rucksack"
        - property.Bezeichnung == "Kerze"
        - property.Bezeichnung == "Schlafsack"
        - property.Bezeichnung == "Tagesration"
        - property.Bezeichnung == "Verkleidungsausrüstung"
        - property.Bezeichnung == "Wasserschlauch"
        - property.Bezeichnung == "Magische Tasche"
    order:
      - Aktiv
      - Bezeichnung
      - Menge
      - Schaden
      - Schadensart
      - Kosten
      - Gewicht
      - Eigenschaften
      - file.name
    sort:
      - column: property.Bezeichnung
        direction: ASC
      - column: file.name
        direction: ASC
    columnSize:
      property.Eigenschaften: 263

```

---

### Persönlichkeit

- ich kenne eine Geschichte, die zu fast jeder Situation passt.
- ich liebe eine gute Beleidigung, auch wenn sie gegen mich gerichtet ist.
- ich lasse mich auf nichts weniger als Perfektion ein.

### Ideale

- Menschen. Ich liebe es, wenn die Menschen sich freuen wenn ich spiele. Das ist alles was zählt (neutral)

### Bindungen

- jemand hat mein wertvolles Instrument gestohlen und eines Tages werde ich es zurück haben.

### Makel 

- ich habe mal einen Witz über einen Adeligen gemacht, der nun meinen Kopf will. Es war ein Fehler den ich wahrscheinlich wiederholen werde.

---

### Klassenmerkmale

##### [[05 - Wikipedia/Charakteroptionen/02. Klassen/Barde#Bardische Inspiration (W6) (Stufe 1)|Bardische Inspiration]]
Als Bonusaktion erhält eine Kreatur (außer dir) innerhalb von 18 Metern, die dich hören kann, einen Inspirationswürfel. Die Kreatur kann ihn 10 Minuten lang zu einer Fähigkeitsprobe, einem Angriffswurf oder einem Rettungswurf addieren. Dies kann geschehen, nachdem es den Wurf gesehen hat, aber bevor es das Ergebnis kennt.

| Stufe | Würfel |
| ----- | ------ |
| 1     | 1W6    |
| 5     | 1W8    |
| 10    | 1W10   |
| 15    | 1W12   |

Bardische Inspiration: 1 Bonusaktion
Verwendet:
<input type="checkbox" unchecked><input type="checkbox" unchecked><input type="checkbox" unchecked><input type="checkbox" unchecked>
Setzt sich nach einer Langen Rast zurück.

##### Übungen
- [Dudelsack](../../../05%20-%20Wikipedia/Gegenstände/Dudelsack.md)
- [Flöte](../../../05%20-%20Wikipedia/Gegenstände/Flöte.md)
- [Laute](../../../05%20-%20Wikipedia/Gegenstände/Laute.md)
- [Pistole](../../../05%20-%20Wikipedia/Gegenstände/Pistole.md) - Belohnung nach Kampagne
- [[../../../03 - Quellen/Quellbücher/01. Grundregelwerk 2014/07-Attributswerte-verwenden#Nachforschungen|Nachforschungen]]
- [[../../../03 - Quellen/Quellbücher/01. Grundregelwerk 2014/07-Attributswerte-verwenden#Täuschen|Täuschen]]
- [[../../../03 - Quellen/Quellbücher/01. Grundregelwerk 2014/07-Attributswerte-verwenden#Wahrnehmung|Wahrnehmung]]

##### [[05 - Wikipedia/Charakteroptionen/02. Klassen/Barde#Zauberwirken (Stufe 1)|Zauberwirken]]
Du kannst bekannte Bardenzauber mit CHA als Zaubermodifikator wirken und bekannte Bardenzauber als Rituale, wenn sie als Ritual gekennzeichnet sind. Du kannst ein Musikinstrument als Zauberfokus verwenden.

##### [[05 - Wikipedia/Charakteroptionen/02. Klassen/Barde#Alleskönner (Stufe 2)|Alleskönner]]
Ab der 2. Stufe kannst du deinen halben Übungsbonus (abgerundet) auf jeden Attributswurf addieren, der nicht bereits durch deinen Übungsbonus verbessert wird.

##### [[05 - Wikipedia/Charakteroptionen/02. Klassen/Barde#Lied der Erholung (W6) (Stufe 2)|Lied der Erholung]]
Ab der 2. Stufe kannst du während einer kurzen Rast mit sanfter Musik oder Erzählungen den Heilungsprozess deiner verwundeten Verbündeten beschleunigen. Wenn du oder eine verbündete Kreatur, die dich hören kann, durch das Verwenden von Trefferwürfeln zum Ende einer kurzen Rast Trefferpunkte zurückerhält, erhält jede Kreatur `1W6` zusätzliche Trefferpunkte zurück.

##### [[05 - Wikipedia/Charakteroptionen/02. Klassen/Barde#Bardenschule (Stufe 3)|Bardenschule: Schule der Eloquenz]]
Auf der 3. Stufe wirst du in die fortgeschrittenen Techniken einer Bardenschule deiner Wahl wie der Schule des Wissens eingeweiht. Deine Wahl gewährt dir ab der 3. sowie ab der 6. und 14. Stufe weitere Merkmale.

##### [[05 - Wikipedia/Charakteroptionen/02. Klassen/Barde#Expertise (Stufe 3)|Expertise]]
Auf der 3. Stufe wählst du zwei deiner Fertigkeiten aus, in denen du geübt bist. Dein Übungsbonus wird bei allen Attributswürfen verdoppelt, bei denen diese Fertigkeiten zur Anwendung kommen

##### [[05 - Wikipedia/Charakteroptionen/02. Klassen/Barde#Quelle der Inspiration (Stufe 5)|Quelle der Inspiration]]
Ab der 5. Stufe erhältst du all deine Anwendungen der Bardischen Inspiration zurück, sobald du eine kurze oder lange Rast beendet hast.

##### [[05 - Wikipedia/Charakteroptionen/02. Klassen/Barde#Bannlied (Stufe 6)|Bannlied]]
Auf der 6. Stufe erlangst du die Fähigkeit, mit Zaubern gewobene Musik und Worte der Macht zu nutzen, um geistesbeeinflussende Effekte abzuwenden. Als Aktion kannst du eine Darbietung geben, die bis zum Ende deines nächsten Zuges andauert. Während dieser Zeit sind deine Verbündeten und du im Abstand von bis zu neun Metern von dir bei Rettungswürfen gegen [[../../../03 - Quellen/Quellbücher/01. Grundregelwerk 2014/Anhang PH-A#Bezaubert|Bezaubert]] oder [[../../../03 - Quellen/Quellbücher/01. Grundregelwerk 2014/Anhang PH-A#Verängstigt|Verängstigt]] im Vorteil. Eine Kreatur muss dich hören können, damit sie diesen Vorzug nutzen kann. Dies endet vorzeitig, falls du zum Schweigen gebracht oder kampfunfähig wirst. Du kannst sie auch freiwillig beenden, wozu keine Aktion notwendig ist.

#### Schule der Eloquenz

##### [[05 - Wikipedia/Charakteroptionen/Klassen/Barde-Schule-Eloquenz#Silberne Zunge|Silberne Zunge]]
Du bist ein Meister darin, das Richtige zur richtigen Zeit zu sagen. Wenn du eine Probe auf Charisma(Überzeugen) oder Charisma(Täuschen) ablegst, kannst du ein Ergebnis eines `W20` von 9 oder niedriger wie eine 10 behandeln.

##### [[05 - Wikipedia/Charakteroptionen/Klassen/Barde-Schule-Eloquenz#Verunsichernde Worte|Verunsichernde Worte]]
Du kannst mit Magie durchzogene Worte spinnen, die eine Kreatur verunsichern und sie an sich selbst zweifeln lassen. Als Bonusaktion kannst du deine Bardischen Inspiration verwenden und eine Kreatur im Umkreis von 18 Metern wählen, die du siehst. Wirf den Würfel für Bardische Inspiration. Die Kreatur muss die gewürfelte Zahl von ihrem nächsten Rettungswurf abziehen, bevor du deinen nächsten Zug beginnst.

##### [[05 - Wikipedia/Charakteroptionen/Klassen/Barde-Schule-Eloquenz#Unermüdliche Inspiration|Unermüdliche Inspiration]]
Deine inspirierenden Worte sind so überzeugend, dass sich andere zum Erfolg getrieben fühlen. Wenn eine Kreatur einen deiner Würfel für Bardische Inspiration zu ihrer Fähigkeitsprüfung, ihrem Angriffswurf oder ihrem Rettungswurf hinzufügt und der Wurf misslingt, darf die Kreatur den Würfel für Bardische Inspiration behalten.

---

# Rassenmerkmale

##### [Dunkelsicht](../../../05%20-%20Wikipedia/Charakteroptionen/Rassen/Halbelf.md#Dunkelsicht)
Du kannst im Dunkeln (Grautöne) bis zu 18 Meter weit sehen.

##### [Feenblut](../../../05%20-%20Wikipedia/Charakteroptionen/Rassen/Halbelf.md#Feenblut)
Du bist bei Rettungswürfen gegen [[../../../03 - Quellen/Quellbücher/01. Grundregelwerk 2014/Anhang PH-A#Bezaubert|Bezaubert]] im Vorteil und gegen Schlafzauber immun.

##### [Vielseitigkeit](../../../05%20-%20Wikipedia/Charakteroptionen/Rassen/Halbelf.md#Vielseitigkeit)
Du bist in zwei Fertigkeiten deiner Wahl geübt.
- [[../../../03 - Quellen/Quellbücher/01. Grundregelwerk 2014/07-Attributswerte-verwenden#Fingerfertigkeit|Fingerfertigkeit]]
- [[../../../03 - Quellen/Quellbücher/01. Grundregelwerk 2014/07-Attributswerte-verwenden#Überzeugen|Überzeugen]]

---

### Talente

#### Feenberührt
Der Kontakt mit der Magie der Feenwelt hat dich verändert und gewährt dir die folgenden Vorteile:

- Erhöht deinen Intelligenz-, Weisheits- oder Charisma-Wert um 1 bis maximal 20.
- Du lernst den Zauber [Nebelschritt](../../../05%20-%20Wikipedia/Zauber/Nebelschritt.md) und einen Zauber des 1. Zaubergrades deiner Wahl. Der Zauber des 1. Grades muss aus der Schule der Erkenntnis- oder der Verzauberungsschule sein. Du kannst jeden dieser Zauber wirken, ohne einen Zauberplatz zu verbrauchen. Sobald du einen dieser Zauber auf diese Weise gewirkt hast, kannst du ihn erst wieder nach einer langen Rast auf diese Weise wirken. Du kannst diese Zauber auch mit Zauberplätzen der entsprechenden Stufe wirken. Der Zaubermodifikator des Zaubers ist der Wert, der durch dieses Talent erhöht wird.

- Charisma +1


Your exposure to the Feywild’s magic has changed you, granting you the following benefits:

Increase your Intelligence, Wisdom, or Charisma score by 1, to a maximum of 20.
You learn the misty step spell and one 1st-level spell of your choice. The 1st-level spell must be from the divination or enchantment school of magic. You can cast each of these spells without expending a spell slot. Once you cast either of these spells in this way, you can’t cast that spell in this way again until you finish a long rest. You can also cast these spells using spell slots you have of the appropriate level. The spells’ spellcasting ability is the ability increased by this feat.

---

### Zauber

| Modifikator    | Zauberangriff                               | Rettungswurf                            |
| -------------- | ------------------------------------------- | --------------------------------------- |
| +`=this.Übung` | +`=floor((this.CHA - 10) / 2) + this.Übung` | `=(this.CHA - 10) / 2 + 8 + this.Übung` |

```base
display:
  property.Bezeichnung: Name
  file.name: File
views:
  - type: table
    name: Zaubertricks
    filters:
      or:
        - property.Bezeichnung == "Licht"
        - property.Bezeichnung == "Gehässiger Spott"
        - Bezeichnung == "Einfache Illusion"
    order:
      - Bezeichnung
      - Zeitaufwand
      - Reichweite
      - Komponenten
      - Wirkungsdauer
      - Angriff
      - file.name
    sort:
      - column: file.name
        direction: ASC
      - column: property.Bezeichnung
        direction: ASC
    columnSize:
      property.Komponenten: 386
  - type: table
    name: Zaubergrad 1
    filters:
      or:
        - property.Bezeichnung == "Dissonantes Flüstern"
        - property.Bezeichnung == "Heilendes Wort"
        - property.Bezeichnung == "Lautloses Trugbild"
        - property.Bezeichnung == "Magie entdecken"
    order:
      - Bezeichnung
      - Zeitaufwand
      - Reichweite
      - Komponenten
      - Wirkungsdauer
      - Angriff
      - file.name
    sort:
      - column: file.name
        direction: ASC
      - column: property.Bezeichnung
        direction: ASC
    columnSize:
      property.Komponenten: 386
  - type: table
    name: Zaubergrad 2
    filters:
      or:
        - property.Bezeichnung == "Klopfen"
        - property.Bezeichnung == "Nebelschritt"
        - property.Bezeichnung == "Spiegelbilder"
        - property.Bezeichnung == "Stille"
    order:
      - Bezeichnung
      - Zeitaufwand
      - Reichweite
      - Komponenten
      - Wirkungsdauer
      - Angriff
      - file.name
    sort:
      - column: file.name
        direction: ASC
      - column: property.Bezeichnung
        direction: ASC
    columnSize:
      property.Komponenten: 386
  - type: table
    name: Zaubergrad 3
    filters:
      or:
        - property.Bezeichnung == "Leomunds Winzige Hütte"
        - property.Bezeichnung == "Magie bannen"
        - property.Bezeichnung == "Mit Toten sprechen"
    order:
      - Bezeichnung
      - Zeitaufwand
      - Reichweite
      - Komponenten
      - Wirkungsdauer
      - Angriff
      - file.name
    sort:
      - column: file.name
        direction: ASC
      - column: property.Bezeichnung
        direction: ASC
    columnSize:
      property.Komponenten: 386
      
```

#### 1. Zaubergrad | Zauberplätze: <input type="checkbox" unchecked><input type="checkbox" unchecked><input type="checkbox" unchecked><input type="checkbox" unchecked>

#### 2. Zaubergrad | Zauberplätze:  <input type="checkbox" unchecked><input type="checkbox" unchecked><input type="checkbox" unchecked>

#### 3. Zaubergrad | Zauberplätze: <input type="checkbox" unchecked><input type="checkbox" unchecked><input type="checkbox" unchecked>

#### 4. Zaubergrad | Zauberplätze: Ab Stufe 7:  <input type="checkbox" unchecked> | Ab Stufe 8: <input type="checkbox" unchecked> | Ab Stufe 9: <input type="checkbox" unchecked>

#### 5. Zaubergrad | Zauberplätze: Ab Stufe 9:  <input type="checkbox" unchecked> | Ab Stufe 10: <input type="checkbox" unchecked> | Ab Stufe 18: <input type="checkbox" unchecked>

#### 6. Zaubergrad | Zauberplätze: Ab Stufe 11:  <input type="checkbox" unchecked> | Ab Stufe 19: <input type="checkbox" unchecked>

#### 7. Zaubergrad | Zauberplätze: Ab Stufe 13:  <input type="checkbox" unchecked> | Ab Stufe 20: <input type="checkbox" unchecked>

#### 8. Zaubergrad | Zauberplätze: Ab Stufe 15: <input type="checkbox" unchecked>

#### 9. Zaubergrad | Zauberplätze: Ab Stufe 17: <input type="checkbox" unchecked>

---

#### 4. Zaubergrad | Zauberplätze: Ab Stufe 7:  <input type="checkbox" unchecked> | Ab Stufe 8: <input type="checkbox" unchecked> | Ab Stufe 9: <input type="checkbox" unchecked>
| Nr. | Name | Zeit | Reichweite | Rettung | Effekt |
| --- | ---- | ---- | ---------- | ------- | ------ |
| 1.  |      |      |            |         |        |
| 2.  |      |      |            |         |        |
| 3.  |      |      |            |         |        |

---

#### 5. Zaubergrad | Zauberplätze: Ab Stufe 9:  <input type="checkbox" unchecked> | Ab Stufe 10: <input type="checkbox" unchecked> | Ab Stufe 18: <input type="checkbox" unchecked>
| Nr. | Name | Zeit | Reichweite | Rettung | Effekt |
| --- | ---- | ---- | ---------- | ------- | ------ |
| 1.  |      |      |            |         |        |
| 2.  |      |      |            |         |        |
| 3.  |      |      |            |         |        |

---

#### 6. Zaubergrad | Zauberplätze: Ab Stufe 11:  <input type="checkbox" unchecked> | Ab Stufe 19: <input type="checkbox" unchecked>
| Nr. | Name | Zeit | Reichweite | Rettung | Effekt |
| --- | ---- | ---- | ---------- | ------- | ------ |
| 1.  |      |      |            |         |        |
| 2.  |      |      |            |         |        |
| 3.  |      |      |            |         |        |

---

#### 7. Zaubergrad | Zauberplätze: Ab Stufe 13:  <input type="checkbox" unchecked> | Ab Stufe 20: <input type="checkbox" unchecked>
| Nr. | Name | Zeit | Reichweite | Rettung | Effekt |
| --- | ---- | ---- | ---------- | ------- | ------ |
| 1.  |      |      |            |         |        |
| 2.  |      |      |            |         |        |
| 3.  |      |      |            |         |        |

---

#### 8. Zaubergrad | Zauberplätze: Ab Stufe 15: <input type="checkbox" unchecked>
| Nr. | Name | Zeit | Reichweite | Rettung | Effekt |
| --- | ---- | ---- | ---------- | ------- | ------ |
| 1.  |      |      |            |         |        |
| 2.  |      |      |            |         |        |
| 3.  |      |      |            |         |        |


---

#### 9. Zaubergrad | Zauberplätze: Ab Stufe 17: <input type="checkbox" unchecked> 
| Nr. | Name | Zeit | Reichweite | Rettung | Effekt |
| --- | ---- | ---- | ---------- | ------- | ------ |
| 1.  |      |      |            |         |        |
| 2.  |      |      |            |         |        |
| 3.  |      |      |            |         |        |
