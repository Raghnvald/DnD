--
Type: Player
Art: "![[Fayn-Steampunk.jpg]]"
Stufe: 5
Erfahrung: 0
RK: 15
Übung: 2
Max_TP: 48
TP: 48
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
Resistances:
  - NONE
Sprachen:
  - Gemeinsprache
  - Elfisch
  - Zwergisch
TempHP: 0
Heal: 0
DmgTkn: 0
this:
  CoinsPlatinum: 0
  CoinsGold: 21
  CoinsElektrum: 0
  CoinsSilver: 12
  CoinsCopper: 2
  TempHP: 0
  DmgTkn: 7
  heal: 0
---

```meta-bind-button
label: "Schaden"
style: destructive
hidden: true
id: "deal-damage"
actions:
  - type: updateMetadata
    bindTarget: TP
    evaluate: true
    value: "x - getMetadata('DmgTkn')"
```

```meta-bind-button
label: "Heilung"
style: destructive
hidden: true
id: "heal-damage"
actions:
  - type: updateMetadata
    bindTarget: TP
    evaluate: true
    value: "x + getMetadata('heal')"
```

```meta-bind-button
label: "Reset"
style: primary
hidden: true
id: "reset-health"
actions:
  - type: updateMetadata
    bindTarget: TP
    evaluate: true
    value: "getMetadata('Max_TP')"
```

https://www.dndbeyond.com/characters/127316527

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
>>**Elektrum** |`INPUT[number:this.CoinsElektrum]` | 
>>**Gold** |`INPUT[number:this.CoinsGold]` | 
>>**Platinum** |`INPUT[number:this.CoinsPlatinum]` |
>
>> [!infobox]
>> ###### Stats
>>  |
>> ---|---|
>> **Stufe** |`=this.Stufe` |
>> **Erfahrung** | `INPUT[number:Erfahrung]` |
>> **Bewegungsrate** |`=this.Bewegungsrate` |
>> **Übungsbonus** | `=this.Übung` |
>> **Initiative** | +`=floor((this.GES - 10) / 2)` |
>> **Max. Trefferpunkte** | `=this.Max_TP` |
>> **Trefferpunkte** | `VIEW[{TP}][text]` |
>> **Temporäre TP** | `INPUT[number:this.TempHP]`|
>> **Schaden** | `INPUT[number:DmgTkn]` `BUTTON[deal-damage]`|
>> **Heilung** |`INPUT[number:heal]` `BUTTON[heal-damage]`|
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
>>
>> ### Attributswerte
| Attribut                                          | Wert        | Mod                            | Übung                             | RW                                          |
| ------------------------------------------------- | ----------- | ------------------------------ | --------------------------------- | ------------------------------------------- |
| <font color="#ff0000">**Stärke**</font>           | `=this.STR` | +`=floor((this.STR - 10) / 2)` | <input type="checkbox" unchecked> | +`=floor((this.STR - 10) / 2)`              |
| <font color="#ffff00">**Geschicklichkeit**</font> | `=this.GES` | +`=floor((this.GES - 10) / 2)` | <input type="checkbox" checked>   | +`=floor((this.GES - 10) / 2) + this.Übung` |
| <font color="#de7802">**Konstitution**</font>     | `=this.KON` | +`=floor((this.KON - 10) / 2)` | <input type="checkbox" unchecked> | +`=floor((this.KON - 10) / 2)`              |
| <font color="#245bdb">**Intelligenz**</font>      | `=this.INT` | +`=floor((this.INT - 10) / 2)` | <input type="checkbox" unchecked> | +`=floor((this.INT - 10) / 2)`              |
| <font color="#00b050">**Weisheit**</font>         | `=this.WEI` | +`=floor((this.WEI - 10) / 2)` | <input type="checkbox" unchecked> | +`=floor((this.WEI - 10) / 2)`              |
| <font color="#7030a0">**Charisma**</font>         | `=this.CHA` | +`=floor((this.CHA - 10) / 2)` | <input type="checkbox" checked>   | +`=floor((this.CHA - 10) / 2) + this.Übung` |
>
>> [!infobox]
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

| Aktiv                             | Name                                                            | Gewicht                              | Menge | Kosten (GM) | Notizen                                                         |
| --------------------------------- | --------------------------------------------------------------- | ------------------------------------ | ----- | ----------- | --------------------------------------------------------------- |
|                                   | **Ausrüstung**                                                  | 10 kg / 20 lbs                       |       |             |                                                                 |
| <input type="checkbox" unchecked> | [Dolch](../../../05%20-%20Wikipedia/Gegenstände/Dolch.md)                                   | 0,5 kg / 1,0 lbs                     | 1     | 2           |                                                                 |
| <input type="checkbox" unchecked> | [Flöte](../../../05%20-%20Wikipedia/Gegenstände/Flöte.md)                                   | 0,5 kg / 1,0 lbs                     | 1     | 2           |                                                                 |
| <input type="checkbox" checked>   | [Einfache Kleidung](../../../05%20-%20Wikipedia/Gegenstände/Kleidung-gewöhnlich.md)         | 1,5 kg / 3,0 lbs.                    | 1     | 0,5         |                                                                 |
| <input type="checkbox" checked>   | [Laute](../../../05%20-%20Wikipedia/Gegenstände/Laute.md)                                   | 1,0 kg / 2,0 lbs                     | 1     | 35          |                                                                 |
| <input type="checkbox" checked>   | [Lederrüstung](../../../05%20-%20Wikipedia/Gegenstände/Lederrüstung.md)                     | 5,0 kg / 10 lbs                      | 1     | 10          |                                                                 |
| <input type="checkbox" checked>   | [Rapier](../../../05%20-%20Wikipedia/Gegenstände/Rapier.md)                                 | 1,0 kg / 2,0 lbs                     | 1     | 25          | `1W8` + `=floor((this.STR - 10) / 2) + this.Übung` Stichschaden |
|                                   |                                                                 |                                      |       |             |                                                                 |
| <input type="checkbox" checked>   | **Rucksack**                                                    | 2,5 kg / 5,0 lbs + 8,5 kg / 17,0 lbs | 1     | 2 + 26,71   |                                                                 |
| <input type="checkbox" unchecked> | [Kerze](../../../05%20-%20Wikipedia/Gegenstände/Kerze.md)                                   | -                                    | 1     | 0,01        |                                                                 |
| <input type="checkbox" unchecked> | [Schlafsack](../../../05%20-%20Wikipedia/Gegenstände/Schlafsack.md)                         | 3,5 kg / 7,0 lbs                     | 1     | 1           |                                                                 |
| <input type="checkbox" unchecked> | [Tagesration](../../../05%20-%20Wikipedia/Gegenstände/Tagesration.md)                       | 1,0 kg / 2,0 lbs                     | 3     | 0,5         |                                                                 |
| <input type="checkbox" unchecked> | [Verkleidungsausrüstung](../../../05%20-%20Wikipedia/Gegenstände/Verkleidungsausrüstung.md) | 1,5 kg / 3,0 lbs                     | 1     | 25          |                                                                 |
| <input type="checkbox" unchecked> | [Wasserschlauch](../../../05%20-%20Wikipedia/Gegenstände/Wasserschlauch.md)                 | 2,5 kg / 5,0 lbs                     | 1     | 0,2         |                                                                 |
| <input type="checkbox" unchecked> | Tasche mit Deko                                                 |                                      |       |             |                                                                 |

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

### Rassenmerkmale

##### [Dunkelsicht](../../../05%20-%20Wikipedia/Charakteroptionen/Rassen/Halbelf.md#Dunkelsicht)
Du kannst im Dunkeln (Grautöne) bis zu 18 Meter weit sehen.

##### [Feenblut](../../../05%20-%20Wikipedia/Charakteroptionen/Rassen/Halbelf.md#Feenblut)
Du bist bei Rettungswürfen gegen [[../../../03 - Quellen/Quellbücher/01. Grundregelwerk 2014/Anhang PH-A#Bezaubert|Bezaubert]] im Vorteil und gegen Schlafzauber immun.

##### [Vielseitigkeit](../../../05%20-%20Wikipedia/Charakteroptionen/Rassen/Halbelf.md#Vielseitigkeit)
Du bist in zwei Fertigkeiten deiner Wahl geübt.
- [[../../../03 - Quellen/Quellbücher/01. Grundregelwerk 2014/07-Attributswerte-verwenden#Fingerfertigkeit|Fingerfertigkeit]]
- [[../../../03 - Quellen/Quellbücher/01. Grundregelwerk 2014/07-Attributswerte-verwenden#Überzeugen|Überzeugen]]

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

#### Schule der Eloquenz

##### [[05 - Wikipedia/Charakteroptionen/Klassen/Barde-Schule-Eloquenz#Silberne Zunge|Silberne Zunge]]
Du bist ein Meister darin, das Richtige zur richtigen Zeit zu sagen. Wenn du eine Probe auf Charisma(Überzeugen) oder Charisma(Täuschen) ablegst, kannst du ein Ergebnis eines `W20` von 9 oder niedriger wie eine 10 behandeln.

##### [[05 - Wikipedia/Charakteroptionen/Klassen/Barde-Schule-Eloquenz#Verunsichernde Worte|Verunsichernde Worte]]
Du kannst mit Magie durchzogene Worte spinnen, die eine Kreatur verunsichern und sie an sich selbst zweifeln lassen. Als Bonusaktion kannst du deine Bardischen Inspiration verwenden und eine Kreatur im Umkreis von 18 Metern wählen, die du siehst. Wirf den Würfel für Bardische Inspiration. Die Kreatur muss die gewürfelte Zahl von ihrem nächsten Rettungswurf abziehen, bevor du deinen nächsten Zug beginnst.

---

### Zauber

| Modifikator | Zauberangriff | Rettungswurf                            |
| ----------- | ------------- | --------------------------------------- |
|  +`=this.Übung`           | +`=floor((this.CHA - 10) / 2) + this.Übung`              | `=(this.CHA - 10) / 2 + 8 + this.Übung` |

#### Zaubertricks 
| Nr. | Name                                           | Zeit     | Reichweite | Rettung                                     | Effekt          |
| --- | ---------------------------------------------- | -------- | ---------- | ------------------------------------------- | --------------- |
| 1.  | [[Gehässiger Spott]] | 1 Aktion | 18 Meter   | WEI `=(this.CHA - 10) / 2 + 8 + this.Übung` | `1W4` Psychisch |
| 2.  | [[../../../05 - Wikipedia/Zauber/Tanzende Lichter]] | 1 Aktion | 36 Meter   | Utility                                     |                 |
| 3.  | [[../../../05 - Wikipedia/Zauber/Taschenspielerei]] | 1 Aktion | 3 Meter    | Utility                                     |                 |
| 4.  | Ab Stufe 10                                    |          |            |                                             |                 |



#### 1. Zaubergrad | Zauberplätze: <input type="checkbox" unchecked><input type="checkbox" unchecked><input type="checkbox" unchecked><input type="checkbox" unchecked>
| Nr. | Name                                                   | Zeit     | Reichweite | Rettung                                     | Effekt                                    |
| --- | ------------------------------------------------------ | -------- | ---------- | ------------------------------------------- | ----------------------------------------- |
| 1.  | [Dissonantes-Flüstern](../../../05%20-%20Wikipedia/Zauber/Dissonantes-Flüstern.md) | 1 Aktion | 18 Meter   | WEI `=(this.CHA - 10) / 2 + 8 + this.Übung` | 3W6 Psychisch                             |
| 2.  | [Heilendes Wort](../../../05%20-%20Wikipedia/Zauber/Heilendes-Wort.md)             | 1 Bonus  | 18 Meter   | -                                           | 1W4+`=floor((this.CHA - 10) / 2)` Heilung |
| 3.  | [Magie entdecken](../../../05%20-%20Wikipedia/Zauber/Magie-entdecken.md)           | 1 Aktion | Selbst     | -                                           | Entdeckung                                |
| 4.  | [Person bezaubern](../../../05%20-%20Wikipedia/Zauber/Person-bezaubern.md)         | 1 Aktion | 9 Meter    | WEI `=(this.CHA - 10) / 2 + 8 + this.Übung` | [Bezaubert](Anhang PH-A#Bezaubert)        |
| 5.  |                                                        |          |            |                                             |                                           |
| 6.  |                                                        |          |            |                                             |                                           |
| 7.  |                                                        |          |            |                                             |                                           |

---

#### 2. Zaubergrad | Zauberplätze:  <input type="checkbox" unchecked><input type="checkbox" unchecked> | Ab Stufe 4: <input type="checkbox" unchecked>
| Nr. | Name                         | Zeit     | Reichweite | Rettung | Effekt |
| --- | ---------------------------- | -------- | ---------- | ------- | ------ |
| 1.  | [Stille](../../../05%20-%20Wikipedia/Zauber/Stille.md)  | 1 Aktion | 36 Meter   |         |        |
| 2.  | [Klopfen](../../../05%20-%20Wikipedia/Zauber/Klopfen.md) | 1 Aktion | 18 Meter   |         |        |
| 3.  |                              |          |            |         |        |

---

#### 3. Zaubergrad | Zauberplätze: Ab Stufe 5:  <input type="checkbox" unchecked><input type="checkbox" unchecked> | Ab Stufe 6: <input type="checkbox" unchecked>
| Nr. | Name | Zeit | Reichweite | Rettung | Effekt |
| --- | ---- | ---- | ---------- | ------- | ------ |
| 1.  |      |      |            |         |        |
| 2.  |      |      |            |         |        |
| 3.  |      |      |            |         |        |

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


Health: `VIEW[{this.TP}][text]` `BUTTON[reset-health]`
```meta-bind 
INPUT[text:Inventory11]
```

```meta-bind
INPUT[text:Inventory21]
```